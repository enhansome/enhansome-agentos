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

* [Hermes Agent](https://github.com/NousResearch/hermes-agent) ⭐ 265,993 | 🐛 54,394 | 🌐 Python | 📅 2026-11-25 - Adaptive AI agent platform built on the Hermes model family.
* [n8n](https://github.com/n8n-io/n8n) ⭐ 212,082 | 🐛 1,265 | 🌐 TypeScript | 📅 2026-11-25 - Fair-code workflow automation platform with native AI capabilities and 400+ integrations.
* [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) ⭐ 188,181 | 🐛 850 | 🌐 Python | 📅 2026-11-25 - Experimental open-source application showcasing GPT-4 capabilities for autonomous tasks.
* [Langflow](https://github.com/langflow-ai/langflow) ⭐ 156,926 | 🐛 1,347 | 🌐 Python | 📅 2026-11-25 - Low-code platform for building and deploying AI-powered agents and workflows.
* [Pi](https://github.com/earendil-works/pi) ⭐ 123,791 | 🐛 303 | 🌐 TypeScript | 📅 2026-11-25 - Agent toolkit providing a unified multi-provider LLM API, an agent runtime with tool calling, a terminal UI, and a self-extensible coding agent CLI.
* [autoresearch](https://github.com/karpathy/autoresearch) ⭐ 100,581 | 🐛 192 | 🌐 Python | 📅 2026-03-26 - AI agents that run research on single-GPU training automatically.
* [MiroFish](https://github.com/666ghj/MiroFish) ⭐ 86,647 | 🐛 247 | 🌐 Python | 📅 2026-10-16 - Swarm-intelligence engine that builds multi-agent simulated worlds from seed data to explore predictions and social dynamics.
* [DeerFlow](https://github.com/bytedance/deer-flow) ⭐ 85,785 | 🐛 968 | 🌐 Python | 📅 2026-11-25 - Open-source SuperAgent harness with sandboxes, memories, tools, and subagents.
* [Open Interpreter](https://github.com/openinterpreter/openinterpreter) ⭐ 68,962 | 🐛 36 | 🌐 Rust | 📅 2026-11-24 - Open-source AI agent that executes code on your computer to perform tasks.
* [OpenManus](https://github.com/FoundationAgents/OpenManus) ⭐ 59,032 | 🐛 465 | 🌐 Python | 📅 2026-11-02 - Open-source implementation of an autonomous AI agent.
* [Goose](https://github.com/block/goose) ⭐ 56,971 | 🐛 509 | 🌐 Rust | 📅 2026-11-25 - On-machine AI agent that automates development tasks with MCP support.
* [Huginn](https://github.com/huginn/huginn) ⭐ 50,633 | 🐛 690 | 🌐 Ruby | 📅 2026-11-24 - System for creating agents that monitor and act on your behalf across the web.
* [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) ⭐ 41,056 | 🐛 32 | 🌐 TypeScript | 📅 2026-11-25 - Teams-first multi-agent orchestration layer for Claude Code with parallel execution.
* [Sim](https://github.com/simstudioai/sim) ⭐ 30,199 | 🐛 331 | 🌐 TypeScript | 📅 2026-11-25 - Open-source platform to build and deploy AI agent workflows.
* [Mastra](https://github.com/mastra-ai/mastra) ⭐ 29,809 | 🐛 960 | 🌐 TypeScript | 📅 2026-11-25 - TypeScript framework for building AI-powered applications and agents.
* [Activepieces](https://github.com/activepieces/activepieces) ⭐ 25,717 | 🐛 1,025 | 🌐 TypeScript | 📅 2026-11-25 - Open-source AI automation framework with MCP server support.
* [Letta](https://github.com/letta-ai/letta) ⭐ 25,540 | 🐛 1 | 📅 2026-10-18 - Platform for building stateful agents with memory that learn over time.
* [Eliza](https://github.com/elizaOS/eliza) ⭐ 19,919 | 🐛 19 | 🌐 Java | 📅 2026-11-25 - Multi-agent simulation framework with Discord, Telegram, and Twitter integration.
* [RowBoat](https://github.com/rowboatlabs/rowboat) ⭐ 18,319 | 🐛 227 | 🌐 TypeScript | 📅 2026-11-24 - Open-source AI coworker with persistent memory for long-running tasks.
* [OpenHarness](https://github.com/HKUDS/OpenHarness) ⭐ 16,236 | 🐛 75 | 🌐 Python | 📅 2026-11-23 - Open agent harness with a built-in personal agent called Ohmo.
* [ironclaw](https://github.com/nearai/ironclaw) ⭐ 12,721 | 🐛 1,575 | 🌐 Rust | 📅 2026-11-09 - Agent OS focused on privacy, security, and extensibility with Rust and WASM.
* [Atomic Agents](https://github.com/Eigenwise/atomic-agents) ⭐ 6,347 | 🐛 21 | 🌐 Python | 📅 2026-11-22 - Lightweight Python framework for building agentic pipelines from composable, single-purpose components built on Pydantic and Instructor.
* [SwarmForge](https://github.com/unclebob/swarm-forge) ⭐ 4,123 | 🐛 53 | 🌐 Clojure | 📅 2026-09-07 - Coordinates AI coding agents in isolated git worktrees and tmux sessions, with durable handoffs and an operator dashboard for approvals and oversight.
* [Auto-Company](https://github.com/MaxMiksa/Auto-Company) ⭐ 3,212 | 🐛 3 | 🌐 Python | 📅 2026-11-20 - Multi-agent system that operates autonomously on your own PC across Windows, Linux, and macOS.
* [NextPy](https://github.com/dot-agent/nextpy) ⭐ 2,347 | 🐛 23 | 🌐 Python | 📅 2024-05-01 - Self-modifying framework for building agentic modular systems.
* [Ouroboros](https://github.com/razzant/ouroboros) ⭐ 1,706 | 🐛 419 | 🌐 Python | 📅 2026-11-25 - Runs general-purpose tasks through a desktop app or headless CLI, coordinates specialist agents, preserves identity and memory across restarts, and can modify its own implementation through reviewed Git commits.
* [SmythOS](https://github.com/SmythOS/sre) ⭐ 1,308 | 🐛 36 | 🌐 TypeScript | 📅 2026-04-03 - Cloud-native runtime for building, running, and managing agentic AI systems.
* [Open Agent](https://github.com/AFK-surf/open-agent) ⭐ 1,064 | 🐛 9 | 🌐 TypeScript | 📅 2025-10-10 - Open-source alternative to Claude Agent SDK, ChatGPT Agents, and Manus.
* [nodetool](https://github.com/nodetool-ai/nodetool) ⭐ 657 | 🐛 61 | 🌐 TypeScript | 📅 2026-11-25 - Open-source, agent-first creative workspace with node-based workflows and multi-provider LLM support.
* [Kitaru](https://github.com/zenml-io/kitaru) ⭐ 322 | 🐛 106 | 🌐 Python | 📅 2026-11-25 - Durable execution layer for AI agents with checkpoints, replay, resume, and memory.
* [kami](https://github.com/kami-community/kami) ⭐ 66 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-09 - Automating content and outreach with multi-agent coordination for early-stage startups.
* [Shire](https://github.com/victor36max/shire) ⭐ 41 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-03 - Persistent workspaces for AI agent teams with inter-agent mailboxes and shared drive.

## Computer-Use & Desktop Automation

Agents that control desktops, interact with operating systems, and automate computer tasks.

* [Project NOMAD](https://github.com/Crosstalk-Solutions/project-nomad) ⭐ 44,375 | 🐛 208 | 🌐 TypeScript | 📅 2026-11-24 - Self-contained, offline survival computer with tools, knowledge, and AI.
* [Puter](https://github.com/HeyPuter/puter) ⭐ 44,255 | 🐛 24 | 🌐 TypeScript | 📅 2026-11-25 - Open-source, self-hostable cloud desktop operating system.
* [UI-TARS Desktop](https://github.com/bytedance/UI-TARS-desktop) ⚠️ Archived - Open-source multimodal AI agent stack for desktop automation.
* [CUA](https://github.com/trycua/cua) ⭐ 32,893 | 🐛 1,595 | 🌐 Rust | 📅 2026-11-25 - Open-source infrastructure for Computer-Use Agents with sandboxes, SDKs, and benchmarks.
* [Agent-S](https://github.com/simular-ai/Agent-S) ⭐ 13,044 | 🐛 85 | 🌐 Python | 📅 2026-11-25 - Open agentic framework designed to use computers like a human.
* [HolaOS](https://github.com/holaboss-ai/holaOS) ⭐ 11,357 | 🐛 12 | 🌐 TypeScript | 📅 2026-11-21 - Local-first agent for work that learns your working context and retains it.
* [Coworker](https://github.com/accomplish-ai/coworker) ⭐ 10,784 | 🐛 13 | 📅 2026-08-13 - Open-source AI coworker that lives on your desktop.
* [OBLITERATUS](https://github.com/elder-plinius/OBLITERATUS) ⭐ 9,697 | 🐛 26 | 🌐 Python | 📅 2026-11-25 - Framework for bypassing AI restrictions and enabling unrestricted model operation.
* [Skales](https://github.com/skalesapp/skales) ⭐ 2,239 | 🐛 2 | 📅 2026-11-24 - Local-first desktop AI agent that runs offline via Ollama or 15+ providers.
* [Autonomous Computer](https://github.com/autonomous-ai/autonomous-computer) ⭐ 1,602 | 🐛 2 | 📅 2026-11-05 - Toolkit for building a personal AI computer.

## Web Agents & Browser Automation

Browser control, web scraping, and internet interaction agents.

* [browser-use](https://github.com/browser-use/browser-use) ⭐ 121,992 | 🐛 587 | 🌐 Python | 📅 2026-11-24 - Library for building agents that see, navigate, and interact with web browsers.
* [Agent Reach](https://github.com/Panniantong/Agent-Reach) ⭐ 114,614 | 🐛 160 | 🌐 Python | 📅 2026-11-24 - Tool for giving AI agents access to Twitter, Reddit, YouTube, GitHub, and more.
* [Crawl4AI](https://github.com/unclecode/crawl4ai) ⭐ 87,812 | 🐛 351 | 🌐 Python | 📅 2026-11-23 - Open-source, LLM-friendly web crawler and scraper for AI data gathering.
* [Lightpanda](https://github.com/lightpanda-io/browser) ⭐ 42,527 | 🐛 82 | 🌐 Zig | 📅 2026-11-25 - Headless browser written in Zig, built for AI and automation, compatible with CDP, Playwright, and Puppeteer.
* [AIHawk](https://github.com/feder-cr/AIHawk) ⭐ 32,637 | 🐛 0 | 🌐 Python | 📅 2026-11-24 - Open-source AI browser agent that browses, clicks, types, and reads the web from plain-English instructions, available as an MCP server (Claude Code, Codex, Gemini CLI) or a standalone web UI.
* [Stagehand](https://github.com/browserbase/stagehand) ⭐ 26,138 | 🐛 459 | 🌐 TypeScript | 📅 2026-11-25 - SDK built on Playwright for authoring browser agents that extract data and interact with websites.
* [Browser Harness](https://github.com/browser-use/browser-harness) ⭐ 19,238 | 🐛 475 | 🌐 Python | 📅 2026-11-25 - Self-healing harness that enables LLMs to complete browser tasks.
* [Web UI](https://github.com/browser-use/web-ui) ⭐ 16,664 | 🐛 329 | 🌐 Python | 📅 2026-09-25 - Web interface for running and managing AI agents in your browser.
* [BrowserOS](https://github.com/browseros-ai/BrowserOS) ⭐ 14,479 | 🐛 171 | 🌐 Rust | 📅 2026-11-24 - Open-source agentic browser as an alternative to proprietary AI browsing tools.
* [Nanobrowser](https://github.com/nanobrowser/nanobrowser) ⭐ 14,383 | 🐛 64 | 🌐 TypeScript | 📅 2026-11-23 - Open-source Chrome extension for AI-powered web automation with multi-agent workflows.
* [Browserless](https://github.com/browserless/browserless) ⭐ 13,961 | 🐛 16 | 🌐 TypeScript | 📅 2026-11-24 - Headless browser deployment platform for Docker and cloud environments.
* [WebVoyager](https://github.com/MinorJerry/WebVoyager) ⭐ 1,129 | 🐛 12 | 🌐 Python | 📅 2024-03-04 - End-to-end web agent framework powered by large multimodal models.
* [Agentic AI Browser](https://github.com/esinecan/agentic-ai-browser) ⭐ 163 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-04 - AI-driven web automation agent using Playwright for decision-making.
* [Vibe Eyes](https://github.com/monteslu/vibe-eyes) ⭐ 54 | 🐛 2 | 🌐 JavaScript | 📅 2026-02-04 - MCP server that enables LLMs to see and interact with browser-based applications.

## Voice & Conversational AI

Text-to-speech, speech-to-text, voice assistants, and real-time audio systems.

* [VibeVoice](https://github.com/microsoft/VibeVoice) ⭐ 57,544 | 🐛 207 | 🌐 Python | 📅 2026-10-08 - Open-source voice AI for audio synthesis.
* [Fish Speech](https://github.com/fishaudio/fish-speech) ⭐ 33,861 | 🐛 31 | 🌐 Python | 📅 2026-11-14 - Open-source text-to-speech engine with multilingual voice cloning.
* [Chatterbox](https://github.com/resemble-ai/chatterbox) ⭐ 28,096 | 🐛 385 | 🌐 Python | 📅 2026-11-04 - Open-source text-to-speech engine for realistic voices.
* [LiveKit](https://github.com/livekit/livekit) ⭐ 22,386 | 🐛 235 | 🌐 Go | 📅 2026-11-25 - End-to-end realtime stack for connecting humans and AI with low-latency audio/video.
* [Dia](https://github.com/nari-labs/dia) ⭐ 19,423 | 🐛 91 | 🌐 Python | 📅 2025-11-19 - TTS model capable of generating realistic dialogue in a single pass.
* [KittenTTS](https://github.com/KittenML/KittenTTS) ⭐ 17,087 | 🐛 150 | 🌐 Python | 📅 2026-11-19 - TTS model under 25MB for compact, high-quality voice synthesis.
* [LiveKit Agents](https://github.com/livekit/agents) ⭐ 15,338 | 🐛 1,026 | 🌐 Python | 📅 2026-11-25 - Framework for building realtime voice AI agents with audio and video pipelines.
* [YuE](https://github.com/multimodal-art-projection/YuE) ⭐ 13,722 | 🐛 46 | 🌐 Python | 📅 2026-11-01 - Open full-song music generation foundation model.
* [Pocket TTS](https://github.com/kyutai-labs/pocket-tts) ⭐ 10,405 | 🐛 76 | 🌐 Python | 📅 2026-11-23 - Text-to-speech model designed to run efficiently on consumer CPUs.
* [MLX Audio](https://github.com/Blaizzy/mlx-audio) ⭐ 8,330 | 🐛 88 | 🌐 Python | 📅 2026-11-25 - Text-to-speech, speech-to-text, and speech-to-speech library built on Apple's MLX framework.
* [Piper](https://github.com/OHF-Voice/piper1-gpl) ⭐ 6,396 | 🐛 71 | 🌐 C++ | 📅 2026-11-24 - Fast and local neural text-to-speech engine for low-latency applications.
* [NeuTTS](https://github.com/neuphonic/neutts) ⭐ 6,345 | 🐛 37 | 🌐 Python | 📅 2026-07-30 - On-device text-to-speech model by Neuphonic for private voice synthesis.
* [MisoTTS](https://github.com/MisoLabsAI/MisoTTS) ⭐ 3,250 | 🐛 22 | 🌐 Python | 📅 2026-06-09 - 8-billion parameter text-to-speech model for highly emotive voice generation.
* [Jarvis](https://github.com/isair/jarvis) ⭐ 2,417 | 🐛 187 | 🌐 Python | 📅 2026-11-19 - Private AI voice assistant that runs offline on your computer.
* [Kokoro TTS](https://github.com/nazdridoy/kokoro-tts) ⭐ 2,038 | 🐛 19 | 🌐 Python | 📅 2026-08-22 - CLI-based text-to-speech tool utilizing the Kokoro model for multiple languages.
* [Tada](https://github.com/HumeAI/tada) ⭐ 1,021 | 🐛 19 | 🌐 Jupyter Notebook | 📅 2026-05-11 - Open-source speech language model for expressive, emotionally-aware audio generation.
* [Fun Audio Chat](https://github.com/QwenAudio/Fun-Audio-Chat) ⭐ 1,015 | 🐛 19 | 🌐 Python | 📅 2026-09-24 - Large audio language model for natural, low-latency voice interactions.
* [Confucius4-TTS](https://github.com/netease-youdao/Confucius4-TTS) ⭐ 861 | 🐛 12 | 🌐 Python | 📅 2026-11-04 - TTS model optimized for long-form Chinese and English content with strong emotion control.
* [Liquid Audio](https://github.com/Liquid4All/liquid-audio) ⭐ 606 | 🐛 13 | 🌐 Python | 📅 2026-10-03 - Speech-to-speech audio models developed by Liquid AI.
* [Audio2Face 3D](https://github.com/NVIDIA/Audio2Face-3D-Samples) ⭐ 343 | 🐛 24 | 🌐 Python | 📅 2026-03-11 - Service for converting audio to facial blendshapes for lipsync and real-time facial performances.
* [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) ⭐ 19 | 🐛 0 | 📅 2026-11-11 - Few-shot voice cloning and text-to-speech model training framework.

## Visual & Creative AI

Image generation, video creation, 3D modeling, and visual manipulation tools.

* [DragGAN](https://github.com/XingangPan/DragGAN) ⭐ 35,831 | 🐛 153 | 🌐 Python | 📅 2024-05-18 - Interactive point-based manipulation for precise control over generative images.
* [Open-Sora](https://github.com/hpcaitech/Open-Sora) ⭐ 29,950 | 🐛 15 | 🌐 Python | 📅 2026-04-09 - Open-source video generation models for efficient video production.
* [InvokeAI](https://github.com/invoke-ai/InvokeAI) ⭐ 29,158 | 🐛 316 | 🌐 TypeScript | 📅 2026-11-25 - Creative engine for Stable Diffusion models to generate visual media.
* [Duix Avatar](https://github.com/duixcom/Duix-Avatar) ⭐ 16,443 | 🐛 425 | 🌐 C | 📅 2026-04-21 - Open-source toolkit for AI avatar creation and digital human cloning.
* [Z-Image](https://github.com/Tongyi-MAI/Z-Image) ⭐ 12,189 | 🐛 114 | 🌐 Python | 📅 2026-02-09 - Open-source image generation model from Alibaba's Tongyi team.
* [Sana](https://github.com/NVlabs/Sana) ⭐ 9,895 | 🐛 138 | 🌐 Python | 📅 2026-11-25 - High-resolution image synthesis using Linear Diffusion Transformers.
* [Modly](https://github.com/lightningpixel/modly) ⭐ 8,779 | 🐛 101 | 🌐 TypeScript | 📅 2026-11-19 - Desktop app for generating 3D models from images using local AI.
* [SkyReels V2](https://github.com/SkyworkAI/SkyReels-V2) ⭐ 7,839 | 🐛 404 | 🌐 Python | 📅 2026-01-29 - Generative model for creating infinite-length AI films.
* [TripoSR](https://github.com/VAST-AI-Research/TripoSR) ⭐ 7,469 | 🐛 109 | 🌐 Python | 📅 2026-06-04 - Fast 3D object reconstruction from a single image using AI.
* [HunyuanVideo 1.5](https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5) ⭐ 4,617 | 🐛 41 | 🌐 Python | 📅 2026-04-10 - Lightweight video generation model for high-quality output.
* [Helios](https://github.com/PKU-YuanGroup/Helios) ⭐ 2,284 | 🐛 55 | 🌐 Python | 📅 2026-11-01 - Real-time long video generation model for streaming video synthesis.
* [Node Banana](https://github.com/shrimbly/node-banana) ⭐ 1,694 | 🐛 24 | 🌐 TypeScript | 📅 2026-11-07 - Free and open-source node-based generative workflow platform.
* [Short Video Maker](https://github.com/gyoridavid/short-video-maker) ⭐ 1,521 | 🐛 32 | 🌐 TypeScript | 📅 2025-06-21 - Creates short videos for TikTok, Instagram Reels, and YouTube Shorts using MCP.
* [FlashWorld](https://github.com/imlixinyang/FlashWorld) ⭐ 887 | 🐛 18 | 🌐 Python | 📅 2026-03-24 - High-quality 3D scene generation framework that works within seconds.
* [Realtime Video](https://github.com/krea-ai/realtime-video) ⭐ 603 | 🐛 19 | 🌐 Python | 📅 2025-11-13 - Open-source model for high-quality, realtime AI video generation.
* [RealWonder](https://github.com/liuwei283/RealWonder) ⭐ 236 | 🐛 3 | 🌐 Python | 📅 2026-03-06 - Real-time physical action-conditioned video generation model.
* [EditThinker](https://github.com/appletea233/EditThinker) ⭐ 114 | 🐛 5 | 🌐 Python | 📅 2026-01-18 - Iterative reasoning framework for step-by-step thinking in image editing.
* [Streamo](https://github.com/maifoundations/Streamo) ⭐ 96 | 🐛 10 | 🌐 Python | 📅 2026-11-12 - Streaming video instruction tuning framework for continuous video understanding.
* [Cutalyst](https://github.com/MamtaRajpurohit/Cutalyst) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-04 - Automated video editing AI that cuts, syncs, and subtitles videos.

## Developer Tools & Code Assistants

Code editors, coding agents, and development tools.

* [Ponytail](https://github.com/DietrichGebert/ponytail) ⭐ 198,390 | 🐛 332 | 🌐 JavaScript | 📅 2026-11-22 - Agent skill and rules package that steers coding agents toward writing minimal code.
* [CodeGraph](https://github.com/colbymchenry/codegraph) ⭐ 78,655 | 🐛 249 | 🌐 TypeScript | 📅 2026-11-23 - Pre-indexed code knowledge graph that auto-syncs on code changes for multiple AI coding tools.
* [Oh My OpenAgent](https://github.com/code-yeongyu/oh-my-openagent) ⭐ 71,101 | 🐛 2,813 | 🌐 TypeScript | 📅 2026-11-25 - Batteries-included agent harness for complex codebases.
* [OpenClaude](https://github.com/Twigpine/openclaude) ⭐ 34,531 | 🐛 38 | 🌐 TypeScript | 📅 2026-11-24 - Open-source coding-agent CLI that works with cloud and local model providers, with tools, agents, and MCP support.
* [Open Lovable](https://github.com/firecrawl/open-lovable) ⭐ 28,955 | 🐛 152 | 🌐 TypeScript | 📅 2026-10-09 - Tool for cloning and recreating websites as modern React apps using AI.
* [Dyad](https://github.com/dyad-sh/dyad) ⭐ 22,447 | 🐛 369 | 🌐 TypeScript | 📅 2026-11-24 - Local, open-source AI app builder for power users.
* [DeepCode](https://github.com/HKUDS/DeepCode) ⭐ 16,869 | 🐛 32 | 🌐 Python | 📅 2026-11-23 - Open agentic coding framework for paper-to-code and web development tasks.
* [OpenBot](https://github.com/CopilotKit/OpenBot) ⭐ 13,470 | 🐛 170 | 🌐 TypeScript | 📅 2026-11-25 - Open-source coding agent for VS Code powered by CopilotKit.
* [sandcastle](https://github.com/mattpocock/sandcastle) ⭐ 9,272 | 🐛 137 | 🌐 TypeScript | 📅 2026-11-18 - TypeScript library for orchestrating sandboxed coding agents.
* [ClawX](https://github.com/ValueCell-ai/ClawX) ⭐ 7,587 | 🐛 48 | 🌐 TypeScript | 📅 2026-11-25 - Desktop app providing a graphical interface for OpenClaw AI agents.
* [Emdash](https://github.com/generalaction/emdash) ⭐ 6,306 | 🐛 92 | 🌐 TypeScript | 📅 2026-11-23 - Open-source agentic development environment for running multiple coding agents in parallel.
* [CodeNomad](https://github.com/NeuralNomadsAI/CodeNomad) ⭐ 2,682 | 🐛 10 | 🌐 TypeScript | 📅 2026-11-25 - Multi-agent coding orchestration platform for parallel AI-assisted development.
* [Mysti](https://github.com/DeepMyst/Mysti) ⭐ 1,160 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-10 - AI coding dream team of agents for VS Code that debate and synthesize solutions.
* [Clawmetry](https://github.com/vivekchand/clawmetry) ⭐ 440 | 🐛 67 | 🌐 Python | 📅 2026-11-25 - Real-time observability dashboard for OpenClaw AI agents.
* [Persona](https://github.com/runtypelabs/persona) ⭐ 266 | 🐛 10 | 🌐 TypeScript | 📅 2026-11-22 - Toolkit for creating agentic front-end experiences for the web with WebMCP support.

## LLM Infrastructure & Model Serving

Model hosting, fine-tuning, API gateways, and inference optimization.

* [RTK](https://github.com/rtk-ai/rtk) ⭐ 87,766 | 🐛 1,727 | 🌐 Rust | 📅 2026-11-25 - Rust CLI proxy that filters and compresses command output before it reaches the LLM context.
* [Headroom](https://github.com/headroomlabs-ai/headroom) ⭐ 80,818 | 🐛 332 | 🌐 Python | 📅 2026-11-25 - Tool for compressing tool outputs, logs, files, and RAG chunks before they reach the LLM.
* [Unsloth](https://github.com/unslothai/unsloth) ⭐ 80,211 | 🐛 559 | 🌐 Python | 📅 2026-11-25 - Fine-tuning and reinforcement learning framework for LLMs.
* [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 63,872 | 🐛 5,495 | 🌐 Python | 📅 2026-11-25 - Python SDK and proxy server to call 100+ LLM APIs in a unified OpenAI format.
* [freellmapi](https://github.com/tashfeenahmed/freellmapi) ⭐ 58,037 | 🐛 42 | 🌐 TypeScript | 📅 2026-11-25 - OpenAI-compatible proxy that stacks free tiers of 28 LLM providers behind a single endpoint with smart routing and failover.
* [LocalAI](https://github.com/mudler/LocalAI) ⭐ 50,530 | 🐛 227 | 🌐 Go | 📅 2026-11-25 - Self-hosted, local-first open-source alternative to OpenAI and Claude APIs.
* [LLMFit](https://github.com/AlexsJones/llmfit) ⭐ 39,294 | 🐛 59 | 🌐 Rust | 📅 2026-11-25 - Tool for discovering hundreds of models across providers to find what runs on your hardware.
* [PowerInfer](https://github.com/Tiiny-AI/PowerInfer) ⭐ 9,900 | 🐛 135 | 🌐 C++ | 📅 2026-05-11 - High-speed LLM serving for local deployment with CPU/GPU heterogeneous inference.

## Security & Offensive AI

Penetration testing, red teaming, vulnerability scanning, and security tools.

* [Strix](https://github.com/usestrix/strix) ⭐ 77,510 | 🐛 636 | 🌐 Python | 📅 2026-11-25 - Open-source AI tool for finding and fixing application vulnerabilities.
* [Shannon](https://github.com/KeygraphHQ/shannon) ⭐ 52,291 | 🐛 25 | 🌐 TypeScript | 📅 2026-11-25 - Autonomous AI pentester for web applications and APIs that analyzes source code and executes exploits.
* [Pentagi](https://github.com/vxcontrol/pentagi) ⭐ 34,995 | 🐛 78 | 🌐 Go | 📅 2026-11-13 - Fully autonomous AI agents system for complex penetration testing tasks end-to-end.
* [SkillSpector](https://github.com/NVIDIA/SkillSpector) ⭐ 27,601 | 🐛 168 | 🌐 Python | 📅 2026-11-24 - Security scanner for AI agent skills that detects vulnerabilities and malicious patterns.
* [OneCLI](https://github.com/onecli/onecli) ⭐ 3,657 | 🐛 194 | 🌐 TypeScript | 📅 2026-11-09 - Open-source credential vault for AI agents that injects API keys transparently.
* [RedAMon](https://github.com/samugit83/redamon) ⭐ 3,493 | 🐛 18 | 🌐 Python | 📅 2026-11-24 - AI-powered agentic red team framework for offensive security operations from recon to post-exploitation.
* [Pentest-Swarm-AI](https://github.com/Armur-Ai/Pentest-Swarm-AI) ⭐ 3,305 | 🐛 19 | 🌐 Go | 📅 2026-11-23 - Autonomous penetration testing using a swarm of AI agents with specialized roles.
* [Azazel](https://github.com/beelzebub-labs/azazel) ⭐ 111 | 🐛 3 | 🌐 C | 📅 2026-11-23 - eBPF-powered observer for containerized runtimes, built for malware analysis and AI monitoring.

## Data, Memory & Knowledge

OCR, knowledge graphs, memory systems, and data infrastructure.

* [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) ⭐ 94,255 | 🐛 376 | 🌐 TypeScript | 📅 2026-11-25 - Turns codebases into interactive knowledge graphs for AI agents to explore, search, and query.
* [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) ⭐ 93,169 | 🐛 285 | 🌐 Python | 📅 2026-09-16 - Comprehensive OCR toolkit supporting 100+ languages and complex layouts.
* [Docling](https://github.com/docling-project/docling) ⭐ 71,015 | 🐛 1,068 | 🌐 Python | 📅 2026-11-25 - Tool for converting various document formats into AI-ready structured data.
* [Pathway](https://github.com/pathwaycom/pathway) ⭐ 61,957 | 🐛 36 | 🌐 Python | 📅 2026-11-25 - Python ETL framework for real-time analytics, stream processing, and RAG.
* [Graphiti](https://github.com/getzep/graphiti) ⭐ 33,080 | 🐛 592 | 🌐 Python | 📅 2026-11-25 - Tool for building real-time knowledge graphs to power AI agent memory.
* [OLMocr](https://github.com/allenai/olmocr) ⭐ 19,848 | 🐛 93 | 🌐 Python | 📅 2026-03-25 - Toolkit for linearizing PDFs to prepare datasets for LLM training.
* [Memori](https://github.com/MemoriLabs/Memori) ⭐ 17,605 | 🐛 63 | 🌐 Python | 📅 2026-10-03 - SQL-native memory layer for LLMs, AI agents, and multi-agent systems.
* [memU](https://github.com/NevaMind-AI/memU) ⭐ 14,639 | 🐛 132 | 🌐 Python | 📅 2026-11-24 - Memory system designed for 24/7 proactive agents.
* [Chandra](https://github.com/datalab-to/chandra) ⭐ 12,774 | 🐛 1 | 🌐 Python | 📅 2026-11-16 - Specialized OCR model for parsing complex tables, forms, and handwriting.
* [MemOS](https://github.com/MemTensor/MemOS) ⭐ 12,504 | 🐛 138 | 🌐 TypeScript | 📅 2026-11-24 - AI memory operating system for persistent skill storage in agent systems.
* [FalkorDB](https://github.com/FalkorDB/FalkorDB) ⭐ 10,503 | 🐛 883 | 🌐 Rust | 📅 2026-11-25 - Fast graph database using GraphBLAS for GraphRAG and knowledge graphs for LLMs.
* [Dolphin](https://github.com/bytedance/Dolphin) ⭐ 9,063 | 🐛 77 | 🌐 Python | 📅 2026-03-25 - Document image parsing framework using heterogeneous anchor prompting.
* [OpenMed](https://github.com/maziyarpanahi/openmed) ⭐ 5,843 | 🐛 1,396 | 🌐 Python | 📅 2026-11-23 - Local-first clinical NLP toolkit for medical entity recognition and HIPAA PII de-identification that runs entirely on-device.
* [PageLM](https://github.com/CaviraOSS/PageLM) ⭐ 2,074 | 🐛 5 | 🌐 TypeScript | 📅 2026-11-15 - Community-driven education platform for transforming study materials into interactive resources.
* [Unbody](https://github.com/unbody-io/unbody) ⭐ 525 | 🐛 3 | 🌐 TypeScript | 📅 2026-04-14 - Modular, open-source backend for building AI-native software designed for knowledge.
* [Myriade](https://github.com/myriade-ai/myriade) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-11-24 - AI-native data platform for exploring and transforming data warehouses.

## Datasets & Benchmarks

Open datasets, evaluation benchmarks, and reference collections for agent systems.

* [System Prompts and Models of AI Tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) ⭐ 144,847 | 🐛 161 | 📅 2026-10-12 - Collection of system prompts and models for various AI tools.
* [12-Factor Agents](https://github.com/humanlayer/12-factor-agents) ⭐ 27,416 | 🐛 29 | 🌐 TypeScript | 📅 2025-09-21 - Principles for building LLM-powered software that is production-ready.
* [Open LLMs](https://github.com/eugeneyan/open-llms) ⭐ 12,881 | 🐛 11 | 📅 2025-02-13 - Curated list of open LLMs available for commercial and research use.
* [Harness Engineering](https://github.com/lopopolo/harness-engineering) ⭐ 2,774 | 🐛 1 | 🌐 Python | 📅 2026-07-18 - Field guide and anthology on harness engineering: improving agent output by curating the context, tools, and environment around a model.

## Productivity & Personal Assistants

Chat interfaces, personal AI assistants, and productivity tools.

* [OpenClaw](https://github.com/openclaw/openclaw) ⭐ 395,174 | 🐛 9,167 | 🌐 TypeScript | 📅 2026-11-25 - Personal AI assistant that runs on any OS and any platform.
* [Open WebUI](https://github.com/open-webui/open-webui) ⭐ 159,506 | 🐛 207 | 🌐 Svelte | 📅 2026-11-25 - Self-hosted web interface for interacting with various LLMs.
* [Airi](https://github.com/moeru-ai/airi) ⭐ 51,745 | 🐛 311 | 🌐 TypeScript | 📅 2026-11-25 - Self-hosted AI companion and VTuber platform with voice chat and real-time interaction.
* [LibreChat](https://github.com/danny-avila/LibreChat) ⭐ 47,510 | 🐛 1,157 | 🌐 TypeScript | 📅 2026-11-25 - Enhanced ChatGPT clone with Agents, MCP, multi-model support, and enterprise features.
* [Jan](https://github.com/janhq/jan) ⭐ 46,105 | 🐛 594 | 🌐 Rust | 📅 2026-11-23 - Open-source alternative to ChatGPT that runs offline on your machine.
* [Khoj](https://github.com/khoj-ai/khoj) ⭐ 38,237 | 🐛 178 | 🌐 Python | 📅 2026-08-02 - AI second brain for searching documents, the web, and building custom agents.
* [Eigent](https://github.com/eigent-ai/eigent) ⭐ 15,887 | 🐛 259 | 🌐 TypeScript | 📅 2026-11-23 - Open-source coworker desktop application for individual productivity.
* [Omi](https://github.com/BasedHardware/omi) ⭐ 14,027 | 🐛 1,415 | 🌐 Python | 📅 2026-11-25 - AI wearable device for real-time transcription and speech processing.
* [Chat UI](https://github.com/huggingface/chat-ui) ⭐ 11,054 | 🐛 332 | 🌐 TypeScript | 📅 2026-11-23 - Open source codebase powering Hugging Face Chat with multi-model support.
* [Feynman](https://github.com/Companion-Inc/feynman) ⭐ 10,155 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-23 - CLI research agent for literature review, deep research, paper critique, and replication planning with citation tracking.
* [Rakazo](https://github.com/elie222/rakazo) ⭐ 9,743 | 🐛 341 | 🌐 TypeScript | 📅 2026-11-25 - Self-hostable platform for running persistent AI teammates with memory, routines, voice mode, and browser, terminal, and desktop access across web, desktop, and mobile apps.
* [Agentic Inbox](https://github.com/cloudflare/agentic-inbox) ⭐ 8,835 | 🐛 65 | 🌐 TypeScript | 📅 2026-04-23 - Self-hosted email client with an AI agent, running on Cloudflare Workers.
* [ClaraVerse](https://github.com/claraverse-space/ClaraVerse) ⭐ 3,896 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-03 - Open-source multimodal AI platform with local LLM, voice, vision, and code execution.
* [Ovi](https://github.com/character-ai/Ovi) ⭐ 1,765 | 🐛 46 | 🌐 Python | 📅 2025-11-15 - Experimental AI character interaction tool from the Character.ai team.
* [Newelle](https://github.com/qwersyk/Newelle) ⭐ 1,506 | 🐛 19 | 🌐 Python | 📅 2026-11-23 - Virtual assistant application for desktop environments.
* [Osaurus](https://github.com/dinoki-ai/osaurus) ⭐ 40 | 🐛 1 | 🌐 HTML | 📅 2026-02-24 - AI edge infrastructure for macOS that runs local or cloud models with MCP tool sharing.

## MCP & Tool Integration

Model Context Protocol servers, tool integrations, and API connectivity.

* [JSON Render](https://github.com/vercel-labs/json-render) ⭐ 19,833 | 🐛 137 | 🌐 TypeScript | 📅 2026-11-23 - Tool for dynamically rendering AI-generated JSON data into user interfaces.
* [OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) ⭐ 17,907 | 🐛 221 | 🌐 Go | 📅 2026-11-25 - General-purpose sandbox platform for AI applications with multi-language SDKs.
* [Claude Context](https://github.com/zilliztech/claude-context) ⭐ 12,724 | 🐛 149 | 🌐 TypeScript | 📅 2026-11-24 - Code search MCP that makes entire codebases accessible to AI agents.
* [Monid](https://github.com/monid-ai/monid) ⭐ 6,228 | 🐛 228 | 🌐 TypeScript | 📅 2026-11-17 - Unified gateway giving agents access to 2,000+ tools across multiple providers, with endpoint discovery and per-call metering.
* [Klavis](https://github.com/Klavis-AI/klavis) ⚠️ Archived - MCP integration platform for reliable tool use by AI agents at scale.
* [Metorial](https://github.com/metorial/metorial) ⭐ 3,379 | 🐛 13 | 🌐 TypeScript | 📅 2026-11-24 - Platform for connecting any AI model to 600+ integrations via MCP.
* [Interactive MCP](https://github.com/ttommyth/interactive-mcp) ⭐ 352 | 🐛 10 | 🌐 TypeScript | 📅 2025-11-20 - Local, cross-platform MCP server for human-in-the-loop interaction with AI agents.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Footnotes

* For a table view of this list with star counts, see [TABLE\_VIEW.md](TABLE_VIEW.md).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-25._
