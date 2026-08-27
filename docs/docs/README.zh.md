# HudHud AIDE: 自主智能开发环境

<p align="center">
  <b>Languages:</b> <a href="../README.md">English</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.ar.md">العربية</a> | <a href="README.ja.md">日本語</a> | <a href="README.ru.md">Русский</a> | <a href="README.es.md">Español</a> | <a href="README.pt.md">Português</a> | <b>简体中文</b>
</p>

---

[![版本](https://img.shields.io/badge/version-v0.4.46-orange.svg)](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46)
[![平台](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)](https://github.com/HudHudMind/hudhudscript)
[![工具链](https://img.shields.io/badge/toolchain-HudHudScript%20x86_64%20(v1..v4)-green.svg)](https://github.com/HudHudMind/hudhudscript)

**HudHud AIDE** 是一款主要为 [**HudHudScript**](https://github.com/HudHudMind/hudhudscript) 设计的集成开发环境（IDE），同时通过其内置编辑器和 AI 编程智能体，全面支持 **Python、Rust、C/C++ 以及 TypeScript/JavaScript** 等现代编程语言的源代码编辑与项目开发。

该环境融合了两种互补的工程工作流：
* **代码编辑与智能体辅助:** 借助具备工作区感知能力的 AI 编程智能体，进行多语言源码编写、诊断与重构。
* **可视化编程 (`.hudhudgraph`):** 基于节点的低耦合可视化编程系统，用于建模、架构和生成原生 **HudHudScript** 逻辑流与多智能体流水线。

HudHud AIDE 将 **传统软件开发与现代编程范式** 深度连接：
* **智能体编程 (Agentic Programming):** 在语言层面定义和部署自主智能体、角色划分、工具绑定及多智能体协作。
* **循环工程与循环链 (Loop Engineering & Loop Chains):** 构建由反馈驱动的执行循环、评估周期与迭代优化链。
* **治理系统 (Governance):** 直接在代码与图形模型中定义和执行操作约束、安全策略、验证规则与权限边界。
* **主体导向编程 (SOP / Subject-Oriented Programming):** 围绕活跃主体、运行上下文和行为意图构建软件架构，取代静态对象。

工程师与开发者可以通过可视化编程界面、纯源码编写，或与内置 AI 智能体协作，轻松构建自定义 AI 智能体与系统架构。

---

## 核心能力概览

```
┌─────────────────────────────────────────────────────────────┐
│                        HudHud AIDE                          │
├───────────────────┬─────────────────────┬───────────────────┤
│   可视化编程      │      编程智能体     │   HudHudScript    │
│  (.hudhudgraph    │ (具备工作区感知的   │ (硬件自适应优化   │
│   节点系统)       │  AI 结对编程助手)   │   原生运行环境)   │
└───────────────────┴─────────────────────┴───────────────────┘
```

* **可视化架构与逻辑建模:** 通过基于节点的可视化编程，直观设计应用流程、智能体管线和状态机结构。
* **自主 AI 结对编程助手:** 深度理解项目代码库、目录结构与可视化图表文件的内置智能体。
* **原生支持 HudHudScript 语言范式:** 全面支持 Agentic Programming、Loop Engineering、Governance 治理规则与主体导向编程 (SOP)。
* **硬件级预编译工具链:** 针对 CPU 指令集 (`x86-64-v1` 至 `v4`) 自动匹配并预配置编译器、解释器、LSP 和包管理器。

---

## 可视化编程与 HudHudGraphs

HudHud AIDE 中的 **可视化编程** 提供了一个交互式画布，可与源码并排直观地设计和审查软件架构与工作流程。

可视化架构以标准 **`.hudhudgraph`** 文件进行存储。

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

### 核心功能:
* **240+ 种专用节点类型:** 涵盖应用流程、智能体定义、数据管线、状态机、治理规则与交互关系的丰富节点。
* **强类型引脚连接:** 具备类型安全校验的清晰数据通道与执行流。
* **属性检查器 (Inspector):** 选中任意节点即可实时配置其参数、行为与属性。
* **混合工作流:** 可视化 `.hudhudgraph` 文件与标准 `.hud` 源码无缝协同，无强制代码生成负担。

### 使用方法:
1. 在工作区中打开或创建任意 `.hudhudgraph` 文件。
2. 在编辑器标签页中点击 **"Open with Visual Designer"**。
3. 从左侧 **组件面板 (Palette)** 将节点拖拽至画布。
4. 在节点之间连接执行路径与数据引脚。
5. 在右侧检查器面板中配置节点属性并保存 (`Ctrl + S` / `Cmd + S`)。

---

## 内置 AI 编程智能体

HudHud AIDE 配备原生 AI 编程助手，直接在您的项目工作区中协同作业。

### 核心辅助任务:
* **工作区上下文分析:** 实时读取并理解源码文件、项目配置及 `.hudhudgraph` 架构。
* **跨文件协同实现:** 单次指令即可在多个文件之间同步完成功能开发与重构。
* **诊断与错误排查:** 精准定位编译器警告、运行时异常及类型错误，并提供经验证的修复方案。
* **任务自动化:** 稳步执行多步骤工程规划、自动化测试与项目迁移。

---

## HudHudScript 语言与范式支持

HudHud AIDE 原生支持 [**HudHudScript**](https://github.com/HudHudMind/hudhudscript) 语言的核心工程范式：

* **智能体编程 (Agentic Programming):** 在语言层面提供定义自主智能体、角色分工、工具绑定及多智能体交互的结构。
* **循环工程 (Loop Engineering):** 结合行动、校验与迭代改进的结构化反馈执行循环。
* **治理系统 (Governance):** 直接在代码与图表中声明角色权限、约束条件、安全委员会及准入策略。
* **主体导向编程 (SOP):** 围绕执行主体、环境上下文及行为职责建模的全新软件体系。

---

## 原生 HudHudScript 工具链

HudHud AIDE 预装了完整的原生工具链。在安装过程中会自动检测您的 CPU 特性 (SSE4.2, AVX2, AVX-512) 并启用最佳匹配的二进制套件 (`x86-64-v1` to `v4`):

| 二进制工具 | 职责与作用 |
| :--- | :--- |
| **`hudhud`** | 命令行 (CLI) 运行时与应用程序执行器 |
| **`hudc`** | 原生优化 HudHudScript 编译器 |
| **`hudi`** | 交互式 REPL Shell 与实时解释器 |
| **`hudconv`** | AST、字节码与数据架构迁移工具 |
| **`hudhudscript-lsp`** | 提供语法高亮、自动补全与悬停文档的语言服务器引擎 |
| **`hudhud_ffi`** | C / Rust 外部函数接口 (FFI) 运行时 |

---

## 统一开发工作流

```
   1. 可视化编程             2. 业务实现                3. 验证与运行
 ┌──────────────────┐      ┌──────────────────┐      ┌──────────────────┐
 │ 图形建模         │ ───► │ 与 AI 智能体协同 │ ───► │ 编译、测试与运行 │
 │ (.hudhudgraph)   │      │ 编写业务代码     │      │ (hudc / hudi)    │
 └──────────────────┘      └──────────────────┘      └──────────────────┘
```

1. **建模:** 使用可视化编程直观构思业务逻辑、智能体管线或数据流。
2. **实现:** 编写 HudHudScript 源码，或与内置 AI 智能体结对完成业务逻辑。
3. **运行与调试:** 直接在 IDE 中利用原生工具链进行编译、断点调试与分析。

---

## 系统要求与安装

您可以从 [GitHub Releases](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46) 页面或通过下方直接链接下载最新的安装包：

### Windows (x64)
* **操作系统:** Windows 10 / 11 (64-bit)
* **下载:** [`hudhud-aide-v0.4.46-win-x64-setup.exe`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-win-x64-setup.exe)
* **SmartScreen / 未签名程序提示说明:**
  由于当前安装程序尚未进行数字签名，Microsoft Defender SmartScreen 可能会弹出 *“Windows 已保护你的电脑”* 提示：
  1. 点击提示窗口中的 **“更多信息”** (*More info*)。
  2. 随后点击 **“仍要运行”** (*Run anyway*) 继续安装。
* *安装程序会自动选择与 CPU 匹配的最优二进制指令级别 (`v1` to `v4`)。*

### Linux (x86_64)
* **操作系统:** Ubuntu 20.04+, Debian 11+, Fedora, Arch Linux, Kali Linux
* **下载:** [`hudhud-aide-v0.4.46-linux-x64-installer.run`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-linux-x64-installer.run)
* **安装步骤:**
  ```bash
  chmod +x hudhud-aide-v0.4.46-linux-x64-installer.run
  ./hudhud-aide-v0.4.46-linux-x64-installer.run
  ```

---

## 社区与链接
 
* **官方网站:** [https://hudhudscript.com](https://hudhudscript.com)
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

## 许可证与支持

HudHud AIDE 是由 **HudHud Script** 开发的专业集成开发环境。

* **代码仓库:** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)

---
*© 2026 HudHud Script. 保留所有权利。*
