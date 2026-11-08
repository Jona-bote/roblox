# This is an Obsidian vault

You are working inside a personal Obsidian vault. Everything is plain markdown with `[[wikilinks]]`.

## Layout

- `00-daily/YYYY-MM-DD.md` — daily notes: diary entries, todos (`- [ ]`), scratch thoughts. The primary source of truth for "what happened when".
- `10-projects/` — one note per active project.
- `20-ideas/` — one note per idea (articles, apps, anything). Frontmatter `status:` is `seed`, `growing`, or `done`.
- `30-reference/` — durable reference material.
- `templates/` — note templates (core Templates plugin syntax: `{{date}}`, `{{time}}`, `{{title}}`).
- `onboarding/`, `tips/`, `ai/` — the starter vault's built-in documentation. Leave these alone unless asked.

## Conventions

- Link with `[[Note Name]]` (no path, no extension). Prefer adding links over moving files.
- Open todos are `- [ ]` anywhere in the vault, most often in daily notes. Completed is `- [x]`.
- Never edit `.obsidian/` unless explicitly asked.
- When summarising a period (a week, a month), read the matching `00-daily/` notes by filename date.
- When asked to capture something new, create it in the right folder using the matching template from `templates/`.
- Keep the user's voice in diary-like content; don't rewrite their daily notes, only append or extract.

## Useful tasks this vault expects from you

- "Summarise my week" → read the last 7 daily notes, produce highlights + open loops.
- "What are my open todos?" → grep `- [ ]` across the vault, group by file.
- "Draft an article from [[some idea]]" → expand the idea note into a draft in `20-ideas/` (new note, link back).
- "Weekly review" → follow the structure in `templates/weekly review.md`.
