<!-- l10n-sync: source-file="README.md" -->
🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎲 Soc Ops

### Un taller práctico para dominar el Modo Agente de GitHub Copilot en VS Code

[![VS Code](https://img.shields.io/badge/VS%20Code-v1.107+-007ACC?logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-requerido-6e40c9?logo=github&logoColor=white)](https://github.com/features/copilot)
[![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-latest-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![License: MIT](https://img.shields.io/badge/Licencia-MIT-yellow.svg)](LICENSE)

**⏱️ ~1 hora &nbsp;|&nbsp; 🎯 Intermedio &nbsp;|&nbsp; 🐍 Python / FastAPI / Jinja2 / HTMX**

</div>

---

## 🚀 ¿Qué es esto?

**Soc Ops** es un juego de Bingo Social para encuentros presenciales — ¡encuentra personas que coincidan con las preguntas y consigue 5 en fila! Pero la verdadera estrella es la **experiencia del taller** construida a su alrededor.

Llevarás esta aplicación desde un prototipo funcional a algo verdaderamente impresionante, guiado completamente por el **Modo Agente de GitHub Copilot**. En el camino aprenderás a usar la IA como un verdadero compañero de desarrollo — no solo autocompletar.

---

## 🛠️ Qué Construirás

Partiendo de una aplicación de Bingo Social funcional, usarás agentes de Copilot para:

| Paso | Qué Harás |
|------|-----------|
| 🎨 **Rediseñar la UI** | Transforma el aspecto con un tema creativo de tu elección |
| 🤖 **Construir un agente personalizado** | Crea un agente Quiz Master que genera temas de tarjetas de bingo |
| ✅ **Añadir una funcionalidad con TDD** | Usa agentes Red→Green→Refactor para construir un modo Búsqueda del Tesoro |
| 🃏 **Lanzar una funcionalidad visual** | Añade una animación de Barajado de Cartas con un agente de diseño dedicado |

---

## 🎯 Lo que Aprenderás

| Habilidad | Descripción |
|-----------|-------------|
| **Ingeniería de Contexto** | Enseña a la IA sobre tu código con instrucciones del workspace |
| **Primitivas Agénticas** | Sesiones CLI de Copilot, agentes en la nube y flujos personalizados |
| **Desarrollo Design-First** | Deja que la IA itere en la UI mientras tú guías la visión creativa |
| **Desarrollo con TDD** | Usa agentes TDD para desarrollo confiable respaldado por pruebas |

---

## 🧰 Stack Tecnológico

```
🐍 Python 3.13    ⚡ FastAPI    🖼️ Jinja2    ✨ HTMX    📦 uv
```

---

## 📋 Requisitos Previos

Antes de comenzar, asegúrate de tener:

- [ ] **VS Code v1.107+** (sin actualizaciones pendientes)
- [ ] **GitHub Copilot** — Free, Pro, Business o Enterprise
- [ ] **Git** instalado
- [ ] **Python 3.13** y **uv** instalados

> 💡 **¡Evita la configuración manual!** Usa el **DevContainer** incluido para un entorno preconfigurado — funciona localmente o en GitHub Codespaces.
>
> ⚠️ **Usuarios del plan gratuito:** Los Agentes en la Nube no están disponibles en los planes gratuitos de Copilot. El taller proporciona alternativas CLI donde sea necesario.

---

## 📚 Guía del Laboratorio

| Parte | Título | Tiempo |
|-------|--------|--------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Visión General y Lista de Verificación | — |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Configuración y Context Engineering | 15 min |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Desarrollo Frontend Orientado al Diseño | 15 min |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agente | 20 min |

> 📝 Las guías del laboratorio también están disponibles en la carpeta [`workshop/`](workshop/) para lectura sin conexión.

---

## ⚡ Primeros Pasos

**1. Crea tu propia copia de este repositorio**

Haz clic en **Use this template** → **Create a new repository** (hazlo público).

**2. Ábrelo en VS Code o Codespaces**

- **Local:** Clona el repositorio y ábrelo en VS Code. Cuando se te solicite, instala las extensiones recomendadas.
- **Codespaces:** Haz clic en **Code** → **Codespaces** → **Create codespace on main**.

**3. Ejecuta el agente de configuración**

Abre el panel de Chat de Copilot y ejecuta:
```
/setup
```
El agente instalará las dependencias e iniciará el servidor de desarrollo. ¡Ya está listo!

---

## 💡 Consejos Pro

1. **Mantén el navegador abierto** — Observa las actualizaciones en vivo mientras codificas
2. **Haz commits frecuentes** — Guarda estados funcionales antes de grandes cambios
3. **Usa Checkpoints** — Revierte cambios inesperados con Chat Checkpoints & Undo
4. **Itera en los planes** — Pide al agente que refine su plan 2+ veces antes de implementar

---

## 🔗 Recursos

- [VS Code en YouTube](https://www.youtube.com/code)
- [Documentación de GitHub Copilot](https://code.visualstudio.com/docs/copilot/overview)
- [Awesome Copilot](https://github.com/github/awesome-copilot)
