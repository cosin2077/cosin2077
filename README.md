## Hi, 我是 cosin2077 👋

Full-stack AI Builder

这些年做过产品、平台、开发者工具、基础设施、Web3、小爬虫、机器人，也写过很多给自己提效的小工具。最近主要在折腾 LLM 和 AI Agent：记忆、工具调用、浏览器自动化、AI 网关、评测，以及怎么让 Agent 真正变得好用。  
I have built products, platforms, developer tools, infra, Web3 bits, crawlers, bots, and plenty of small workflow tools. These days I spend most of my tinkering time on LLMs and AI Agents: memory, tool use, browser automation, gateways, evals, and making agents actually useful.

有些东西想明白了，或者还没完全想明白，我会顺手记下来。主要是分享，也方便未来的自己少踩几次坑。  
I write things down when I figure something out, or when I am still figuring it out. Mostly for sharing, and partly so future me has fewer mysteries to solve.

## 最近关注 / Current Focus

- 让 AI Agent 真的记得住东西，而且记忆可追溯、可重建  
  Making AI Agent memory traceable, rebuildable, and less hand-wavy.
- 搭一些 Agent 基础设施：网关、工具、连接器、运行时、编排  
  Building agent plumbing: gateways, tools, connectors, runtimes, orchestration.
- 做 LLM 代码能力评测，给感觉配一点数据  
  Running LLM coding evals so the vibes have numbers attached.
- 折腾浏览器自动化，尤其是那些必须依赖真实登录态的工作流  
  Playing with browser automation, especially workflows that need a real logged-in session.
- 把突然冒出来的想法快速做成 demo，再看看值不值得继续打磨  
  Turning random ideas into working demos, then deciding which ones deserve more polish.

## 最近项目 / Recent Projects

| Project | Notes |
| --- | --- |
| 🧠 [memo](https://github.com/cosin2077/memo) | 给 AI Agent 做记忆的一次尝试：原始对话可追溯，长期记忆可重建，Agent 也可以自己查证。<br>My attempt to give AI Agents a real, inspectable memory. |
| 🚦 [aigate](https://github.com/cosin2077/aigate) | AI API 网关，用来管理多个模型 Provider：重试、故障切换、多租户、Token、guardrails、文档。<br>An AI API gateway for taming multiple providers in one place. |
| 🔀 [multicall](https://github.com/cosin2077/multicall) | 给 coding agents 用的轻量编排内核。有时候一个 Agent 不够，有时候多个 Agent 又需要一个裁判。<br>A small orchestration kernel for coding agents. |
| 🏭 [app-factory](https://github.com/cosin2077/app-factory) | 按 spec 生成 App seed 的小工厂，目标是快速把想法跑起来，但不要每个 App 都长得像模板。<br>A spec-driven app factory for turning rough ideas into runnable seeds. |
| 📊 [llm-benchmark](https://github.com/cosin2077/llm-benchmark) | FastBench，LLM 代码能力评测工具，多 Provider、规则裁判、LLM 裁判、历史记录和报告。<br>A practical LLM coding benchmark setup with history and reports. |
| 🛡️ [safecafe](https://github.com/cosin2077/safecafe) | Safenet staking 的非托管工具，有 Web App、CLI、交易规划和 Safe Transaction Builder 导出。<br>A non-custodial Safenet staking interface and CLI. |
| ✉️ [agentmail](https://github.com/cosin2077/agentmail) | 给 AI Agent 用的邮件 API。让 Agent 有邮箱，但不用真的打开浏览器装成人类。<br>Email API for AI Agents on Cloudflare Workers. |
| 🌉 [browser-rpc-bridge](https://github.com/cosin2077/browser-rpc-bridge) | 驻留在浏览器里的 RPC 桥，可以让脚本借用真实 Chrome 登录态发请求。<br>A browser-resident RPC bridge for authenticated-session workflows. |
| 🎧 [easyVoice](https://github.com/cosin2077/easyVoice) | 文本/小说转语音、有声书、字幕、流式播放、多角色配音。<br>Text and novel-to-speech, audiobooks, subtitles, streaming playback, and multi-character voices. |
| 📈 [longbridge-va](https://github.com/cosin2077/longbridge-va) | 基于长桥 OpenAPI 的 VA 定投 CLI，把策略计算、模拟、回测这些枯燥数学交给工具。<br>A Value Averaging investment CLI for Longbridge OpenAPI. |
| 🔎 [nodex](https://github.com/cosin2077/nodex) | AI 增强的 Node.js 爬虫平台：队列、代理、提取、存储、索引、监控面板。<br>An AI-enhanced Node.js crawler platform. |
| 💱 [dexflow](https://github.com/cosin2077/dexflow) | DEX 聚合器实验，围绕多链交换、路由比较、钱包集成和实时价格做的一套全栈尝试。<br>A DEX aggregator experiment around multi-chain swaps and route comparison. |
| 🧪 [learn-llm](https://github.com/cosin2077/learn-llm) | 我的 LLM 实验场：mini agents、浏览器自动化、GPT/VITS、连接器、沙箱、RAG、embedding。<br>My LLM playground: mini agents, browser automation, connectors, sandboxes, RAG, embeddings, and notes. |

> 有些项目暂时未开源。Some projects are not open-source yet.

## 技术栈 / Toolbox

<p>
  <img src="https://img.shields.io/badge/TypeScript-0f172a?style=flat-square&logo=typescript&logoColor=60a5fa" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-0f172a?style=flat-square&logo=nodedotjs&logoColor=22c55e" alt="Node.js" />
  <img src="https://img.shields.io/badge/React-0f172a?style=flat-square&logo=react&logoColor=38bdf8" alt="React" />
  <img src="https://img.shields.io/badge/Bun-0f172a?style=flat-square&logo=bun&logoColor=fbf0df" alt="Bun" />
  <img src="https://img.shields.io/badge/pnpm-0f172a?style=flat-square&logo=pnpm&logoColor=facc15" alt="pnpm" />
  <img src="https://img.shields.io/badge/Biome-0f172a?style=flat-square&logo=biome&logoColor=60a5fa" alt="Biome" />
  <img src="https://img.shields.io/badge/Hono-0f172a?style=flat-square&logo=hono&logoColor=eab308" alt="Hono" />
  <img src="https://img.shields.io/badge/Cloudflare-0f172a?style=flat-square&logo=cloudflare&logoColor=f97316" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/SQLite-0f172a?style=flat-square&logo=sqlite&logoColor=38bdf8" alt="SQLite" />
  <img src="https://img.shields.io/badge/PostgreSQL-0f172a?style=flat-square&logo=postgresql&logoColor=60a5fa" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Drizzle-0f172a?style=flat-square&logo=drizzle&logoColor=c4f000" alt="Drizzle ORM" />
  <img src="https://img.shields.io/badge/Docker-0f172a?style=flat-square&logo=docker&logoColor=38bdf8" alt="Docker" />
  <img src="https://img.shields.io/badge/Solidity-0f172a?style=flat-square&logo=solidity&logoColor=e5e7eb" alt="Solidity" />
  <img src="https://img.shields.io/badge/Python-0f172a?style=flat-square&logo=python&logoColor=facc15" alt="Python" />
</p>

## 联系 / Connect

- GitHub: [@cosin2077](https://github.com/cosin2077)
- 我会分享一些 LLM、AI Agent、基础设施、产品工程相关的笔记、实验和半成品想法。  
  I share notes, experiments, and half-finished thoughts around LLMs, AI Agents, infra, and product engineering.
