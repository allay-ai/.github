# 🪽 Allay

[![Allay release](https://img.shields.io/github/v/release/allay-ai/minecraft?label=allay&logo=github)](https://github.com/allay-ai/minecraft/releases/latest) [![Allay Server release](https://img.shields.io/github/v/release/allay-ai/server?label=server&logo=github)](https://github.com/allay-ai/server/releases/latest) [![Spigot | Paper 26.3](https://img.shields.io/badge/Spigot%20%7C%20Paper-26.3-F7CF0D)](https://github.com/allay-ai/minecraft) [![Docker image](https://img.shields.io/badge/ghcr.io-allay--ai%2Fserver-2496ED?logo=docker&logoColor=white)](https://github.com/allay-ai/server/pkgs/container/server)

![Allay, an AI helper for Minecraft](https://raw.githubusercontent.com/allay-ai/.github/master/media/preview-minecraft.png)

<img src="https://raw.githubusercontent.com/allay-ai/.github/master/media/allay-in-game.gif" width="100%" alt="Allay in the game: a player types /ask, the status above the hotbar shows what Allay does, and the answer comes with buttons in the text">

**Allay** is an AI helper for Minecraft, named after the friendly mob that brings players what they need. A player types `/ask` in a server's chat and gets an answer grounded in their real game: their inventory, what they're looking at, the chests around them, the server's recipes and rules. Allay has two parts: a plugin on your Minecraft server and a backend that runs the model.

## Repositories

- **[💬 minecraft](https://github.com/allay-ai/minecraft)**—the plugin for Spigot, Paper 26.3, and their forks: `/ask`, `/askall`, chat mode, trails, marks, and automation agents, in each player's language.
- **[🛠️ server](https://github.com/allay-ai/server)**—the backend: an agent that reads the asker's game, searches the web, remembers each player, and comes with an admin panel. Run it with one Docker Compose file.
- **[🤖 telegram](https://github.com/allay-ai/telegram)**—the old Telegram bot, archived.

## Get started

1. Put [`allay-spigot.jar`](https://github.com/allay-ai/minecraft/releases/latest/download/allay-spigot.jar) into `plugins/` of a Spigot or Paper 26.3 server and restart it.
2. Run `/allay link` for a subscription, bring your own OpenRouter key, or [host the backend yourself](https://github.com/allay-ai/server).
3. Ask: `/ask how do I craft a beacon?`

Coming from MCBuddy? Allay is its new name from 4.0.0 on. Run Allay 6.6 once to move MCBuddy's data, then update.

## Privacy

Allay is EU (GDPR) and US privacy law friendly. On allay.chat, player data stays in the EU (Helsinki), and conversations, memories, deaths, settings, and traces are encrypted at rest with AES-256-GCM. Every player agrees before their first question and confirms their age, by their country's rules. With `/allay privacy` players see, export, and erase what's kept. The [privacy policy](https://allay.chat/privacy/) says what is kept, why, and for how long.

## Documentation

- **[Allay wiki](https://github.com/allay-ai/minecraft/wiki)**—installing the plugin, asking, commands, configuration, and languages.
- **[Allay Server wiki](https://github.com/allay-ai/server/wiki)**—self-hosting with Docker, the admin panel, who pays for the model, and how the agent works.

## Try it live

Allay runs on [Moonlands](https://minecraft.mairwunnx.com), my hard survival server. Join at `minecraft.mairwunnx.com` and ask it something.

## Related projects

- **[Moonlands](https://minecraft.mairwunnx.com)**—the hard-survival server where all of these run.
- **[WorldAPI](https://github.com/MairwunNx/minecraft-worldapi)**—REST and WebSocket API to a Paper server's world, players, and stats.
- **[Minecraft MCP](https://github.com/MairwunNx/minecraft-mcp)**—lets an AI client read and run a server through WorldAPI.
- **[Mo’Joins](https://github.com/MairwunNx/mojoins)**—join and quit messages in each player's language.
- **[Mo’Afks](https://github.com/MairwunNx/moafks)**—a safe AFK mode that doesn't block the night.
- **[Mo’Bosses](https://github.com/MairwunNx/mobosses)**—monsters that spawn as bosses with classes, abilities, and loot.
- **[minecraft-exporter](https://github.com/MairwunNx/minecraft-exporter)**—Prometheus metrics from WorldAPI.
- **[minecraft-grafana](https://github.com/MairwunNx/minecraft-grafana)**—the Grafana dashboard for WorldAPI.

The allay and its texture are Mojang's. The avatar is rendered from the game's own model.

> 🫡 Made by Pavel Erokhin (Павел Ерохин), aka mairwunnx.
