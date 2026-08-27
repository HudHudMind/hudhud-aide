# Privacy Policy for HudHud AIDE

**Last Updated:** August 27, 2026  
**Official Website:** [https://hudhudscript.com](https://hudhudscript.com)  
**Organization:** HudHud Script

---

## 🛡️ Our Core Privacy Commitment

**HudHud AIDE is engineered with a strict Privacy-First and Zero-Telemetry architecture.**

We firmly believe that your code, workspace files, architecture diagrams, and development thoughts belong exclusively to you. HudHud Script does **NOT** collect, track, sell, or analyze your personal data, source code, or IDE usage patterns.

---

## 1. Zero Telemetry & Diagnostics Policy

* **Disabled by Default:** Built-in telemetry, crash reporting pings to centralized telemetry collectors, and background usage analytics are **100% disabled** by default in HudHud AIDE.
* **No Code Harvesting:** We never upload, inspect, or store your project files, source code, commit history, or workspace structure on our servers.
* **No Behavioral Tracking:** HudHud AIDE does not track your keystrokes, editor interactions, commands executed, or time spent coding.

---

## 2. Local-First AI Agent & Toolchain Execution

* **Direct-to-Provider AI Calls:** When you interact with the AI Coding Agent or Visual Designer, your queries and prompt context are sent **directly from your local machine to your chosen AI provider** (e.g., Anthropic, OpenAI, Google Gemini, Ollama, or local LLMs) using your own credentials.
* **No Middleman Server:** No prompt data passes through any intermediary proxy or collection server managed by HudHud Script.
* **Local Models & Offline Use:** When using local AI backends (like Ollama or local LLMs), no network traffic leaves your computer.

---

## 3. Network Communications

HudHud AIDE initiates outbound network connections **only** for essential, user-initiated actions:

1. **AI Model Requests:** Direct TLS-encrypted API calls to user-configured AI providers.
2. **Extensions Marketplace:** Fetching and updating community extensions via standard marketplace endpoints.
3. **Version & Update Checks:** Checking for the latest official HudHud AIDE release tags on GitHub.
4. **Git Operations:** User-triggered git fetch, pull, and push commands to user-configured remotes.

---

## 4. Local Data Storage & Secrets

* **API Keys & Credentials:** All API keys, environment variables, and authentication tokens are stored securely on your local filesystem using your operating system's native secure credential storage (such as Windows Credential Manager, macOS Keychain, or Linux Secret Service).
* **Workspace State:** Project settings, chat history cache, and local preferences remain stored strictly inside your local `.hudhud` folder and IDE application data directory.

---

## 5. Third-Party Services & Links

When you choose to visit external documentation, issue trackers, or community channels (such as GitHub, YouTube, or X), your interaction is governed by the privacy policies of those respective third-party platforms.

---

## 6. Contact & Inquiries

For questions, feedback, or security inquiries regarding this Privacy Policy:
* **Website:** [https://hudhudscript.com](https://hudhudscript.com)
* **GitHub Issues:** [https://github.com/HudHudMind/hudhud-aide/issues](https://github.com/HudHudMind/hudhud-aide/issues)
* **Community:** [@hudhud_script](https://x.com/hudhud_script)
