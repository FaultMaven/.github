
<p align="center">
  <img src="fm-logo-dark.svg" alt="FaultMaven" width="180" />
</p>

<h1 align="center">FaultMaven</h1>

<p align="center">
  <strong>The AI-Powered Troubleshooting Copilot for Modern Engineering</strong>
</p>

<p align="center">
  Stop context-switching. Start fixing.
</p>

<p align="center">
  <a href="https://github.com/FaultMaven/faultmaven-deploy">
    <img src="https://img.shields.io/badge/Deploy_Now-Open_Source-blue?style=for-the-badge" alt="Deploy" />
  </a>
  &nbsp;
  <a href="https://faultmaven.ai/founders">
    <img src="https://img.shields.io/badge/Join-Beta_Founders-green?style=for-the-badge" alt="Beta Founders" />
  </a>
  &nbsp;
  <a href="https://faultmaven.ai">
    <img src="https://img.shields.io/badge/Website-faultmaven.ai-purple?style=for-the-badge" alt="Website" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/FaultMaven/faultmaven/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="License" />
  </a>
</p>

---

## The Problem

Your monitoring tools tell you **what** broke. Generic LLMs guess **why**, but they can't see your infrastructure.

You end up copy-pasting logs into ChatGPT, losing context, and solving the same problems over and over.

**FaultMaven bridges this gap.**

---

## What Is FaultMaven?

An open-source AI copilot that connects your full stack—logs, metrics, traces, configs, and code—to a unified knowledge engine.

- **Deep Context Awareness** — Correlates your entire stack, not just error snippets
- **Tiered Knowledge Engine** — Global patterns + Team runbooks + Personal context
- **Zero Context-Switching** — Browser extension overlays intelligence on your existing tools
- **Continuous Learning** — Every resolved case becomes searchable institutional knowledge

---

## Quick Start

```bash
git clone https://github.com/FaultMaven/faultmaven-deploy.git && cd faultmaven-deploy
cp .env.example .env && ./faultmaven start
```

**Dashboard:** http://localhost:3000 — **API:** http://localhost:8090

→ [Full deployment guide](https://github.com/FaultMaven/faultmaven-deploy)

---

## The Ecosystem

<table>
<tr>
<td width="50%" valign="top">

**Start Here**

| Repository | Description |
| :--- | :--- |
| [faultmaven-deploy](https://github.com/FaultMaven/faultmaven-deploy) | Deploy in 5 minutes |
| [faultmaven](https://github.com/FaultMaven/faultmaven) | Architecture & docs |

</td>
<td width="50%" valign="top">

**User Interfaces**

| Repository | Description |
| :--- | :--- |
| [faultmaven-copilot](https://github.com/FaultMaven/faultmaven-copilot) | Browser extension |
| [faultmaven-dashboard](https://github.com/FaultMaven/faultmaven-dashboard) | Web UI |

</td>
</tr>
</table>

<details>
<summary><strong>All Microservices →</strong></summary>

| Service | Purpose |
| :--- | :--- |
| [fm-api-gateway](https://github.com/FaultMaven/fm-api-gateway) | Request routing & auth |
| [fm-agent-service](https://github.com/FaultMaven/fm-agent-service) | AI troubleshooting engine |
| [fm-knowledge-service](https://github.com/FaultMaven/fm-knowledge-service) | Semantic search & RAG |
| [fm-case-service](https://github.com/FaultMaven/fm-case-service) | Investigation tracking |
| [fm-evidence-service](https://github.com/FaultMaven/fm-evidence-service) | File & log uploads |
| [fm-auth-service](https://github.com/FaultMaven/fm-auth-service) | Authentication |
| [fm-session-service](https://github.com/FaultMaven/fm-session-service) | Session management |
| [fm-job-worker](https://github.com/FaultMaven/fm-job-worker) | Background processing |
| [fm-core-lib](https://github.com/FaultMaven/fm-core-lib) | Shared utilities |

</details>

---

## Open Source & Cloud

**Self-Hosted** — Full control. Free forever. Apache 2.0.
Run on your infrastructure with your choice of LLM (OpenAI, Anthropic, or local via Ollama).

**Cloud** — Zero ops. Pre-loaded knowledge base. Team features.
Free during beta. → [Join Beta Founders](https://faultmaven.ai/founders)

→ [Compare options](https://github.com/FaultMaven/faultmaven#self-hosted-vs-enterprise-cloud)

---

## Get Involved

<table>
<tr>
<td align="center" width="33%">

### 🚀 Deploy

Self-host in 5 minutes.
Free forever.

**[Get Started →](https://github.com/FaultMaven/faultmaven-deploy)**

</td>
<td align="center" width="33%">

### 🤝 Contribute

Code, docs, or ideas.
All welcome.

**[Contributing Guide →](https://github.com/FaultMaven/faultmaven/blob/main/CONTRIBUTING.md)**

</td>
<td align="center" width="33%">

### 💬 Community

Questions, feedback,
show & tell.

**[Discussions →](https://github.com/FaultMaven/faultmaven/discussions)**

</td>
</tr>
</table>

---

<p align="center">
  <strong>FaultMaven</strong> — Your AI copilot for troubleshooting.
</p>

<p align="center">
  <sub>
    <a href="https://faultmaven.ai">Website</a> ·
    <a href="https://github.com/FaultMaven/faultmaven">Documentation</a> ·
    <a href="https://faultmaven.ai/founders">Beta Founders</a>
  </sub>
</p>
