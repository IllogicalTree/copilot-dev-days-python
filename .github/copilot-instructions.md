# Project Guidelines

## Overview

**Soc Ops** is a Social Bingo game — Python 3.13, FastAPI, Jinja2 templates, HTMX for interactivity. No JS frameworks.

## Architecture

```
app/
├── main.py          # FastAPI routes (HTMX endpoints return HTML fragments)
├── models.py        # Pydantic models (GameState, BingoSquareData, BingoLine)
├── game_logic.py    # Pure functions: board generation, toggle, bingo detection
├── game_service.py  # GameSession dataclass, in-memory session store
├── data.py          # Question bank (24 prompts + FREE_SPACE)
├── templates/       # Jinja2: base.html, home.html, components/
└── static/css/      # Custom utility classes (Tailwind-like)
tests/
├── test_api.py      # Integration tests (FastAPI TestClient)
└── test_game_logic.py  # Unit tests for pure game logic
```

**Key boundaries:**
- `game_logic.py` is pure — no side effects, no session access
- `game_service.py` owns state mutations via `GameSession`
- Routes in `main.py` are thin: get session → delegate → render template
- HTMX swaps HTML fragments from `templates/components/`; no JSON APIs

## Build & Test

```bash
uv sync                                              # Install deps
uv run uvicorn app.main:app --reload --port 8000     # Dev server
uv run pytest                                        # Tests
uv run ruff check .                                  # Lint
```

## Conventions

- **Immutable models**: `BingoSquareData` uses `frozen=True`; use `model_copy(update=...)` to change fields
- **snake_case** everywhere, type hints on all signatures
- **Tests**: class-grouped by feature (`TestGenerateBoard`, `TestToggleSqare`), `pytest` fixtures for shared setup
- **Templates**: HTMX attributes drive interactions (`hx-post`, `hx-target`, `hx-swap`). No inline JS
- **Styling**: Custom CSS utilities in `app/static/css/app.css` — see `.github/instructions/css-utilities.instructions.md`
- **No Simple Browser**: Always use `$BROWSER` or instruct user to open URLs externally

## Pitfalls

- Board is a flat `list[BingoSquareData]` of 25 items; center index is 12 (the free space)
- Sessions are in-memory (`_sessions` dict) — lost on restart, by design for this app
- `_get_winning_lines()` is `@functools.cache`'d — it never changes at runtime
