<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2500&pause=900&color=FF4444&center=true&vCenter=true&repeat=true&width=820&height=36&lines=AI+Security+Researcher+%7C+AI+%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6;LLM+%2F+Agent+Red+Teaming+%7C+%E5%A4%A7%E6%A8%A1%E5%9E%8B%E4%B8%8E+Agent+%E7%BA%A2%E9%98%9F;MCP+Security+%7C+MCP+%E4%B8%8E%E5%B7%A5%E5%85%B7%E9%93%BE%E5%AE%89%E5%85%A8)](https://github.com/Coff0xc)

<br/>

<a href="https://github.com/Coff0xc?tab=followers"><img src="https://img.shields.io/github/followers/Coff0xc?style=flat&logo=github&label=Followers&color=181717" alt="GitHub followers" /></a>&nbsp;
<a href="https://github.com/Coff0xc?tab=repositories&sort=stargazers"><img src="https://img.shields.io/github/stars/Coff0xc?style=flat&logo=github&label=Stars&color=181717" alt="GitHub stars" /></a>&nbsp;
<img src="https://komarev.com/ghpvc/?username=Coff0xc&style=flat&color=grey" alt="Profile views" />

</div>

---

```text
$ whoami
Coff0xc - AI security researcher.
专注 AI 红队、LLM 应用安全、Agent 运行时滥用、MCP/工具链风险。

$ mission
Build reproducible tools for authorized testing and defensive validation.
构建可复现的授权测试工具，把攻击路径转化为防御证据。

$ current-focus
Prompt injection -> Agent hijacking -> MCP exploitation -> Tool poisoning
提示词注入 -> Agent 劫持 -> MCP 利用 -> 工具投毒
```

---

### Research Areas / 研究方向

| Area / 方向 | What I work on / 关注内容 |
| --- | --- |
| LLM and agent red teaming / 大模型与 Agent 红队 | Reproducible attack chains for authorized model, agent, and workflow assessment. 授权场景下的大模型、Agent、工作流攻击链复现与评估。 |
| MCP and tool security / MCP 与工具安全 | Tool poisoning, unsafe tool invocation, sandbox boundaries, and protocol-level abuse paths. 工具投毒、不安全调用、沙箱边界与协议级滥用路径。 |
| Secret and token exposure / 密钥与 Token 暴露 | GitHub/API key discovery workflows, validation safety, and remediation-oriented evidence. 面向修复的密钥发现、验证安全和证据产出。 |
| Defensive automation / 防御自动化 | CI-friendly reports, SARIF output, ATT&CK-style mapping, and repeatable test artifacts. CI 报告、SARIF、ATT&CK 映射和可重复测试产物。 |

---

### Featured Projects / 代表项目

| Project / 项目 | Focus / 重点 | Defensive value / 防御价值 |
| --- | --- | --- |
| [AutoRedTeam-Orchestrator](https://github.com/Coff0xc/AutoRedTeam-Orchestrator) | AI red team orchestration with SDK, CLI, MCP, Docker sandboxing, and CI artifacts. AI 红队编排、SDK/CLI/MCP、Docker 沙箱与 CI 证据。 | Turns ad hoc testing into repeatable assessment workflows. 把零散测试沉淀为可复现评估流程。 |
| [catchclaw](https://github.com/Coff0xc/catchclaw) | Multi-platform agent security testing with DAG-style attack chains and Rust components. 多平台 Agent 安全测试、DAG 攻击链与 Rust 组件。 | Helps evaluate agent behavior, tool trust boundaries, and exploit paths. 评估 Agent 行为、工具信任边界和利用路径。 |
| [LLM-Security-Assessment-Framework](https://github.com/Coff0xc/LLM-Security-Assessment-Framework) | LLM assessment framework covering jailbreak, prompt injection, and adapter-driven testing. 覆盖越狱、提示词注入和多适配器测试的大模型评估框架。 | Gives teams structured scenarios for measuring model and app resilience. 为模型和应用韧性测试提供结构化场景。 |
| [CTF-MCP](https://github.com/Coff0xc/CTF-MCP) | MCP server for CTF workflows across web, crypto, pwn, and challenge automation. 面向 Web/Crypto/Pwn/自动解题流程的 CTF MCP Server。 | Demonstrates how tool-rich agents can be constrained, tested, and audited. 展示富工具 Agent 如何约束、测试和审计。 |
| [Github-API-scan](https://github.com/Coff0xc/Github-API-scan) | GitHub API key scanning and validation workflows for multiple AI providers. 多 AI Provider 的 GitHub API Key 扫描与验证流程。 | Supports secret discovery, exposure triage, and remediation evidence. 支持密钥发现、暴露分级和修复证据。 |
| [coffee-skill](https://github.com/Coff0xc/coffee-skill) | Codex/agent workflow skill pack for dev, RAG, API/data, and security review tasks. 面向开发、RAG、API/数据和安全审查的 Agent 工作流技能包。 | Encodes repeatable engineering and security workflows for agentic development. 固化可复用的工程与安全工作流。 |

---

### Operating Principles / 行动原则

- Authorized testing only / 仅用于授权测试：research code is intended for owned systems, lab environments, CTFs, or explicitly approved assessments.
- Evidence over claims / 证据优先：prefer reproducible commands, logs, SARIF, screenshots, and minimal proof artifacts.
- Defender-first release style / 防御者优先：publish methods in a way that helps detection, hardening, and regression testing.
- Small tools, sharp boundaries / 小工具、清边界：avoid hidden production assumptions, credential leakage, and irreversible actions.

---

### Stack / 技术栈

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,rust,docker,linux,git,github,vscode,bash&theme=dark&perline=8" alt="Python, Rust, Docker, Linux, Git, GitHub, VS Code, Bash" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MCP_Protocol-FF6B35?style=for-the-badge" alt="MCP Protocol" />
  <img src="https://img.shields.io/badge/LLM_Security-DC143C?style=for-the-badge" alt="LLM Security" />
  <img src="https://img.shields.io/badge/Agent_Security-4B0082?style=for-the-badge" alt="Agent Security" />
  <img src="https://img.shields.io/badge/Prompt_Injection-8B0000?style=for-the-badge" alt="Prompt Injection" />
  <img src="https://img.shields.io/badge/Tool_Security-006400?style=for-the-badge" alt="Tool Security" />
</p>

---

### Activity / 活动

Private contribution visibility is controlled by GitHub profile settings.
This README uses the contribution graph generated from the visible profile
activity instead of third-party stats cards.

私有贡献展示由 GitHub 个人资料设置控制。
这里使用基于可见 Profile 活动生成的贡献图，不使用容易漏私有数据的第三方统计卡。

<p align="center">
  <a href="https://github.com/Coff0xc?tab=overview&from=2026-05-01&to=2026-05-24">
    <img src="https://img.shields.io/badge/GitHub_Profile_Activity-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile activity" />
  </a>
</p>

### Contributions / 贡献

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Coff0xc/Coff0xc/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Coff0xc/Coff0xc/output/github-snake.svg" />
  <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/Coff0xc/Coff0xc/output/github-snake-dark.svg" />
</picture>

---

<div align="center">

```text
COFF0XC :: break carefully, document clearly
谨慎验证，清晰记录，让防御更可复现
```

</div>
