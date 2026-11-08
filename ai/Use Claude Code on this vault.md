# Use Claude Code on this vault

Your vault is a folder of markdown files, which means any AI coding agent can work with it directly — no plugin, no export, no API glue. This vault ships with a `CLAUDE.md` in the root that teaches [Claude Code](https://claude.com/claude-code) the folder layout and conventions automatically.

## Setup (once)

```bash
cd path/to/this/vault
claude
```

That's genuinely it.

## Things to ask it

- **"Summarise my week"** — it reads the last 7 daily notes and gives you highlights + open loops. A weekly review draft for free.
- **"What are all my open todos, grouped by project?"** — greps every `- [ ]` across the vault.
- **"Draft an article from [[some idea note]]"** — expands a seed idea into a full draft, saved as a new linked note.
- **"What did I say about X last month?"** — semantic memory over your own diary.
- **"Create a project note for Y and backfill the log from my daily notes"** — retroactive organisation.

## Ground rules worth keeping

- Let it *read* everything, but tell it to only **append or create** notes, never rewrite your diary entries. (The bundled `CLAUDE.md` already says this.)
- Review what it creates like you'd review a PR. It's your second brain; the AI is a very fast intern in it.

## Other routes

- **Obsidian Local REST API plugin + an MCP server** — lets AI clients talk to Obsidian itself (respects the app's index, works while Obsidian is open).
- **In-app plugins** — Smart Connections, Copilot for Obsidian, Text Generator. Several support local models via Ollama, so this works fully offline with any model you like.
- **Any other agent/model** — the "point it at the folder" trick is model-agnostic. Plain text is the ultimate integration layer.
