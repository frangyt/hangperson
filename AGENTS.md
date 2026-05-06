# AGENTS.md

## Commands

- **Install**: `yarn install`
- **Run**: `node src/index.js`
- **Lint**: `npx eslint .` (no npm script defined)

## Setup

- Requires `.env` with `DISCORD_TOKEN` at project root
- Uses **yarn** (yarn.lock present), not npm

## Architecture

- Entry point: `src/index.js`
- Discord bot using **discord.js v13** (uses `Intents.FLAGS` syntax; v14+ changed this)
- Only intents used: `GUILDS`
- `src/utils/config.ts` is dead code — unused, no TypeScript config in repo

## Conventions

- ESLint: tabs, single quotes, semicolons, Stroustrup brace style
