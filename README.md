# outstanding-ai-agents
Outstanding AI agents is a curated list of open-source tools and solutions to build AI agents.

---

## 🗂️ Categories

**Core Building Blocks**
- [Agent Frameworks](#-agent-frameworks)
- [Orchestration & Workflow](#-orchestration--workflow)
- [Memory & Knowledge](#-memory--knowledge)
- [Tool Use & Function Calling](#-tool-use--function-calling)

**Autonomy**
- [Autonomy Levels & Classification](#-autonomy-levels--classification)
- [Human-in-the-Loop (HITL)](#-human-in-the-loop-hitl)
- [Self-Improving & Reflective Agents](#-self-improving--reflective-agents)
- [Planning & Goal Management](#-planning--goal-management)
- [Safety, Guardrails & Alignment](#-safety-guardrails--alignment)

**Evaluation & Deployment**
- [Evaluation & Observability](#-evaluation--observability)
- [Multimodal Agents](#-multimodal-agents)
- [Specialized / Domain-Specific](#-specialized--domain-specific)
- [Resources & Learning](#-resources--learning)

---

## 🧱 Agent Frameworks

Core frameworks for building and running AI agents.

* [LangChain](https://github.com/langchain-ai/langchain): The most widely adopted framework for chaining LLM calls, tools, and retrieval pipelines.
* [AutoGen](https://github.com/microsoft/autogen): Microsoft's multi-agent conversation framework with customizable agent roles and behaviors.
* [CrewAI](https://github.com/crewAIInc/crewAI): Orchestrates teams of role-playing autonomous agents that collaborate on complex tasks.
* [MetaGPT](https://github.com/geekan/MetaGPT): Simulates a software company by assigning specialized roles (PM, engineer, QA) to agents.
* [LlamaIndex](https://github.com/run-llama/llama_index): Connects LLMs to external data sources with powerful indexing, retrieval, and agent tooling.
* [Semantic Kernel](https://github.com/microsoft/semantic-kernel): Microsoft's SDK for integrating LLMs into apps via plugins and planners in Python and C#.

---

## 🔀 Orchestration & Workflow

Tools for chaining agents, managing tasks, and defining multi-step pipelines.

* [LangGraph](https://github.com/langchain-ai/langgraph): Builds stateful, graph-based multi-agent workflows with conditional routing and checkpointing.
* [n8n](https://github.com/n8n-io/n8n): Self-hostable automation platform with 400+ integrations and native AI agent workflow support.
* [Dify](https://github.com/langgenius/dify): Low-code platform for deploying production-ready LLM apps and agentic RAG pipelines quickly.
* [Flowise](https://github.com/FlowiseAI/Flowise): Drag-and-drop UI for building LLM flows and agent pipelines built on LangChain.
* [Prefect](https://github.com/PrefectHQ/prefect): Python-native workflow orchestration with observability, scheduling, and task dependency management.

---

## 🧠 Memory & Knowledge

Solutions for agent memory, vector stores, retrieval-augmented generation (RAG), and knowledge management.

* [Mem0](https://github.com/mem0ai/mem0): Persistent memory layer for AI agents that learns and adapts from user interactions over time.
* [RAGFlow](https://github.com/infiniflow/ragflow): End-to-end RAG framework for grounding agents in documents, databases, and external APIs.
* [Chroma](https://github.com/chroma-core/chroma): Open-source embedding database for storing and querying vector representations at any scale.
* [Weaviate](https://github.com/weaviate/weaviate): Cloud-native vector database with hybrid search combining semantic and keyword retrieval.
* [Letta (MemGPT)](https://github.com/cpacker/letta): Stateful agents with self-editing memory that persist context beyond the LLM's context window.

---

## 🛠️ Tool Use & Function Calling

Libraries and frameworks focused on giving agents access to external tools, APIs, and functions.

* [Composio](https://github.com/ComposioHQ/composio): Gives agents 250+ pre-built integrations (GitHub, Slack, Gmail) with managed auth and tool execution.
* [ToolBench](https://github.com/OpenBMB/ToolBench): Trains and evaluates LLMs on real-world API tool use across 16,000+ REST APIs.
* [OpenAI Swarm](https://github.com/openai/swarm): Lightweight educational framework for exploring ergonomic multi-agent tool-calling handoffs.
* [Agno](https://github.com/agno-agi/agno): Fast multi-modal agent framework with built-in tool support, memory, and reasoning capabilities.
* [e2b](https://github.com/e2b-dev/e2b): Secure cloud sandboxes that let agents safely execute code and run long-running tools.

---

## 🎚️ Autonomy Levels & Classification

Frameworks, taxonomies, and tools that define or measure *how autonomous* an agent is — from fully supervised to fully autonomous.

* [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT): One of the first fully autonomous agents; loops on goals independently with minimal human prompting.
* [BabyAGI](https://github.com/yoheinakajima/babyagi): Minimal task-driven autonomous agent loop using LLMs to create, prioritize, and execute tasks.
* [AgentBench](https://github.com/THUDM/AgentBench): Benchmarks LLM agents across 8 real-world environments to measure autonomy and task completion.
* [CAMEL](https://github.com/camel-ai/camel): Studies communicative agent behavior and role assignment to understand emergent autonomy in multi-agent systems.
* [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter): Runs code locally via natural language, enabling high-autonomy control of the user's own computer.

---

## 🙋 Human-in-the-Loop (HITL)

Tools and patterns for keeping humans in control — approval flows, intervention hooks, feedback loops, and escalation mechanisms.

* [LangGraph](https://github.com/langchain-ai/langgraph): Supports native HITL via graph checkpointing, letting humans review and approve agent steps mid-run.
* [Argilla](https://github.com/argilla-io/argilla): Open-source data annotation platform for collecting human feedback to improve and align LLM agents.
* [Label Studio](https://github.com/HumanSignal/label-studio): Flexible data labeling tool used to build HITL review queues for agent output quality control.
* [RLHF-Blender](https://github.com/facebookresearch/rlhf-blender): Facebook Research toolkit for blending human feedback signals into agent reward modeling pipelines.
* [Guardrails AI](https://github.com/guardrails-ai/guardrails): Validates and corrects LLM outputs in real-time, escalating to humans when constraints are violated.

---

## 🔁 Self-Improving & Reflective Agents

Agents that can critique their own outputs, retry on failure, learn from feedback, or improve their behavior over time.

* [Reflexion](https://github.com/noahshinn/reflexion): Agents verbally reflect on prior task failures and store insights as episodic memory for future runs.
* [Self-Refine](https://github.com/madaan/self-refine): Iterative self-feedback framework where an LLM critiques and rewrites its own outputs to improve quality.
* [PraisonAI](https://github.com/MervinPraison/PraisonAI): Production-ready multi-agent framework with built-in self-reflection and 100+ LLM support.
* [DSPy](https://github.com/stanfordnlp/dspy): Compiles and optimizes LLM pipelines programmatically, auto-improving prompts via feedback signals.
* [Agentic Context Engine](https://github.com/agenticsorg/agentic-context-engine): Self-improving agents that curate and update their own context based on execution feedback.

---

## 🗺️ Planning & Goal Management

Approaches to long-horizon task planning, goal decomposition, subgoal tracking, and autonomous decision-making over extended sequences.

* [Tree of Thoughts](https://github.com/princeton-nlp/tree-of-thought-llm): Princeton's framework for deliberate reasoning by exploring multiple thought branches before committing.
* [TaskWeaver](https://github.com/microsoft/TaskWeaver): Microsoft's code-first agent framework for decomposing and planning complex data analytics tasks.
* [HuggingGPT](https://github.com/microsoft/JARVIS): Uses ChatGPT as a planner to route subtasks to specialized Hugging Face models dynamically.
* [Voyager](https://github.com/MineDreamer/Voyager): LLM-powered lifelong learning agent that plans, executes, and stores skills in a growing library.
* [AgentVerse](https://github.com/OpenBMB/AgentVerse): Multi-agent simulation framework with dynamic team formation and task-level goal assignment.

---

## 🛡️ Safety, Guardrails & Alignment

Tools focused on keeping autonomous agents safe — output filtering, policy enforcement, red-teaming, sandboxing, and alignment research toolkits.

* [NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails): NVIDIA's programmable guardrail toolkit for LLM apps covering jailbreaks, topic control, and PII.
* [Guardrails AI](https://github.com/guardrails-ai/guardrails): 60+ open-source validators for structuring, filtering, and correcting LLM inputs and outputs.
* [Llama Guard](https://github.com/meta-llama/PurpleLlama): Meta's fine-tuned safety classifier for detecting harmful inputs and outputs in LLM applications.
* [Promptfoo](https://github.com/promptfoo/promptfoo): CLI tool for red-teaming agents, running adversarial tests, and automated safety regression checks.
* [Microsoft Presidio](https://github.com/microsoft/presidio): Detects and anonymizes PII in text and images before it enters or exits an agent pipeline.

---

## 📈 Evaluation & Observability

Tools for benchmarking, testing, tracing, and monitoring agent behavior.

* [LangSmith](https://github.com/langchain-ai/langsmith-sdk): LangChain's native platform for tracing, debugging, and evaluating LLM chains and agent runs.
* [Langfuse](https://github.com/langfuse/langfuse): Open-source MIT-licensed observability stack covering tracing, prompt versioning, and LLM-as-judge evals.
* [Weights & Biases Weave](https://github.com/wandb/weave): Extends W&B experiment tracking to LLM apps with structured tracing and evaluation workflows.
* [AgentOps](https://github.com/AgentOps-AI/agentops): Tracks agent sessions, costs, tool calls, and errors across 400+ LLMs with session replay.
* [Helicone](https://github.com/Helicone/helicone): Proxy-based LLM observability with one-line setup, cost tracking, caching, and request logging.

---

## 🖼️ Multimodal Agents

Agents that work across text, images, audio, video, or other modalities.

* [Agent-S](https://github.com/simular-ai/Agent-S): ICLR 2025 Best Paper; open agentic framework that controls a computer interface like a human.
* [SWE-agent](https://github.com/princeton-nlp/SWE-agent): Autonomously resolves GitHub issues by reading, editing, and running code in a terminal interface.
* [OpenHands](https://github.com/All-Hands-AI/OpenHands): Open-source software engineering agent that writes code, browses the web, and runs terminal commands.
* [Browser Use](https://github.com/browser-use/browser-use): Gives AI agents the ability to control and navigate a real browser for web-based tasks.
* [Qwen-VL-Agent](https://github.com/QwenLM/Qwen-VL): Alibaba's vision-language agent for understanding and reasoning over images, documents, and diagrams.

---

## 🎯 Specialized / Domain-Specific

Agents built for specific use cases (coding, research, data analysis, customer support, etc.).

* [Aider](https://github.com/Aider-AI/aider): CLI pair-programming agent that edits local git repos and auto-commits changes with GPT/Claude.
* [GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer): Generates entire codebases from a natural language spec with iterative clarification prompts.
* [Perplexica](https://github.com/ItzCrazyKns/Perplexica): Open-source AI search agent that browses the web and synthesizes sourced answers in real time.
* [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot): Multi-agent framework tailored for financial analysis, forecasting, and document understanding.
* [BioPlanner](https://github.com/bioplanner/bioplanner): Autonomous agent for planning and executing biology experiment workflows using scientific literature.

---

## 📚 Resources & Learning

Papers, blog posts, repos, and tutorials that have shaped your understanding.

* [Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents): Curated list of open-source AI agents and frameworks maintained by the e2b team.
* [Awesome Agents](https://github.com/kyrolabs/awesome-agents): Community-curated list of agent SDKs, frameworks, and tools updated regularly.
* [ReAct Paper](https://github.com/ysymyth/ReAct): Original repo for the ReAct (Reason + Act) prompting paradigm foundational to modern agents.
* [LLM Agent Survey](https://github.com/Paitesanshi/LLM-Agent-Survey): Comprehensive academic survey of LLM-based agent architectures, capabilities, and benchmarks.
* [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide): Deep resource covering CoT, ReAct, ToT, and other prompting techniques central to agent design.

---

*Last updated: 03/28/2026*
