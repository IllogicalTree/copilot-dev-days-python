<!-- l10n-sync: source-file="README.md" -->
🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎲 Soc Ops

### Um workshop prático para dominar o Modo Agente do GitHub Copilot no VS Code

[![VS Code](https://img.shields.io/badge/VS%20Code-v1.107+-007ACC?logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-obrigatório-6e40c9?logo=github&logoColor=white)](https://github.com/features/copilot)
[![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-latest-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![License: MIT](https://img.shields.io/badge/Licença-MIT-yellow.svg)](LICENSE)

**⏱️ ~1 hora &nbsp;|&nbsp; 🎯 Intermediário &nbsp;|&nbsp; 🐍 Python / FastAPI / Jinja2 / HTMX**

</div>

---

## 🚀 O Que É Isso?

**Soc Ops** é um jogo de Bingo Social para encontros presenciais — encontre pessoas que correspondam às perguntas e consiga 5 em linha! Mas a verdadeira estrela é a **experiência do workshop** construída ao redor dele.

Você vai transformar este app de um protótipo funcional em algo verdadeiramente impressionante, guiado inteiramente pelo **Modo Agente do GitHub Copilot**. Ao longo do caminho, você aprenderá a usar a IA como um verdadeiro parceiro de desenvolvimento — não apenas autocompletar.

---

## 🛠️ O Que Você Vai Construir

Partindo de um app de Bingo Social funcional, você usará agentes do Copilot para:

| Passo | O Que Você Fará |
|-------|----------------|
| 🎨 **Redesenhar a UI** | Transforme a aparência com um tema criativo da sua escolha |
| 🤖 **Construir um agente personalizado** | Crie um agente Quiz Master que gera temas de cartelas de bingo |
| ✅ **Adicionar uma funcionalidade com TDD** | Use agentes Red→Green→Refactor para construir um modo Caça ao Tesouro |
| 🃏 **Lançar uma funcionalidade visual** | Adicione uma animação de Embaralhamento de Cartas com um agente de design dedicado |

---

## 🎯 O Que Você Vai Aprender

| Habilidade | Descrição |
|------------|-----------|
| **Engenharia de Contexto** | Ensine a IA sobre sua base de código com instruções de workspace |
| **Primitivas Agênticas** | Sessões CLI do Copilot, agentes em nuvem e fluxos personalizados |
| **Desenvolvimento Design-First** | Deixe a IA iterar na UI enquanto você guia a visão criativa |
| **Desenvolvimento com TDD** | Use agentes TDD para desenvolvimento confiável com cobertura de testes |

---

## 🧰 Stack Tecnológico

```
🐍 Python 3.13    ⚡ FastAPI    🖼️ Jinja2    ✨ HTMX    📦 uv
```

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter:

- [ ] **VS Code v1.107+** (sem atualizações pendentes)
- [ ] **GitHub Copilot** — Free, Pro, Business ou Enterprise
- [ ] **Git** instalado
- [ ] **Python 3.13** e **uv** instalados

> 💡 **Pule a configuração manual!** Use o **DevContainer** incluído para um ambiente pré-configurado — funciona localmente ou no GitHub Codespaces.
>
> ⚠️ **Usuários do plano gratuito:** Os Agentes em Nuvem não estão disponíveis nos planos gratuitos do Copilot. O workshop fornece alternativas via CLI onde necessário.

---

## 📚 Guia do Lab

| Parte | Título | Tempo |
|-------|--------|-------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Visão Geral & Lista de Verificação | — |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto | 15 min |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Frontend Design-First | 15 min |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agente | 20 min |

> 📝 Os guias do lab também estão disponíveis na pasta [`workshop/`](workshop/) para leitura offline.

---

## ⚡ Primeiros Passos

**1. Crie sua própria cópia deste repositório**

Clique em **Use this template** → **Create a new repository** (torne-o público).

**2. Abra no VS Code ou Codespaces**

- **Local:** Clone o repositório e abra no VS Code. Quando solicitado, instale as extensões recomendadas.
- **Codespaces:** Clique em **Code** → **Codespaces** → **Create codespace on main**.

**3. Execute o agente de configuração**

Abra o painel de Chat do Copilot e execute:
```
/setup
```
O agente instalará as dependências e iniciará o servidor de desenvolvimento. Pronto!

---

## 💡 Dicas Pro

1. **Mantenha o navegador aberto** — Veja as atualizações ao vivo enquanto você codifica
2. **Faça commits com frequência** — Salve estados funcionais antes de grandes mudanças
3. **Use Checkpoints** — Reverta mudanças inesperadas com Chat Checkpoints & Undo
4. **Itere nos planos** — Peça ao agente para refinar seu plano 2+ vezes antes de implementar

---

## 🔗 Recursos

- [VS Code no YouTube](https://www.youtube.com/code)
- [Documentação do GitHub Copilot](https://code.visualstudio.com/docs/copilot/overview)
- [Awesome Copilot](https://github.com/github/awesome-copilot)
