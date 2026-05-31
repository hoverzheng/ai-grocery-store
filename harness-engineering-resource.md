# Agent Harness 资源汇总
> 
> 本文档汇总了当前关于 AI Agent Harness（智能体编排框架）的相关文章、书籍、开源框架、技能和工具资源。

---

## 目录

1. [核心 Agent Harness 框架](#核心-agent-harness-框架)
2. [主流 AI Agent 框架](#主流-ai-agent-框架)
3. [Awesome 列表与资源汇总](#awesome-列表与资源汇总)
4. [终端/CLI Agent 工具](#终端 cli-agent-工具)
5. [多智能体协作系统](#多智能体协作系统)
6. [学习与文档资源](#学习与文档资源)
7. [协议与标准](#协议与标准)
8. [可观测性与评估工具](#可观测性与评估工具)

---

## 核心 Agent Harness 框架

| 名称 | 链接 | 说明 | Stars |
|------|------|------|-------|
| **ECC** | https://github.com/affaan-m/ECC | Agent harness 性能优化系统，提供技能、记忆、安全和研究优先开发功能，支持 Claude Code、Codex、Opencode 等 | 199,821 |
| **deer-flow** | https://github.com/bytedance/deer-flow | 字节跳动开源的长周期 SuperAgent harness，支持研究、编码和创建任务，具备沙箱、记忆、工具、技能和子代理功能 | 70,069 |
| **oh-my-openagent** | https://github.com/code-yeongyu/oh-my-openagent | 最佳 agent harness（前身为 oh-my-opencode），提供完整的智能体编排能力 | 60,392 |
| **agents** | https://github.com/wshobson/agents | 多 harness 智能体插件市场，支持 Claude Code、Codex CLI、Cursor、OpenCode 和 Gemini CLI | 36,176 |
| **oh-my-agent** | https://github.com/first-fluke/oh-my-agent | 便携式、供应商无关的 agent harness，支持项目特定技能、工作流和代理团队 | 1,038 |
| **dexto** | https://github.com/truffle-ai/dexto | 编码智能体和通用 agent harness，用于构建和编排智能体应用 | 630 |
| **Citadel** | https://github.com/SethGammon/Citadel | Claude Code 的智能体编排 harness，四层路由、跨会话持久化、并行代理 | 579 |
| **KARIMO** | https://github.com/opensesh/KARIMO | Claude Code harness 工程插件，产品驱动的智能体编排，支持子代理 | 203 |
| **maestro** | https://github.com/ReinaMacCredy/maestro | 代码库专用的 agent harness，为 Claude Code、Codex 和 CI 提供共享任务系统 | 179 |
| **argue** | https://github.com/onevcat/argue | Harness 无关的多智能体共识工作流编排包 | 242 |
| **omnicoreagent** | https://github.com/omnirexflora-labs/omnicoreagent | 开源 Python agent harness，支持工具、MCP、记忆、工作区、遥测、子代理 | 241 |
| **agentflow** | https://github.com/berabuddies/agentflow | 以编程方式编排数千个智能体和 harness 的图系统 | 1,262 |
| **nexent** | https://github.com/ModelEngine-Group/nexent | 零代码平台，使用 Harness Engineering 原理自动生成生产级 AI 智能体 | 4,797 |
| **agentic-harness-patterns-skill** | https://github.com/keli-wen/agentic-harness-patterns-skill | Agent harness 工程技能：记忆、权限、上下文工程、多智能体协调 | 282 |
| **harness-kit** | https://github.com/deepklarity/harness-kit | AI 智能体构建工具包：不仅编排，还包括工程模式 | 75 |
| **agent-design-patterns** | https://github.com/huangjia2019/agent-design-patterns | 7×6 智能体架构框架，28 个模式，可运行的 Python 代码 | 29 |
| **agent-harness-engineering** | https://github.com/cauchyturing/agent-harness-engineering | 91 个生产验证模式，从 51.2 万行代码库中提取，涵盖智能体循环、工具系统、权限 | 4 |
| **initializer** | https://github.com/carlosbrown2/initializer | 使用 Compound Engineering 和 Ralph 循环模式的 Agent Harness 模板 | 2 |
| **harness** | https://github.com/suhanlee/harness | Harness Engineering - 3 智能体流水线模式（Planner/Generator/Evaluator） | 1 |

---

## 主流 AI Agent 框架

| 名称 | 链接 | 说明 | Stars |
|------|------|------|-------|
| **LangChain** | https://github.com/langchain-ai/langchain | Agent 工程平台，模块化架构，统一 LLM 接口，预构建代理工具包 | 138,099 |
| **MetaGPT** | https://github.com/FoundationAgents/MetaGPT | 多智能体框架，首个 AI 软件公司，支持自然语言编程 | 68,435 |
| **Microsoft AutoGen** | https://github.com/microsoft/autogen | 用于构建多智能体会话系统的编程框架，支持代码执行 | 58,561 |
| **crewAI** | https://github.com/crewAIInc/crewAI | 用于编排角色扮演自主 AI 智能体的框架，支持多智能体协作 | 52,512 |
| **LangGraph** | https://github.com/langchain-ai/langgraph | 构建弹性智能体，支持状态图和工作流编排 | 33,443 |
| **OpenAI Agents (Python)** | https://github.com/openai/openai-agents-python | 轻量级、强大的多智能体工作流框架 | 26,787 |
| **Haystack** | https://github.com/deepset-ai/haystack | 开源 AI 编排框架，用于构建生产级 LLM 应用 | 25,418 |
| **Mastra** | https://github.com/mastra-ai/mastra | Gatsby 团队出品，用于构建 AI 驱动应用和智能体的框架 | 24,591 |
| **eliza** | https://github.com/elizaOS/eliza | 开源智能体操作系统 | 18,486 |
| **agent-zero** | https://github.com/agent0ai/agent-zero | Agent Zero AI 框架 | 17,869 |
| **SuperAGI** | https://github.com/TransformerOptimus/SuperAGI | 开发者优先的开源自主 AI 智能体框架 | 17,553 |
| **Google ADK** | https://github.com/google/adk-python | Agent Development Kit，用于构建、评估和部署 AI 智能体 | 19,929 |
| **Semantic Kernel** | https://github.com/microsoft/semantic-kernel | 企业级 AI 模型集成框架，支持多语言和插件架构 | 28,012 |
| **Dify** | https://github.com/langgenius/dify | 开源 LLM 应用开发框架，可视化提示编排 | 143,218 |
| **Llama Index** | https://github.com/run-llama/llama_index | LLM 应用数据框架，支持 160+ 数据源 | 49,787 |
| **Embedchain** | https://github.com/embedchain/embedchain | 构建类 ChatGPT 机器人的框架，支持多源数据摄入 | 57,164 |
| **AstrBot** | https://github.com/AstrBotDevs/AstrBot | AI 智能体助手和开发框架，集成多种 IM 平台 | 33,522 |
| **agentUniverse** | https://github.com/agentuniverse-ai/agentUniverse | LLM 多智能体框架，轻松构建多智能体应用 | 2,261 |

---

## Awesome 列表与资源汇总

| 名称 | 链接 | 说明 | Stars |
|------|------|------|-------|
| **awesome-harness-engineering** | https://github.com/ai-boost/awesome-harness-engineering | AI agent harness 工程资源汇总：工具、模式、评估、记忆、MCP、权限、可观测性 | 1,432 |
| **awesome-llm-agents** | https://github.com/kaushikb11/awesome-llm-agents | LLM 智能体框架精选列表 | 1,497 |
| **awesome-ai-agents-2026** | https://github.com/caramaschiHG/awesome-ai-agents-2026 | 2026 年最全面的 AI 智能体、框架和工具列表，340+ 资源，20+ 类别 | 996 |
| **awesome-web-agents** | https://github.com/steel-dev/awesome-web-agents | 构建 AI Web 智能体的工具、框架和资源列表 | 1,453 |
| **awesome-ai-sdks** | https://github.com/e2b-dev/awesome-ai-sdks | AI 智能体 SDK、框架、库和工具数据库 | 1,180 |
| **awesome-ai-apps** | https://github.com/rohitg00/awesome-ai-apps | 使用多种技术栈构建的 AI 智能体和 LLM 应用精选 | 778 |
| **Awesome-Context-Engineering** | https://github.com/Meirtz/Awesome-Context-Engineering | 上下文工程综合调查：从提示工程到生产级 AI 系统 | 3,159 |
| **acu** | https://github.com/trycua/acu | AI Computer Use 智能体资源列表，包括研究论文、项目、框架和工具 | 1,674 |
| **awesome-cli-coding-agents** | https://github.com/bradAGI/awesome-cli-coding-agents | 终端原生 AI 编码智能体和编排 harness 的精选目录 | 473 |

---

## 终端/CLI Agent 工具

| 名称 | 链接 | 说明 | Stars |
|------|------|------|-------|
| **Claude Code** | https://docs.anthropic.com/en/docs/claude-code | Anthropic CLI 智能体，最佳推理能力，SWE-bench 80.9%，支持 Agent Teams | 官方 |
| **OpenAI Codex CLI** | https://github.com/openai/codex | OpenAI 终端智能体，Agents SDK，支持多智能体 | 官方 |
| **Gemini CLI** | https://github.com/google-gemini/gemini-cli | Google 官方开源终端智能体，ReAct 循环，MCP 支持，1M 上下文 | 官方 |
| **late-cli** | https://github.com/mlhher/late-cli | 在 5GB VRAM 上编排整个 AI 开发团队，临时子代理，单静态二进制 | 334 |
| **opencode-workspace** | https://github.com/kdcokenny/opencode-workspace | OpenCode 捆绑的多智能体编排 harness | 465 |

---

## 多智能体协作系统

| 名称 | 链接 | 说明 | Stars |
|------|------|------|-------|
| **OpenManus** | https://github.com/FoundationAgents/OpenManus | 开源通用 AI 智能体平台，模块化架构，支持数据分析和可视化 | 56,414 |
| **12-factor-agents** | https://github.com/humanlayer/12-factor-agents | 构建 LLM 驱动软件的原则和最佳实践 | 22,859 |
| **hyperframes** | https://github.com/heygen-com/hyperframes | 编写 HTML，渲染视频，为智能体构建 | 22,710 |
| **Open-AutoGLM** | https://github.com/zai-org/Open-AutoGLM | 开源手机智能体模型和框架，让每个人都能使用 AI 手机 | 25,388 |

---

## 学习与文档资源

### 官方文档

| 资源 | 链接 | 说明 |
|------|------|------|
| ECC 文档 | https://ecc.tools | ECC agent harness 的官方文档和教程 |
| deer-flow 文档 | https://deerflow.tech | 字节跳动 deer-flow 的官方文档 |
| LangChain 文档 | https://python.langchain.com/ | LangChain 完整文档和 API 参考 |
| AutoGen 文档 | https://microsoft.github.io/autogen/ | Microsoft AutoGen 使用指南 |
| crewAI 文档 | https://docs.crewai.com/ | crewAI 框架文档和示例 |
| Google ADK 文档 | https://google.github.io/adk-docs/ | Google Agent Development Kit 官方文档 |
| LangGraph 文档 | https://langchain-ai.github.io/langgraph/ | LangGraph 状态图和智能体编排文档 |

### 核心文章与论文

#### OpenAI 官方文章

| 标题 | 链接 | 说明 |
|------|------|------|
| Harness Engineering | https://openai.com/index/harness-engineering/ | OpenAI 对 harness engineering 学科的官方定义：如何设计让 Codex 等智能体可靠运行的脚手架 |
| Unrolling the Codex Agent Loop | https://openai.com/index/unrolling-the-codex-agent-loop/ | OpenAI 详细拆解 Codex 智能体循环，揭示每个 harness 组件及其改进点 |
| Run Long-Horizon Tasks with Codex | https://developers.openai.com/blog/run-long-horizon-tasks-with-codex/ | OpenAI 长周期任务规划实践指南：介绍 Plan.md、Implement.md、Documentation.md 等可复用 harness 工件 |
| Unlocking the Codex Harness | https://openai.com/index/unlocking-the-codex-harness/ | OpenAI 工程深度解析 Item/Turn/Thread 协议（JSON-RPC/JSONL over stdio），解释为何需要专用协议 |
| Testing Agent Skills Systematically with Evals | https://developers.openai.com/blog/eval-skills/ | OpenAI 技能回归测试框架：四个评估维度、JSONL 追踪捕获、基于规则的评分 |
| A Practical Guide to Building AI Agents | https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/ | OpenAI 2026 年 4 月综合指南：单智能体 vs 多智能体编排、工具设计、分层防护模式 |
| The Next Evolution of the Agents SDK | https://openai.com/index/the-next-evolution-of-the-agents-sdk/ | OpenAI 2026 年 4 月更新：新增沙箱执行、可配置记忆、沙箱感知编排 |

#### Anthropic 官方文章

| 标题 | 链接 | 说明 |
|------|------|------|
| Building Effective Agents | https://www.anthropic.com/research/building-effective-agents | Anthropic 智能体架构基础指南：何时使用工作流 vs 智能体，如何组合原语 |
| Harness Design for Long-Running Application Development | https://www.anthropic.com/engineering/harness-design-long-running-apps | Anthropic 工程博客：设计长周期、多会话开发任务的 harness，关键洞察是每个 harness 组件都假设模型无法做某事 |
| Writing Effective Tools for Agents | https://www.anthropic.com/engineering/writing-effective-tools-for-agents | Anthropic 工具接口设计指南：命名、模式、错误展示，工具设计即智能体 UX |
| Beyond Permission Prompts | https://www.anthropic.com/engineering/beyond-permission-prompts | Anthropic 关于在智能体 harness 中构建结构化权限和授权系统 |
| Demystifying Evals for AI Agents | https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents | Anthropic 评估智能体行为的框架：测量什么、如何构建评估 harness |
| What is an AI Agent? | https://www.anthropic.com/research/what-is-an-agent | Anthropic 定义性文章，为 harness 设计决策提供清晰的智能体模型 |
| Building a C Compiler with a Team of Parallel Claudes | https://www.anthropic.com/engineering/building-c-compiler | Anthropic 协调 16 个 Claude 实例并行工作的经验：git 原生任务分配、避免上下文污染 |
| Managed Agents: Decoupling the Brain from the Hands | https://www.anthropic.com/engineering/managed-agents | Anthropic 生产架构：分离"大脑"（Claude + harness）、"手"（沙箱/工具）和"会话"（追加式事件日志） |
| 2026 Agentic Coding Trends Report | https://resources.anthropic.com/hubfs/2026%20Agentic%20Coding%20Trends%20Report.pdf | Anthropic 行业基准：基础设施配置可将基准分数提高 5+ 个百分点 |
| An Update on Recent Claude Code Quality Reports | https://www.anthropic.com/engineering/april-23-postmortem | Anthropic 2026 年 4 月透明事后分析：追踪 Claude Code 质量下降到三个 harness 级变更 |

#### Google 官方文章

| 标题 | 链接 | 说明 |
|------|------|------|
| Agent Development Kit: Making it easy to build multi-agent applications | https://developers.googleblog.com/en/agent-development-kit-easy-to-build-multi-agent-applications/ | Google ADK 公告和设计原理：解释多智能体拓扑、工具注册模型和评估流水线 |
| Supercharge Your AI Agents: The New ADK Integrations Ecosystem | https://developers.googleblog.com/en/supercharge-your-ai-agents-adk-integrations-ecosystem/ | Google 2026 年 ADK 更新：扩展生态系统集成（Hugging Face、GitHub、Daytona、Notion 等） |
| Building AI Agent Using Google ADK as MCP Client | https://medium.com/google-cloud/building-ai-agents-with-googles-agent-development-kit-adk-as-mcp-client-a-deep-dive-full-54d683713afe | 深度教程：使用 Google ADK 作为 MCP 客户端构建 AI 智能体 |
| Introducing BigQuery Agent Analytics | https://cloud.google.com/blog/products/data-analytics/introducing-bigquery-agent-analytics/ | Google Cloud 2026 年发布：将智能体追踪、工具调用、会话和结果作为分析数据处理 |

#### 其他核心资源

| 标题 | 链接 | 说明 |
|------|------|------|
| Harness Engineering (Martin Fowler) | https://martinfowler.com/articles/exploring-gen-ai/harness-engineering.html | Martin Fowler 综合文章：三个互锁系统——上下文工程、架构约束、熵管理 |
| Harness engineering for coding agent users | https://martinfowler.com/articles/harness-engineering.html | Birgitta Böckeler 的系统心智模型（2026 年 4 月）：前馈指南 + 反馈传感器 |
| The Anatomy of an Agent Harness | https://blog.langchain.com/the-anatomy-of-an-agent-harness/ | LangChain 结构分解：组成 harness 的五个原语（文件系统、代码执行、沙箱、记忆、上下文管理） |
| Improving Deep Agents with Harness Engineering | https://blog.langchain.com/improving-deep-agents-with-harness-engineering/ | LangChain 案例研究：仅 harness 改动将编码智能体从第 30 名提升至前 5 名 |
| How Middleware Lets You Customize Your Agent Harness | https://blog.langchain.com/how-middleware-lets-you-customize-your-agent-harness/ | 介绍 AgentMiddleware：六个可组合钩子，实现确定性策略执行、动态工具注入 |
| Continual learning for AI agents | https://blog.langchain.com/continual-learning-for-ai-agents/ | LangChain 2026 年 4 月框架：智能体学习分为三个层次（模型权重、harness 行为、上下文记忆） |
| Agent Evaluation Readiness Checklist | https://blog.langchain.com/agent-evaluation-readiness-checklist/ | 33 项检查清单，涵盖完整评估生命周期 |
| Evaluating Skills | https://blog.langchain.com/evaluating-skills/ | LangChain 方法学：在 Docker 沙箱环境中基准测试智能体技能 |
| Building AI Coding Agents for the Terminal | https://arxiv.org/abs/2603.05344 | 第一篇关于终端原生编码智能体 harness 设计的系统实践论文 |
| Natural-Language Agent Harnesses | https://arxiv.org/abs/2603.25723 | 提出将智能体控制逻辑外化为可移植自然语言工件（NLAHs） |
| Ranking Engineer Agent (REA): Meta's Autonomous AI System | https://engineering.fb.com/2026/03/17/developer-tools/ranking-engineer-agent-rea-autonomous-ai-system-accelerating-meta-ads-ranking-innovation/ | Meta 生产 harness：多日 ML 流水线自动化，支持休眠 - 唤醒检查点 |
| How We Build Azure SRE Agent with Agentic Workflows | https://techcommunity.microsoft.com/blog/appsonazureblog/how-we-build-azure-sre-agent-with-agentic-workflows/4508753 | Microsoft 架构 walkthrough：处理 35,000+ 生产事件的智能体，将缓解时间从 40.5 小时降至 3 分钟 |
| Context Engineering for Reliable AI Agents | https://techcommunity.microsoft.com/blog/appsonazureblog/context-engineering-lessons-from-building-azure-sre-agent/4481200/ | Microsoft 经验：从 100+ 定制工具转向基于文件系统的上下文工程系统，"意图满足"分数从 45% 升至 75% |
| Harness Engineering: Structured Workflows for AI-Assisted Development | https://developers.redhat.com/articles/2026/04/07/harness-engineering-structured-workflows-ai-assisted-development/ | Red Hat 企业视角（2026 年 4 月 7 日）：四大支柱模型（vibes、specs、skills、agents） |
| Eval-Driven Development: Build and Evaluate Reliable AI Agents | https://developers.redhat.com/articles/2026/03/23/eval-driven-development-build-evaluate-ai-agents/ | Red Hat 八阶段评估成熟度进展：从手动 CLI 测试到成本感知持续监控 |
| Distributed Tracing for Agentic Workflows with OpenTelemetry | https://developers.redhat.com/articles/2026/04/06/distributed-tracing-agentic-workflows-opentelemetry/ | Red Hat 2026 年 4 月 6 日指南：使用标准追踪基础设施跨路由智能体、专业智能体、MCP 服务器传播上下文 |
| Microsoft Agent Framework 1.0 | https://devblogs.microsoft.com/agent-framework/microsoft-agent-framework-version-1-0/ | 生产就绪 1.0 版本（2026 年 4 月）：统一 Semantic Kernel 和 AutoGen，图编排、中间件流水线 |
| Orchestrating Ambient Agents with Temporal | https://temporal.io/blog/orchestrating-ambient-agents-with-temporal/ | Temporal.io harness 基础设施：持久智能体工作流，原生智能体握手协议 |
| Building Observable AI Agents: Temporal + Braintrust | https://temporal.io/blog/building-observable-ai-agents-temporal-now-integrates-with-braintrust/ | 结合 Temporal 持久执行与 Braintrust LLM 追踪的集成模式 |
| Red-Teaming Anthropic's Internal Agent Monitoring Systems | https://metr.org/blog/2026-03-25-red-teaming-anthropic-agent-monitoring/ | METR 三周对抗性审计：压力测试智能体监控基础设施的具体方法 |

### Hacker News 讨论精选

| 标题 | 链接 | 说明 |
|------|------|------|
| Show HN: Agent Orchestrator, a local-first Harness Engineering control plane | https://news.ycombinator.com/item?id=47562440 | 本地优先的 Harness Engineering 控制面板（15 分） |
| Show HN: Altimate Code – Open-Source Agentic Data Engineering Harness | https://github.com/AltimateAI/altimate-code | 开源数据工程 harness（20 分） |
| Show HN: Oh-my-agent – A structural harness for AI agents in real projects | https://github.com/first-fluke/oh-my-agent | 真实项目的结构化 harness（3 分） |
| Harness Engineering: 52 Days, One Person, 965K Lines of Code | https://agentsmesh.ai/blog/building-agentsmesh-with-agentsmesh | 个人使用 harness engineering 构建 96.5 万行代码的经验 |
| Ask HN: What does your agentic software dark factory look like? | https://news.ycombinator.com/item?id=47920020 | 讨论各自的智能体软件"暗工厂"架构 |
| What I changed in how I use Claude Code after Anthropic's postmortem | https://news.ycombinator.com/item?id=47957402 | Anthropic 事后分析后改变 Claude Code 使用方式 |
| AI Agent Frameworks Comparison | https://deepresearch.ninja/2026/05/AI-Agent-Frameworks-A-Comparative-Analysis-of-DSPy-Claude-Agent-SDK-OpenAI-Agents-SDK-CrewAI-AutoGen-LangGraph-and-Google-ADK/ | 主流框架对比分析（DSPy、Claude Agent SDK、OpenAI Agents SDK 等） |
| Show HN: GitAgent – An open standard that turns any Git repo into an AI agent | https://www.gitagent.sh/ | 将任何 Git 仓库变成 AI 智能体的开放标准（147 分） |
| Show HN: AgentKit – JavaScript Alternative to OpenAI Agents SDK with Native MCP | https://github.com/inngest/agent-kit | 原生 MCP 的 JavaScript 替代方案（64 分） |
| Show HN: Automated Testing for AI Agents | https://agents.zalor.ai/ | AI 智能体自动化测试平台 |

---

## 协议与标准

| 名称 | 链接 | 说明 | Stars |
|------|------|------|-------|
| **MCP (Model Context Protocol)** | https://modelcontextprotocol.io/ | 模型上下文协议，AI 智能体与外部工具/数据源的标准接口 | 官方 |
| **GNAP** | https://github.com/farol-team/gnap | Git-Native Agent Protocol，使用 4 个 JSON 文件在 git 仓库中协调 AI 智能体团队 | 新兴 |
| **A2A (Agent-to-Agent)** | https://github.com/google/A2A | Google 推出的智能体间通信协议 | 官方 |

---

## 可观测性与评估工具

| 名称 | 链接 | 说明 | Stars |
|------|------|------|-------|
| **Weights & Biases** | https://wandb.ai/ | ML 实验跟踪，自动日志记录，可视化训练过程 | 商业 |
| **LangSmith** | https://smith.langchain.com/ | LangChain 的调试和监控平台 | 商业 |
| **Arize Phoenix** | https://github.com/Arize-ai/phoenix | LLM 可观测性和评估工具 | 开源 |
| **evaluating-llms-harness** | https://github.com/diwhy/evaluating-llms-harness | 在 60+ 学术基准（MMLU、HumanEval 等）上评估 LLM | 研究 |

---

## 关键概念解释

### 什么是 Agent Harness？

**Harness Engineering** 是设计围绕 AI 智能体的脚手架的学科，包括：
- 上下文交付（Context Delivery）
- 工具接口（Tool Interfaces）
- 规划工件（Planning Artifacts）
- 验证循环（Verification Loops）
- 记忆系统（Memory Systems）
- 沙箱环境（Sandboxes）

这些组件决定了 AI 智能体在真实任务上是成功还是失败。

### Harness vs Framework 的区别

| 特性 | Harness | Framework |
|------|---------|-----------|
| 定位 | 围绕特定 Agent（如 Claude Code）的编排层 | 完整的智能体开发平台 |
| 灵活性 | 通常针对特定 Agent 优化 | 更通用，支持多种 LLM |
| 复杂度 | 相对轻量 | 功能更全面 |
| 示例 | ECC, oh-my-openagent | LangChain, AutoGen, crewAI |

### Harness Engineering 核心原则（来自 OpenAI/Anthropic）

1. **Harness 设计决定成败**：模型能力不是瓶颈，harness 设计才是
2. **每个组件都有假设**：每个 harness 组件都假设模型无法做某事，这些假设会随模型改进而过期
3. **上下文工程优先**：暴露一切（源代码、运行手册、查询模式）作为文件，让智能体使用标准工具访问
4. **验证循环内置**：将验证构建到 harness 循环中，而不是事后评估
5. **分离关注点**：将"大脑"（LLM + harness）、"手"（沙箱/工具）和"会话"（事件日志）分离
6. **工具设计即 UX**：工具接口设计是智能体 UX，命名、模式、错误展示至关重要
7. **权限结构化**：构建结构化权限和授权系统，而非依赖自然语言权限文本

---

## 趋势与洞察 (2026)

1. **终端原生优先**：Claude Code、Codex CLI、Gemini CLI 等终端智能体成为开发者首选
2. **Harness 工程兴起**：从单纯使用模型转向设计完整的智能体脚手架
3. **多智能体协作**：从单智能体任务转向多智能体团队协作
4. **Git 原生协议**：GNAP 等协议使用 git 作为智能体协调的底层机制
5. **本地部署**：越来越多的工具支持本地运行，数据可控
6. **MCP 标准化**：Model Context Protocol 成为智能体与工具交互的事实标准
7. **评估驱动开发**：从手动测试到成本感知持续监控的八阶段成熟度进展
8. **可观测性统一**：将智能体追踪、工具调用、会话和结果作为分析数据处理
9. **持久执行**：Temporal 等持久工作流引擎与 LLM 追踪集成
10. **架构健康传感器**：实时架构传感器形成反馈循环，让智能体在熵增前自我纠正

---

## 推荐学习路径

### 初学者
1. 从 **LangChain** 或 **crewAI** 开始，了解基本概念
2. 阅读 **awesome-llm-agents** 列表
3. 尝试 **Claude Code** 或 **OpenAI Codex CLI**
4. 阅读 Anthropic 的 **Building Effective Agents**

### 进阶开发者
1. 研究 **ECC** 或 **deer-flow** 等 harness 系统
2. 学习 **Harness Engineering** 原则（OpenAI、Anthropic、Martin Fowler 文章）
3. 探索 **MCP** 协议和工具集成
4. 实现验证循环和 CI 集成（promptfoo、AgentBench）

### 生产环境
1. 评估 **LangGraph** 或 **AutoGen** 用于复杂工作流
2. 集成 **可观测性工具**（LangSmith、W&B、Langfuse）
3. 实现 **验证循环** 和 **沙箱环境**
4. 设计 **持久执行** 和 **检查点恢复**
5. 构建 **评估流水线**（回归测试、成本监控）

---

## 贡献与更新

本文档将持续更新。如发现遗漏或有价值的资源，欢迎参考以下 Awesome 列表提交 PR：

- https://github.com/ai-boost/awesome-harness-engineering
- https://github.com/kaushikb11/awesome-llm-agents
- https://github.com/caramaschiHG/awesome-ai-agents-2026
