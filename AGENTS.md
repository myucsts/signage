# Repository Guidelines

## Project Structure & Module Organization
- `src/` contains the single-page dashboard entry point at `src/index.html`.
- There are no `tests/` or `assets/` directories yet. If you add them, document new paths in `README.md` and keep the layout simple.

## Build, Test, and Development Commands
- No build, test, or dev commands are defined. Open `src/index.html` directly in a browser to run the app.
- If you introduce tooling (for example `package.json` or `Makefile`), document the exact commands and their purpose here (e.g., `npm run dev` for local server).

## Coding Style & Naming Conventions
- Use consistent indentation (2 spaces for HTML/CSS/JS in this repo).
- Keep JavaScript in modern ES6+ style, with `camelCase` for variables and functions.
- Prefer descriptive IDs and class names that map to UI sections (e.g., `news-list`, `quake-list`).
- If you add a formatter or linter, include configuration files and document the command (e.g., `npx prettier --write src/index.html`).

## Testing Guidelines
- No tests are set up. If you add tests, place them under `tests/` and document naming (e.g., `*.spec.js`) and how to run them.

## Commit & Pull Request Guidelines
- Use clear, imperative commit messages (e.g., "Add info dashboard page").
- PRs should include a brief summary, scope of changes, and screenshots for UI updates. Link related issues when applicable.

## Agent-Specific Instructions
- Follow this `AGENTS.md` when changing structure, commands, or conventions.
