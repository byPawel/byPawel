<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hey%2C%20I'm%20Pawel%20%F0%9F%91%8B&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%20Product%20Engineer%20%E2%80%A2%20Full%20Stack%20Developer%20%E2%80%A2%20Frontend%20Lead&descAlignY=55&descSize=16" width="100%"/>

**AI Product Engineer building production AI tooling — MCP servers, multi-model orchestration, and agent memory systems.**

🟢 Open to **AI Product Engineer / Full-Stack** roles — AI tooling, developer platforms, agent workflows

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pawel-pawlowski-dev/)
[![Blog](https://img.shields.io/badge/bypawel.com-000000?style=for-the-badge&logo=hashnode&logoColor=white)](https://bypawel.com)
[![GitHub followers](https://img.shields.io/github/followers/byPawel?style=for-the-badge&logo=github&logoColor=white&color=181717)](https://github.com/byPawel)

</div>

---

## 🧠 About Me

I build AI products that go beyond chat UIs: published npm packages, MCP servers, orchestration systems, and memory layers that developers actually run. I design systems where multiple AI models collaborate — checking each other's work, debating solutions, and producing better outputs together.

- 🔭 Currently building **[TachiBot](https://tachibot.com)** — open-source multi-model AI orchestration, live on npm
- 🧩 Exploring agent memory architectures with **[dokoro](https://github.com/byPawel/dokoro)**
- ✍️ Writing about AI architecture & multi-model systems at **[bypawel.com](https://bypawel.com)**
- 🎯 3,700+ contributions in the last year

---

## 🚀 Featured Projects

### 🤖 [tachibot-mcp](https://github.com/byPawel/tachibot-mcp) — multi-model AI orchestration over MCP

[![npm version](https://img.shields.io/npm/v/tachibot-mcp?style=flat-square&logo=npm&color=CB3837)](https://www.npmjs.com/package/tachibot-mcp)
[![npm downloads](https://img.shields.io/npm/dm/tachibot-mcp?style=flat-square&logo=npm)](https://www.npmjs.com/package/tachibot-mcp)
![stars](https://img.shields.io/github/stars/byPawel/tachibot-mcp?style=flat-square&logo=github)
![last commit](https://img.shields.io/github/last-commit/byPawel/tachibot-mcp?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Problem:** LLM outputs are often accepted without independent verification — hallucinations slip through.
**What I built:** A TypeScript MCP server that runs GPT, Gemini, Grok, Qwen, Kimi & more in parallel so they critique and cross-check each other's work before you act on it. 50+ tools, multi-model jury synthesis, configurable profiles.

```bash
npm install -g tachibot-mcp
```

### 🧠 [dokoro](https://github.com/byPawel/dokoro) — multi-layer memory for AI agents

[![npm version](https://img.shields.io/npm/v/dokoro?style=flat-square&logo=npm&color=CB3837)](https://www.npmjs.com/package/dokoro)
[![npm downloads](https://img.shields.io/npm/dm/dokoro?style=flat-square&logo=npm)](https://www.npmjs.com/package/dokoro)
![stars](https://img.shields.io/github/stars/byPawel/dokoro?style=flat-square&logo=github)
![last commit](https://img.shields.io/github/last-commit/byPawel/dokoro?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Problem:** Most agent "memory" is a toy key-value store that forgets everything between sessions.
**What I built:** An MCP memory server with working, episodic, semantic, procedural & affective memory layers — inspectable, persistent memory for Claude Code and any MCP client.

### ⚡ [tachi-agent](https://github.com/byPawel/tachi-agent) — local-first orchestration agent

![stars](https://img.shields.io/github/stars/byPawel/tachi-agent?style=flat-square&logo=github)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MIT](https://img.shields.io/badge/MIT-green?style=flat-square)

**Problem:** Agent workflows usually depend on hosted APIs and hidden state.
**What I built:** A local-first ReAct agent that fuses dokoro memory + tachibot multi-model council over MCP. Pluggable brains: Qwen via Ollama, Nous Hermes via vLLM/llama.cpp, or any OpenAI-compatible endpoint — runs 100% local.

### 🌐 [TachiBot](https://tachibot.com) — the platform

![Live](https://img.shields.io/badge/Live-tachibot.com-black?style=flat-square&logo=vercel)

Open-source AI orchestration platform coordinating GPT, Gemini, Perplexity, Grok, Qwen, Kimi & MiniMax through unified workflows.

---

## 🛠️ Tech Stack

**AI Engineering** — agentic AI (ReAct agents, tool use, multi-agent workflows), MCP servers & clients, multi-model orchestration, agent frameworks (LangGraph, Mastra, CrewAI), agent memory systems, LLM observability & evals (Langfuse, Evalite), local-first LLM workflows (Ollama/Qwen), OpenAI / Anthropic / Gemini / OpenRouter APIs

![Agentic AI](https://img.shields.io/badge/Agentic_AI-FF6F00?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Protocol-blueviolet?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![Mastra](https://img.shields.io/badge/Mastra-000000?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A60B5?style=for-the-badge&logoColor=white)
![Evalite](https://img.shields.io/badge/Evalite-evals-yellow?style=for-the-badge)

**Full Stack** — TypeScript, React, Next.js, Node.js, Python, Django, GraphQL & REST API design, state management (Redux, Zustand), data viz with D3.js, E2E testing with Playwright, open-source package maintenance

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAF8?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433D38?style=for-the-badge&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3dotjs&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logoColor=white)

---

## ✍️ Writing

I write about AI architecture, multi-model orchestration, and building AI-powered applications.

➡️ **[Read on bypawel.com](https://bypawel.com)**

---

## 🤝 Let's Talk

Open to **AI Product Engineer** and **Full-Stack Engineer** roles — especially teams building AI tools, developer platforms, agents, or production LLM workflows.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Reach_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pawel-pawlowski-dev/)

*Building the future of AI collaboration, one model at a time.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
