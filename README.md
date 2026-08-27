# HudHud AIDE: Autonomous Intelligent Development Environment

<p align="center">
  <b>Languages:</b> <b>English</b> | <a href="docs/README.tr.md">Türkçe</a> | <a href="docs/README.ar.md">العربية</a> | <a href="docs/README.ja.md">日本語</a> | <a href="docs/README.ru.md">Русский</a> | <a href="docs/README.es.md">Español</a> | <a href="docs/README.pt.md">Português</a> | <a href="docs/README.zh.md">简体中文</a>
</p>

<p align="center">
  <a href="INSTALL.md"><b>📖 Installation Guide</b></a> | 
  <a href="ONBOARDING.md"><b>🚀 First Run & Onboarding</b></a>
</p>

---

[![Version](https://img.shields.io/badge/version-v0.4.46-orange.svg)](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)](https://github.com/HudHudMind/hudhudscript)
[![Toolchain](https://img.shields.io/badge/toolchain-HudHudScript%20x86_64%20(v1..v4)-green.svg)](https://github.com/HudHudMind/hudhudscript)

<p align="center">
  <img src="assets/screenshots/hudhudaide_welcome_screen.png" alt="HudHud AIDE Welcome Screen" width="100%" />
</p>

**HudHud AIDE** is an integrated development environment primarily designed for [**HudHudScript**](https://github.com/HudHudMind/hudhudscript), while supporting source code editing and project development in modern languages such as **Python, Rust, C/C++, and TypeScript/JavaScript** through its built-in editor and AI coding agent.

The environment combines two complementary development workflows:
* **Code Editing & Agent Assistance:** Multi-language source code authoring, diagnostics, and refactoring with a workspace-aware AI coding agent.
* **Visual Programming (`.hudhudgraph`):** A node-based visual programming system used to model, structure, and generate native **HudHudScript** logic flows and multi-agent pipelines.

HudHud AIDE bridges **conventional software development with modern paradigms**:
* **Agentic Programming:** Specification and deployment of autonomous agents, roles, tool bindings, and multi-agent coordination.
* **Loop Engineering & Loop Chains:** Construction of feedback-driven execution loops, evaluation cycles, and iterative refinement chains.
* **Governance Systems:** Enforcement of operational constraints, safety policies, validation rules, and permission boundaries directly within code and graph models.
* **Subject-Oriented Programming (SOP):** Software structuring based on active subjects, operational contexts, and behavioral intents.

Engineers and developers can build custom AI agents and system architectures visually through visual programming, programmatically in source code, or collaboratively with the integrated coding agent.

---

## Key Capabilities at a Glance

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                                 HudHud AIDE                                 │
├───────────────────┬─────────────────────┬─────────────────┬─────────────────┤
│Visual Programming │ HudHud Coding Agent │   HudHud Code   │  HudHudScript   │
│  (.hudhudgraph    │ (Autonomous Multi-  │ (Interactive AI │(Native Hardware │
│   Node System)    │  File Refactoring)  │Coding Companion)│    Runtime)     │
└───────────────────┴─────────────────────┴─────────────────┴─────────────────┘
```

* **Visual Architecture & Logic Modeling:** Model application flows, agent pipelines, and state structures with node-based visual programming.
* **HudHud Coding Agent:** Autonomous in-editor AI pair programmer that modifies multiple files, executes tools, and fixes diagnostics across your workspace.
* **HudHud Code:** Interactive conversational AI companion for deep codebase queries, architecture planning, model switching, and real-time pair programming.
* **HudHudScript Engine Support:** Native language integration for Agentic Programming, Loop Engineering, Governance rules, and Subject-Oriented Programming (SOP).
* **Pre-bundled Hardware-Optimized Toolchain:** Zero-configuration compiler, interpreter, LSP, package manager, and runtime pre-configured for your CPU (`x86-64-v1` to `v4`).

---

## Visual Programming & HudHudGraphs

**Visual Programming** in HudHud AIDE provides an interactive canvas for designing and inspecting software architectures and workflows visually alongside your source code.

Visual architectures are saved in standard **`.hudhudgraph`** files.

<p align="center">
  <img src="assets/screenshots/hudhudaide_visual_editor.png" alt="HudHud AIDE Visual Programming Editor" width="100%" />
</p>

```
                    ┌─────────────────────────┐
                    │       Agent Node        │
                    ├───────────┬─────────────┤
                    │ Role      │ Governance  │
                    │ Tools     │ Validation  │
                    └─────┬─────┴──────┬──────┘
                          │            │
                          ▼            ▼
                   [ Action / Loop ] [ Policy ]
```

<p align="center">
  <img src="assets/screenshots/hudhudaide_visual_editor_2.png" alt="HudHud AIDE Graph Canvas and Inspector" width="100%" />
</p>

### Capabilities:
* **240+ Specialized Node Types:** Nodes covering application flow, agent definitions, data pipelines, state machines, governance rules, and UI relationships.
* **Typed Pin Connections:** Clear data channels and execution flows with type-safe pin validation.
* **Properties Inspector:** Select any node to configure its parameters, behavior, and attributes in real time.
* **Hybrid Workflow:** Use visual `.hudhudgraph` files alongside standard `.hud` source code without forced code generation overhead.

### How to Use:
1. Open or create any `.hudhudgraph` file in your workspace.
2. Click **"Open with Visual Designer"** in the editor tab.
3. Drag nodes from the left **Palette** onto the canvas.
4. Link execution paths and data pins between nodes.
5. Edit node properties in the right inspector panel and save (`Ctrl + S` / `Cmd + S`).

---

## HudHud Coding Agent

The **HudHud Coding Agent** is an autonomous, workspace-aware pair programmer designed to execute multi-file software engineering tasks directly in your repository.

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_edit.png" alt="HudHud Coding Agent Multi-File Edit" width="100%" />
</p>

### Autonomous Coding Capabilities:
* **Multi-File Implementation & Refactoring:** Writes new features, updates complex types, and refactors dependencies across multiple project files in a single pass.
* **Workspace Analysis:** Reads and understands source files, project configuration files, and `.hudhudgraph` visual architectures.
* **Diagnostics & Error Resolution:** Pinpoints compiler warnings, runtime exceptions, and type errors, automatically generating and testing verified fixes.
* **Task Automation:** Follows multi-step engineering plans, test executions, and project migrations autonomously.
* **Interactive Tool & Diff Approval:** Inspect inline diffs and approve or reject file changes before they are committed to disk.

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_approve.png" alt="HudHud Coding Agent Tool and Diff Approval Flow" width="100%" />
</p>

---

## HudHud Code

**HudHud Code** is the conversational AI companion and interactive intelligence hub integrated directly into HudHud AIDE. It enables natural language discussions with your entire codebase, architecture planning, and seamless model switching.

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_model_suggestion.png" alt="HudHud Code Model Selection and Suggestions" width="100%" />
</p>

### Interactive Capabilities:
* **Codebase & Architecture Inquiries:** Ask deep questions about your logic flows, agent interactions, and `.hudhudgraph` pipelines with full repository context.
* **Multi-Model Intelligence:** Switch effortlessly between top-tier coding models (Anthropic Claude 3.5 Sonnet, OpenAI GPT-4o, Google Gemini 1.5 Pro, DeepSeek) or local LLMs via Ollama.
* **Custom Instructions & Temperature Control:** Tailor reasoning style, token limits, system instructions, and temperature per conversation.
* **Configurable Tool Permissions:** Toggle automated tool execution (reading files, running terminal commands, generating graphs) with granular control.

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_settings_model.png" alt="HudHud Code Model and Provider Configuration" width="100%" />
</p>

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_settings.png" alt="HudHud Code Settings and Execution Options" width="100%" />
</p>

---

## HudHudScript Language & Paradigm Support

HudHud AIDE is built to natively understand and support the core paradigms of the [**HudHudScript**](https://github.com/HudHudMind/hudhudscript) language:

* **Agentic Programming:** Language-level structures for defining autonomous agents, roles, responsibilities, tools, and multi-agent interactions.
* **Loop Engineering:** Structured, feedback-driven execution loops combining actions, validations, and iterative refinements.
* **Governance Systems:** Built-in constructs for defining roles, rules, constraints, councils, and permissions directly in code and graphs.
* **Subject-Oriented Programming (SOP):** Software modeling centered around subjects, contexts, and behavioral responsibilities.

---

## Native HudHudScript Toolchain

HudHud AIDE comes pre-bundled with the complete native toolchain. During installation, the environment detects your CPU features (SSE4.2, AVX2, AVX-512) and activates the matching binary set (`x86-64-v1` to `v4`):

| Binary / Tool | Role |
| :--- | :--- |
| **`hudhud`** | CLI runtime and application executor |
| **`hudc`** | Native optimizing HudHudScript compiler |
| **`hudi`** | Interactive REPL shell and live interpreter |
| **`hudconv`** | AST, bytecode, and schema migration utility |
| **`hudhudscript-lsp`** | Language Server Protocol engine powering syntax highlighting, autocompletion, and hover docs |
| **`hudhud_ffi`** | C / Rust Foreign Function Interface runtime |

---

## Unified Development Workflow

```
   1. Visual Programming     2. Implementation          3. Verification
 ┌──────────────────┐      ┌──────────────────┐      ┌──────────────────┐
 │  Model Graph     │ ───► │ Write Code with  │ ───► │ Compile, Test &  │
 │ (.hudhudgraph)   │      │ AI Coding Agent  │      │ Run (hudc/hudi)  │
 └──────────────────┘      └──────────────────┘      └──────────────────┘
```

1. **Model:** Map out your logic, agents, or pipeline visually using Visual Programming.
2. **Implement:** Write HudHudScript code or collaborate with the integrated Coding Agent to implement handlers and business logic.
3. **Execute & Debug:** Run and debug directly in the IDE using native toolchain binaries and interactive debugging tools.

---

## System Requirements & Installation

> [!TIP]
> For a visual, step-by-step installation walkthrough, see the [**Complete Installation Guide (INSTALL.md)**](INSTALL.md) or [**Türkçe Kurulum Kılavuzu (docs/INSTALL.tr.md)**](docs/INSTALL.tr.md).

Download the latest installation packages from [GitHub Releases](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46) or via the direct links below:

### Windows (x64)
* **OS:** Windows 10 / 11 (64-bit)
* **Download:** [`hudhud-aide-v0.4.46-win-x64-setup.exe`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-win-x64-setup.exe)
* **SmartScreen / Unsigned Binary Note:**
  As the binary is currently unsigned, Microsoft Defender SmartScreen may display a *"Windows protected your PC"* prompt:
  1. Click **"More info"**.
  2. Click **"Run anyway"** to proceed with installation.
* *The installer automatically configures the matching CPU binary level (`v1` to `v4`).*

### Linux (x86_64)
* **OS:** Ubuntu 20.04+, Debian 11+, Fedora, Arch Linux, Kali Linux
* **Download:** [`hudhud-aide-v0.4.46-linux-x64-installer.run`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-linux-x64-installer.run)
* **Installation:**
  ```bash
  chmod +x hudhud-aide-v0.4.46-linux-x64-installer.run
  ./hudhud-aide-v0.4.46-linux-x64-installer.run
  ```

---

## Community & Links

* **Website:** [https://hudhudscript.com](https://hudhudscript.com)
* **GitHub (HudHudScript):** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)
* **GitHub (HudHud AIDE):** [https://github.com/HudHudMind/hudhud-aide](https://github.com/HudHudMind/hudhud-aide)
* **Discord:** [https://discord.gg/UxEJ5MfH](https://discord.gg/UxEJ5MfH)
* **Reddit:** [https://www.reddit.com/r/hudhudscript/](https://www.reddit.com/r/hudhudscript/)
* **Twitter / X:** [https://x.com/hudhud_script](https://x.com/hudhud_script)
* **Instagram:** [https://www.instagram.com/hudhudscript/](https://www.instagram.com/hudhudscript/)
* **TikTok:** [https://www.tiktok.com/@hudhudscript](https://www.tiktok.com/@hudhudscript)
* **YouTube:** [https://www.youtube.com/@HudHudScripting](https://www.youtube.com/@HudHudScripting)
* **LinkedIn:** [https://www.linkedin.com/groups/27050016/](https://www.linkedin.com/groups/27050016/)
* **Patreon:** [https://www.patreon.com/cw/hudhudscript](https://www.patreon.com/cw/hudhudscript)

---

## License & Inquiries

<p align="center">
  <img src="assets/screenshots/hudhudaide_about_dialog.png" alt="HudHud AIDE About Dialog" width="100%" />
</p>

HudHud AIDE is a professional development environment developed by **HudHud Script**.

* **Repository:** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)

---
*© 2026 HudHud Script. All rights reserved.*
