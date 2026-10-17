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

* [Hermes Agent](https://github.com/NousResearch/hermes-agent) ⭐ 254,480 | 🐛 49,713 | 🌐 Python | 📅 2026-10-17 - Adaptive AI agent platform built on the Hermes model family.
* [n8n](https://github.com/n8n-io/n8n) ⭐ 207,737 | 🐛 1,176 | 🌐 TypeScript | 📅 2026-10-17 - Fair-code workflow automation platform with native AI capabilities and 400+ integrations.
* [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) ⭐ 187,618 | 🐛 697 | 🌐 Python | 📅 2026-10-17 - Experimental open-source application showcasing GPT-4 capabilities for autonomous tasks.
* [Langflow](https://github.com/langflow-ai/langflow) ⭐ 155,764 | 🐛 1,144 | 🌐 Python | 📅 2026-10-17 - Low-code platform for building and deploying AI-powered agents and workflows.
* [Pi](https://github.com/earendil-works/pi) ⭐ 115,787 | 🐛 347 | 🌐 TypeScript | 📅 2026-10-16 - Agent toolkit providing a unified multi-provider LLM API, an agent runtime with tool calling, a terminal UI, and a self-extensible coding agent CLI.
* [autoresearch](https://github.com/karpathy/autoresearch) ⭐ 98,037 | 🐛 197 | 🌐 Python | 📅 2026-03-26 - AI agents that run research on single-GPU training automatically.
* [DeerFlow](https://github.com/bytedance/deer-flow) ⭐ 83,974 | 🐛 957 | 🌐 Python | 📅 2026-10-17 - Open-source SuperAgent harness with sandboxes, memories, tools, and subagents.
* [MiroFish](https://github.com/666ghj/MiroFish) ⭐ 79,788 | 🐛 148 | 🌐 Python | 📅 2026-10-16 - Swarm-intelligence engine that builds multi-agent simulated worlds from seed data to explore predictions and social dynamics.
* [Open Interpreter](https://github.com/openinterpreter/openinterpreter) ⭐ 68,590 | 🐛 15 | 🌐 Rust | 📅 2026-10-11 - Open-source AI agent that executes code on your computer to perform tasks.
* [OpenManus](https://github.com/FoundationAgents/OpenManus) ⭐ 58,696 | 🐛 443 | 🌐 Python | 📅 2026-09-30 - Open-source implementation of an autonomous AI agent.
* [Goose](https://github.com/block/goose) ⭐ 55,350 | 🐛 494 | 🌐 Rust | 📅 2026-10-17 - On-machine AI agent that automates development tasks with MCP support.
* [Huginn](https://github.com/huginn/huginn) ⭐ 50,068 | 🐛 706 | 🌐 Ruby | 📅 2026-10-17 - System for creating agents that monitor and act on your behalf across the web.
* [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) ⭐ 39,980 | 🐛 7 | 🌐 TypeScript | 📅 2026-10-17 - Teams-first multi-agent orchestration layer for Claude Code with parallel execution.
* [Sim](https://github.com/simstudioai/sim) ⭐ 29,834 | 🐛 347 | 🌐 TypeScript | 📅 2026-10-17 - Open-source platform to build and deploy AI agent workflows.
* [Mastra](https://github.com/mastra-ai/mastra) ⭐ 28,860 | 🐛 593 | 🌐 TypeScript | 📅 2026-10-17 - TypeScript framework for building AI-powered applications and agents.
* [Letta](https://github.com/letta-ai/letta) ⭐ 25,168 | 🐛 0 | 📅 2026-09-10 - Platform for building stateful agents with memory that learn over time.
* [Activepieces](https://github.com/activepieces/activepieces) ⭐ 25,078 | 🐛 755 | 🌐 TypeScript | 📅 2026-10-16 - Open-source AI automation framework with MCP server support.
* [Eliza](https://github.com/elizaOS/eliza) ⭐ 19,611 | 🐛 61 | 🌐 TypeScript | 📅 2026-10-17 - Multi-agent simulation framework with Discord, Telegram, and Twitter integration.
* [RowBoat](https://github.com/rowboatlabs/rowboat) ⭐ 18,028 | 🐛 207 | 🌐 TypeScript | 📅 2026-10-16 - Open-source AI coworker with persistent memory for long-running tasks.
* [OpenHarness](https://github.com/HKUDS/OpenHarness) ⭐ 16,000 | 🐛 93 | 🌐 Python | 📅 2026-06-04 - Open agent harness with a built-in personal agent called Ohmo.
* [ironclaw](https://github.com/nearai/ironclaw) ⭐ 12,659 | 🐛 1,551 | 🌐 Rust | 📅 2026-10-13 - Agent OS focused on privacy, security, and extensibility with Rust and WASM.
* [Atomic Agents](https://github.com/Eigenwise/atomic-agents) ⭐ 6,288 | 🐛 7 | 🌐 Python | 📅 2026-10-15 - Lightweight Python framework for building agentic pipelines from composable, single-purpose components built on Pydantic and Instructor.
* [SwarmForge](https://github.com/unclebob/swarm-forge) ⭐ 4,010 | 🐛 53 | 🌐 Clojure | 📅 2026-09-07 - Coordinates AI coding agents in isolated git worktrees and tmux sessions, with durable handoffs and an operator dashboard for approvals and oversight.
* [Auto-Company](https://github.com/MaxMiksa/Auto-Company) ⭐ 3,137 | 🐛 11 | 🌐 Python | 📅 2026-10-16 - Multi-agent system that operates autonomously on your own PC across Windows, Linux, and macOS.
* [NextPy](https://github.com/dot-agent/nextpy) ⭐ 2,349 | 🐛 23 | 🌐 Python | 📅 2024-05-01 - Self-modifying framework for building agentic modular systems.
* [Ouroboros](https://github.com/razzant/ouroboros) ⭐ 1,540 | 🐛 349 | 🌐 Python | 📅 2026-10-17 - Runs general-purpose tasks through a desktop app or headless CLI, coordinates specialist agents, preserves identity and memory across restarts, and can modify its own implementation through reviewed Git commits.
* [SmythOS](https://github.com/SmythOS/sre) ⭐ 1,303 | 🐛 35 | 🌐 TypeScript | 📅 2026-04-03 - Cloud-native runtime for building, running, and managing agentic AI systems.
* [Open Agent](https://github.com/AFK-surf/open-agent) ⭐ 1,034 | 🐛 9 | 🌐 TypeScript | 📅 2025-10-10 - Open-source alternative to Claude Agent SDK, ChatGPT Agents, and Manus.
* [nodetool](https://github.com/nodetool-ai/nodetool) ⭐ 571 | 🐛 18 | 🌐 TypeScript | 📅 2026-10-17 - Open-source, agent-first creative workspace with node-based workflows and multi-provider LLM support.
* [Kitaru](https://github.com/zenml-io/kitaru) ⭐ 309 | 🐛 54 | 🌐 Python | 📅 2026-10-14 - Durable execution layer for AI agents with checkpoints, replay, resume, and memory.
* [kami](https://github.com/kami-community/kami) ⭐ 64 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-09 - Automating content and outreach with multi-agent coordination for early-stage startups.
* [Shire](https://github.com/victor36max/shire) ⭐ 41 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-03 - Persistent workspaces for AI agent teams with inter-agent mailboxes and shared drive.

## Computer-Use & Desktop Automation

Agents that control desktops, interact with operating systems, and automate computer tasks.

* [Puter](https://github.com/HeyPuter/puter) ⭐ 43,773 | 🐛 47 | 🌐 TypeScript | 📅 2026-10-17 - Open-source, self-hostable cloud desktop operating system.
* [Project NOMAD](https://github.com/Crosstalk-Solutions/project-nomad) ⭐ 40,419 | 🐛 95 | 🌐 TypeScript | 📅 2026-10-16 - Self-contained, offline survival computer with tools, knowledge, and AI.
* [UI-TARS Desktop](https://github.com/bytedance/UI-TARS-desktop) ⭐ 39,299 | 🐛 501 | 🌐 TypeScript | 📅 2026-10-09 - Open-source multimodal AI agent stack for desktop automation.
* [CUA](https://github.com/trycua/cua) ⭐ 29,980 | 🐛 1,220 | 🌐 Rust | 📅 2026-10-17 - Open-source infrastructure for Computer-Use Agents with sandboxes, SDKs, and benchmarks.
* [Agent-S](https://github.com/simular-ai/Agent-S) ⭐ 12,630 | 🐛 64 | 🌐 Python | 📅 2026-10-08 - Open agentic framework designed to use computers like a human.
* [HolaOS](https://github.com/holaboss-ai/holaOS) ⭐ 11,446 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-21 - Local-first agent for work that learns your working context and retains it.
* [Coworker](https://github.com/accomplish-ai/coworker) ⭐ 10,843 | 🐛 13 | 📅 2026-08-13 - Open-source AI coworker that lives on your desktop.
* [OBLITERATUS](https://github.com/elder-plinius/OBLITERATUS) ⭐ 8,835 | 🐛 27 | 🌐 Python | 📅 2026-10-17 - Framework for bypassing AI restrictions and enabling unrestricted model operation.
* [Skales](https://github.com/skalesapp/skales) ⭐ 2,192 | 🐛 2 | 📅 2026-10-16 - Local-first desktop AI agent that runs offline via Ollama or 15+ providers.
* [Autonomous Computer](https://github.com/autonomous-ai/autonomous-computer) ⭐ 1,535 | 🐛 1 | 📅 2026-10-06 - Toolkit for building a personal AI computer.

## Web Agents & Browser Automation

Browser control, web scraping, and internet interaction agents.

* [browser-use](https://github.com/browser-use/browser-use) ⭐ 118,243 | 🐛 569 | 🌐 Python | 📅 2026-10-17 - Library for building agents that see, navigate, and interact with web browsers.
* [Agent Reach](https://github.com/Panniantong/Agent-Reach) ⭐ 98,334 | 🐛 221 | 🌐 Python | 📅 2026-10-15 - Tool for giving AI agents access to Twitter, Reddit, YouTube, GitHub, and more.
* [Crawl4AI](https://github.com/unclecode/crawl4ai) ⭐ 85,683 | 🐛 261 | 🌐 Python | 📅 2026-10-15 - Open-source, LLM-friendly web crawler and scraper for AI data gathering.
* [Lightpanda](https://github.com/lightpanda-io/browser) ⭐ 36,603 | 🐛 87 | 🌐 Zig | 📅 2026-10-17 - Headless browser written in Zig, built for AI and automation, compatible with CDP, Playwright, and Puppeteer.
* [AIHawk](https://github.com/feder-cr/AIHawk) ⭐ 32,119 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-17 - Open-source AI browser agent that browses, clicks, types, and reads the web from plain-English instructions, available as an MCP server (Claude Code, Codex, Gemini CLI) or a standalone web UI.
* [Stagehand](https://github.com/browserbase/stagehand) ⭐ 25,712 | 🐛 399 | 🌐 TypeScript | 📅 2026-10-16 - SDK built on Playwright for authoring browser agents that extract data and interact with websites.
* [Browser Harness](https://github.com/browser-use/browser-harness) ⭐ 18,456 | 🐛 410 | 🌐 Python | 📅 2026-10-15 - Self-healing harness that enables LLMs to complete browser tasks.
* [Web UI](https://github.com/browser-use/web-ui) ⭐ 16,617 | 🐛 326 | 🌐 Python | 📅 2026-09-25 - Web interface for running and managing AI agents in your browser.
* [Nanobrowser](https://github.com/nanobrowser/nanobrowser) ⭐ 14,106 | 🐛 70 | 🌐 TypeScript | 📅 2026-10-15 - Open-source Chrome extension for AI-powered web automation with multi-agent workflows.
* [BrowserOS](https://github.com/browseros-ai/BrowserOS) ⭐ 13,958 | 🐛 97 | 🌐 TypeScript | 📅 2026-10-16 - Open-source agentic browser as an alternative to proprietary AI browsing tools.
* [Browserless](https://github.com/browserless/browserless) ⭐ 13,815 | 🐛 15 | 🌐 TypeScript | 📅 2026-10-16 - Headless browser deployment platform for Docker and cloud environments.
* [WebVoyager](https://github.com/MinorJerry/WebVoyager) ⭐ 1,127 | 🐛 12 | 🌐 Python | 📅 2024-03-04 - End-to-end web agent framework powered by large multimodal models.
* [Agentic AI Browser](https://github.com/esinecan/agentic-ai-browser) ⭐ 163 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-04 - AI-driven web automation agent using Playwright for decision-making.
* [Vibe Eyes](https://github.com/monteslu/vibe-eyes) ⭐ 54 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-04 - MCP server that enables LLMs to see and interact with browser-based applications.

## Voice & Conversational AI

Text-to-speech, speech-to-text, voice assistants, and real-time audio systems.

* [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) ⭐ 62,944 | 🐛 898 | 🌐 Python | 📅 2026-10-08 - Few-shot voice cloning and text-to-speech model training framework.
* [VibeVoice](https://github.com/microsoft/VibeVoice) ⭐ 54,855 | 🐛 201 | 🌐 Python | 📅 2026-10-08 - Open-source voice AI for audio synthesis.
* [Fish Speech](https://github.com/fishaudio/fish-speech) ⭐ 33,221 | 🐛 19 | 🌐 Python | 📅 2026-10-14 - Open-source text-to-speech engine with multilingual voice cloning.
* [Chatterbox](https://github.com/resemble-ai/chatterbox) ⭐ 27,018 | 🐛 373 | 🌐 Python | 📅 2026-07-21 - Open-source text-to-speech engine for realistic voices.
* [LiveKit](https://github.com/livekit/livekit) ⭐ 21,496 | 🐛 190 | 🌐 Go | 📅 2026-10-16 - End-to-end realtime stack for connecting humans and AI with low-latency audio/video.
* [Dia](https://github.com/nari-labs/dia) ⭐ 19,407 | 🐛 91 | 🌐 Python | 📅 2025-11-19 - TTS model capable of generating realistic dialogue in a single pass.
* [KittenTTS](https://github.com/KittenML/KittenTTS) ⭐ 16,096 | 🐛 132 | 🌐 Python | 📅 2026-10-16 - TTS model under 25MB for compact, high-quality voice synthesis.
* [LiveKit Agents](https://github.com/livekit/agents) ⭐ 14,775 | 🐛 753 | 🌐 Python | 📅 2026-10-17 - Framework for building realtime voice AI agents with audio and video pipelines.
* [YuE](https://github.com/multimodal-art-projection/YuE) ⭐ 12,055 | 🐛 81 | 🌐 Python | 📅 2026-10-06 - Open full-song music generation foundation model.
* [Pocket TTS](https://github.com/kyutai-labs/pocket-tts) ⭐ 9,913 | 🐛 61 | 🌐 Python | 📅 2026-10-16 - Text-to-speech model designed to run efficiently on consumer CPUs.
* [MLX Audio](https://github.com/Blaizzy/mlx-audio) ⭐ 8,054 | 🐛 110 | 🌐 Python | 📅 2026-10-16 - Text-to-speech, speech-to-text, and speech-to-speech library built on Apple's MLX framework.
* [NeuTTS](https://github.com/neuphonic/neutts) ⭐ 6,313 | 🐛 37 | 🌐 Python | 📅 2026-07-30 - On-device text-to-speech model by Neuphonic for private voice synthesis.
* [Piper](https://github.com/OHF-Voice/piper1-gpl) ⭐ 5,902 | 🐛 145 | 🌐 C++ | 📅 2026-10-16 - Fast and local neural text-to-speech engine for low-latency applications.
* [MisoTTS](https://github.com/MisoLabsAI/MisoTTS) ⭐ 3,243 | 🐛 21 | 🌐 Python | 📅 2026-06-09 - 8-billion parameter text-to-speech model for highly emotive voice generation.
* [Jarvis](https://github.com/isair/jarvis) ⭐ 2,091 | 🐛 167 | 🌐 Python | 📅 2026-10-14 - Private AI voice assistant that runs offline on your computer.
* [Kokoro TTS](https://github.com/nazdridoy/kokoro-tts) ⭐ 1,941 | 🐛 18 | 🌐 Python | 📅 2026-08-22 - CLI-based text-to-speech tool utilizing the Kokoro model for multiple languages.
* [Tada](https://github.com/HumeAI/tada) ⭐ 1,020 | 🐛 19 | 🌐 Jupyter Notebook | 📅 2026-05-11 - Open-source speech language model for expressive, emotionally-aware audio generation.
* [Fun Audio Chat](https://github.com/QwenAudio/Fun-Audio-Chat) ⭐ 1,008 | 🐛 19 | 🌐 Python | 📅 2026-09-24 - Large audio language model for natural, low-latency voice interactions.
* [Confucius4-TTS](https://github.com/netease-youdao/Confucius4-TTS) ⭐ 842 | 🐛 11 | 🌐 Python | 📅 2026-09-03 - TTS model optimized for long-form Chinese and English content with strong emotion control.
* [Liquid Audio](https://github.com/Liquid4All/liquid-audio) ⭐ 576 | 🐛 10 | 🌐 Python | 📅 2026-10-03 - Speech-to-speech audio models developed by Liquid AI.
* [Audio2Face 3D](https://github.com/NVIDIA/Audio2Face-3D-Samples) ⭐ 334 | 🐛 24 | 🌐 Python | 📅 2026-03-11 - Service for converting audio to facial blendshapes for lipsync and real-time facial performances.

## Visual & Creative AI

Image generation, video creation, 3D modeling, and visual manipulation tools.

* [DragGAN](https://github.com/XingangPan/DragGAN) ⭐ 35,729 | 🐛 154 | 🌐 Python | 📅 2024-05-18 - Interactive point-based manipulation for precise control over generative images.
* [Open-Sora](https://github.com/hpcaitech/Open-Sora) ⭐ 29,870 | 🐛 14 | 🌐 Python | 📅 2026-04-09 - Open-source video generation models for efficient video production.
* [InvokeAI](https://github.com/invoke-ai/InvokeAI) ⭐ 28,699 | 🐛 447 | 🌐 TypeScript | 📅 2026-10-17 - Creative engine for Stable Diffusion models to generate visual media.
* [Duix Avatar](https://github.com/duixcom/Duix-Avatar) ⭐ 15,947 | 🐛 424 | 🌐 C | 📅 2026-04-21 - Open-source toolkit for AI avatar creation and digital human cloning.
* [Z-Image](https://github.com/Tongyi-MAI/Z-Image) ⭐ 12,096 | 🐛 112 | 🌐 Python | 📅 2026-02-09 - Open-source image generation model from Alibaba's Tongyi team.
* [Sana](https://github.com/NVlabs/Sana) ⭐ 9,370 | 🐛 144 | 🌐 Python | 📅 2026-10-16 - High-resolution image synthesis using Linear Diffusion Transformers.
* [Modly](https://github.com/lightningpixel/modly) ⭐ 8,218 | 🐛 106 | 🌐 TypeScript | 📅 2026-10-04 - Desktop app for generating 3D models from images using local AI.
* [SkyReels V2](https://github.com/SkyworkAI/SkyReels-V2) ⭐ 7,694 | 🐛 369 | 🌐 Python | 📅 2026-01-29 - Generative model for creating infinite-length AI films.
* [TripoSR](https://github.com/VAST-AI-Research/TripoSR) ⭐ 7,097 | 🐛 107 | 🌐 Python | 📅 2026-06-04 - Fast 3D object reconstruction from a single image using AI.
* [HunyuanVideo 1.5](https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5) ⭐ 4,571 | 🐛 38 | 🌐 Python | 📅 2026-04-10 - Lightweight video generation model for high-quality output.
* [Helios](https://github.com/PKU-YuanGroup/Helios) ⭐ 2,209 | 🐛 44 | 🌐 Python | 📅 2026-08-24 - Real-time long video generation model for streaming video synthesis.
* [Node Banana](https://github.com/shrimbly/node-banana) ⭐ 1,631 | 🐛 22 | 🌐 TypeScript | 📅 2026-10-14 - Free and open-source node-based generative workflow platform.
* [Short Video Maker](https://github.com/gyoridavid/short-video-maker) ⭐ 1,411 | 🐛 29 | 🌐 TypeScript | 📅 2025-06-21 - Creates short videos for TikTok, Instagram Reels, and YouTube Shorts using MCP.
* [FlashWorld](https://github.com/imlixinyang/FlashWorld) ⭐ 868 | 🐛 18 | 🌐 Python | 📅 2026-03-24 - High-quality 3D scene generation framework that works within seconds.
* [Realtime Video](https://github.com/krea-ai/realtime-video) ⭐ 589 | 🐛 17 | 🌐 Python | 📅 2025-11-13 - Open-source model for high-quality, realtime AI video generation.
* [RealWonder](https://github.com/liuwei283/RealWonder) ⭐ 229 | 🐛 3 | 🌐 Python | 📅 2026-03-06 - Real-time physical action-conditioned video generation model.
* [EditThinker](https://github.com/appletea233/EditThinker) ⭐ 113 | 🐛 4 | 🌐 Python | 📅 2026-01-18 - Iterative reasoning framework for step-by-step thinking in image editing.
* [Streamo](https://github.com/maifoundations/Streamo) ⭐ 93 | 🐛 10 | 🌐 Python | 📅 2026-02-25 - Streaming video instruction tuning framework for continuous video understanding.
* [Cutalyst](https://github.com/MamtaRajpurohit/Cutalyst) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-04 - Automated video editing AI that cuts, syncs, and subtitles videos.

## Developer Tools & Code Assistants

Code editors, coding agents, and development tools.

* [Ponytail](https://github.com/DietrichGebert/ponytail) ⭐ 165,335 | 🐛 23 | 🌐 JavaScript | 📅 2026-10-16 - Agent skill and rules package that steers coding agents toward writing minimal code.
* [CodeGraph](https://github.com/colbymchenry/codegraph) ⭐ 74,304 | 🐛 613 | 🌐 C | 📅 2026-10-17 - Pre-indexed code knowledge graph that auto-syncs on code changes for multiple AI coding tools.
* [Oh My OpenAgent](https://github.com/code-yeongyu/oh-my-openagent) ⭐ 70,120 | 🐛 1,419 | 🌐 TypeScript | 📅 2026-10-17 - Batteries-included agent harness for complex codebases.
* [OpenClaude](https://github.com/Twigpine/openclaude) ⭐ 33,953 | 🐛 70 | 🌐 TypeScript | 📅 2026-10-15 - Open-source coding-agent CLI that works with cloud and local model providers, with tools, agents, and MCP support.
* [Open Lovable](https://github.com/firecrawl/open-lovable) ⭐ 28,715 | 🐛 152 | 🌐 TypeScript | 📅 2026-10-09 - Tool for cloning and recreating websites as modern React apps using AI.
* [Dyad](https://github.com/dyad-sh/dyad) ⭐ 21,954 | 🐛 337 | 🌐 TypeScript | 📅 2026-10-16 - Local, open-source AI app builder for power users.
* [DeepCode](https://github.com/HKUDS/DeepCode) ⭐ 16,720 | 🐛 24 | 🌐 Python | 📅 2026-10-14 - Open agentic coding framework for paper-to-code and web development tasks.
* [sandcastle](https://github.com/mattpocock/sandcastle) ⭐ 8,482 | 🐛 178 | 🌐 TypeScript | 📅 2026-10-16 - TypeScript library for orchestrating sandboxed coding agents.
* [ClawX](https://github.com/ValueCell-ai/ClawX) ⭐ 7,604 | 🐛 43 | 🌐 TypeScript | 📅 2026-10-15 - Desktop app providing a graphical interface for OpenClaw AI agents.
* [OpenBot](https://github.com/CopilotKit/OpenBot) ⭐ 6,571 | 🐛 27 | 🌐 TypeScript | 📅 2026-10-17 - Open-source coding agent for VS Code powered by CopilotKit.
* [Emdash](https://github.com/generalaction/emdash) ⭐ 6,008 | 🐛 93 | 🌐 TypeScript | 📅 2026-10-14 - Open-source agentic development environment for running multiple coding agents in parallel.
* [CodeNomad](https://github.com/NeuralNomadsAI/CodeNomad) ⭐ 2,626 | 🐛 16 | 🌐 TypeScript | 📅 2026-10-17 - Multi-agent coding orchestration platform for parallel AI-assisted development.
* [Mysti](https://github.com/DeepMyst/Mysti) ⭐ 1,142 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-13 - AI coding dream team of agents for VS Code that debate and synthesize solutions.
* [Clawmetry](https://github.com/vivekchand/clawmetry) ⭐ 429 | 🐛 117 | 🌐 Python | 📅 2026-10-17 - Real-time observability dashboard for OpenClaw AI agents.
* [Persona](https://github.com/runtypelabs/persona) ⭐ 252 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-16 - Toolkit for creating agentic front-end experiences for the web with WebMCP support.

## LLM Infrastructure & Model Serving

Model hosting, fine-tuning, API gateways, and inference optimization.

* [RTK](https://github.com/rtk-ai/rtk) ⭐ 83,644 | 🐛 1,551 | 🌐 Rust | 📅 2026-10-17 - Rust CLI proxy that filters and compresses command output before it reaches the LLM context.
* [Unsloth](https://github.com/unslothai/unsloth) ⭐ 78,145 | 🐛 353 | 🌐 Python | 📅 2026-10-17 - Fine-tuning and reinforcement learning framework for LLMs.
* [Headroom](https://github.com/headroomlabs-ai/headroom) ⭐ 75,541 | 🐛 437 | 🌐 Python | 📅 2026-10-17 - Tool for compressing tool outputs, logs, files, and RAG chunks before they reach the LLM.
* [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 61,406 | 🐛 5,570 | 🌐 Python | 📅 2026-10-17 - Python SDK and proxy server to call 100+ LLM APIs in a unified OpenAI format.
* [LocalAI](https://github.com/mudler/LocalAI) ⭐ 49,590 | 🐛 191 | 🌐 Go | 📅 2026-10-16 - Self-hosted, local-first open-source alternative to OpenAI and Claude APIs.
* [LLMFit](https://github.com/AlexsJones/llmfit) ⭐ 38,001 | 🐛 53 | 🌐 Rust | 📅 2026-10-15 - Tool for discovering hundreds of models across providers to find what runs on your hardware.
* [freellmapi](https://github.com/tashfeenahmed/freellmapi) ⭐ 36,304 | 🐛 41 | 🌐 TypeScript | 📅 2026-10-16 - OpenAI-compatible proxy that stacks free tiers of 28 LLM providers behind a single endpoint with smart routing and failover.
* [PowerInfer](https://github.com/Tiiny-AI/PowerInfer) ⭐ 9,834 | 🐛 133 | 🌐 C++ | 📅 2026-05-11 - High-speed LLM serving for local deployment with CPU/GPU heterogeneous inference.

## Security & Offensive AI

Penetration testing, red teaming, vulnerability scanning, and security tools.

* [Strix](https://github.com/usestrix/strix) ⭐ 69,068 | 🐛 476 | 🌐 Python | 📅 2026-10-15 - Open-source AI tool for finding and fixing application vulnerabilities.
* [Shannon](https://github.com/KeygraphHQ/shannon) ⭐ 49,004 | 🐛 24 | 🌐 TypeScript | 📅 2026-10-15 - Autonomous AI pentester for web applications and APIs that analyzes source code and executes exploits.
* [Pentagi](https://github.com/vxcontrol/pentagi) ⭐ 30,787 | 🐛 38 | 🌐 Go | 📅 2026-10-17 - Fully autonomous AI agents system for complex penetration testing tasks end-to-end.
* [SkillSpector](https://github.com/NVIDIA/SkillSpector) ⭐ 20,390 | 🐛 139 | 🌐 Python | 📅 2026-10-16 - Security scanner for AI agent skills that detects vulnerabilities and malicious patterns.
* [OneCLI](https://github.com/onecli/onecli) ⭐ 3,578 | 🐛 177 | 🌐 TypeScript | 📅 2026-10-14 - Open-source credential vault for AI agents that injects API keys transparently.
* [RedAMon](https://github.com/samugit83/redamon) ⭐ 3,132 | 🐛 19 | 🌐 Python | 📅 2026-10-15 - AI-powered agentic red team framework for offensive security operations from recon to post-exploitation.
* [Pentest-Swarm-AI](https://github.com/Armur-Ai/Pentest-Swarm-AI) ⭐ 2,996 | 🐛 23 | 🌐 Go | 📅 2026-10-16 - Autonomous penetration testing using a swarm of AI agents with specialized roles.
* [Azazel](https://github.com/beelzebub-labs/azazel) ⭐ 110 | 🐛 3 | 🌐 C | 📅 2026-10-13 - eBPF-powered observer for containerized runtimes, built for malware analysis and AI monitoring.

## Data, Memory & Knowledge

OCR, knowledge graphs, memory systems, and data infrastructure.

* [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) ⭐ 91,257 | 🐛 248 | 🌐 Python | 📅 2026-09-16 - Comprehensive OCR toolkit supporting 100+ languages and complex layouts.
* [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) ⭐ 86,683 | 🐛 325 | 🌐 TypeScript | 📅 2026-10-12 - Turns codebases into interactive knowledge graphs for AI agents to explore, search, and query.
* [Docling](https://github.com/docling-project/docling) ⭐ 68,996 | 🐛 882 | 🌐 Python | 📅 2026-10-16 - Tool for converting various document formats into AI-ready structured data.
* [Pathway](https://github.com/pathwaycom/pathway) ⭐ 62,109 | 🐛 37 | 🌐 Python | 📅 2026-10-17 - Python ETL framework for real-time analytics, stream processing, and RAG.
* [Graphiti](https://github.com/getzep/graphiti) ⭐ 31,828 | 🐛 480 | 🌐 Python | 📅 2026-10-15 - Tool for building real-time knowledge graphs to power AI agent memory.
* [OLMocr](https://github.com/allenai/olmocr) ⭐ 19,751 | 🐛 93 | 🌐 Python | 📅 2026-03-25 - Toolkit for linearizing PDFs to prepare datasets for LLM training.
* [Memori](https://github.com/MemoriLabs/Memori) ⭐ 17,151 | 🐛 37 | 🌐 Python | 📅 2026-10-03 - SQL-native memory layer for LLMs, AI agents, and multi-agent systems.
* [memU](https://github.com/NevaMind-AI/memU) ⭐ 14,549 | 🐛 133 | 🌐 Python | 📅 2026-10-16 - Memory system designed for 24/7 proactive agents.
* [Chandra](https://github.com/datalab-to/chandra) ⭐ 12,507 | 🐛 63 | 🌐 Python | 📅 2026-06-26 - Specialized OCR model for parsing complex tables, forms, and handwriting.
* [MemOS](https://github.com/MemTensor/MemOS) ⭐ 11,897 | 🐛 146 | 🌐 TypeScript | 📅 2026-10-10 - AI memory operating system for persistent skill storage in agent systems.
* [FalkorDB](https://github.com/FalkorDB/FalkorDB) ⭐ 10,303 | 🐛 1,011 | 🌐 Rust | 📅 2026-10-16 - Fast graph database using GraphBLAS for GraphRAG and knowledge graphs for LLMs.
* [Dolphin](https://github.com/bytedance/Dolphin) ⭐ 9,065 | 🐛 78 | 🌐 Python | 📅 2026-03-25 - Document image parsing framework using heterogeneous anchor prompting.
* [OpenMed](https://github.com/maziyarpanahi/openmed) ⭐ 5,694 | 🐛 576 | 🌐 Python | 📅 2026-10-16 - Local-first clinical NLP toolkit for medical entity recognition and HIPAA PII de-identification that runs entirely on-device.
* [PageLM](https://github.com/CaviraOSS/PageLM) ⭐ 2,030 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-13 - Community-driven education platform for transforming study materials into interactive resources.
* [Unbody](https://github.com/unbody-io/unbody) ⭐ 523 | 🐛 3 | 🌐 TypeScript | 📅 2026-04-14 - Modular, open-source backend for building AI-native software designed for knowledge.
* [Myriade](https://github.com/myriade-ai/myriade) ⭐ 62 | 🐛 0 | 🌐 Shell | 📅 2026-10-16 - AI-native data platform for exploring and transforming data warehouses.

## Datasets & Benchmarks

Open datasets, evaluation benchmarks, and reference collections for agent systems.

* [System Prompts and Models of AI Tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) ⭐ 144,055 | 🐛 162 | 📅 2026-10-12 - Collection of system prompts and models for various AI tools.
* [12-Factor Agents](https://github.com/humanlayer/12-factor-agents) ⭐ 26,729 | 🐛 27 | 🌐 TypeScript | 📅 2025-09-21 - Principles for building LLM-powered software that is production-ready.
* [Open LLMs](https://github.com/eugeneyan/open-llms) ⭐ 12,890 | 🐛 10 | 📅 2025-02-13 - Curated list of open LLMs available for commercial and research use.
* [Harness Engineering](https://github.com/lopopolo/harness-engineering) ⭐ 2,732 | 🐛 1 | 🌐 Python | 📅 2026-07-18 - Field guide and anthology on harness engineering: improving agent output by curating the context, tools, and environment around a model.

## Productivity & Personal Assistants

Chat interfaces, personal AI assistants, and productivity tools.

* [OpenClaw](https://github.com/openclaw/openclaw) ⭐ 392,221 | 🐛 9,369 | 🌐 TypeScript | 📅 2026-10-17 - Personal AI assistant that runs on any OS and any platform.
* [Open WebUI](https://github.com/open-webui/open-webui) ⭐ 155,939 | 🐛 256 | 🌐 Python | 📅 2026-10-16 - Self-hosted web interface for interacting with various LLMs.
* [Airi](https://github.com/moeru-ai/airi) ⭐ 50,449 | 🐛 238 | 🌐 TypeScript | 📅 2026-10-17 - Self-hosted AI companion and VTuber platform with voice chat and real-time interaction.
* [LibreChat](https://github.com/danny-avila/LibreChat) ⭐ 45,834 | 🐛 961 | 🌐 TypeScript | 📅 2026-10-17 - Enhanced ChatGPT clone with Agents, MCP, multi-model support, and enterprise features.
* [Jan](https://github.com/janhq/jan) ⭐ 44,975 | 🐛 588 | 🌐 Rust | 📅 2026-10-16 - Open-source alternative to ChatGPT that runs offline on your machine.
* [Khoj](https://github.com/khoj-ai/khoj) ⭐ 37,713 | 🐛 169 | 🌐 Python | 📅 2026-08-02 - AI second brain for searching documents, the web, and building custom agents.
* [Eigent](https://github.com/eigent-ai/eigent) ⭐ 15,575 | 🐛 245 | 🌐 TypeScript | 📅 2026-10-16 - Open-source coworker desktop application for individual productivity.
* [Omi](https://github.com/BasedHardware/omi) ⭐ 13,754 | 🐛 1,695 | 🌐 Python | 📅 2026-10-17 - AI wearable device for real-time transcription and speech processing.
* [Chat UI](https://github.com/huggingface/chat-ui) ⭐ 10,988 | 🐛 311 | 🌐 TypeScript | 📅 2026-10-16 - Open source codebase powering Hugging Face Chat with multi-model support.
* [Feynman](https://github.com/Companion-Inc/feynman) ⭐ 9,976 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-17 - CLI research agent for literature review, deep research, paper critique, and replication planning with citation tracking.
* [Agentic Inbox](https://github.com/cloudflare/agentic-inbox) ⭐ 8,319 | 🐛 51 | 🌐 TypeScript | 📅 2026-04-23 - Self-hosted email client with an AI agent, running on Cloudflare Workers.
* [Rakazo](https://github.com/elie222/rakazo) ⭐ 4,354 | 🐛 46 | 🌐 TypeScript | 📅 2026-10-17 - Self-hostable platform for running persistent AI teammates with memory, routines, voice mode, and browser, terminal, and desktop access across web, desktop, and mobile apps.
* [ClaraVerse](https://github.com/claraverse-space/ClaraVerse) ⭐ 3,902 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-03 - Open-source multimodal AI platform with local LLM, voice, vision, and code execution.
* [Ovi](https://github.com/character-ai/Ovi) ⭐ 1,761 | 🐛 47 | 🌐 Python | 📅 2025-11-15 - Experimental AI character interaction tool from the Character.ai team.
* [Newelle](https://github.com/qwersyk/Newelle) ⭐ 1,488 | 🐛 23 | 🌐 Python | 📅 2026-10-15 - Virtual assistant application for desktop environments.
* [Osaurus](https://github.com/dinoki-ai/osaurus) ⭐ 38 | 🐛 1 | 🌐 HTML | 📅 2026-02-24 - AI edge infrastructure for macOS that runs local or cloud models with MCP tool sharing.

## MCP & Tool Integration

Model Context Protocol servers, tool integrations, and API connectivity.

* [JSON Render](https://github.com/vercel-labs/json-render) ⭐ 18,701 | 🐛 139 | 🌐 TypeScript | 📅 2026-10-13 - Tool for dynamically rendering AI-generated JSON data into user interfaces.
* [OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) ⭐ 15,911 | 🐛 130 | 🌐 Python | 📅 2026-10-17 - General-purpose sandbox platform for AI applications with multi-language SDKs.
* [Claude Context](https://github.com/zilliztech/claude-context) ⭐ 12,620 | 🐛 146 | 🌐 TypeScript | 📅 2026-07-14 - Code search MCP that makes entire codebases accessible to AI agents.
* [Klavis](https://github.com/Klavis-AI/klavis) ⭐ 5,812 | 🐛 307 | 🌐 Python | 📅 2026-06-01 - MCP integration platform for reliable tool use by AI agents at scale.
* [Monid](https://github.com/monid-ai/monid) ⭐ 4,627 | 🐛 85 | 🌐 TypeScript | 📅 2026-10-16 - Unified gateway giving agents access to 2,000+ tools across multiple providers, with endpoint discovery and per-call metering.
* [Metorial](https://github.com/metorial/metorial) ⭐ 3,367 | 🐛 7 | 🌐 TypeScript | 📅 2026-10-16 - Platform for connecting any AI model to 600+ integrations via MCP.
* [Interactive MCP](https://github.com/ttommyth/interactive-mcp) ⭐ 351 | 🐛 9 | 🌐 TypeScript | 📅 2025-11-20 - Local, cross-platform MCP server for human-in-the-loop interaction with AI agents.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Footnotes

* For a table view of this list with star counts, see [TABLE\_VIEW.md](TABLE_VIEW.md).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-17._
