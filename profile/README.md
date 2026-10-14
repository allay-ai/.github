# 💬 MCBuddy

**MCBuddy** is an AI buddy for Minecraft players. A player types `/ask` in a server's chat and gets an answer grounded in their real game: their inventory, what they're looking at, the chests around them, the server's recipes and rules. The assistant knows Java Edition inside out, searches the web for fresh facts, remembers each player, and answers in the language of the question.

## Projects

### 💬 [MCBuddy Spigot](https://github.com/mcbuddy-ai/mcbuddy-spigot)

The plugin for Spigot and Paper 26.3: `/ask` and `/askx` in the chat.

- The assistant looks things up in the game while it answers: status, inventory with bundles and shulker boxes, whatever is under the crosshair, chests nearby, structures and biomes
- Buttons under answers, recipe, enchanting, and villager windows, a notebook, goals with a boss bar, reminders
- A live status like Claude Code: a spinner, a changing verb, and a line for each tool the assistant uses
- Every player reads the plugin in their own language: English, Russian, Spanish, Portuguese, German
- Tools see only the player who asked; anything that gives items or changes the world is for operators only

### 🛠️ [MCBuddy Server](https://github.com/mcbuddy-ai/mcbuddy-server)

The backend: a Mastra agent on Bun that answers through OpenRouter, streams its work to the plugin, calls the plugin's game tools, searches the web, computes exactly, and keeps each player's conversation and memories. Run your own with Docker, or use the hosted one at `mcbuddy.ru`.

### 🤖 [MCBuddy Bot](https://github.com/mcbuddy-ai/mcbuddy-bot)

The Telegram bot, archived.

## Get started

1. Download the plugin from [Releases](https://github.com/mcbuddy-ai/mcbuddy-spigot/releases) and put it in your server's `plugins/` folder.
2. Restart the server.
3. Ask: `/ask how do I craft a beacon?`

## Try it live

MCBuddy runs on [Moonlands](https://minecraft.mairwunnx.com), a hard survival server. Join at `minecraft.mairwunnx.com`.

## From the same author

- [Mo’Joins](https://github.com/MairwunNx/mojoins)—🎉 join and quit lines in each player's language
- [Mo’Afks](https://github.com/MairwunNx/moafks)—🛡️ a safe AFK mode
- [Mo’Bosses](https://github.com/mairwunnx/mobosses)—🏆 ordinary mobs become epic bosses

> 🫡 Made by Pavel Erokhin (Павел Ерохин), aka mairwunnx.
