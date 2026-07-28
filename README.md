# Hey there, I'm ScarletRedJoker 👋

## About Me

I'm a software developer and homelab enthusiast building **Nebula Command** — a self-hosted AI platform that brings local-first AI inference, infrastructure management, and creator tools into a unified system. When I'm not coding, you'll find me tinkering with GPU passthrough, managing distributed infrastructure, or pushing the limits of what a homelab can do.

## 🚀 Current Project: Nebula Command

A production-grade, self-hosted AI platform and homelab command center that runs on my own hardware:

- **Jarvis AI Assistant**: 70+ tools, dual-agent orchestration, persistent memory, and a standalone MCP tool server — it deploys services, switches GPU modes, and manages infrastructure from chat
- **Local-First AI**: Ollama, Stable Diffusion, and ComfyUI on dedicated GPU hardware, with policy-controlled cloud fallback (OpenAI)
- **Unified Dashboard**: Next.js 14 dashboard with 120+ pages, 180+ API route groups, and a 260+ table PostgreSQL schema behind it
- **Distributed Fleet**: Cloud VPS edge (30+ containers) + home servers + a GPU workstation VM, all meshed over Tailscale with agents, watchdogs, and self-healing deploy pipelines
- **Creator Tools**: Discord bot (AI chat, music, moderation), multi-platform stream bot (Twitch/YouTube/Kick), media library automation
- **Full Observability**: Prometheus, Grafana, Loki, plus a built-in verify/reconcile system and 180+ Vitest test files

**Status**: In production daily use — dashboard, bots, AI routing, fleet management, and observability are live; creative pipelines (video, 3D/XR) are in active development

[→ View Nebula Command](https://github.com/ScarletRedJoker/Nebula-Command)

## What I'm Working With

* 💻 **Current Focus**: Hardening Nebula Command — self-healing infrastructure, AI capability routing (local vs cloud per feature), and creative generation pipelines
* 🏠 **Homelab**: GPU passthrough, KVM/IPMI management, a multi-node Tailscale fleet, and containerized everything
* 🤖 **AI Stack**: Local Ollama models, Stable Diffusion, ComfyUI, LiteLLM gateway, OpenAI integration
* 🎨 **Side Projects**: Graphic design, community platforms, streaming automation
* 🖥️ **OS Philosophy**: Ubuntu host with Windows VM for GPU-dependent workloads (gaming, Adobe Suite)
* 🔓 **Principle**: Root access > walled gardens

## Tech Stack & Infrastructure

### Languages & Frameworks
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)

### Infrastructure & Tools
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Tailscale](https://img.shields.io/badge/-Tailscale-000000?style=flat-square&logo=tailscale&logoColor=white)
![Caddy](https://img.shields.io/badge/-Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)

### AI & ML
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Stable Diffusion](https://img.shields.io/badge/-Stable_Diffusion-FF6F00?style=flat-square)
![ComfyUI](https://img.shields.io/badge/-ComfyUI-1A1A1A?style=flat-square)

## Homelab Highlights

### 🎮 GPU Workstation Architecture
* **Host**: Ubuntu 24.04 with KVM/QEMU
* **GPU Passthrough**: NVIDIA RTX 3060 to Windows 11 VM
* **AI Workloads**: Ollama (LLMs), Stable Diffusion, ComfyUI — with on-demand wake/idle-park orchestration
* **Game Streaming**: Sunshine/Moonlight for low-latency remote gaming
* **Mode Switching**: Dynamic GPU allocation between AI inference, gaming, and productivity

### 🐳 Cloud & Fleet Infrastructure (30+ Containers)
* **Reverse Proxy**: Caddy with automatic TLS
* **Services**: Next.js dashboard, Discord bot, stream bot, n8n automation, self-hosted Mailu email
* **Monitoring**: Prometheus, Grafana, Loki stack + built-in verify/reconcile self-healing
* **Fleet**: Cloud VPS edge, home media node, CPU inference node, and GPU VM — all agent-managed
* **Networking**: Tailscale mesh VPN connecting every node, no port forwarding

### 🤖 AI Pipeline
* **Local-First**: Ollama models preferred (zero marginal cost, privacy-first), routed per-feature between CPU and GPU nodes
* **Smart Fallback**: Policy-controlled OpenAI routing when local GPU is unavailable
* **Model Management**: Pull, switch, and monitor models from the dashboard or by asking Jarvis
* **Image Generation**: Local Stable Diffusion / ComfyUI with DALL-E 3 cloud backup

## My Sites & Projects

* 🌐 [Personal Portfolio](https://scarletredjoker.com)
* 🎮 [RigCity Community](https://rig-city.com)
* 📺 [Streambot](https://stream.evindrake.net)
* 🤖 [Discordbot](https://bot.evindrake.net)
* 🚀 [Nebula Command](https://github.com/ScarletRedJoker/Nebula-Command)

## Current Focus

🔨 **Evolving Nebula Command beyond the MVP:**
- ✅ Core platform: auth, AI chat, service orchestration, monitoring, bots, GPU management — live in production
- 🔄 Now: self-healing fleet operations, per-feature AI capability routing, media library automation
- 🔭 Next: creative pipelines (video, 3D/AR-VR generation), website design studio, deeper Jarvis autonomy

💡 **Philosophy**: "Your iPhone is cool sure; I have root"

---

📫 **Let's connect**: Building something cool with homelabs, AI, or infrastructure? Let's talk.
