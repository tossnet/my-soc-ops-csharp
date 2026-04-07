🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎲 Soc Ops

### Social Bingo for In-Person Mixers

*Find people who match the questions. Get 5 in a row. Win!*

[![.NET](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor](https://img.shields.io/badge/Blazor-WebAssembly-512BD4?logo=blazor&logoColor=white)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
[![C#](https://img.shields.io/badge/C%23-13-239120?logo=csharp&logoColor=white)](https://learn.microsoft.com/dotnet/csharp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-222?logo=github)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)

<br/>

[🎮 **Play the Game**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) &nbsp;•&nbsp; [📚 **Lab Guide**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/) &nbsp;•&nbsp; [⚡ **Quick Start**](#-quick-start)

</div>

---

## 🌟 What is Soc Ops?

**Soc Ops** is a web-based Social Bingo game designed for conferences, meetups, and team events. Players explore the room, find people who match the prompts on their board, and race to complete a line.

But it's also more than a game — **Soc Ops is a hands-on workshop** where you'll use [VS Code Agent Mode](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode) and GitHub Copilot to build real features in a real app. In roughly an hour, you'll go from starter template to a fully customized, AI-assisted project.

---

## ✨ Features

| | |
|---|---|
| 🟦 **5×5 Bingo Board** | Classic bingo layout with dynamic, event-specific prompts |
| 🎉 **Win Detection** | Automatic line detection across rows, columns, and diagonals |
| 📱 **Mobile-First** | Touch-friendly design that works great on any device |
| 🎨 **Themeable UI** | Custom agent lets you swap in fun quiz themes instantly |
| ⚡ **Blazor WASM** | Runs entirely in the browser — no server required after deploy |
| 🤖 **AI-Ready Codebase** | Structured with GitHub Copilot context engineering in mind |

---

## 🎓 Workshop — What You'll Build

This project is the foundation for a **VS Code + GitHub Copilot Agent Lab**. Over four hands-on parts, you'll learn how to leverage AI agents in your daily development workflow:

| Part | Title | Duration | Skills |
|------|-------|----------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist | — | Orientation |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering | 15 min | Copilot instructions, project context |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend | 15 min | Agentic UI iteration |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master | 10 min | Custom agent creation |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development | 20 min | TDD agents, feature development |

> 📝 Lab guides are also available offline in the [`workshop/`](workshop/) folder.

---

## ⚡ Quick Start

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher
- [VS Code](https://code.visualstudio.com/) with [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) extension

### Run locally

```bash
cd SocOps
dotnet run
```

Then open your browser at `http://localhost:5000`.

### Build

```bash
cd SocOps
dotnet build
```

### Open in GitHub Codespaces ☁️

The fastest way to get started — no local setup required:

1. Click **Use this template** → **Create a new repository**
2. In your new repo, click **Code** → **Codespaces** → **Create codespace on main**
3. Wait for the dev container to finish setup
4. Run `cd SocOps && dotnet run` in the terminal

> The devcontainer pre-installs .NET 10, VS Code extensions, and everything else you need.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | C# 13 |
| Framework | .NET 10 Blazor WebAssembly |
| Styling | Custom CSS utility classes |
| Hosting | GitHub Pages (auto-deploy on push to `main`) |
| AI Tooling | VS Code Agent Mode + GitHub Copilot |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) to get started.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — © Microsoft Corporation.
