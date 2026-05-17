## Cursor Cloud specific instructions

This repository is a **GitHub Profile README** (`thecarinsiwa/thecarinsiwa`). It contains only static markdown files — no application code, no dependencies, no build system.

### Repository contents

- `README.md` — GitHub profile page with badges, tech stack, GitHub analytics, and contact info.
- `TECHNICAL_NOTE.md` — Documentation on modular architecture and REST API security best practices.

### Development workflow

- **Lint**: `markdownlint README.md TECHNICAL_NOTE.md` (installed globally via `npm install -g markdownlint-cli`). Existing files have known lint warnings (line length, inline HTML for badges) that are intentional for a GitHub profile README.
- **Preview**: `markdown-it <file>.md` renders markdown to HTML (installed globally via `npm install -g markdown-it`).
- **No build/test/run steps** — there is no application to start or automated test suite to execute.
