<p align="center">
  <img src="https://raw.githubusercontent.com/BugTraceAI/BugTraceAI/master/logo.png" alt="BugTraceAI" width="120" />
</p>

<h1 align="center">BugTrace-AI has evolved into BugTraceAI v2</h1>

<p align="center">
  <a href="https://github.com/BugTraceAI/BugTraceAI"><img src="https://img.shields.io/badge/New_Repo-BugTraceAI_v2-blue?style=for-the-badge&logo=github" alt="New Repo" /></a>
  <a href="https://bugtraceai.com"><img src="https://img.shields.io/badge/Website-bugtraceai.com-green?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" /></a>
</p>

---

> **This repository is archived.** The project has been completely rebuilt from the ground up as **BugTraceAI v2** — a fully autonomous, multi-agent AI security scanning platform.

## What changed?

BugTrace-AI started as a browser-based AI analysis suite (the code in this repo). **BugTraceAI v2** is a completely new platform:

| | BugTrace-AI (this repo) | BugTraceAI v2 (new) |
|---|---|---|
| **Approach** | Manual AI-assisted analysis | Fully autonomous multi-agent scanning |
| **Scanning** | Non-invasive reconnaissance | Active exploitation + browser-based validation |
| **Specialists** | General-purpose AI chat | 10+ dedicated agents (XSS, SQLi, SSRF, IDOR, LFI, RCE, XXE, JWT...) |
| **Validation** | AI analysis only | Headless Chromium + Vision AI screenshot confirmation |
| **Architecture** | Single React app | CLI scanner + Web dashboard + Docker deployment |
| **Fuzzers** | None | Go-compiled high-speed fuzzers |
| **Pipeline** | Single-pass analysis | 5-phase pipeline: Discovery, Analysis, Consolidation, Exploitation, Validation |
| **Deployment** | Manual Docker build | One-command wizard with 3 deployment modes |
| **API** | None | Full REST API + WebSocket real-time streaming |

## Get BugTraceAI v2

**One-command install:**

```bash
git clone https://github.com/BugTraceAI/BugTraceAI-Launcher.git ~/bugtraceai-launcher && ~/bugtraceai-launcher/launcher.sh
```

**Requirements:** Docker 24.0+, Git, 4 GB RAM, [OpenRouter API key](https://openrouter.ai/keys)

## Links

- **Main repo:** [github.com/BugTraceAI/BugTraceAI](https://github.com/BugTraceAI/BugTraceAI)
- **CLI (scanner engine):** [github.com/BugTraceAI/BugTraceAI-CLI](https://github.com/BugTraceAI/BugTraceAI-CLI)
- **Web dashboard:** [github.com/BugTraceAI/BugTraceAI-WEB](https://github.com/BugTraceAI/BugTraceAI-WEB)
- **Launcher (Docker deploy):** [github.com/BugTraceAI/BugTraceAI-Launcher](https://github.com/BugTraceAI/BugTraceAI-Launcher)
- **Website:** [bugtraceai.com](https://bugtraceai.com)

## Demo videos (original BugTrace-AI)

These demos show the original version of the tool (this repo):

| English | Spanish |
| :---: | :---: |
| [![Demo English](https://img.youtube.com/vi/exrqesNWp1M/0.jpg)](https://youtu.be/exrqesNWp1M) | [![Demo Spanish](https://img.youtube.com/vi/CwT66Uqe6to/0.jpg)](https://youtu.be/CwT66Uqe6to) |

## License

MIT License. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with care by Albert C. <a href="https://x.com/yz9yt">@yz9yt</a><br/>
  <a href="https://bugtraceai.com">bugtraceai.com</a>
</p>
