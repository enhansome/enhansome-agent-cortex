# Awesome Agent Cortex with stars

<p align="center">
  <img src="public/readme/agent-cortex-hero.jpeg" alt="Awesome Agent Cortex maps the sovereign agent stack" width="960">
</p>

<p align="center">
  <strong>A curated map of the tools, memory systems, identity rails, and operational patterns behind capable AI agents.</strong>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-CC0-FF6A2A.svg" alt="CC0 license"></a>
  <a href="https://github.com/0xNyk/awesome-agent-cortex/actions/workflows/docs-health.yml"><img src="https://github.com/0xNyk/awesome-agent-cortex/actions/workflows/docs-health.yml/badge.svg" alt="Documentation health"></a>
  <a href="https://github.com/0xNyk/awesome-agent-cortex"><img src="https://img.shields.io/github/stars/0xNyk/awesome-agent-cortex" alt="GitHub stars"></a>
</p>

***

Awesome Agent Cortex connects the layers that ordinary framework lists leave apart: agent runtimes, coding tools, MCP, evaluation, memory, knowledge graphs, on-chain identity, payments, security, and observability. Use it to find one component or to understand how the pieces fit into a complete agent system.

![Navigate the directory through build, operate, remember, and own](public/readme/find-your-layer.jpeg)

Choose a route from the contents below:

* **Build:** frameworks, coding agents, MCP, skills, and prompt systems.
* **Operate:** runtimes, harnessing, evaluation, security, and observability.
* **Remember:** context engineering, knowledge graphs, neural memory, and Obsidian.
* **Own:** identity, wallets, payments, DeFi, and Solana infrastructure.

![The sovereign agent stack moves from models and tools through memory, identity, and evidence](public/readme/sovereign-agent-stack.jpeg)

Some resources appear in more than one section when they serve distinct workflows. Cross-listing is deliberate, limited, and reviewed under the contribution rules.

## Contents

