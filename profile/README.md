# 🪽 Allay

![Allay, an AI helper for Minecraft](https://raw.githubusercontent.com/allay-ai/.github/master/media/preview-minecraft.png)

**Allay** is an AI helper for Minecraft players, named after the friendly mob that brings players what they need. A player types `/ask` in a server's chat and gets an answer grounded in their real game: their inventory, what they're looking at, the chests around them, the server's recipes and rules. Allay knows Java Edition inside out, searches the web for fresh facts, remembers each player, and answers in the language of the question.

## Projects

### 💬 [Allay for Minecraft](https://github.com/allay-ai/minecraft)

The plugin for Spigot, Paper 26.3, and their forks: `/ask`, `/askall`, `/askx`, and chat mode.

- Allay looks things up in the game while it answers: status, inventory with bundles and shulker boxes, whatever is under the crosshair, chests nearby, structures and biomes
- Buttons under answers, recipe, enchanting, and villager windows, a notebook, goals with a boss bar, reminders
- A live status like Claude Code: a spinner, a changing verb, and a line for each tool Allay uses; and it sounds like an allay
- Every player reads the plugin in their own language: English, Russian, Spanish, Portuguese, German
- Tools see only the player who asked; anything that gives items or changes the world is for operators only

### 🛠️ [Allay Server](https://github.com/allay-ai/server)

The backend: a Mastra agent on Bun that answers through OpenRouter, streams its work to the plugin, calls the plugin's game tools, searches the web, computes exactly, and keeps each player's conversation and memories. Run your own with Docker, or use the hosted one at `allay.chat`.

### 🤖 [Allay for Telegram](https://github.com/allay-ai/telegram)

The Telegram bot, archived.

## Get started

1. Download the plugin from [Releases](https://github.com/allay-ai/minecraft/releases) and put it in your server's `plugins/` folder.
2. Restart the server.
3. Ask: `/ask how do I craft a beacon?`

Coming from MCBuddy? Allay is its new name from 4.0.0 on, and it moves MCBuddy's data over by itself.

## Try it live

Allay runs on [Moonlands](https://minecraft.mairwunnx.com), a hard survival server. Join at `minecraft.mairwunnx.com`.

## From the same author

- [Mo’Joins](https://github.com/MairwunNx/mojoins)—🎉 join and quit lines in each player's language
- [Mo’Afks](https://github.com/MairwunNx/moafks)—🛡️ a safe AFK mode
- [Mo’Bosses](https://github.com/mairwunnx/mobosses)—🏆 ordinary mobs become epic bosses

The allay and its texture are Mojang's; the avatar is rendered from the game's own model.

> 🫡 Made by Pavel Erokhin (Павел Ерохин), aka mairwunnx.
