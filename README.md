# Awesome AgentOS with stars

> Platforms that coordinate AI agents with tools, voice, vision, and memory.

## Contents

* [Agent Frameworks & Orchestrators](#agent-frameworks--orchestrators)
* [Computer-Use & Desktop Automation](#computer-use--desktop-automation)
* [Web Agents & Browser Automation](#web-agents--browser-automation)
* [Voice & Conversational AI](#voice--conversational-ai)
* [Visual & Creative AI](#visual--creative-ai)
* [Developer Tools & Code Assistants](#developer-tools--code-assistants)
* [LLM Infrastructure & Model Serving](#llm-infrastructure--model-serving)
* [Security & Offensive AI](#security--offensive-ai)
* [Data, Memory & Knowledge](#data-memory--knowledge)
* [Datasets & Benchmarks](#datasets--benchmarks)
* [Productivity & Personal Assistants](#productivity--personal-assistants)
* [MCP & Tool Integration](#mcp--tool-integration)

## Agent Frameworks & Orchestrators

Frameworks for building, deploying, and managing multi-agent systems.

* [Hermes Agent](https://github.com/NousResearch/hermes-agent) ⭐ 257,141 | 🐛 51,158 | 🌐 Python | 📅 2026-10-26 - Adaptive AI agent platform built on the Hermes model family.
* [n8n](https://github.com/n8n-io/n8n) ⭐ 208,613 | 🐛 1,262 | 🌐 TypeScript | 📅 2026-10-26 - Fair-code workflow automation platform with native AI capabilities and 400+ integrations.
* [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) ⭐ 187,750 | 🐛 731 | 🌐 Python | 📅 2026-10-26 - Experimental open-source application showcasing GPT-4 capabilities for autonomous tasks.
* [Langflow](https://github.com/langflow-ai/langflow) ⭐ 156,024 | 🐛 1,225 | 🌐 Python | 📅 2026-10-26 - Low-code platform for building and deploying AI-powered agents and workflows.
* [Pi](https://github.com/earendil-works/pi) ⭐ 117,859 | 🐛 385 | 🌐 TypeScript | 📅 2026-10-25 - Agent toolkit providing a unified multi-provider LLM API, an agent runtime with tool calling, a terminal UI, and a self-extensible coding agent CLI.
* [autoresearch](https://github.com/karpathy/autoresearch) ⭐ 98,590 | 🐛 195 | 🌐 Python | 📅 2026-03-26 - AI agents that run research on single-GPU training automatically.
* [DeerFlow](https://github.com/bytedance/deer-flow) ⭐ 84,431 | 🐛 955 | 🌐 Python | 📅 2026-10-26 - Open-source SuperAgent harness with sandboxes, memories, tools, and subagents.
* [MiroFish](https://github.com/666ghj/MiroFish) ⭐ 81,965 | 🐛 202 | 🌐 Python | 📅 2026-10-16 - Swarm-intelligence engine that builds multi-agent simulated worlds from seed data to explore predictions and social dynamics.
* [Open Interpreter](https://github.com/openinterpreter/openinterpreter) ⭐ 68,672 | 🐛 24 | 🌐 Rust | 📅 2026-10-11 - Open-source AI agent that executes code on your computer to perform tasks.
* [OpenManus](https://github.com/FoundationAgents/OpenManus) ⭐ 58,783 | 🐛 441 | 🌐 Python | 📅 2026-09-30 - Open-source implementation of an autonomous AI agent.
* [Goose](https://github.com/block/goose) ⭐ 55,725 | 🐛 514 | 🌐 Rust | 📅 2026-10-26 - On-machine AI agent that automates development tasks with MCP support.
* [Huginn](https://github.com/huginn/huginn) ⭐ 50,139 | 🐛 688 | 🌐 Ruby | 📅 2026-10-24 - System for creating agents that monitor and act on your behalf across the web.
* [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) ⭐ 40,268 | 🐛 12 | 🌐 TypeScript | 📅 2026-10-26 - Teams-first multi-agent orchestration layer for Claude Code with parallel execution.
* [Sim](https://github.com/simstudioai/sim) ⭐ 29,921 | 🐛 347 | 🌐 TypeScript | 📅 2026-10-25 - Open-source platform to build and deploy AI agent workflows.
* [Mastra](https://github.com/mastra-ai/mastra) ⭐ 29,076 | 🐛 620 | 🌐 TypeScript | 📅 2026-10-26 - TypeScript framework for building AI-powered applications and agents.
* [Letta](https://github.com/letta-ai/letta) ⭐ 25,259 | 🐛 0 | 📅 2026-10-18 - Platform for building stateful agents with memory that learn over time.
* [Activepieces](https://github.com/activepieces/activepieces) ⭐ 25,228 | 🐛 792 | 🌐 TypeScript | 📅 2026-10-26 - Open-source AI automation framework with MCP server support.
* [Eliza](https://github.com/elizaOS/eliza) ⭐ 19,652 | 🐛 506 | 🌐 TypeScript | 📅 2026-10-26 - Multi-agent simulation framework with Discord, Telegram, and Twitter integration.
* [RowBoat](https://github.com/rowboatlabs/rowboat) ⭐ 18,086 | 🐛 216 | 🌐 TypeScript | 📅 2026-10-26 - Open-source AI coworker with persistent memory for long-running tasks.
* [OpenHarness](https://github.com/HKUDS/OpenHarness) ⭐ 16,095 | 🐛 97 | 🌐 Python | 📅 2026-06-04 - Open agent harness with a built-in personal agent called Ohmo.
* [ironclaw](https://github.com/nearai/ironclaw) ⭐ 12,676 | 🐛 1,565 | 🌐 Rust | 📅 2026-10-25 - Agent OS focused on privacy, security, and extensibility with Rust and WASM.
* [Atomic Agents](https://github.com/Eigenwise/atomic-agents) ⭐ 6,308 | 🐛 6 | 🌐 Python | 📅 2026-10-24 - Lightweight Python framework for building agentic pipelines from composable, single-purpose components built on Pydantic and Instructor.
* [SwarmForge](https://github.com/unclebob/swarm-forge) ⭐ 4,043 | 🐛 53 | 🌐 Clojure | 📅 2026-09-07 - Coordinates AI coding agents in isolated git worktrees and tmux sessions, with durable handoffs and an operator dashboard for approvals and oversight.
* [Auto-Company](https://github.com/MaxMiksa/Auto-Company) ⭐ 3,157 | 🐛 1 | 🌐 Python | 📅 2026-10-23 - Multi-agent system that operates autonomously on your own PC across Windows, Linux, and macOS.
* [NextPy](https://github.com/dot-agent/nextpy) ⭐ 2,348 | 🐛 23 | 🌐 Python | 📅 2024-05-01 - Self-modifying framework for building agentic modular systems.
* [Ouroboros](https://github.com/razzant/ouroboros) ⭐ 1,586 | 🐛 215 | 🌐 Python | 📅 2026-10-26 - Runs general-purpose tasks through a desktop app or headless CLI, coordinates specialist agents, preserves identity and memory across restarts, and can modify its own implementation through reviewed Git commits.
* [SmythOS](https://github.com/SmythOS/sre) ⭐ 1,303 | 🐛 35 | 🌐 TypeScript | 📅 2026-04-03 - Cloud-native runtime for building, running, and managing agentic AI systems.
* [Open Agent](https://github.com/AFK-surf/open-agent) ⭐ 1,037 | 🐛 9 | 🌐 TypeScript | 📅 2025-10-10 - Open-source alternative to Claude Agent SDK, ChatGPT Agents, and Manus.
* [nodetool](https://github.com/nodetool-ai/nodetool) ⭐ 588 | 🐛 10 | 🌐 TypeScript | 📅 2026-10-26 - Open-source, agent-first creative workspace with node-based workflows and multi-provider LLM support.
* [Kitaru](https://github.com/zenml-io/kitaru) ⭐ 314 | 🐛 94 | 🌐 Python | 📅 2026-10-26 - Durable execution layer for AI agents with checkpoints, replay, resume, and memory.
* [kami](https://github.com/kami-community/kami) ⭐ 65 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-09 - Automating content and outreach with multi-agent coordination for early-stage startups.
* [Shire](https://github.com/victor36max/shire) ⭐ 40 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-03 - Persistent workspaces for AI agent teams with inter-agent mailboxes and shared drive.

## Computer-Use & Desktop Automation

Agents that control desktops, interact with operating systems, and automate computer tasks.

* [Puter](https://github.com/HeyPuter/puter) ⭐ 43,890 | 🐛 44 | 🌐 TypeScript | 📅 2026-10-26 - Open-source, self-hostable cloud desktop operating system.
* [Project NOMAD](https://github.com/Crosstalk-Solutions/project-nomad) ⭐ 40,952 | 🐛 132 | 🌐 TypeScript | 📅 2026-10-22 - Self-contained, offline survival computer with tools, knowledge, and AI.
* [UI-TARS Desktop](https://github.com/bytedance/UI-TARS-desktop) ⭐ 39,391 | 🐛 506 | 🌐 TypeScript | 📅 2026-10-09 - Open-source multimodal AI agent stack for desktop automation.
* [CUA](https://github.com/trycua/cua) ⭐ 30,979 | 🐛 1,299 | 🌐 Rust | 📅 2026-10-26 - Open-source infrastructure for Computer-Use Agents with sandboxes, SDKs, and benchmarks.
* [Agent-S](https://github.com/simular-ai/Agent-S) ⭐ 12,741 | 🐛 71 | 🌐 Python | 📅 2026-10-24 - Open agentic framework designed to use computers like a human.
* [HolaOS](https://github.com/holaboss-ai/holaOS) ⭐ 11,428 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-25 - Local-first agent for work that learns your working context and retains it.
* [Coworker](https://github.com/accomplish-ai/coworker) ⭐ 10,831 | 🐛 13 | 📅 2026-08-13 - Open-source AI coworker that lives on your desktop.
* [OBLITERATUS](https://github.com/elder-plinius/OBLITERATUS) ⭐ 8,962 | 🐛 6 | 🌐 Python | 📅 2026-10-24 - Framework for bypassing AI restrictions and enabling unrestricted model operation.
* [Skales](https://github.com/skalesapp/skales) ⭐ 2,216 | 🐛 2 | 📅 2026-10-22 - Local-first desktop AI agent that runs offline via Ollama or 15+ providers.
* [Autonomous Computer](https://github.com/autonomous-ai/autonomous-computer) ⭐ 1,542 | 🐛 1 | 📅 2026-10-06 - Toolkit for building a personal AI computer.

## Web Agents & Browser Automation

Browser control, web scraping, and internet interaction agents.

* [browser-use](https://github.com/browser-use/browser-use) ⭐ 119,150 | 🐛 608 | 🌐 Python | 📅 2026-10-24 - Library for building agents that see, navigate, and interact with web browsers.
* [Agent Reach](https://github.com/Panniantong/Agent-Reach) ⭐ 102,658 | 🐛 244 | 🌐 Python | 📅 2026-10-25 - Tool for giving AI agents access to Twitter, Reddit, YouTube, GitHub, and more.
* [Crawl4AI](https://github.com/unclecode/crawl4ai) ⭐ 86,277 | 🐛 282 | 🌐 Python | 📅 2026-10-22 - Open-source, LLM-friendly web crawler and scraper for AI data gathering.
* [Lightpanda](https://github.com/lightpanda-io/browser) ⭐ 37,002 | 🐛 98 | 🌐 Zig | 📅 2026-10-26 - Headless browser written in Zig, built for AI and automation, compatible with CDP, Playwright, and Puppeteer.
* [AIHawk](https://github.com/feder-cr/AIHawk) ⭐ 32,250 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-25 - Open-source AI browser agent that browses, clicks, types, and reads the web from plain-English instructions, available as an MCP server (Claude Code, Codex, Gemini CLI) or a standalone web UI.
* [Stagehand](https://github.com/browserbase/stagehand) ⭐ 25,814 | 🐛 386 | 🌐 TypeScript | 📅 2026-10-23 - SDK built on Playwright for authoring browser agents that extract data and interact with websites.
* [Browser Harness](https://github.com/browser-use/browser-harness) ⭐ 18,619 | 🐛 426 | 🌐 Python | 📅 2026-10-25 - Self-healing harness that enables LLMs to complete browser tasks.
* [Web UI](https://github.com/browser-use/web-ui) ⭐ 16,624 | 🐛 326 | 🌐 Python | 📅 2026-09-25 - Web interface for running and managing AI agents in your browser.
* [Nanobrowser](https://github.com/nanobrowser/nanobrowser) ⭐ 14,181 | 🐛 47 | 🌐 TypeScript | 📅 2026-10-24 - Open-source Chrome extension for AI-powered web automation with multi-agent workflows.
* [BrowserOS](https://github.com/browseros-ai/BrowserOS) ⭐ 14,102 | 🐛 101 | 🌐 TypeScript | 📅 2026-10-26 - Open-source agentic browser as an alternative to proprietary AI browsing tools.
* [Browserless](https://github.com/browserless/browserless) ⭐ 13,859 | 🐛 18 | 🌐 TypeScript | 📅 2026-10-26 - Headless browser deployment platform for Docker and cloud environments.
* [WebVoyager](https://github.com/MinorJerry/WebVoyager) ⭐ 1,127 | 🐛 12 | 🌐 Python | 📅 2024-03-04 - End-to-end web agent framework powered by large multimodal models.
* [Agentic AI Browser](https://github.com/esinecan/agentic-ai-browser) ⭐ 163 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-04 - AI-driven web automation agent using Playwright for decision-making.
* [Vibe Eyes](https://github.com/monteslu/vibe-eyes) ⭐ 54 | 🐛 2 | 🌐 JavaScript | 📅 2026-02-04 - MCP server that enables LLMs to see and interact with browser-based applications.

## Voice & Conversational AI

Text-to-speech, speech-to-text, voice assistants, and real-time audio systems.

* [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) ⭐ 63,736 | 🐛 904 | 🌐 Python | 📅 2026-10-19 - Few-shot voice cloning and text-to-speech model training framework.
* [VibeVoice](https://github.com/microsoft/VibeVoice) ⭐ 54,972 | 🐛 201 | 🌐 Python | 📅 2026-10-08 - Open-source voice AI for audio synthesis.
* [Fish Speech](https://github.com/fishaudio/fish-speech) ⭐ 33,404 | 🐛 25 | 🌐 Python | 📅 2026-10-14 - Open-source text-to-speech engine with multilingual voice cloning.
* [Chatterbox](https://github.com/resemble-ai/chatterbox) ⭐ 27,254 | 🐛 376 | 🌐 Python | 📅 2026-07-21 - Open-source text-to-speech engine for realistic voices.
* [LiveKit](https://github.com/livekit/livekit) ⭐ 21,819 | 🐛 198 | 🌐 Go | 📅 2026-10-26 - End-to-end realtime stack for connecting humans and AI with low-latency audio/video.
* [Dia](https://github.com/nari-labs/dia) ⭐ 19,406 | 🐛 91 | 🌐 Python | 📅 2025-11-19 - TTS model capable of generating realistic dialogue in a single pass.
* [KittenTTS](https://github.com/KittenML/KittenTTS) ⭐ 16,485 | 🐛 143 | 🌐 Python | 📅 2026-10-22 - TTS model under 25MB for compact, high-quality voice synthesis.
* [LiveKit Agents](https://github.com/livekit/agents) ⭐ 14,935 | 🐛 806 | 🌐 Python | 📅 2026-10-26 - Framework for building realtime voice AI agents with audio and video pipelines.
* [YuE](https://github.com/multimodal-art-projection/YuE) ⭐ 12,731 | 🐛 91 | 🌐 Python | 📅 2026-10-06 - Open full-song music generation foundation model.
* [Pocket TTS](https://github.com/kyutai-labs/pocket-tts) ⭐ 10,073 | 🐛 64 | 🌐 Python | 📅 2026-10-22 - Text-to-speech model designed to run efficiently on consumer CPUs.
* [MLX Audio](https://github.com/Blaizzy/mlx-audio) ⭐ 8,103 | 🐛 97 | 🌐 Python | 📅 2026-10-25 - Text-to-speech, speech-to-text, and speech-to-speech library built on Apple's MLX framework.
* [NeuTTS](https://github.com/neuphonic/neutts) ⭐ 6,334 | 🐛 37 | 🌐 Python | 📅 2026-07-30 - On-device text-to-speech model by Neuphonic for private voice synthesis.
* [Piper](https://github.com/OHF-Voice/piper1-gpl) ⭐ 6,022 | 🐛 155 | 🌐 C++ | 📅 2026-10-25 - Fast and local neural text-to-speech engine for low-latency applications.
* [MisoTTS](https://github.com/MisoLabsAI/MisoTTS) ⭐ 3,246 | 🐛 21 | 🌐 Python | 📅 2026-06-09 - 8-billion parameter text-to-speech model for highly emotive voice generation.
* [Jarvis](https://github.com/isair/jarvis) ⭐ 2,137 | 🐛 157 | 🌐 Python | 📅 2026-10-20 - Private AI voice assistant that runs offline on your computer.
* [Kokoro TTS](https://github.com/nazdridoy/kokoro-tts) ⭐ 1,961 | 🐛 18 | 🌐 Python | 📅 2026-08-22 - CLI-based text-to-speech tool utilizing the Kokoro model for multiple languages.
* [Tada](https://github.com/HumeAI/tada) ⭐ 1,019 | 🐛 19 | 🌐 Jupyter Notebook | 📅 2026-05-11 - Open-source speech language model for expressive, emotionally-aware audio generation.
* [Fun Audio Chat](https://github.com/QwenAudio/Fun-Audio-Chat) ⭐ 1,011 | 🐛 19 | 🌐 Python | 📅 2026-09-24 - Large audio language model for natural, low-latency voice interactions.
* [Confucius4-TTS](https://github.com/netease-youdao/Confucius4-TTS) ⭐ 848 | 🐛 11 | 🌐 Python | 📅 2026-10-23 - TTS model optimized for long-form Chinese and English content with strong emotion control.
* [Liquid Audio](https://github.com/Liquid4All/liquid-audio) ⭐ 578 | 🐛 10 | 🌐 Python | 📅 2026-10-03 - Speech-to-speech audio models developed by Liquid AI.
* [Audio2Face 3D](https://github.com/NVIDIA/Audio2Face-3D-Samples) ⭐ 334 | 🐛 24 | 🌐 Python | 📅 2026-03-11 - Service for converting audio to facial blendshapes for lipsync and real-time facial performances.

## Visual & Creative AI

Image generation, video creation, 3D modeling, and visual manipulation tools.

* [DragGAN](https://github.com/XingangPan/DragGAN) ⭐ 35,720 | 🐛 154 | 🌐 Python | 📅 2024-05-18 - Interactive point-based manipulation for precise control over generative images.
* [Open-Sora](https://github.com/hpcaitech/Open-Sora) ⭐ 29,878 | 🐛 14 | 🌐 Python | 📅 2026-04-09 - Open-source video generation models for efficient video production.
* [InvokeAI](https://github.com/invoke-ai/InvokeAI) ⭐ 28,865 | 🐛 399 | 🌐 TypeScript | 📅 2026-10-26 - Creative engine for Stable Diffusion models to generate visual media.
* [Duix Avatar](https://github.com/duixcom/Duix-Avatar) ⭐ 16,076 | 🐛 423 | 🌐 C | 📅 2026-04-21 - Open-source toolkit for AI avatar creation and digital human cloning.
* [Z-Image](https://github.com/Tongyi-MAI/Z-Image) ⭐ 12,118 | 🐛 113 | 🌐 Python | 📅 2026-02-09 - Open-source image generation model from Alibaba's Tongyi team.
* [Sana](https://github.com/NVlabs/Sana) ⭐ 9,652 | 🐛 132 | 🌐 Python | 📅 2026-10-23 - High-resolution image synthesis using Linear Diffusion Transformers.
* [Modly](https://github.com/lightningpixel/modly) ⭐ 8,384 | 🐛 106 | 🌐 TypeScript | 📅 2026-10-20 - Desktop app for generating 3D models from images using local AI.
* [SkyReels V2](https://github.com/SkyworkAI/SkyReels-V2) ⭐ 7,735 | 🐛 375 | 🌐 Python | 📅 2026-01-29 - Generative model for creating infinite-length AI films.
* [TripoSR](https://github.com/VAST-AI-Research/TripoSR) ⭐ 7,221 | 🐛 107 | 🌐 Python | 📅 2026-06-04 - Fast 3D object reconstruction from a single image using AI.
* [HunyuanVideo 1.5](https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5) ⭐ 4,579 | 🐛 39 | 🌐 Python | 📅 2026-04-10 - Lightweight video generation model for high-quality output.
* [Helios](https://github.com/PKU-YuanGroup/Helios) ⭐ 2,225 | 🐛 44 | 🌐 Python | 📅 2026-08-24 - Real-time long video generation model for streaming video synthesis.
* [Node Banana](https://github.com/shrimbly/node-banana) ⭐ 1,649 | 🐛 23 | 🌐 TypeScript | 📅 2026-10-26 - Free and open-source node-based generative workflow platform.
* [Short Video Maker](https://github.com/gyoridavid/short-video-maker) ⭐ 1,433 | 🐛 29 | 🌐 TypeScript | 📅 2025-06-21 - Creates short videos for TikTok, Instagram Reels, and YouTube Shorts using MCP.
* [FlashWorld](https://github.com/imlixinyang/FlashWorld) ⭐ 869 | 🐛 18 | 🌐 Python | 📅 2026-03-24 - High-quality 3D scene generation framework that works within seconds.
* [Realtime Video](https://github.com/krea-ai/realtime-video) ⭐ 593 | 🐛 17 | 🌐 Python | 📅 2025-11-13 - Open-source model for high-quality, realtime AI video generation.
* [RealWonder](https://github.com/liuwei283/RealWonder) ⭐ 229 | 🐛 3 | 🌐 Python | 📅 2026-03-06 - Real-time physical action-conditioned video generation model.
* [EditThinker](https://github.com/appletea233/EditThinker) ⭐ 113 | 🐛 5 | 🌐 Python | 📅 2026-01-18 - Iterative reasoning framework for step-by-step thinking in image editing.
* [Streamo](https://github.com/maifoundations/Streamo) ⭐ 95 | 🐛 10 | 🌐 Python | 📅 2026-02-25 - Streaming video instruction tuning framework for continuous video understanding.
* [Cutalyst](https://github.com/MamtaRajpurohit/Cutalyst) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-04 - Automated video editing AI that cuts, syncs, and subtitles videos.

## Developer Tools & Code Assistants

Code editors, coding agents, and development tools.

* [Ponytail](https://github.com/DietrichGebert/ponytail) ⭐ 176,379 | 🐛 137 | 🌐 JavaScript | 📅 2026-10-18 - Agent skill and rules package that steers coding agents toward writing minimal code.
* [CodeGraph](https://github.com/colbymchenry/codegraph) ⭐ 75,358 | 🐛 540 | 🌐 C | 📅 2026-10-24 - Pre-indexed code knowledge graph that auto-syncs on code changes for multiple AI coding tools.
* [Oh My OpenAgent](https://github.com/code-yeongyu/oh-my-openagent) ⭐ 70,341 | 🐛 1,771 | 🌐 TypeScript | 📅 2026-10-26 - Batteries-included agent harness for complex codebases.
* [OpenClaude](https://github.com/Twigpine/openclaude) ⭐ 34,154 | 🐛 55 | 🌐 TypeScript | 📅 2026-10-26 - Open-source coding-agent CLI that works with cloud and local model providers, with tools, agents, and MCP support.
* [Open Lovable](https://github.com/firecrawl/open-lovable) ⭐ 28,799 | 🐛 152 | 🌐 TypeScript | 📅 2026-10-09 - Tool for cloning and recreating websites as modern React apps using AI.
* [Dyad](https://github.com/dyad-sh/dyad) ⭐ 22,069 | 🐛 349 | 🌐 TypeScript | 📅 2026-10-22 - Local, open-source AI app builder for power users.
* [DeepCode](https://github.com/HKUDS/DeepCode) ⭐ 16,754 | 🐛 34 | 🌐 Python | 📅 2026-10-25 - Open agentic coding framework for paper-to-code and web development tasks.
* [sandcastle](https://github.com/mattpocock/sandcastle) ⭐ 8,643 | 🐛 184 | 🌐 TypeScript | 📅 2026-10-20 - TypeScript library for orchestrating sandboxed coding agents.
* [ClawX](https://github.com/ValueCell-ai/ClawX) ⭐ 7,602 | 🐛 44 | 🌐 TypeScript | 📅 2026-10-26 - Desktop app providing a graphical interface for OpenClaw AI agents.
* [OpenBot](https://github.com/CopilotKit/OpenBot) ⭐ 7,138 | 🐛 43 | 🌐 TypeScript | 📅 2026-10-25 - Open-source coding agent for VS Code powered by CopilotKit.
* [Emdash](https://github.com/generalaction/emdash) ⭐ 6,079 | 🐛 103 | 🌐 TypeScript | 📅 2026-10-23 - Open-source agentic development environment for running multiple coding agents in parallel.
* [CodeNomad](https://github.com/NeuralNomadsAI/CodeNomad) ⭐ 2,648 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-26 - Multi-agent coding orchestration platform for parallel AI-assisted development.
* [Mysti](https://github.com/DeepMyst/Mysti) ⭐ 1,144 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-13 - AI coding dream team of agents for VS Code that debate and synthesize solutions.
* [Clawmetry](https://github.com/vivekchand/clawmetry) ⭐ 434 | 🐛 154 | 🌐 Python | 📅 2026-10-26 - Real-time observability dashboard for OpenClaw AI agents.
* [Persona](https://github.com/runtypelabs/persona) ⭐ 253 | 🐛 12 | 🌐 TypeScript | 📅 2026-10-25 - Toolkit for creating agentic front-end experiences for the web with WebMCP support.

## LLM Infrastructure & Model Serving

Model hosting, fine-tuning, API gateways, and inference optimization.

* [RTK](https://github.com/rtk-ai/rtk) ⭐ 84,573 | 🐛 1,601 | 🌐 Rust | 📅 2026-10-25 - Rust CLI proxy that filters and compresses command output before it reaches the LLM context.
* [Unsloth](https://github.com/unslothai/unsloth) ⭐ 78,572 | 🐛 339 | 🌐 Python | 📅 2026-10-26 - Fine-tuning and reinforcement learning framework for LLMs.
* [Headroom](https://github.com/headroomlabs-ai/headroom) ⭐ 77,846 | 🐛 550 | 🌐 Python | 📅 2026-10-24 - Tool for compressing tool outputs, logs, files, and RAG chunks before they reach the LLM.
* [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 62,043 | 🐛 5,707 | 🌐 Python | 📅 2026-10-26 - Python SDK and proxy server to call 100+ LLM APIs in a unified OpenAI format.
* [LocalAI](https://github.com/mudler/LocalAI) ⭐ 49,963 | 🐛 188 | 🌐 Go | 📅 2026-10-25 - Self-hosted, local-first open-source alternative to OpenAI and Claude APIs.
* [freellmapi](https://github.com/tashfeenahmed/freellmapi) ⭐ 41,713 | 🐛 47 | 🌐 TypeScript | 📅 2026-10-25 - OpenAI-compatible proxy that stacks free tiers of 28 LLM providers behind a single endpoint with smart routing and failover.
* [LLMFit](https://github.com/AlexsJones/llmfit) ⭐ 38,379 | 🐛 70 | 🌐 Rust | 📅 2026-10-26 - Tool for discovering hundreds of models across providers to find what runs on your hardware.
* [PowerInfer](https://github.com/Tiiny-AI/PowerInfer) ⭐ 9,850 | 🐛 131 | 🌐 C++ | 📅 2026-05-11 - High-speed LLM serving for local deployment with CPU/GPU heterogeneous inference.

## Security & Offensive AI

Penetration testing, red teaming, vulnerability scanning, and security tools.

* [Strix](https://github.com/usestrix/strix) ⭐ 71,947 | 🐛 506 | 🌐 Python | 📅 2026-10-25 - Open-source AI tool for finding and fixing application vulnerabilities.
* [Shannon](https://github.com/KeygraphHQ/shannon) ⭐ 49,355 | 🐛 29 | 🌐 TypeScript | 📅 2026-10-15 - Autonomous AI pentester for web applications and APIs that analyzes source code and executes exploits.
* [Pentagi](https://github.com/vxcontrol/pentagi) ⭐ 32,445 | 🐛 57 | 🌐 Go | 📅 2026-10-22 - Fully autonomous AI agents system for complex penetration testing tasks end-to-end.
* [SkillSpector](https://github.com/NVIDIA/SkillSpector) ⭐ 21,639 | 🐛 170 | 🌐 Python | 📅 2026-10-23 - Security scanner for AI agent skills that detects vulnerabilities and malicious patterns.
* [OneCLI](https://github.com/onecli/onecli) ⭐ 3,591 | 🐛 180 | 🌐 TypeScript | 📅 2026-10-22 - Open-source credential vault for AI agents that injects API keys transparently.
* [RedAMon](https://github.com/samugit83/redamon) ⭐ 3,214 | 🐛 23 | 🌐 Python | 📅 2026-10-22 - AI-powered agentic red team framework for offensive security operations from recon to post-exploitation.
* [Pentest-Swarm-AI](https://github.com/Armur-Ai/Pentest-Swarm-AI) ⭐ 3,050 | 🐛 23 | 🌐 Go | 📅 2026-10-26 - Autonomous penetration testing using a swarm of AI agents with specialized roles.
* [Azazel](https://github.com/beelzebub-labs/azazel) ⭐ 111 | 🐛 3 | 🌐 C | 📅 2026-10-19 - eBPF-powered observer for containerized runtimes, built for malware analysis and AI monitoring.

## Data, Memory & Knowledge

OCR, knowledge graphs, memory systems, and data infrastructure.

* [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) ⭐ 91,676 | 🐛 258 | 🌐 Python | 📅 2026-09-16 - Comprehensive OCR toolkit supporting 100+ languages and complex layouts.
* [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) ⭐ 88,296 | 🐛 336 | 🌐 TypeScript | 📅 2026-10-22 - Turns codebases into interactive knowledge graphs for AI agents to explore, search, and query.
* [Docling](https://github.com/docling-project/docling) ⭐ 69,593 | 🐛 917 | 🌐 Python | 📅 2026-10-25 - Tool for converting various document formats into AI-ready structured data.
* [Pathway](https://github.com/pathwaycom/pathway) ⭐ 62,065 | 🐛 37 | 🌐 Python | 📅 2026-10-26 - Python ETL framework for real-time analytics, stream processing, and RAG.
* [Graphiti](https://github.com/getzep/graphiti) ⭐ 32,224 | 🐛 519 | 🌐 Python | 📅 2026-10-26 - Tool for building real-time knowledge graphs to power AI agent memory.
* [OLMocr](https://github.com/allenai/olmocr) ⭐ 19,802 | 🐛 92 | 🌐 Python | 📅 2026-03-25 - Toolkit for linearizing PDFs to prepare datasets for LLM training.
* [Memori](https://github.com/MemoriLabs/Memori) ⭐ 17,141 | 🐛 43 | 🌐 Python | 📅 2026-10-03 - SQL-native memory layer for LLMs, AI agents, and multi-agent systems.
* [memU](https://github.com/NevaMind-AI/memU) ⭐ 14,561 | 🐛 136 | 🌐 Python | 📅 2026-10-26 - Memory system designed for 24/7 proactive agents.
* [Chandra](https://github.com/datalab-to/chandra) ⭐ 12,586 | 🐛 64 | 🌐 Python | 📅 2026-10-22 - Specialized OCR model for parsing complex tables, forms, and handwriting.
* [MemOS](https://github.com/MemTensor/MemOS) ⭐ 12,096 | 🐛 161 | 🌐 TypeScript | 📅 2026-10-24 - AI memory operating system for persistent skill storage in agent systems.
* [FalkorDB](https://github.com/FalkorDB/FalkorDB) ⭐ 10,493 | 🐛 855 | 🌐 Rust | 📅 2026-10-26 - Fast graph database using GraphBLAS for GraphRAG and knowledge graphs for LLMs.
* [Dolphin](https://github.com/bytedance/Dolphin) ⭐ 9,064 | 🐛 78 | 🌐 Python | 📅 2026-03-25 - Document image parsing framework using heterogeneous anchor prompting.
* [OpenMed](https://github.com/maziyarpanahi/openmed) ⭐ 5,712 | 🐛 623 | 🌐 Python | 📅 2026-10-25 - Local-first clinical NLP toolkit for medical entity recognition and HIPAA PII de-identification that runs entirely on-device.
* [PageLM](https://github.com/CaviraOSS/PageLM) ⭐ 2,045 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-13 - Community-driven education platform for transforming study materials into interactive resources.
* [Unbody](https://github.com/unbody-io/unbody) ⭐ 523 | 🐛 3 | 🌐 TypeScript | 📅 2026-04-14 - Modular, open-source backend for building AI-native software designed for knowledge.
* [Myriade](https://github.com/myriade-ai/myriade) ⭐ 62 | 🐛 0 | 🌐 Shell | 📅 2026-10-25 - AI-native data platform for exploring and transforming data warehouses.

## Datasets & Benchmarks

Open datasets, evaluation benchmarks, and reference collections for agent systems.

* [System Prompts and Models of AI Tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) ⭐ 144,260 | 🐛 163 | 📅 2026-10-12 - Collection of system prompts and models for various AI tools.
* [12-Factor Agents](https://github.com/humanlayer/12-factor-agents) ⭐ 26,872 | 🐛 28 | 🌐 TypeScript | 📅 2025-09-21 - Principles for building LLM-powered software that is production-ready.
* [Open LLMs](https://github.com/eugeneyan/open-llms) ⭐ 12,889 | 🐛 10 | 📅 2025-02-13 - Curated list of open LLMs available for commercial and research use.
* [Harness Engineering](https://github.com/lopopolo/harness-engineering) ⭐ 2,736 | 🐛 1 | 🌐 Python | 📅 2026-07-18 - Field guide and anthology on harness engineering: improving agent output by curating the context, tools, and environment around a model.

## Productivity & Personal Assistants

Chat interfaces, personal AI assistants, and productivity tools.

* [OpenClaw](https://github.com/openclaw/openclaw) ⭐ 393,086 | 🐛 7,842 | 🌐 TypeScript | 📅 2026-10-26 - Personal AI assistant that runs on any OS and any platform.
* [Open WebUI](https://github.com/open-webui/open-webui) ⭐ 156,770 | 🐛 196 | 🌐 Python | 📅 2026-10-26 - Self-hosted web interface for interacting with various LLMs.
* [Airi](https://github.com/moeru-ai/airi) ⭐ 50,728 | 🐛 246 | 🌐 TypeScript | 📅 2026-10-26 - Self-hosted AI companion and VTuber platform with voice chat and real-time interaction.
* [LibreChat](https://github.com/danny-avila/LibreChat) ⭐ 46,328 | 🐛 978 | 🌐 TypeScript | 📅 2026-10-26 - Enhanced ChatGPT clone with Agents, MCP, multi-model support, and enterprise features.
* [Jan](https://github.com/janhq/jan) ⭐ 45,088 | 🐛 555 | 🌐 Rust | 📅 2026-10-26 - Open-source alternative to ChatGPT that runs offline on your machine.
* [Khoj](https://github.com/khoj-ai/khoj) ⭐ 37,832 | 🐛 173 | 🌐 Python | 📅 2026-08-02 - AI second brain for searching documents, the web, and building custom agents.
* [Eigent](https://github.com/eigent-ai/eigent) ⭐ 15,663 | 🐛 265 | 🌐 TypeScript | 📅 2026-10-25 - Open-source coworker desktop application for individual productivity.
* [Omi](https://github.com/BasedHardware/omi) ⭐ 13,818 | 🐛 1,499 | 🌐 Python | 📅 2026-10-26 - AI wearable device for real-time transcription and speech processing.
* [Chat UI](https://github.com/huggingface/chat-ui) ⭐ 11,001 | 🐛 311 | 🌐 TypeScript | 📅 2026-10-23 - Open source codebase powering Hugging Face Chat with multi-model support.
* [Feynman](https://github.com/Companion-Inc/feynman) ⭐ 10,024 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-24 - CLI research agent for literature review, deep research, paper critique, and replication planning with citation tracking.
* [Agentic Inbox](https://github.com/cloudflare/agentic-inbox) ⭐ 8,514 | 🐛 56 | 🌐 TypeScript | 📅 2026-04-23 - Self-hosted email client with an AI agent, running on Cloudflare Workers.
* [Rakazo](https://github.com/elie222/rakazo) ⭐ 5,825 | 🐛 85 | 🌐 TypeScript | 📅 2026-10-25 - Self-hostable platform for running persistent AI teammates with memory, routines, voice mode, and browser, terminal, and desktop access across web, desktop, and mobile apps.
* [ClaraVerse](https://github.com/claraverse-space/ClaraVerse) ⭐ 3,901 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-03 - Open-source multimodal AI platform with local LLM, voice, vision, and code execution.
* [Ovi](https://github.com/character-ai/Ovi) ⭐ 1,761 | 🐛 47 | 🌐 Python | 📅 2025-11-15 - Experimental AI character interaction tool from the Character.ai team.
* [Newelle](https://github.com/qwersyk/Newelle) ⭐ 1,497 | 🐛 23 | 🌐 Python | 📅 2026-10-23 - Virtual assistant application for desktop environments.
* [Osaurus](https://github.com/dinoki-ai/osaurus) ⭐ 38 | 🐛 1 | 🌐 HTML | 📅 2026-02-24 - AI edge infrastructure for macOS that runs local or cloud models with MCP tool sharing.

## MCP & Tool Integration

Model Context Protocol servers, tool integrations, and API connectivity.

* [JSON Render](https://github.com/vercel-labs/json-render) ⭐ 18,792 | 🐛 103 | 🌐 TypeScript | 📅 2026-10-24 - Tool for dynamically rendering AI-generated JSON data into user interfaces.
* [OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) ⭐ 16,172 | 🐛 149 | 🌐 Python | 📅 2026-10-26 - General-purpose sandbox platform for AI applications with multi-language SDKs.
* [Claude Context](https://github.com/zilliztech/claude-context) ⭐ 12,647 | 🐛 147 | 🌐 TypeScript | 📅 2026-07-14 - Code search MCP that makes entire codebases accessible to AI agents.
* [Monid](https://github.com/monid-ai/monid) ⭐ 6,715 | 🐛 138 | 🌐 TypeScript | 📅 2026-10-22 - Unified gateway giving agents access to 2,000+ tools across multiple providers, with endpoint discovery and per-call metering.
* [Klavis](https://github.com/Klavis-AI/klavis) ⭐ 5,827 | 🐛 307 | 🌐 Python | 📅 2026-06-01 - MCP integration platform for reliable tool use by AI agents at scale.
* [Metorial](https://github.com/metorial/metorial) ⭐ 3,367 | 🐛 10 | 🌐 TypeScript | 📅 2026-10-25 - Platform for connecting any AI model to 600+ integrations via MCP.
* [Interactive MCP](https://github.com/ttommyth/interactive-mcp) ⭐ 351 | 🐛 10 | 🌐 TypeScript | 📅 2025-11-20 - Local, cross-platform MCP server for human-in-the-loop interaction with AI agents.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Footnotes

* For a table view of this list with star counts, see [TABLE\_VIEW.md](TABLE_VIEW.md).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-26._
