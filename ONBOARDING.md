# HudHud AIDE First Run & Onboarding Guide

<p align="center">
  <b>Languages:</b> <b>English</b> | <a href="docs/ONBOARDING.tr.md">Türkçe (Turkish)</a>
</p>

<p align="center">
  <a href="README.md"><b>🏠 Main README</b></a> | 
  <a href="INSTALL.md"><b>📖 Installation Guide</b></a>
</p>

---

Welcome to **HudHud AIDE** (Autonomous Intelligent Development Environment)! When you launch HudHud AIDE for the first time, an intuitive 6-step setup wizard guides you through tailoring the environment to your preferences, configuring your AI coding agent, verifying hardware-optimized toolchains, and opening your first project.

This guide walks you through each step with screenshots and explanations.

---

## Table of Contents
1. [6-Step Onboarding Walkthrough](#6-step-onboarding-walkthrough)
   - [Step 1: Welcome & Interface Language](#step-1-welcome--interface-language)
   - [Step 2: Theme & Visual Appearance](#step-2-theme--visual-appearance)
   - [Step 3: AI Coding Agent & Model Configuration](#step-3-ai-coding-agent--model-configuration)
   - [Step 4: Toolchain & Hardware Engine Verification](#step-4-toolchain--hardware-engine-verification)
   - [Step 5: Visual Programming & Features](#step-5-visual-programming--features)
   - [Step 6: Ready to Code & Project Setup](#step-6-ready-to-code--project-setup)
2. [Configuring the AI Coding Agent](#configuring-the-ai-coding-agent)
   - [Model Selection & Suggestions](#model-selection--suggestions)
   - [Agent Settings & Provider Keys](#agent-settings--provider-keys)
   - [Reviewing & Approving Changes](#reviewing--approving-changes)
3. [Exploring Visual Programming (`.hudhudgraph`)](#exploring-visual-programming-hudhudgraph)
4. [Creating Your First Project](#creating-your-first-project)
5. [Essential Shortcuts](#essential-shortcuts)

---

## 6-Step Onboarding Walkthrough

### Step 1: Welcome & Interface Language

Upon launching HudHud AIDE for the first time, the onboarding wizard welcomes you:

<p align="center">
  <img src="assets/onboarding/onboarding1.png" alt="Onboarding Step 1 - Welcome Screen" width="100%" />
</p>

* Select your preferred interface language (**English** or **Türkçe**).
* You can change the language anytime later from the Command Palette (`Ctrl + Shift + P` -> `Configure Display Language`).
* Click **Next** to proceed.

---

### Step 2: Theme & Visual Appearance

Personalize your development environment theme:

<p align="center">
  <img src="assets/onboarding/onboarding2.png" alt="Onboarding Step 2 - Theme Selection" width="100%" />
</p>

* Choose from built-in themes:
  * **HudHud Dark / Modern Dark** (Recommended for eye comfort during long coding sessions)
  * **Modern Light**
  * **High Contrast Dark / Light**
* Syntax highlighting colors for HudHudScript (`.hud`), visual graph definitions, and standard languages (Python, Rust, C/C++, TypeScript) will adapt immediately.
* Click **Next** to continue.

---

### Step 3: AI Coding Agent & Model Configuration

Configure the built-in autonomous AI coding agent:

<p align="center">
  <img src="assets/onboarding/onboarding3.png" alt="Onboarding Step 3 - AI Coding Agent Setup" width="100%" />
</p>

* **AI Provider Selection:** Connect to your preferred AI models (Anthropic Claude, OpenAI, Google Gemini, Ollama, or local LLM server).
* **API Key & Endpoint Configuration:** Securely enter your API key or configure a custom endpoint URL. Keys are stored safely in your local OS credential vault.
* **Autonomous Agent Mode:** Choose whether the agent should ask for confirmation before applying file edits or operate in full autonomous mode.
* Click **Next** to proceed.

---

### Step 4: Toolchain & Hardware Engine Verification

HudHud AIDE automatically verifies your native HudHudScript toolchain:

<p align="center">
  <img src="assets/onboarding/onboarding4.png" alt="Onboarding Step 4 - Toolchain Verification" width="100%" />
</p>

* The system checks the availability of core toolchain binaries:
  * `hudhud`: CLI runtime & executor
  * `hudc`: Native optimizing compiler
  * `hudi`: Interactive REPL engine
  * `hudhudscript-lsp`: Language Server Protocol engine
  * `hudhud_ffi`: C / Rust Foreign Function Interface runtime
* Confirms active hardware optimization level (`x86-64-v1`, `v2`, `v3`, or `v4`).
* Click **Next** to continue.

---

### Step 5: Visual Programming & Features

Discover the built-in Visual Programming features:

<p align="center">
  <img src="assets/onboarding/onboarding5.png" alt="Onboarding Step 5 - Visual Programming" width="100%" />
</p>

* **Node-Based System:** Visual design canvas supporting 240+ specialized node types for Agentic Programming, Loop Chains, and Governance policies.
* **Hybrid Editing:** Seamlessly switch between code files (`.hud`) and graph designs (`.hudhudgraph`).
* Click **Next** to proceed to the final step.

---

### Step 6: Ready to Code & Project Setup

You are all set!

<p align="center">
  <img src="assets/onboarding/onboarding6.png" alt="Onboarding Step 6 - Completion & Workspace" width="100%" />
</p>

* Choose how you'd like to get started:
  * **Open Existing Folder / Workspace:** Browse and open any existing source folder.
  * **Create New HudHud Project:** Initialize a new HudHudScript application or visual graph project with sample templates.
  * **Clone from Git Repository:** Clone a remote repository directly into AIDE.
* Click **Finish Setup** to open the main editor workspace.

---

## Configuring HudHud Code & HudHud Coding Agent

HudHud AIDE features both an interactive conversational companion (**HudHud Code**) and an autonomous multi-file pair programmer (**HudHud Coding Agent**).

### HudHud Code: Interactive Model Selection & Queries

You can pick recommended models or configure custom endpoints:

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_model_suggestion.png" alt="HudHud Code Model Suggestions and Queries" width="100%" />
</p>

* Open the AI sidebar panel by clicking the **Agent** icon on the activity bar or pressing `Ctrl + Shift + A` / `Cmd + Shift + A`.
* Choose from curated high-performance coding models (Claude 3.5 Sonnet, GPT-4o, Gemini 1.5 Pro, DeepSeek) or local Ollama instances.

### HudHud Code: Settings & Provider Keys

Access settings to adjust parameters, context size, system instructions, and provider keys:

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_settings_model.png" alt="HudHud Code Model and Provider Configuration" width="100%" />
</p>

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_settings.png" alt="HudHud Code Execution Settings" width="100%" />
</p>

* Configure temperature, max tokens, streaming response options, and workspace indexing preferences.
* Enable or disable automatic tool calling (file reading, file editing, terminal execution, graph generation).

### HudHud Coding Agent: Reviewing & Approving Multi-File Edits

When the autonomous coding agent proposes code edits, you have full control over reviewing and applying changes:

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_edit.png" alt="HudHud Coding Agent Multi-File Diff View" width="100%" />
</p>

<p align="center">
  <img src="assets/screenshots/hudhudaide_coding_agent_approve.png" alt="HudHud Coding Agent Tool & Change Approval Flow" width="100%" />
</p>

* **Interactive Diff View:** Inspect inline additions (green) and deletions (red).
* **One-Click Approval:** Click **Approve** to apply the diffs or **Reject** to ask the agent for an alternative approach.

---

## Exploring Visual Programming (`.hudhudgraph`)

Visual programming allows you to model multi-agent workflows, logic loops, and governance systems with drag-and-drop nodes:

<p align="center">
  <img src="assets/screenshots/hudhudaide_visual_editor.png" alt="Visual Programming Editor" width="100%" />
</p>

<p align="center">
  <img src="assets/screenshots/hudhudaide_visual_editor_2.png" alt="Graph Canvas and Properties Inspector" width="100%" />
</p>

1. Create or open any `.hudhudgraph` file.
2. Select nodes from the palette (Agents, Actions, Loop Controllers, Policies, I/O Pins).
3. Connect execution and data pins with type validation.
4. Customize node properties in the right inspector panel.
5. Save with `Ctrl + S`.

---

## Creating Your First Project

To start developing in HudHud AIDE:

1. Open or create any folder in HudHud AIDE (`File` -> `Open Folder...`).
2. Create a new source file named `main.hud` (or a visual graph `app.hudhudgraph`).
3. Add your HudHudScript code or drag nodes onto the visual canvas:
   ```hudhud
   subject Main {
       fn start() {
           println("Hello from HudHudScript!");
       }
   }
   ```
4. Run your code directly from the integrated terminal (`Ctrl + \``):
   ```bash
   hudhud run main.hud
   ```
5. Or compile to a native hardware-optimized executable:
   ```bash
   hudc build main.hud -o my_app.exe
   ```

---

## Essential Shortcuts

| Action | Windows / Linux | macOS |
| :--- | :--- | :--- |
| **Command Palette** | `Ctrl + Shift + P` | `Cmd + Shift + P` |
| **Open File / Quick Open** | `Ctrl + P` | `Cmd + P` |
| **Toggle AI Agent Panel** | `Ctrl + Shift + A` | `Cmd + Shift + A` |
| **Toggle Terminal** | `Ctrl + \`` | `Cmd + \`` |
| **Save File / Graph** | `Ctrl + S` | `Cmd + S` |
| **Open Visual Designer** | `Ctrl + Alt + V` | `Cmd + Option + V` |
| **Format Document** | `Shift + Alt + F` | `Shift + Option + F` |

---

## Need Help?
- Visit our [Installation Guide (INSTALL.md)](INSTALL.md)
- Check the [Main README](README.md)
- Join the community on [Discord](https://discord.gg/UxEJ5MfH)

---
*© 2026 HudHud Script. All rights reserved.*
