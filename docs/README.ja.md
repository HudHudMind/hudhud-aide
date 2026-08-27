# HudHud AIDE: 自律型インテリジェント開発環境

<p align="center">
  <b>Languages:</b> <a href="../README.md">English</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.ar.md">العربية</a> | <b>日本語</b> | <a href="README.ru.md">Русский</a> | <a href="README.es.md">Español</a> | <a href="README.pt.md">Português</a> | <a href="README.zh.md">简体中文</a>
</p>

---

[![Version](https://img.shields.io/badge/version-v0.4.46-orange.svg)](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)](https://github.com/HudHudMind/hudhudscript)
[![Toolchain](https://img.shields.io/badge/toolchain-HudHudScript%20x86_64%20(v1..v4)-green.svg)](https://github.com/HudHudMind/hudhudscript)

**HudHud AIDE** は、[**HudHudScript**](https://github.com/HudHudMind/hudhudscript) を主軸に設計された統合開発環境（IDE）であり、内蔵エディタと AI コーディングエージェントを通じて **Python、Rust、C/C++、TypeScript/JavaScript** などの最新プログラミング言語でのソースコード編集およびプロジェクト開発にも対応しています。

本環境は、2つの相互補完的な開発ワークフローを統合しています：
* **コード編集とエージェント支援:** ワークスペースを認識する AI コーディングエージェントによる、多言語ソースコードの作成、診断、リファクタリング。
* **ビジュアルプログラミング（`.hudhudgraph`）:** ネイティブ **HudHudScript** のロジックフローおよびマルチエージェントパイプラインを視覚的にモデル化・構造化・コード生成するノードベースのシステム。

HudHud AIDE は、**従来のソフトウェア開発手法と現代のパラダイム** をシームレスに架橋します：
* **エージェンティック・プログラミング（Agentic Programming）:** 自律型エージェント、ロール、ツール連携、マルチエージェント協調の定義と展開。
* **ループエンジニアリング＆ループチェーン（Loop Engineering & Loop Chains）:** フィードバック駆動型の実行ループ、評価サイクル、反復的改善チェーンの構築。
* **ガバナンスシステム（Governance）:** 動作制約、安全ポリシー、検証ルール、権限境界をコードおよびグラフモデル内で直接適用。
* **主体指向プログラミング（SOP / Subject-Oriented Programming）:** 静的なオブジェクトではなく、能動的な主体、文脈、意図を中心にソフトウェアを構造化。

エンジニアや開発者は、ビジュアルプログラミングによる視覚的操作、ソースコードの直接記述、または統合コーディングエージェントとの協調作業を通じて、独自の AI エージェントやシステムアーキテクチャを自在に構築できます。

---

## 主な機能概要

```
┌─────────────────────────────────────────────────────────────┐
│                        HudHud AIDE                          │
├───────────────────┬─────────────────────┬───────────────────┤
│ ビジュアルプログラ│    コーディング     │   HudHudScript    │
│      ミング       │     エージェント    │ (ハードウェア最適 │
│  (.hudhudgraph)   │ (ワークスペース認識)│   化ランタイム)   │
└───────────────────┴─────────────────────┴───────────────────┘
```

* **視覚的アーキテクチャ＆ロジックモデリング:** ノードベースのビジュアルプログラミングにより、アプリケーションフロー、エージェントパイプライン、状態構造を視覚的に設計。
* **自律型 AI ペアプログラミング:** コードベース、プロジェクト構成、ビジュアルグラフファイルを直接分析する統合エージェント。
* **HudHudScript 言語パラダイムのネイティブサポート:** Agentic Programming、Loop Engineering、Governance ルール、SOP を言語レベルで統合。
* **事前構成済みツールチェーン:** CPU（`x86-64-v1` to `v4`）に合わせて最適化されたコンパイラ、インタープリタ、LSP、パッケージマネージャを標準搭載。

---

## ビジュアルプログラミングと HudHudGraphs

HudHud AIDE の **ビジュアルプログラミング** は、ソースコードと並行してソフトウェアアーキテクチャやワークフローを視覚的に設計・検証するためのインタラクティブなキャンバスを提供します。

ビジュアルアーキテクチャは標準の **`.hudhudgraph`** ファイルとして保存されます。

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

### 主な機能:
* **240種類以上の専用ノード:** アプリケーションフロー、エージェント定義、データパイプライン、ステートマシン、ガバナンスルールなどを網羅するノード群。
* **型安全なピン接続:** 型検証を備えた明確なデータチャネルと実行フロー。
* **プロパティインスペクター:** 任意のノードを選択し、パラメータや挙動をリアルタイムに設定。
* **ハイブリッドワークフロー:** 不要なコード生成オーバーヘッドなしに、`.hudhudgraph` と標準 `.hud` コードを併用可能。

### 使用手順:
1. ワークスペースで `.hudhudgraph` ファイルを開くか新規作成します。
2. エディタタブの **「Open with Visual Designer」** をクリックします。
3. 左側の **パレット** からノードをキャンバスにドラッグします。
4. ノード間の実行パスとデータピンを接続します。
5. 右側のインスペクターパネルでプロパティを設定し、保存します（`Ctrl + S` / `Cmd + S`）。

---

## 統合 AI コーディングエージェント

HudHud AIDE には、プロジェクトワークスペース全体を直接認識して動作する AI コーディングアシスタントが統合されています。

### 主な支援機能:
* **ワークスペース分析:** ソースファイル、プロジェクト設定、`.hudhudgraph` アーキテクチャを包括的に把握。
* **複数ファイルの一括実装:** 複数のファイルにまたがる機能追加やリファクタリングをワンステップで実行。
* **診断とエラー解決:** コンパイラ警告、実行時例外、型エラーを特定し、検証済みの修正を提案。
* **タスクの自動化:** 複数ステップの開発計画、テスト実行、マイグレーションを自動推進。

---

## HudHudScript 言語・パラダイムサポート

HudHud AIDE は、[**HudHudScript**](https://github.com/HudHudMind/hudhudscript) 言語の主要パラダイムをネイティブに理解し支援します：

* **エージェンティック・プログラミング（Agentic Programming）:** 自律エージェント、役割、ツール、マルチエージェント連携を記述する構文。
* **ループエンジニアリング（Loop Engineering）:** アクション、検証、反復改善を組み合わせた構造化フィードバックループ。
* **ガバナンスシステム（Governance）:** ルール、制約、監査、権限をコードおよびグラフで直接定義。
* **主体指向プログラミング（SOP）:** 主体、文脈、振る舞いの責任を中心に据えたソフトウェアモデリング。

---

## ネイティブ HudHudScript ツールチェーン

HudHud AIDE には完全なネイティブツールチェーンが同梱されています。インストール時に CPU 機能（SSE4.2、AVX2、AVX-512）を検出し、最適なバイナリ（`x86-64-v1` to `v4`）を自動設定します：

| ツール | 役割 |
| :--- | :--- |
| **`hudhud`** | CLI ランタイムおよびアプリケーション実行エンジン |
| **`hudc`** | ネイティブ最適化コンパイラ |
| **`hudi`** | インタラクティブ REPL シェルおよびインタープリタ |
| **`hudconv`** | AST、バイトコード、スキーマ移行ユーティリティ |
| **`hudhudscript-lsp`** | シンタックスハイライト、補完、ホバードキュメントを提供する LSP エンジン |
| **`hudhud_ffi`** | C / Rust 外部関数インターフェース（FFI）ランタイム |

---

## 統合開発ワークフロー

```
   1. ビジュアルプログラミング    2. 実装                    3. 検証・実行
 ┌───────────────────────┐      ┌──────────────────┐      ┌──────────────────┐
 │ グラフモデリング      │ ───► │ AI エージェント  │ ───► │ コンパイル・テスト│
 │ (.hudhudgraph)        │      │ とコード記述     │      │ 実行 (hudc/hudi) │
 └───────────────────────┘      └──────────────────┘      └──────────────────┘
```

1. **モデリング:** ビジュアルプログラミングでロジック、エージェント構成、パイプラインを視覚的に設計します。
2. **実装:** HudHudScript コードを記述するか、統合 AI エージェントと協力してビジネスロジックを実装します。
3. **実行とデバッグ:** ネイティブバイナリとインタラクティブツールを使用して IDE 内で直接実行・検証します。

---

## システム要件とインストール

最新のインストールパッケージは [GitHub Releases](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46) ページまたは以下の直接リンクからダウンロードできます：

### Windows (x64)
* **OS:** Windows 10 / 11 (64-bit)
* **ダウンロード:** [`hudhud-aide-v0.4.46-win-x64-setup.exe`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-win-x64-setup.exe)
* **SmartScreen / 未署名バイナリに関する注意:**
  本インストーラは現在デジタル未署名のため、Microsoft Defender SmartScreen により「*Windows によって PC が保護されました*」と表示される場合があります：
  1. 画面上の **「詳細情報」**（*More info*）をクリックします。
  2. **「実行」**（*Run anyway*）ボタンをクリックしてインストールを続行してください。
* *インストーラが CPU 最適化バイナリレベル（`v1` to `v4`）を自動設定します。*

### Linux (x86_64)
* **OS:** Ubuntu 20.04+, Debian 11+, Fedora, Arch Linux, Kali Linux
* **ダウンロード:** [`hudhud-aide-v0.4.46-linux-x64-installer.run`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-linux-x64-installer.run)
* **インストール:**
  ```bash
  chmod +x hudhud-aide-v0.4.46-linux-x64-installer.run
  ./hudhud-aide-v0.4.46-linux-x64-installer.run
  ```

---

## コミュニティとリンク
 
* **Webサイト:** [https://hudhudscript.com](https://hudhudscript.com)
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

## ライセンス・お問い合わせ

HudHud AIDE は **HudHud Script** が開発するプロフェッショナルな統合開発環境です。

* **リポジトリ:** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)

---
*© 2026 HudHud Script. All rights reserved.*