* [Agent Frameworks](#agent-frameworks)
* [Coding Agents](#coding-agents)
* [Voice and Multimodal Agents](#voice-and-multimodal-agents)
* [Hermes Stack](#hermes-stack)
* [CLI and TUI Tools](#cli-and-tui-tools)
* [Agent Runtime Infrastructure](#agent-runtime-infrastructure)
* [Agent Protocols and MCP Ecosystem](#agent-protocols-and-mcp-ecosystem)
* [Prompt Engineering](#prompt-engineering)
* [Agent Harnessing and Evaluation](#agent-harnessing-and-evaluation)
* [ArXiv Deep Research Map](#arxiv-deep-research-map)
* [Context Engineering](#context-engineering)
* [Neural Networks and Neural Linking](#neural-networks-and-neural-linking)
* [Obsidian Vault Architecture for Agents](#obsidian-vault-architecture-for-agents)
* [Agent Security and Robustness](#agent-security-and-robustness)
* [Agent Configs and Dotfiles](#agent-configs-and-dotfiles)
* [Skill Engineering and Playbooks](#skill-engineering-and-playbooks)
* [Knowledge Graphs and Memory](#knowledge-graphs-and-memory)
* [Solana Agent Infrastructure](#solana-agent-infrastructure)
* [Agent Identity and Wallets](#agent-identity-and-wallets)
* [Agent Payments](#agent-payments)
* [DeFi Agents](#defi-agents)
* [Quant and Trading Agents](#quant-and-trading-agents)
* [Agent Observability and Testing](#agent-observability-and-testing)
* [Research Papers](#research-papers)
* [Communities](#communities)

## Agent Frameworks

Multi-agent orchestration, single-agent SDKs, and runtime frameworks.

* [OpenClaw](https://github.com/openclaw/openclaw) ⭐ 389,047 | 🐛 6,217 | 🌐 TypeScript | 📅 2026-09-06 - Self-hosted personal AI agent with multi-platform messaging and skill registry.
* [Hermes Agent](https://github.com/NousResearch/hermes-agent) ⭐ 242,509 | 🐛 40,329 | 🌐 Python | 📅 2026-09-06 - Tool-using autonomous agent platform with memory, skills, delegation, and MCP support.
* [LangChain](https://github.com/langchain-ai/langchain) ⭐ 145,808 | 🐛 450 | 🌐 Python | 📅 2026-09-06 - Composable framework for building LLM-powered applications.
* [AutoGen](https://github.com/microsoft/autogen) ⭐ 60,839 | 🐛 1,050 | 🌐 Python | 📅 2026-04-15 - Multi-agent conversation framework from Microsoft Research.
* [Magentic-One](https://github.com/microsoft/autogen/tree/main/python/packages/autogen-magentic-one) ⭐ 60,839 | 🐛 1,050 | 🌐 Python | 📅 2026-04-15 - Multi-agent team for complex web and file tasks.
* [CrewAI](https://github.com/crewAIInc/crewAI) ⭐ 58,160 | 🐛 747 | 🌐 Python | 📅 2026-09-04 - Role-based multi-agent orchestration framework.
* [LlamaIndex](https://github.com/run-llama/llama_index) ⭐ 52,039 | 🐛 715 | 🌐 Python | 📅 2026-09-05 - Data framework for document agents, retrieval, and workflow orchestration.
* [Agno](https://github.com/agno-agi/agno) ⭐ 42,071 | 🐛 1,352 | 🌐 Python | 📅 2026-09-06 - Framework for building and running agentic software at scale.
* [LangGraph](https://github.com/langchain-ai/langgraph) ⭐ 41,138 | 🐛 754 | 🌐 Python | 📅 2026-09-06 - Library for building stateful multi-agent workflows as graphs.
* [OpenAI Agents SDK for Python](https://github.com/openai/openai-agents-python) ⭐ 29,224 | 🐛 75 | 🌐 Python | 📅 2026-09-05 - Official Python SDK for agent workflows, tools, handoffs, and guardrails.
* [Smolagents](https://github.com/huggingface/smolagents) ⭐ 29,202 | 🐛 785 | 🌐 Python | 📅 2026-08-25 - Lightweight agent framework from Hugging Face.
* [Semantic Kernel](https://github.com/microsoft/semantic-kernel) ⭐ 28,536 | 🐛 284 | 🌐 C# | 📅 2026-09-04 - SDK for integrating LLMs into apps with plugin architecture.
* [Mastra](https://github.com/mastra-ai/mastra) ⭐ 27,740 | 🐛 542 | 🌐 TypeScript | 📅 2026-09-06 - TypeScript framework for building AI applications and agents.
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 26,435 | 🐛 127 | 🌐 Python | 📅 2026-09-04 - LLM orchestration framework for building search and RAG pipelines.
* [Letta](https://github.com/letta-ai/letta) ⭐ 24,635 | 🐛 39 | 📅 2026-08-23 - Stateful agents with long-term memory (formerly MemGPT).
* [Swarm](https://github.com/openai/swarm) ⭐ 21,944 | 🐛 35 | 🌐 Python | 📅 2026-04-15 - Educational framework for multi-agent handoffs and routines.
* [Google ADK](https://github.com/google/adk-python) ⭐ 21,427 | 🐛 502 | 🌐 Python | 📅 2026-09-06 - Agent Development Kit for building agents with Gemini.
* [PydanticAI](https://github.com/pydantic/pydantic-ai) ⭐ 19,753 | 🐛 824 | 🌐 Python | 📅 2026-09-06 - Type-safe agent framework built around Pydantic.
* [ElizaOS](https://github.com/elizaOS/eliza) ⭐ 19,270 | 🐛 1,317 | 🌐 TypeScript | 📅 2026-09-06 - Multi-agent simulation framework for autonomous characters.
* [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) ⭐ 13,355 | 🐛 650 | 🌐 Python | 📅 2026-09-06 - Framework for building, orchestrating, and deploying agents with Python and .NET support.
* [Rig](https://github.com/0xPlaygrounds/rig) ⭐ 8,540 | 🐛 114 | 🌐 Rust | 📅 2026-09-06 - Rust framework for building LLM-powered applications.
* [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) ⭐ 8,047 | 🐛 449 | 🌐 Python | 📅 2026-09-06 - Official Python SDK for building agents on the Claude Code runtime.
* [Julep](https://github.com/julep-ai/julep) ⭐ 6,591 | 🐛 2 | 🌐 Python | 📅 2026-08-06 - Stateful agent platform with built-in persistence and task workflows.
* [AG2](https://github.com/ag2ai/ag2) ⭐ 4,908 | 🐛 26 | 🌐 Python | 📅 2026-09-06 - Open-source AgentOS for building multi-agent systems (evolved from AutoGen).
* [OpenAI Agents SDK for TypeScript](https://github.com/openai/openai-agents-js) ⭐ 3,762 | 🐛 34 | 🌐 TypeScript | 📅 2026-09-05 - Official TypeScript SDK for agent workflows and voice agents.
* [LightAgent](https://github.com/wanxingai/LightAgent) ⭐ 1,216 | 🐛 6 | 🌐 Python | 📅 2026-09-04 - Lightweight Python framework for tool-using agents, workflows, MCP/SSE integration, memory, and multi-agent collaboration.
* [fractal](https://github.com/plasma-ai/fractal) ⭐ 714 | 🐛 4 | 🌐 Python | 📅 2026-09-05 - Runs supported coding-agent CLIs as a recursive hierarchy with per-node Git worktrees, configurable limits, persistent run state, and a live terminal UI.
* [OpenProgram](https://github.com/Fzkuji/OpenProgram) ⭐ 391 | 🐛 1 | 🌐 Python | 📅 2026-09-06 - Self-programming agent runtime with reviewable workflows, DAG context, tools, memory, and multi-agent execution.
* [Hivekeep](https://github.com/MarlBurroW/hivekeep) ⭐ 53 | 🐛 32 | 🌐 TypeScript | 📅 2026-09-06 - Self-hosted platform to run a team of specialized AI agents with persistent memory, a web UI, and chat channels.

## Coding Agents

AI agents that write, review, and debug code.

* [Codex CLI](https://github.com/openai/codex) ⭐ 121,958 | 🐛 15,602 | 🌐 Rust | 📅 2026-09-06 - OpenAI's open-source coding agent for terminal workflows.
* [OpenHands](https://github.com/OpenHands/OpenHands) ⭐ 86,370 | 🐛 668 | 🌐 TypeScript | 📅 2026-09-06 - Platform for AI software development agents (formerly OpenDevin).
* [Cline](https://github.com/cline/cline) ⭐ 67,582 | 🐛 1,249 | 🌐 TypeScript | 📅 2026-09-05 - Autonomous coding agent for VS Code with tool use.
* [Goose](https://github.com/aaif-goose/goose) ⭐ 53,969 | 🐛 312 | 🌐 Rust | 📅 2026-09-06 - Open-source developer agent governed by the Agentic AI Foundation.
* [Aider](https://github.com/Aider-AI/aider) ⭐ 48,794 | 🐛 1,853 | 🌐 Python | 📅 2026-05-22 - AI pair programming in the terminal with git integration.
* [Continue](https://github.com/continuedev/continue) ⭐ 35,806 | 🐛 945 | 🌐 TypeScript | 📅 2026-09-06 - Open-source AI code assistant for VS Code and JetBrains.
* [SWE-Agent](https://github.com/SWE-agent/SWE-agent) ⭐ 20,260 | 🐛 100 | 🌐 Python | 📅 2026-08-31 - Agent for resolving software engineering tasks from GitHub issues.
* [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's agentic CLI for code generation and editing.
* [Cursor](https://cursor.com) - AI-first code editor built on VS Code.
* [Devin](https://devin.ai) - Autonomous software engineering agent by Cognition.
* [Windsurf](https://codeium.com/windsurf) - AI-native IDE by Codeium with agentic flows.

### Claude Code Resources

* [Everything Claude Code](https://github.com/affaan-m/ECC) ⭐ 251,196 | 🐛 170 | 🌐 JavaScript | 📅 2026-09-05 - Community collection of Claude Code skills, hooks, agents, and configuration patterns.
* [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) ⭐ 53,601 | 🐛 999 | 🌐 Python | 📅 2026-09-06 - Curated list of Claude Code resources.
* [claude-code-tips](https://github.com/ykdojo/claude-code-tips) ⭐ 10,046 | 🐛 4 | 🌐 HTML | 📅 2026-09-02 - Community-sourced tips and tricks.
* [Claude Code Hooks](https://docs.anthropic.com/en/docs/claude-code/hooks) - Event-driven shell command automation.
* [Claude Code Skills](https://docs.anthropic.com/en/docs/claude-code/memory#slash-commands-as-custom-skills) - Reusable prompt-driven workflows.
* [CLAUDE.md Guide](https://docs.anthropic.com/en/docs/claude-code/memory) - Official documentation on memory files.

### Codex Resources

* [AGENTS.md Guide (Codex)](https://developers.openai.com/codex/guides/agents-md) - Instruction hierarchy and scoping patterns for Codex.
* [Codex CLI](https://developers.openai.com/codex/cli) - Guide to local Codex CLI workflows.
* [Codex Docs](https://developers.openai.com/codex) - Official Codex documentation hub.
* [Codex Non-Interactive Mode](https://developers.openai.com/codex/noninteractive) - Batch and CI automation with `codex exec`.
* [Codex Optimization Playbook (this repo)](guides/codex-optimization-playbook.md) - Practical operator patterns for speed, safety, and quality.

## Voice and Multimodal Agents

Agents with voice, vision, and multimodal capabilities.

* [Whisper](https://github.com/openai/whisper) ⭐ 108,620 | 🐛 146 | 🌐 Python | 📅 2026-08-31 - Open-source speech recognition model from OpenAI.
* [Pipecat](https://github.com/pipecat-ai/pipecat) ⭐ 15,275 | 🐛 309 | 🌐 Python | 📅 2026-09-06 - Framework for building voice and multimodal conversational agents.
* [LiveKit Agents](https://github.com/livekit/agents) ⭐ 14,037 | 🐛 791 | 🌐 Python | 📅 2026-09-06 - Framework for building real-time multimodal AI agents.
* [TEN Framework](https://github.com/TEN-framework/ten-framework) ⭐ 11,112 | 🐛 234 | 🌐 Python | 📅 2026-09-04 - Open-source framework for conversational voice AI agents.
* [Ultravox](https://github.com/fixie-ai/ultravox) ⭐ 4,559 | 🐛 63 | 🌐 Python | 📅 2025-12-12 - Fast multimodal LLM for real-time voice AI.
* [Vocode Core](https://github.com/vocodedev/vocode-core) ⭐ 3,788 | 🐛 1 | 🌐 Python | 📅 2024-11-15 - Modular open-source framework for building voice-based LLM agents.
* [ElevenLabs](https://github.com/elevenlabs/elevenlabs-python) ⭐ 3,086 | 🐛 37 | 🌐 Python | 📅 2026-09-03 - Text-to-speech and voice cloning API for agent voice interfaces.
* [Vapi](https://vapi.ai) - Platform for building and deploying voice AI agents.

## Hermes Stack

Hermes Agent runtime, deployment rails, and operator resources.

* [Hermes Agent](https://github.com/NousResearch/hermes-agent) ⭐ 242,509 | 🐛 40,329 | 🌐 Python | 📅 2026-09-06 - Open-source autonomous AI agent with CLI, gateway, memory, subagents, and broad tool integrations.
* [Hermes Agent Self-Evolution](https://github.com/NousResearch/hermes-agent-self-evolution) ⭐ 5,261 | 🐛 121 | 🌐 Python | 📅 2026-06-17 - Evolutionary self-improvement framework for optimizing Hermes Agent prompts, skills, and code.
* [Hermes Paperclip Adapter](https://github.com/NousResearch/hermes-paperclip-adapter) ⭐ 1,861 | 🐛 148 | 🌐 TypeScript | 📅 2026-04-04 - Adapter for running Hermes Agent as a managed employee inside Paperclip.
* [hermes-fly](https://github.com/alexfazio/hermes-fly) ⭐ 48 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-22 - Fly.io deployment and operations CLI for Hermes Agent with deploy, logs, doctor, and teardown workflows.
* [Hermes Agent + hermes-fly Best Practices (this repo)](guides/hermes-agent-hermes-fly-playbook.md) - Practical setup, operations, security, and optimization playbook.
* [Hermes Agent Optimization Playbook (this repo)](guides/hermes-agent-optimization-playbook.md) - Deep operator guide for context, delegation, memory, and execution tuning.
* [Hermes Hub (this repo)](hermes/README.md) - Local operator knowledge base for Hermes setup, configuration, memory/skills workflows, and contribution orientation.
* [Hermes Stack Maturity Ladder (this repo)](guides/hermes-stack-maturity-ladder.md) - L1-L3 readiness model with upgrade paths and operational checklist.
* [Hermes Stack Quickstart Recipes (this repo)](guides/hermes-stack-quickstart-recipes.md) - Copy/paste recipes for local dev, hosted production, secure mode, and CI operations.

## CLI and TUI Tools

Terminal-based agent interfaces and developer tools.

* [Hermes Agent](https://github.com/NousResearch/hermes-agent) ⭐ 242,509 | 🐛 40,329 | 🌐 Python | 📅 2026-09-06 - CLI and gateway agent runtime with tools, memory, delegation, and automation support.
* [Codex CLI](https://github.com/openai/codex) ⭐ 121,958 | 🐛 15,602 | 🌐 Rust | 📅 2026-09-06 - Open-source coding agent from OpenAI.
* [Gemini CLI](https://github.com/google-gemini/gemini-cli) ⭐ 106,838 | 🐛 845 | 🌐 TypeScript | 📅 2026-09-06 - Google's command-line interface for Gemini models.
* [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 82,070 | 🐛 1,029 | 🌐 Go | 📅 2026-09-06 - Terminal UI for git commonly paired with coding agents.
* [tmux](https://github.com/tmux/tmux) ⭐ 49,102 | 🐛 33 | 🌐 C | 📅 2026-09-05 - Terminal multiplexer for running agents in persistent sessions.
* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,299 | 🐛 1,898 | 🌐 Rust | 📅 2026-08-31 - Terminal workspace with plugin system for agent integration.
* [Glow](https://github.com/charmbracelet/glow) ⭐ 27,208 | 🐛 230 | 🌐 Go | 📅 2026-09-06 - Terminal Markdown renderer useful for agent output.
* [llm](https://github.com/simonw/llm) ⭐ 12,472 | 🐛 689 | 🌐 Python | 📅 2026-09-02 - CLI tool for interacting with LLMs from the terminal.
* [aichat](https://github.com/sigoden/aichat) ⭐ 10,434 | 🐛 101 | 🌐 Rust | 📅 2026-02-23 - All-in-one LLM CLI with chat, shell assistant, RAG, and agent features.
* [sgpt](https://github.com/tbckr/sgpt) ⭐ 464 | 🐛 1 | 🌐 Go | 📅 2026-09-04 - Command-line productivity tool powered by LLMs.
* [hermes-fly](https://github.com/alexfazio/hermes-fly) ⭐ 48 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-22 - CLI wizard to deploy and operate Hermes Agent on Fly.io.
* [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Agentic CLI that operates directly in the terminal.
* [Warp](https://www.warp.dev) - Modern terminal with built-in AI assistance.

## Agent Runtime Infrastructure

Execution sandboxes and runtime platforms for safely running agent actions and generated code.

* [Daytona](https://github.com/daytonaio/daytona) ⭐ 71,781 | 🐛 455 | 📅 2026-07-24 - Secure and elastic runtime infrastructure for AI-generated code execution.
* [Firecracker](https://github.com/firecracker-microvm/firecracker) ⭐ 36,578 | 🐛 103 | 🌐 Rust | 📅 2026-09-04 - Secure and fast microVM technology for isolated agent execution.
* [NemoClaw](https://github.com/NVIDIA/NemoClaw) ⭐ 22,387 | 🐛 618 | 🌐 TypeScript | 📅 2026-09-06 - NVIDIA tooling for running OpenClaw inside an OpenShell sandbox with managed inference.
* [CUA](https://github.com/trycua/cua) ⭐ 22,264 | 🐛 818 | 🌐 HTML | 📅 2026-09-06 - Open-source infrastructure for computer-use agents with sandboxes, SDKs, and benchmarks.
* [gVisor](https://github.com/google/gvisor) ⭐ 19,238 | 🐛 872 | 🌐 Go | 📅 2026-09-06 - Application kernel for containers that adds a strong isolation boundary.
* [E2B](https://github.com/e2b-dev/E2B) ⭐ 13,685 | 🐛 54 | 🌐 Python | 📅 2026-09-04 - Open-source secure cloud sandbox environment for AI agents.
* [Kata Containers](https://github.com/kata-containers/kata-containers) ⭐ 8,670 | 🐛 1,182 | 🌐 Rust | 📅 2026-09-05 - Lightweight VM-based container runtime for stronger workload isolation.
* [SandBase Harness](https://github.com/sandbaseai/sandbase-harness) ⭐ 642 | 🐛 14 | 🌐 TypeScript | 📅 2026-09-06 - Self-hosted agent runtime and MCP bridge with persistent sessions, approvals, credentials, audit/replay, and selectable execution backends.
* [RunPod Python SDK](https://github.com/runpod/runpod-python) ⭐ 309 | 🐛 85 | 🌐 Python | 📅 2026-09-02 - Python SDK for RunPod serverless and worker-based AI workloads.
* [Modal](https://modal.com) - Serverless compute platform often used for running agent workloads and tools.

<a id="mcp-ecosystem"></a>

## Agent Protocols and MCP Ecosystem

Open protocols, SDKs, servers, clients, and registries for connecting agents to tools, other agents, interfaces, and editors.

* [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) ⭐ 94,470 | 🐛 4,006 | 📅 2026-09-01 - Curated list of MCP server implementations.
* [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) ⭐ 90,109 | 🐛 493 | 🌐 TypeScript | 📅 2026-09-03 - Official reference implementations for Model Context Protocol servers.
* [Context7 MCP](https://github.com/upstash/context7) ⭐ 61,707 | 🐛 73 | 🌐 TypeScript | 📅 2026-09-04 - MCP server that retrieves current, version-specific library documentation.
* [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) ⭐ 51,156 | 🐛 99 | 🌐 TypeScript | 📅 2026-09-06 - Official Chrome DevTools MCP server for coding and browser automation agents.
* [Playwright MCP](https://github.com/microsoft/playwright-mcp) ⭐ 36,856 | 🐛 8 | 🌐 TypeScript | 📅 2026-09-04 - MCP server for browser automation via Playwright.
* [GitHub MCP Server](https://github.com/github/github-mcp-server) ⭐ 32,762 | 🐛 315 | 🌐 Go | 📅 2026-09-05 - Official MCP server for GitHub workflows and repository actions.
* [FastMCP](https://github.com/PrefectHQ/fastmcp) ⭐ 27,541 | 🐛 303 | 🌐 Python | 📅 2026-09-05 - Pythonic framework for building MCP servers and clients quickly.
* [Agent2Agent (A2A)](https://github.com/a2aproject/A2A) ⭐ 25,658 | 🐛 246 | 🌐 Shell | 📅 2026-09-04 - Linux Foundation protocol for communication between independent agent applications.
* [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) ⭐ 24,216 | 🐛 393 | 🌐 Python | 📅 2026-09-06 - Official Python SDK for building MCP servers.
* [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners) ⭐ 17,162 | 🐛 16 | 🌐 Jupyter Notebook | 📅 2026-09-03 - Cross-language curriculum and practical examples for learning MCP.
* [AG-UI](https://github.com/ag-ui-protocol/ag-ui) ⭐ 15,748 | 🐛 344 | 🌐 Python | 📅 2026-09-06 - Event-based protocol for connecting agent backends to interactive user interfaces.
* [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) ⭐ 13,336 | 🐛 597 | 🌐 TypeScript | 📅 2026-09-06 - Official TypeScript SDK for building MCP servers.
* [MCP Inspector](https://github.com/modelcontextprotocol/inspector) ⭐ 10,834 | 🐛 31 | 🌐 TypeScript | 📅 2026-09-06 - Official inspector and debugging tool for MCP servers.
* [MCP Specification Repo](https://github.com/modelcontextprotocol/modelcontextprotocol) ⭐ 9,146 | 🐛 144 | 🌐 TypeScript | 📅 2026-09-04 - Canonical specification and documentation repository.
* [MCP Go SDK](https://github.com/mark3labs/mcp-go) ⭐ 9,079 | 🐛 33 | 🌐 Go | 📅 2026-09-02 - Go implementation of the Model Context Protocol.
* [MCP Agent](https://github.com/lastmile-ai/mcp-agent) ⭐ 8,525 | 🐛 135 | 🌐 Python | 📅 2026-01-25 - Framework patterns for building agents on top of MCP.
* [MCP Registry](https://github.com/modelcontextprotocol/registry) ⭐ 7,226 | 🐛 152 | 🌐 Go | 📅 2026-09-05 - Community registry service for discovering MCP servers.
* [Agent Client Protocol](https://github.com/zed-industries/agent-client-protocol) ⭐ 4,168 | 🐛 42 | 🌐 Rust | 📅 2026-09-06 - Open protocol between coding agents and editors or IDEs.
* [MCP Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) ⭐ 3,891 | 🐛 57 | 🌐 Rust | 📅 2026-09-06 - Official Rust SDK for building MCP servers.
* [SandBase CLI](https://github.com/sandbaseai/cli) ⭐ 120 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-28 - Open-source CLI and local MCP server that configures 25 AI clients for access to 2,000+ models and APIs, with six tools for discovery, execution, run history, and account status.
* [Hexis](https://github.com/Bevel-Software/Hexis) ⭐ 84 | 🐛 8 | 🌐 TypeScript | 📅 2026-09-06 - Git-backed platform for managing skills, tools, and context for AI agents, with review workflows, role-based access, and a remote MCP server.
* [MCP Spec](https://modelcontextprotocol.io/specification) - Official Model Context Protocol specification.
* [Smithery](https://smithery.ai) - Registry and hosting platform for MCP servers.

## Prompt Engineering

Instruction-writing craft: system prompts, response framing, and reusable prompt templates.
Focus here on *what to ask and how to phrase it* at the prompt layer.

* [awesome-chatgpt-prompts](https://github.com/f/prompts.chat) ⭐ 169,507 | 🐛 74 | 🌐 HTML | 📅 2026-09-06 - Collection of prompt examples for ChatGPT.
* [fabric](https://github.com/danielmiessler/fabric) ⭐ 43,848 | 🐛 70 | 🌐 Go | 📅 2026-09-03 - Framework for augmenting humans using AI with curated prompts.
* [DSPy](https://github.com/stanfordnlp/dspy) ⭐ 37,805 | 🐛 653 | 🌐 Python | 📅 2026-09-05 - Framework for programming with foundation models instead of prompting.
* [Promptfoo](https://github.com/promptfoo/promptfoo) ⭐ 24,865 | 🐛 587 | 🌐 TypeScript | 📅 2026-09-06 - Testing and evaluation framework for LLM prompts.
* [System Prompts](https://github.com/mustvlad/ChatGPT-System-Prompts) ⭐ 1,220 | 🐛 1 | 📅 2024-12-11 - Collection of system prompts for various AI models.
* [Anthropic Prompt Library](https://docs.anthropic.com/en/prompt-library) - Official prompt examples from Anthropic.
* [Claude System Prompts](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering) - Guide to writing effective system prompts.
* [LangChain Hub](https://smith.langchain.com/hub) - Community-driven prompt and chain sharing platform.
* [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) - Official guide to designing reliable prompts and instruction patterns.

## Agent Harnessing and Evaluation

Harnesses, benchmarks, and evaluation frameworks for measuring agent quality and reliability.

### Benchmark Reality Check (real-world tool use)

* [browser-use](https://github.com/browser-use/browser-use) ⭐ 112,681 | 🐛 397 | 🌐 Python | 📅 2026-09-05 - Framework for browser task automation and agent web interaction loops.

* [AutoGen agbench](https://github.com/microsoft/autogen/blob/main/python/packages/agbench/README.md) ⭐ 60,839 | 🐛 1,050 | 🌐 Python | 📅 2026-04-15 - Benchmark runner for AutoGen agent workflows.

* [Stagehand](https://github.com/browserbase/stagehand) ⭐ 24,159 | 🐛 348 | 🌐 TypeScript | 📅 2026-09-06 - Browser automation framework for agentic web workflows and reproducible runs.

* [SWE-bench](https://github.com/SWE-bench/SWE-bench) ⭐ 5,785 | 🐛 10 | 🌐 Python | 📅 2026-09-02 - Canonical benchmark for coding agents on real GitHub issue tasks.

* [AgentBench](https://github.com/THUDM/AgentBench) ⭐ 3,714 | 🐛 76 | 🌐 Python | 📅 2026-02-08 - Multi-domain benchmark suite for evaluating LLMs as agents.

* [OSWorld](https://github.com/xlang-ai/OSWorld) ⭐ 3,125 | 🐛 202 | 🌐 Python | 📅 2026-08-30 - Open-ended benchmark environment for desktop computer-use agents.

* [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) ⭐ 2,714 | 🐛 274 | 🌐 Python | 📅 2026-09-06 - Open-source framework for reproducible LLM and agent evaluations.

* [MLE-bench](https://github.com/openai/mle-bench) ⭐ 1,736 | 🐛 10 | 🌐 Python | 📅 2026-04-24 - Benchmark harness for autonomous ML engineering tasks.

* [WebArena](https://github.com/web-arena-x/webarena) ⭐ 1,602 | 🐛 103 | 🌐 Python | 📅 2025-11-26 - Real-world web task benchmark environment for browser agents.

* [Tau-Bench](https://github.com/sierra-research/tau-bench) ⭐ 1,424 | 🐛 53 | 🌐 Python | 📅 2026-03-18 - Realistic interactive benchmark for measuring agent reliability.

* [BrowserGym](https://github.com/ServiceNow/BrowserGym) ⭐ 1,346 | 🐛 39 | 🌐 Python | 📅 2026-07-17 - Gym-style environment for training and evaluating browser agents.

* [OpenCUA](https://github.com/xlang-ai/OpenCUA) ⭐ 833 | 🐛 16 | 🌐 Python | 📅 2026-05-25 - Open foundation stack for building and evaluating computer-use agents.

* [AgentDojo](https://github.com/ethz-spylab/agentdojo) ⭐ 805 | 🐛 51 | 🌐 Python | 📅 2026-06-02 - Security and robustness benchmark suite for tool-using agents.

* [AgentEvals](https://github.com/langchain-ai/agentevals) ⭐ 717 | 🐛 25 | 🌐 Python | 📅 2026-07-14 - Evaluation utilities for scoring agent trajectories and outcomes.

* [JailbreakBench](https://github.com/JailbreakBench/jailbreakbench) ⭐ 665 | 🐛 12 | 🌐 Python | 📅 2025-04-04 - Open robustness benchmark for measuring jailbreak resistance in language models and agents.

* [ClawBench](https://github.com/TIGER-AI-Lab/ClawBench) ⭐ 663 | 🐛 52 | 🌐 Python | 📅 2026-09-05 - Browser-agent benchmark with 283 tasks (V1 153 + V2 130) across 163 live websites, safe final-action interception, and replay, action, network, and message traces.

* [AgentLab](https://github.com/ServiceNow/AgentLab) ⭐ 628 | 🐛 36 | 🌐 Python | 📅 2026-07-17 - Research platform for developing and evaluating web agents.

* [AppWorld](https://github.com/StonyBrookNLP/appworld) ⭐ 502 | 🐛 11 | 🌐 Python | 📅 2026-09-04 - Multi-application environment for benchmarking autonomous task completion.

* [MCPMark](https://github.com/eval-sys/mcpmark) ⭐ 461 | 🐛 21 | 🌐 Python | 📅 2026-06-12 - Stress-testing benchmark for evaluating model and agent capability on MCP tasks.

* [WorkArena](https://github.com/ServiceNow/WorkArena) ⭐ 270 | 🐛 25 | 🌐 Python | 📅 2026-04-25 - Enterprise task benchmark for browser-based agent workflows.

* [MCPMark (paper)](https://arxiv.org/abs/2509.24002) - 127-task MCP benchmark; reports best pass\@1 at 52.56% (gpt-5-medium), with several strong models below 30% pass\@1.

* [MCPMark (leaderboard)](https://mcpmark.ai/) - Live model comparisons for realistic MCP task execution.

* [τ-bench](https://arxiv.org/abs/2406.12045) - Tool-agent-user benchmark; reports strong function-calling agents still below 50% task success in its setup.

* [OSWorld](https://arxiv.org/abs/2404.07972) - Open-ended computer-use benchmark; reports best model 12.24% vs 72.36% human success in initial results.

* [WebArena](https://arxiv.org/abs/2307.13854) - Realistic web-task benchmark; reports best GPT-4-based agent at 14.41% vs 78.24% human.

* [GAIA](https://arxiv.org/abs/2311.12983) - General assistant benchmark; original framing reports large human-model gap on tool-heavy questions.

* [ALFWorld](https://alfworld.github.io/) - Interactive long-horizon benchmark environment for embodied planning agents.

* [HELM](https://crfm.stanford.edu/helm/latest/) - Standardized evaluation framework for model and agent behavior comparison.

* [GAIA Benchmark](https://huggingface.co/gaia-benchmark) - Realistic benchmark for tool-using, multi-step general assistant tasks.

* [Agent Harnessing Playbook (this repo)](guides/agent-harnessing-playbook.md) - Practical framework for benchmark design, regression gates, and release readiness.

## ArXiv Deep Research Map

Deep-dive reading map organized by the major categories in this repository.

* [ArXiv Deep Research Map (this repo)](guides/arxiv-deep-research-map.md) - Curated paper paths with per-category must-reads, a recent watchlist, and a monthly refresh workflow across frameworks, coding, MCP/tool use, eval reliability, memory, security, multimodal, quant, and on-chain/DeFi-adjacent research.

## Context Engineering

Systems-level context design: memory, retrieval, compression, routing, and long-horizon state management.
Focus here on *what information the model gets, when, and in what form*.

* [12-Factor Agents](https://github.com/humanlayer/12-factor-agents) ⭐ 25,727 | 🐛 27 | 🌐 TypeScript | 📅 2025-09-21 - Engineering principles for building reliable, production-grade LLM agents.
* [Anthropic: Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents) - Practical engineering patterns for agent design and execution loops.
* [Anthropic: Contextual Retrieval](https://www.anthropic.com/engineering/contextual-retrieval) - Retrieval architecture guidance for improving grounding and precision.
* [Anthropic: Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) - Production guidance for context composition and lifecycle management.
* [Anthropic: Effective Harnesses for Long-Running Agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) - Patterns for long-horizon orchestration and reliability.
* [LangChain: Context Engineering for Agents](https://blog.langchain.com/context-engineering-for-agents/) - Practical taxonomy for writing, selecting, compressing, and isolating context.
* [Manus: Context Engineering for AI Agents](https://manus.im/blog/Context-Engineering-for-AI-Agents-Lessons-from-Building-Manus) - Practitioner lessons from building production autonomous workflows.
* [OpenAI Cookbook: Getting Started with Evals](https://developers.openai.com/cookbook/examples/evaluation/getting_started_with_openai_evals) - Practical eval setup walkthrough.
* [OpenAI Evals Guide](https://platform.openai.com/docs/guides/evals) - Official framework for building eval loops and quality gates.
* [RAG (Lewis et al., 2020)](https://arxiv.org/abs/2005.11401) - Foundational retrieval-augmented generation paper.
* [Chain-of-Thought Prompting (Wei et al., 2022)](https://arxiv.org/abs/2203.02155) - Foundational reasoning/prompting technique paper.
* [Lost in the Middle (Liu et al., 2023)](https://arxiv.org/abs/2307.03172) - Key long-context failure analysis paper.
* [Context Engineering Playbook (this repo)](guides/context-engineering-playbook.md) - Practical context budget, memory, retrieval, and anti-drift checklist.
* [Agent Operator Trend Signals (this repo)](guides/agent-operator-trend-signals-2026.md) - Synthesized practitioner themes for harness and context strategy.

## Neural Networks and Neural Linking

Neural memory, retrieval, and graph-linking foundations relevant to advanced agent cognition.

* [DeepProbLog](https://github.com/ML-KULeuven/deepproblog) ⭐ 352 | 🐛 1 | 🌐 Python | 📅 2024-08-09 - Neural-symbolic framework combining perception models and logic rules.
* [Neural Turing Machines (2014)](https://arxiv.org/abs/1410.5401) - Foundational differentiable external-memory architecture.
* [End-to-End Memory Networks (2015)](https://arxiv.org/abs/1503.08895) - Multi-hop memory lookup architecture for iterative reasoning.
* [Differentiable Neural Computer (2016)](https://arxiv.org/abs/1605.08582) - Enhanced neural memory addressing for long-horizon reasoning.
* [Transformer-XL (2019)](https://arxiv.org/abs/1901.02860) - Segment-level recurrence for long-context memory reuse.
* [Compressive Transformer (2019)](https://arxiv.org/abs/1911.05507) - Compressed memory tiers for scalable sequence retention.
* [RAG (Lewis et al., 2020)](https://arxiv.org/abs/2005.11401) - Canonical retrieval-augmented generation architecture.
* [kNN Language Models (2020)](https://arxiv.org/abs/1911.00172) - Non-parametric memory retrieval at inference time.
* [RETRO (2021)](https://arxiv.org/abs/2112.04426) - Retrieval-heavy architecture for efficient knowledge access.
* [Neural Bellman-Ford Networks (2021)](https://arxiv.org/abs/2106.06935) - Graph neural reasoning for multi-hop relational inference.
* [Neural Linking and Memory Playbook (this repo)](guides/neural-linking-memory-playbook.md) - Practical guide for agent memory architectures and neural-symbolic linking patterns.

## Obsidian Vault Architecture for Agents

Obsidian-specific architecture patterns and APIs for using vaults as agent memory backends.

* [Obsidian Git](https://github.com/Vinzent03/obsidian-git) ⭐ 11,928 | 🐛 135 | 🌐 TypeScript | 📅 2026-08-17 - Versioned vault operations for auditable agent writes.
* [Dataview](https://github.com/blacksmithgu/obsidian-dataview) ⭐ 9,323 | 🐛 663 | 🌐 TypeScript | 📅 2025-11-17 - Query engine for structured note metadata and graph-aware retrieval.
* [Local REST API Plugin](https://github.com/coddingtonbear/obsidian-local-rest-api) ⭐ 2,895 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-31 - Local HTTP interface for external agent integrations.
* [obsidian-api](https://github.com/obsidianmd/obsidian-api) ⭐ 2,320 | 🐛 20 | 📅 2026-07-14 - Official API type definitions for plugin development.
* [Advanced URI](https://github.com/Vinzent03/obsidian-advanced-uri) ⭐ 1,202 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-17 - URI-based automation hooks for cross-tool workflows.
* [Juggl](https://github.com/HEmile/juggl) ⭐ 821 | 🐛 64 | 🌐 TypeScript | 📅 2025-02-27 - Advanced graph exploration plugin for complex link topology workflows.
* [How Obsidian Stores Data](https://help.obsidian.md/Files+and+folders/How+Obsidian+stores+data) - Canonical vault-on-disk model and config layout.
* [Obsidian Plugin Guide](https://docs.obsidian.md/Plugins/Getting+started/Build+a+plugin) - Official plugin architecture and lifecycle entrypoint.
* [Obsidian Properties](https://help.obsidian.md/Editing+and+formatting/Properties) - Structured metadata schema for machine-readable note attributes.
* [Obsidian TypeScript API (Vault)](https://docs.obsidian.md/Reference/TypeScript+API/Vault) - Programmatic CRUD layer for vault files.
* [Obsidian Vault Architecture Playbook (this repo)](guides/obsidian-vault-architecture-playbook.md) - Reference architecture and operational patterns for agent-connected Obsidian systems.

## Agent Security and Robustness

Safety, red-teaming, and robustness tools for hardening agent behavior.

* [Promptfoo](https://github.com/promptfoo/promptfoo) ⭐ 24,865 | 🐛 587 | 🌐 TypeScript | 📅 2026-09-06 - Red-teaming and robustness testing toolkit for LLM systems.
* [garak](https://github.com/NVIDIA/garak) ⭐ 9,127 | 🐛 417 | 🌐 Python | 📅 2026-09-04 - LLM vulnerability scanning and red-teaming toolkit for security testing.
* [Guardrails AI](https://github.com/guardrails-ai/guardrails) ⭐ 7,365 | 🐛 80 | 🌐 Python | 📅 2026-09-04 - Validation and safety guardrails framework for LLM outputs.
* [NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) ⭐ 7,073 | 🐛 218 | 🌐 Python | 📅 2026-09-04 - Toolkit for adding programmable safety and policy guardrails to LLM systems.
* [llm-attacks](https://github.com/llm-attacks/llm-attacks) ⭐ 4,781 | 🐛 69 | 🌐 Python | 📅 2024-08-02 - Reference implementation and resources for adversarial jailbreak attack evaluation.
* [PyRIT](https://github.com/microsoft/PyRIT) ⭐ 4,413 | 🐛 114 | 🌐 Python | 📅 2026-09-04 - Python Risk Identification Tool for testing generative AI systems.
* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 890 | 🐛 3 | 🌐 Python | 📅 2026-09-06 - Open source (GPL-3.0) autonomous AI penetration testing platform covering web, API, Active Directory and Kubernetes.
* [JailbreakBench](https://github.com/JailbreakBench/jailbreakbench) ⭐ 665 | 🐛 12 | 🌐 Python | 📅 2025-04-04 - Open robustness benchmark for measuring jailbreak resistance in language models and agents.
* [Invariant](https://github.com/invariantlabs-ai/invariant) ⭐ 453 | 🐛 13 | 🌐 Python | 📅 2026-01-12 - Guardrails framework for secure and robust agent development.
* [MCP Security Best Practices](https://modelcontextprotocol.io/docs/tutorials/security/security_best_practices) - Official security guidance for MCP authorization flows, threats, and mitigations.

## Agent Configs and Dotfiles

Configuration files and workflow examples for AI coding tools.

* [awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) ⭐ 40,733 | 🐛 60 | 🌐 JavaScript | 📅 2026-05-30 - Curated list of Cursor rule files.
* [Trail of Bits Claude Code Config](https://github.com/trailofbits/claude-code-config) ⭐ 2,102 | 🐛 18 | 🌐 Shell | 📅 2026-08-24 - Opinionated Claude Code defaults and workflows from a security-focused engineering team.
* [Herbert](https://github.com/robertaustinbell/herbert) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-08-27 - Runtime-neutral template for building a personal AI agent with explicit identity, judgment, memory, authority boundaries, and verified-action requirements.
* [Claude Code Memory Files](https://docs.anthropic.com/en/docs/claude-code/memory) - Guide to CLAUDE.md and project memory.
* [Claude Code Starter Configs](claude/) - Ready-to-use CLAUDE.md, rules, hooks, and skills for Claude Code projects.
* [Codex CLI Starter Configs](codex/) - Ready-to-use AGENTS.md and config for OpenAI Codex CLI projects.
* [Cursor Starter Configs](cursorrules/) - Ready-to-use .cursorrules and rule files for Cursor projects.
* [CursorDirectory](https://cursor.directory) - Community-shared Cursor rules and configurations.
* [dotfiles](https://dotfiles.github.io) - Guide to managing dotfiles including agent configurations.

## Skill Engineering and Playbooks

Hands-on resources for designing, testing, and shipping high-quality agent skills.

* [anthropics/skills](https://github.com/anthropics/skills) ⭐ 174,847 | 🐛 1,213 | 🌐 Python | 📅 2026-09-03 - Official production-ready skill examples and reference implementations.
* [Agent Skills Specification](https://github.com/agentskills/agentskills) ⭐ 25,088 | 🐛 77 | 🌐 Python | 📅 2026-08-09 - Open format and reference documentation for portable agent skill packages.
* [NVIDIA Agent Skills](https://github.com/NVIDIA/skills) ⭐ 3,218 | 🐛 14 | 🌐 Python | 📅 2026-09-06 - NVIDIA-maintained catalog of skills for CUDA-X libraries, blueprints, and platform tools.
* [SkillsBench](https://github.com/benchflow-ai/skillsbench) ⭐ 1,748 | 🐛 113 | 🌐 PDDL | 📅 2026-07-23 - Benchmark for measuring how agents use skill packages across verifiable tasks.
* [Suede Creator Skills](https://github.com/JasonColapietro/suede-creator-skills) ⭐ 133 | 🐛 7 | 🌐 JavaScript | 📅 2026-09-06 - MIT-licensed collection of 71 Claude Code and Codex skills for orchestration, worker fleets, code review, AI evaluation, product, design, and growth workflows.
* [Anthropic: The Complete Guide to Building Skills for Claude (PDF)](https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf) - Canonical end-to-end guide covering structure, triggering, testing, and distribution.
* [Claude Skill Engineering Playbook (this repo)](guides/claude-skill-engineering-playbook.md) - Distilled patterns, anti-patterns, templates, and troubleshooting from the Anthropic guide.
* [Claude Skills Quickstart Checklist (this repo)](guides/claude-skills-quickstart-checklist.md) - Build-test-ship checklist for repeatable skill quality.

## Knowledge Graphs and Memory

Agent memory architectures, knowledge graphs, and second-brain integrations.

* [Mem0](https://github.com/mem0ai/mem0) ⭐ 64,795 | 🐛 732 | 🌐 Python | 📅 2026-09-04 - Memory layer for AI assistants and agents.
* [LightRAG](https://github.com/HKUDS/LightRAG) ⭐ 39,438 | 🐛 229 | 🌐 Python | 📅 2026-09-06 - Simple and fast RAG framework using graph structures.
* [Khoj](https://github.com/khoj-ai/khoj) ⭐ 37,158 | 🐛 146 | 🌐 Python | 📅 2026-08-02 - Personal AI assistant with long-term memory and knowledge search.
* [GraphRAG](https://github.com/microsoft/graphrag) ⭐ 35,856 | 🐛 46 | 🌐 Python | 📅 2026-09-02 - Graph-based retrieval augmented generation from Microsoft.
* [Qdrant](https://github.com/qdrant/qdrant) ⭐ 34,411 | 🐛 706 | 🌐 Rust | 📅 2026-09-06 - High-performance vector search engine for agent memory.
* [Graphiti](https://github.com/getzep/graphiti) ⭐ 30,640 | 🐛 490 | 🌐 Python | 📅 2026-09-06 - Real-time knowledge graph framework for AI agents.
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 30,533 | 🐛 483 | 🌐 Python | 📅 2026-09-06 - Memory management layer for LLM apps using knowledge graphs.
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,197 | 🐛 247 | 🌐 Java | 📅 2026-08-24 - Graph database platform widely used for agent knowledge stores.
* [Weaviate](https://github.com/weaviate/weaviate) ⭐ 16,784 | 🐛 719 | 🌐 Go | 📅 2026-09-05 - Vector database with built-in modules for AI workloads.
* [txtai](https://github.com/neuml/txtai) ⭐ 12,928 | 🐛 8 | 🌐 Python | 📅 2026-09-04 - All-in-one embeddings database for semantic search and workflows.
* [FalkorDB](https://github.com/FalkorDB/FalkorDB) ⭐ 5,917 | 🐛 677 | 🌐 Rust | 📅 2026-09-06 - Ultra-fast graph database for AI agent knowledge.
* [Zep](https://github.com/getzep/zep) ⭐ 4,890 | 🐛 32 | 🌐 Python | 📅 2026-09-03 - Memory infrastructure and retrieval stack for AI assistants and agents.
* [Memgraph](https://github.com/memgraph/memgraph) ⭐ 4,392 | 🐛 820 | 🌐 C++ | 📅 2026-09-06 - In-memory graph database for real-time agent queries.
* [ReMe](https://github.com/agentscope-ai/ReMe) ⭐ 3,419 | 🐛 29 | 🌐 Python | 📅 2026-09-04 - Local-first agent memory layer with editable Markdown storage and hybrid retrieval.
* [LangMem](https://github.com/langchain-ai/langmem) ⭐ 1,646 | 🐛 65 | 🌐 Python | 📅 2026-09-04 - Memory management toolkit for building long-horizon agent systems.
* [ODIN](https://github.com/memgraph/odin) ⭐ 612 | 🐛 4 | 🌐 TypeScript | 📅 2024-03-04 - Knowledge graph construction tool built on Memgraph.
* [LWC](https://github.com/JanYork/llm-wiki-cli) ⭐ 52 | 🐛 0 | 🌐 Rust | 📅 2026-09-05 - Source-grounded project memory for coding agents with SQLite full-text retrieval, optional document and code graphs, lifecycle hooks, and a bounded read-only MCP interface.
* [obsidian-graph-query](https://github.com/azuma520/obsidian-graph-query) ⭐ 35 | 🐛 0 | 🌐 Shell | 📅 2026-03-21 - Query and traverse Obsidian vault graphs programmatically.
* [Obsidian](https://obsidian.md) - Knowledge base and note-taking app usable as agent memory backend.
* [Pinecone](https://www.pinecone.io) - Vector database for semantic memory and retrieval.

## Solana Agent Infrastructure

Tools and SDKs for building AI agents on Solana.

* [Anchor](https://github.com/solana-foundation/anchor) ⭐ 5,127 | 🐛 128 | 🌐 Rust | 📅 2026-09-06 - Core Solana framework for building and integrating smart contracts and clients.
* [Solana Web3.js](https://github.com/solana-foundation/solana-web3.js) ⭐ 2,754 | 🐛 23 | 🌐 TypeScript | 📅 2026-09-06 - JavaScript SDK for interacting with the Solana blockchain.
* [LangChain Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit) ⭐ 1,709 | 🐛 67 | 🌐 TypeScript | 📅 2026-05-14 - LangChain tools for Solana agent operations.
* [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit) ⭐ 1,709 | 🐛 67 | 🌐 TypeScript | 📅 2026-05-14 - Toolkit for connecting AI agents to Solana protocols.
* [GOAT SDK](https://github.com/goat-sdk/goat) ⭐ 1,007 | 🐛 70 | 🌐 TypeScript | 📅 2026-07-02 - Open-source toolkit connecting AI agents to 200+ on-chain tools across Solana and EVM chains.
* [Yellowstone gRPC](https://github.com/rpcpool/yellowstone-grpc) ⭐ 997 | 🐛 18 | 🌐 Rust | 📅 2026-09-05 - High-throughput real-time Solana data streams for low-latency agents and indexers.
* [Jito-Solana](https://github.com/jito-foundation/jito-solana) ⭐ 746 | 🐛 39 | 🌐 Rust | 📅 2026-09-06 - MEV-aware Solana client infrastructure for advanced execution agents.
* [Solana Kit](https://github.com/anza-xyz/kit) ⭐ 694 | 🐛 58 | 🌐 TypeScript | 📅 2026-09-04 - Modern Solana client SDK stack for building high-quality applications and agents.
* [Metaplex](https://github.com/metaplex-foundation/metaplex-program-library) ⭐ 646 | 🐛 37 | 🌐 Rust | 📅 2026-03-13 - Solana programs for NFTs and digital assets used in agent identity.
* [Awesome Solana AI](https://github.com/solana-foundation/awesome-solana-ai) ⭐ 416 | 🐛 107 | 📅 2026-08-04 - Solana Foundation's curated list of AI-Solana projects.
* [Light Protocol](https://github.com/Lightprotocol/light-protocol) ⭐ 339 | 🐛 135 | 🌐 Rust | 📅 2026-08-28 - ZK compression for scalable on-chain agent state.
* [Helius SDK](https://github.com/helius-labs/helius-sdk) ⭐ 287 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-03 - TypeScript SDK for Solana RPC, webhooks, and DAS API.
* [Pyth Crosschain](https://github.com/pyth-network/pyth-crosschain) ⭐ 247 | 🐛 170 | 🌐 TypeScript | 📅 2026-09-06 - Oracle infrastructure for low-latency market data used by agent strategies.
* [Solana Actions](https://github.com/solana-developers/solana-actions) ⭐ 146 | 🐛 21 | 🌐 TypeScript | 📅 2024-11-11 - Spec and tools for blockchain-powered actions and blinks.
* [Switchboard Solana SDK](https://github.com/switchboard-xyz/solana-sdk) ⭐ 112 | 🐛 56 | 🌐 Rust | 📅 2026-08-26 - Verifiable oracle and data-feed SDK for agent decision systems.
* [Jupiter Swap API Docs](https://dev.jup.ag/docs/swap) - Official documentation for integrating Jupiter routing and swaps.
* [Solana Agent Architecture Playbook (this repo)](guides/solana-agent-architecture-playbook.md) - Reference architecture, security controls, and ops checklist for production Solana agents.

## Agent Identity and Wallets

On-chain identity, wallets, and trust infrastructure for autonomous AI agents.

* [Safe](https://github.com/safe-fndn/safe-smart-account) ⭐ 2,176 | 🐛 34 | 🌐 TypeScript | 📅 2026-09-03 - Multi-signature smart account for EVM agent treasuries.
* [Solana Agent Identity](https://github.com/sendaifun/solana-agent-kit) ⭐ 1,709 | 🐛 67 | 🌐 TypeScript | 📅 2026-05-14 - Agent wallet and identity features in Solana Agent Kit.
* [Coinbase AgentKit](https://github.com/coinbase/agentkit) ⭐ 1,299 | 🐛 367 | 🌐 TypeScript | 📅 2026-09-03 - Toolkit for giving AI agents programmable wallet capabilities.
* [UCAN](https://github.com/ucan-wg/spec) ⭐ 291 | 🐛 23 | 📅 2026-07-08 - User-controlled authorization for decentralized agent capabilities.
* [Squads Protocol](https://github.com/Squads-Protocol/v4) ⭐ 198 | 🐛 22 | 🌐 HTML | 📅 2026-08-20 - Multisig and smart account protocol for Solana agents.
* [Sign-In With Solana](https://github.com/phantom/sign-in-with-solana) ⭐ 157 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-18 - Wallet-native authentication pattern for Solana apps and agents.
* [AgentLayer](https://github.com/lopushok9/Agent-Layer) ⭐ 27 | 🐛 16 | 🌐 Python | 📅 2026-09-01 - Open-source, local-first wallet for AI agents, with x402 payments and DeFi tools for Base, Solana, and Ethereum, including swaps, lending, and borrowing. Keys are stored in the macOS Keychain.
* [Lit Protocol](https://github.com/LIT-Protocol/lit-peer) ⭐ 3 | 🐛 21 | 🌐 Rust | 📅 2026-03-30 - Decentralized key management and programmable signing infrastructure.
* [Crossmint](https://www.crossmint.com) - Wallet-as-a-service for agent-owned wallets and NFT minting.
* [EIP-1271](https://eips.ethereum.org/EIPS/eip-1271) - Standard for contract wallet signature validation in dapps and agent auth flows.
* [EIP-4337](https://eips.ethereum.org/EIPS/eip-4337) - Account abstraction standard enabling programmable smart accounts for agents.
* [EIP-4361 (SIWE)](https://eips.ethereum.org/EIPS/eip-4361) - Sign-In with Ethereum standard for wallet-based authentication.
* [EIP-7702](https://eips.ethereum.org/EIPS/eip-7702) - EOA delegation model for temporary smart-account-like behavior.
* [ERC-7579](https://ercs.ethereum.org/ERCS/erc-7579) - Modular smart account standard for plugin-based permissions and execution.
* [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004) - Proposed standard for cross-chain agent identity.
* [Privy](https://www.privy.io) - Embedded wallet infrastructure for agent authentication.
* [Turnkey](https://www.turnkey.com) - Secure key infrastructure for programmatic wallet management.

## Agent Payments

Payment protocols and infrastructure for autonomous agent transactions.

* [Google A2A x402 Extension](https://github.com/google-agentic-commerce/a2a-x402) ⭐ 559 | 🐛 62 | 🌐 Python | 📅 2026-08-04 - Cryptocurrency payments for the Agent-to-Agent protocol via x402.
* [x402 Protocol](https://github.com/coinbase/x402) ⭐ 150 | 🐛 173 | 🌐 TypeScript | 📅 2026-09-03 - Open HTTP payment protocol using the 402 status code for agent-to-service payments.
* [Awesome Agentic Commerce](https://github.com/Merit-Systems/awesome-agentic-commerce) ⭐ 148 | 🐛 260 | 📅 2026-07-29 - Curated directory of agent payments and commerce protocols, including x402.
* [Coinbase Agentic Wallets](https://www.coinbase.com/developer-platform/discover/launches/agentic-wallets) - Wallet infrastructure for AI agents with programmable spending limits.
* [lobster.cash](https://www.lobster.cash) - Agent payment solution on Solana with Visa Intelligent Commerce integration by Crossmint.
* [Request Network](https://request.network) - Crypto-native invoicing and payment request rails for agent billing workflows.
* [Solana Pay](https://solanapay.com) - Open payments standard for Solana-based checkout and transfer flows.
* [Superfluid](https://superfluid.org) - Streaming payment primitives for machine-to-machine and agent subscriptions.
* [x402 Foundation](https://www.x402.org) - Open protocol foundation governing the x402 payment standard.

## DeFi Agents

AI agents for decentralized finance operations and strategy.

* [ElizaOS DeFi Plugins](https://github.com/elizaOS/eliza/tree/main/packages) ⭐ 19,270 | 🐛 1,317 | 🌐 TypeScript | 📅 2026-09-06 - DeFi protocol integrations for ElizaOS agents.
* [Orca Whirlpools SDK](https://github.com/orca-so/whirlpools) ⭐ 540 | 🐛 45 | 🌐 TypeScript | 📅 2026-09-03 - Solana concentrated liquidity SDK for agent strategies.
* [Drift Protocol v2](https://github.com/drift-labs/protocol-v2) ⚠️ Archived - On-chain perpetuals protocol infrastructure for autonomous trading agents.
* [Raydium SDK](https://github.com/raydium-io/raydium-sdk-V2) ⭐ 349 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-02 - Solana AMM SDK for agent-driven liquidity provision.
* [Yearn Vaults](https://github.com/yearn/yearn-vaults-v3) ⭐ 180 | 🐛 4 | 🌐 Python | 📅 2026-08-10 - Automated yield vaults usable as agent strategy backends.
* [Autonolas](https://github.com/valory-xyz/open-autonomy) ⭐ 127 | 🐛 12 | 🌐 Python | 📅 2026-08-27 - Framework for building autonomous agent services on-chain.
* [Kamino KLend SDK](https://github.com/Kamino-Finance/klend-sdk) ⭐ 61 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-24 - Lending protocol SDK for credit and yield allocation agents.
* [DeFi Llama API](https://defillama.com/docs/api) - Open API for DeFi protocol data used by trading agents.
* [Gauntlet](https://www.gauntlet.xyz) - Risk management and simulation platform for DeFi agents.
* [Griffain](https://griffain.com) - AI agent platform for Solana DeFi operations.
* [Lulo](https://lulo.fi) - Yield optimization protocol with agent-friendly APIs.
* [Virtuals Protocol](https://www.virtuals.io) - Agent tokenization and autonomous commerce protocol tracking agentic GDP.

## Quant and Trading Agents

Quantitative finance frameworks and AI-driven trading systems.

* [TradingAgents](https://github.com/TauricResearch/TradingAgents) ⭐ 102,731 | 🐛 364 | 🌐 Python | 📅 2026-09-01 - Multi-agent LLM framework simulating a trading firm.
* [Freqtrade](https://github.com/freqtrade/freqtrade) ⭐ 54,095 | 🐛 29 | 🌐 Python | 📅 2026-09-06 - Open-source algorithmic trading bot in Python.
* [Qlib](https://github.com/microsoft/qlib) ⭐ 48,355 | 🐛 474 | 🌐 Python | 📅 2026-09-02 - AI-oriented quantitative investment platform from Microsoft.
* [NautilusTrader](https://github.com/nautechsystems/nautilus_trader) ⭐ 28,520 | 🐛 119 | 🌐 Rust | 📅 2026-09-06 - High-performance algorithmic trading platform in Rust and Python.
* [Lean](https://github.com/QuantConnect/Lean) ⭐ 21,500 | 🐛 260 | 🌐 C# | 📅 2026-09-05 - Algorithmic trading engine by QuantConnect.
* [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) ⭐ 21,216 | 🐛 84 | 🌐 Jupyter Notebook | 📅 2026-09-03 - Open-source financial LLM framework.
* [Hummingbot](https://github.com/hummingbot/hummingbot) ⭐ 19,875 | 🐛 157 | 🌐 Python | 📅 2026-09-05 - Open-source market making and arbitrage bot.
* [FinRL](https://github.com/AI4Finance-Foundation/FinRL) ⭐ 16,227 | 🐛 310 | 🌐 Jupyter Notebook | 📅 2026-07-13 - Deep reinforcement learning library for quantitative finance.
* [VectorBT](https://github.com/polakowo/vectorbt) ⭐ 9,013 | 🐛 140 | 🌐 Python | 📅 2026-08-02 - Fast backtesting and analysis library for trading strategies.
* [Zipline](https://github.com/stefan-jansen/zipline-reloaded) ⭐ 1,933 | 🐛 44 | 🌐 Python | 📅 2026-01-06 - Pythonic algorithmic trading library for backtesting.
* [Phoenix v1](https://github.com/Ellipsis-Labs/phoenix-v1) ⭐ 279 | 🐛 13 | 🌐 Rust | 📅 2026-06-13 - On-chain central limit order book protocol for low-latency execution agents.
* [DriftPy](https://github.com/drift-labs/driftpy) ⚠️ Archived - Python SDK for building Solana-based perp and risk management agents.
* [BitQuant](https://github.com/OpenGradient/BitQuant) ⭐ 54 | 🐛 7 | 🌐 Python | 📅 2026-08-05 - Multi-agent quantitative analysis framework.

## Agent Observability and Testing

Debugging, tracing, evaluation, and testing tools for AI agents.

* [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 58,166 | 🐛 4,928 | 🌐 Python | 📅 2026-09-06 - LLM gateway and proxy with logging, cost tracking, and routing controls.
* [LangFuse](https://github.com/langfuse/langfuse) ⭐ 34,261 | 🐛 916 | 🌐 TypeScript | 📅 2026-09-06 - Open-source LLM engineering platform for tracing and evaluation.
* [SigNoz](https://github.com/SigNoz/signoz) ⭐ 32,028 | 🐛 1,538 | 🌐 TypeScript | 📅 2026-09-05 - OpenTelemetry-native observability platform for traces, logs, and metrics.
* [Opik](https://github.com/comet-ml/opik) ⭐ 21,834 | 🐛 265 | 🌐 Python | 📅 2026-09-06 - Open-source platform for LLM and agent tracing, evaluation, and monitoring.
* [OpenAI Evals](https://github.com/openai/evals) ⭐ 19,395 | 🐛 333 | 🌐 Python | 📅 2026-04-14 - Framework and benchmark registry for evaluating LLM systems.
* [DeepEval](https://github.com/confident-ai/deepeval) ⭐ 18,127 | 🐛 571 | 🌐 Python | 📅 2026-09-06 - Open-source LLM evaluation framework.
* [Portkey](https://github.com/Portkey-AI/gateway) ⭐ 12,915 | 🐛 258 | 🌐 TypeScript | 📅 2026-05-25 - AI gateway with observability, caching, and fallback routing.
* [Phoenix](https://github.com/Arize-ai/phoenix) ⭐ 11,346 | 🐛 979 | 🌐 Python | 📅 2026-09-06 - Open-source AI observability platform from Arize.
* [OpenLLMetry](https://github.com/traceloop/openllmetry) ⭐ 7,413 | 🐛 671 | 🌐 Python | 📅 2026-08-10 - OpenTelemetry-based observability for LLM applications.
* [Helicone](https://github.com/Helicone/helicone) ⭐ 6,133 | 🐛 155 | 🌐 TypeScript | 📅 2026-08-31 - Open-source LLM observability and monitoring platform.
* [AgentOps](https://github.com/AgentOps-AI/agentops) ⭐ 5,810 | 🐛 177 | 🌐 Python | 📅 2026-06-25 - Monitoring, cost tracking, and benchmarking for agent workflows.
* [TruLens](https://github.com/truera/trulens) ⭐ 3,536 | 🐛 64 | 🌐 Python | 📅 2026-09-04 - Open-source framework for evaluating and tracking LLM and agent experiments.
* [Weave](https://github.com/wandb/weave) ⭐ 1,125 | 🐛 220 | 🌐 Python | 📅 2026-09-04 - Toolkit for tracking and evaluating LLM applications from W\&B.
* [ax](https://github.com/Necmttn/ax) ⭐ 105 | 🐛 37 | 🌐 TypeScript | 📅 2026-09-06 - Local telemetry, recall, cost, skill, routing, and hook analytics for AI coding agents.
* [Braintrust](https://www.braintrust.dev) - Evaluation and observability platform for AI products.
* [LangSmith](https://smith.langchain.com) - Platform for debugging, testing, and monitoring LLM applications.

## Research Papers

Curated papers on AI agents, multi-agent systems, and agent infrastructure.

* [A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432) - Comprehensive survey of LLM-based agent architectures.
* [ArXiv Deep Research Map (this repo)](guides/arxiv-deep-research-map.md) - Category-by-category reading map spanning frameworks, coding, MCP/tool use, memory, security, multimodal, and quant/on-chain adjacent domains.
* [Awesome AI Agent Papers](https://github.com/VoltAgent/awesome-ai-agent-papers) ⭐ 1,752 | 🐛 0 | 📅 2026-09-05 - Continuously updated collection of agent research papers.
* [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) - Foundational paper on reasoning in language models.
* [Generative Agents](https://arxiv.org/abs/2304.03442) - Simulating human behavior with LLM-driven agents in a sandbox.
* [MemGPT](https://arxiv.org/abs/2310.08560) - OS-inspired memory management for LLM context windows.
* [ReAct](https://arxiv.org/abs/2210.03629) - Synergizing reasoning and acting in language models.
* [Reflexion](https://arxiv.org/abs/2303.11366) - Language agents with verbal reinforcement learning.
* [The Landscape of Emerging AI Agent Architectures](https://arxiv.org/abs/2404.11584) - Survey of multi-agent design patterns.
* [Toolformer](https://arxiv.org/abs/2302.04761) - Language models that learn to use tools autonomously.
* [Voyager](https://arxiv.org/abs/2305.16291) - Open-ended embodied agent with LLM-powered curriculum.

## Communities

Forums, Discord servers, newsletters, and social accounts.

* [AI Agent Discord Servers](https://discord.gg/crewai) - CrewAI community Discord.
* [Anthropic Discord](https://discord.gg/anthropic) - Official Anthropic community.
* [ElizaOS Discord](https://discord.gg/elizaos) - Community for ElizaOS agent builders.
* [LangChain Discord](https://discord.gg/langchain) - LangChain developer community.
* [Latent Space Podcast](https://www.latent.space) - Podcast covering AI engineering and agents.
* [r/artificial](https://www.reddit.com/r/artificial/) - Subreddit for AI discussions and news.
* [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) - Community for local LLM deployment and agent experimentation.
* [Solana AI Discord](https://discord.gg/solana) - Solana developer community with AI channels.

***

## Contributing

![Resources are reviewed for maintenance, documentation, distinct value, operability, and security](public/readme/resource-signals.jpeg)

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) before opening a pull request. One focused resource per PR keeps review evidence clear.

For broken links, outdated descriptions, or missing categories, use the repository's structured [issue forms](https://github.com/0xNyk/awesome-agent-cortex/issues/new/choose) ⭐ 218 | 🐛 25 | 🌐 JavaScript | 📅 2026-09-02. [SUPPORT.md](SUPPORT.md) routes broader questions, and [SECURITY.md](SECURITY.md) covers private vulnerability reporting.

Maintenance is best-effort. Inclusion does not mean endorsement, security certification, or a promise that a third-party project will remain available.

### Support the project

If the directory saves you research time, [sponsor its continued maintenance](https://github.com/sponsors/0xNyk) or support the repository with a star.

Solana: `2k1oq9U99mwy4gm8P2hXPJoZusoXQCpFs35EEf5Ve73y`

***

Built and maintained by [Nyk](https://nyk.dev). Follow [@nykdotdev](https://x.com/nykdotdev). For agent infrastructure, trading systems, and Solana product work, visit [Builderz](https://builderz.dev).

Released under [CC0 1.0 Universal](LICENSE).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-06._
