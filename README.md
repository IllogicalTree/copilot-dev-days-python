🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎲 Soc Ops

### A hands-on workshop to master GitHub Copilot Agent Mode in VS Code

[![VS Code](https://img.shields.io/badge/VS%20Code-v1.107+-007ACC?logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-required-6e40c9?logo=github&logoColor=white)](https://github.com/features/copilot)
[![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-latest-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**⏱️ ~1 hour &nbsp;|&nbsp; 🎯 Intermediate &nbsp;|&nbsp; 🐍 Python / FastAPI / Jinja2 / HTMX**

</div>

---

## 🚀 What Is This?

**Soc Ops** is a Social Bingo game for in-person mixers — find people who match the questions and get 5 in a row! But the real star of the show is the **lab experience** built around it.

You'll take this app from a simple working prototype to something genuinely impressive, guided entirely by **GitHub Copilot's Agent Mode**. Along the way you'll learn how to wield AI as a real development partner — not just autocomplete.

---

## 🛠️ What You'll Build

Starting from a working Social Bingo app, you'll use Copilot agents to:

| Step | What You'll Do |
|------|----------------|
| 🎨 **Redesign the UI** | Transform the look and feel with a creative theme of your choosing |
| 🤖 **Build a custom agent** | Create a Quiz Master agent that generates bingo card themes |
| ✅ **Add a feature with TDD** | Use Red→Green→Refactor agents to build a Scavenger Hunt mode |
| 🃏 **Ship a visual feature** | Add a Card Deck Shuffle animation with a dedicated design agent |

---

## 🎯 What You'll Learn

| Skill | Description |
|-------|-------------|
| **Context Engineering** | Teach AI about your codebase with workspace instructions |
| **Agentic Primitives** | Copilot CLI sessions, cloud agents, and custom workflows |
| **Design-First Development** | Let AI iterate on UI while you guide the creative vision |
| **Test-Driven Development** | Use TDD agents for reliable, test-backed feature development |

---

## 🧰 Tech Stack

```
🐍 Python 3.13    ⚡ FastAPI    🖼️ Jinja2    ✨ HTMX    📦 uv
```

---

## 📋 Prerequisites

Before you begin, make sure you have:

- [ ] **VS Code v1.107+** (no pending updates)
- [ ] **GitHub Copilot** — Free, Pro, Business, or Enterprise
- [ ] **Git** installed
- [ ] **Python 3.13** & **uv** installed

> 💡 **Skip the setup hassle!** Use the included **DevContainer** for a pre-configured environment — works locally or in GitHub Codespaces.
>
> ⚠️ **Free-tier users:** Cloud Agents aren't available on free-tier Copilot plans. The workshop provides CLI alternatives wherever Cloud Agents are used.

---

## 📚 Lab Guide

| Part | Title | Time |
|------|-------|------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist | — |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering | 15 min |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend | 15 min |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master | 10 min |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development | 20 min |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

---

## ⚡ Getting Started

**1. Create your own copy of this repo**

Click **Use this template** → **Create a new repository** (make it public).

**2. Open it in VS Code or Codespaces**

- **Local:** Clone the repo and open in VS Code. When prompted, install recommended extensions.
- **Codespaces:** Click **Code** → **Codespaces** → **Create codespace on main**.

**3. Run the setup agent**

Open the Copilot Chat panel and run:
```
/setup
```
The agent will install dependencies and start the dev server. That's it — you're ready!

---

## 💡 Pro Tips

1. **Keep the browser open** — Watch live updates as you code
2. **Commit often** — Save working states before big changes
3. **Use Checkpoints** — Revert unexpected changes with Chat Checkpoints & Undo
4. **Iterate on plans** — Ask the agent to refine its plan 2+ times before implementing

---

## 🔗 Resources

- [VS Code YouTube](https://www.youtube.com/code)
- [GitHub Copilot Docs](https://code.visualstudio.com/docs/copilot/overview)
- [Awesome Copilot](https://github.com/github/awesome-copilot)
