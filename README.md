### Hey, I'm Lucas

[![X @tobenwarrior](https://img.shields.io/badge/X-@tobenwarrior-000?style=flat&logo=x)](https://x.com/tobenwarrior)

I build tools for AI agents: model providers, plugins and desktop features for [Hermes Agent](https://github.com/NousResearch/hermes-agent), and my own harness on top of [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness).

Most recently, I built out the Hermes desktop plugin SDK, seven new extension points for plugins, from session-list slots to a sandboxed embed and a backend-to-desktop event bridge. Two of my plugins ship in the official Hermes plugin catalog.

Right now I'm working on Bot Mode for the Hermes desktop app, so bot rooms feel like a group chat: emoji reactions, quoted replies, visible bot-to-bot threads and a tab per bot.

#### Building

- **[Y Harness](https://github.com/tobenwarrior/y-harness)** - My personal agent harness, a fork of DeepSeek Harness that adds a ChatGPT subscription provider (run through the official Codex app) and a Nous Portal provider.
- **[kiro-acp](https://github.com/tobenwarrior/hermes-kiro-provider)** [![Hermes plugin catalog](https://img.shields.io/badge/Hermes-plugin_catalog-gold?style=flat)](https://github.com/NousResearch/hermes-agent/blob/main/plugin-catalog/kiro-acp.yaml) - Kiro CLI (AWS) as a Hermes model provider: Kiro's agent runs as an ACP subprocess behind Hermes' normal provider interface, with zero edits to Hermes core.
- **[Provider Copy](https://github.com/tobenwarrior/hermes-provider-copy)** [![Hermes plugin catalog](https://img.shields.io/badge/Hermes-plugin_catalog-gold?style=flat)](https://github.com/NousResearch/hermes-agent/blob/main/plugin-catalog/provider-copy.yaml) - Copy provider API keys from one Hermes profile to your other bots, once and explicitly. OAuth sign-ins and bot tokens never travel.
- **[need-follow-up](https://github.com/tobenwarrior/need-follow-up)** - Telegram pings when Claude Code needs approval or finishes a task.

#### Contributing to

- **[Hermes Agent](https://github.com/NousResearch/hermes-agent)** [![GitHub stars](https://img.shields.io/github/stars/NousResearch/hermes-agent?style=flat&color=gold)](https://github.com/NousResearch/hermes-agent) - Desktop plugin SDK: session-list API and row-decoration slots, sidebar nav visibility and order, model-pill label providers, a typed skills/toolsets/profiles bridge, an appearance-settings slot with the app's swatch grid, a sandboxed embed primitive, and a public backend-to-desktop event bridge. Also external-process (ACP) plugin providers in the model picker, ACP launch kwargs keyed on provider profile, annotated-tag pin verification for plugin installs, pinned-session card rendering, and filing group chats into user-made roster sections. ([commits](https://github.com/NousResearch/hermes-agent/commits/main?author=tobenwarrior) · [pull requests](https://github.com/NousResearch/hermes-agent/pulls?q=is%3Apr+author%3Atobenwarrior) · [issues](https://github.com/NousResearch/hermes-agent/issues?q=is%3Aissue+author%3Atobenwarrior))
