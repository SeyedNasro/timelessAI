# Timeless AI ⏳🤖

![Untit312321led-2](https://github.com/user-attachments/assets/6e0f43f6-1fc8-452e-9044-a1d6e48ced5d)

<div align="center">

📖 [TWITTER-GROK-CLIENT](https://timelessai.github.io/docs)

</div>
## Overview

- 🛠️ Seamless real-time data access with Grok integration
- 🔗 Twitter, Discord, and Telegram connectors
- 👥 Multi-agent support with advanced room management
- 📖 Intelligent document ingestion and interaction
- 🔐 Secure, retrievable memory and data store
- 🚀 Highly customizable and extensible
- ☁️ Supports various models: Grok, Llama, OpenAI, Anthropic, and more
- 📦 Hassle-free deployment

## Use Cases

- 🤔 Real-time trading insights
- 🤖 Advanced chatbot with real time information leveraging Grok
- 🕵️ Autonomous decision-making agents
- 📊 Business analytics and insights
- 🎮 Video game AI and NPCs

## ✨ Grok Integration Highlights

Timeless AI leverages cutting-edge Grok technology, connecting real-time data from Twitter with X-AI’s language models. Grokky, a bridge between Grok’s API and Twitter, enables agents to:

- Monitor and respond to conversations in real-time with context-aware replies.
- Analyze account behavior, personalities, and engagement patterns.
- Summarize threads, distilling key points and actionable insights.
- Perform trend analysis to understand sentiment and identify key influencers.

This transforms Timeless AI into a dynamic, real-time conversational analyst.

## 🚀 Quick Start

### Prerequisites

- [Python 3.7+](https://www.python.org/downloads/)
- [Node.js 16+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is recommended.

### Start with the Starter Template

```bash
git clone https://github.com/timeless-ai/starter.git
cd starter
cp .env.example .env
pnpm i && pnpm build && pnpm start
```

Follow the instructions to launch the agent and start the client:

```bash
pnpm start:client
```

Check the [Documentation](https://timelessai.github.io/docs) for further customization options.

### Manual Setup

For advanced users who prefer manual installation:

```bash
git clone https://github.com/timeless-ai/timeless.git
cd timeless
git checkout $(git describe --tags --abbrev=0)
```

### Environment Configuration

Copy and configure the environment file:

```bash
cp .env.example .env
```

### Running the Agent

Start the agent with the default configuration:

```bash
sh scripts/start.sh
```

To modify the default character, edit `src/defaultCharacter.ts`.
