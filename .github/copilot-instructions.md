# Copilot / AI Agent Instructions for css-rescue

This repository is a minimal static site: a single `index.html` and `style.css`. The guidance below focuses on the concrete, discoverable patterns an AI coding agent needs to be productive here.

**Big Picture:**
- **Type:** Static single-page site (no build system, no package manifests).
- **Files of interest:** `index.html` (markup) and `style.css` (all styling and design tokens).
- **Primary flow:** `index.html` loads `style.css` and the browser renders the page. There are no server-side components or third-party integrations.

**Notable, discoverable patterns:**
- CSS uses a centralized variables block in `:root` for all colors and tokens. Example variables: `--duck-color-body`, `--water-color-medium`.
- The CSS file includes Dutch comment headers (e.g. `/* ===== EEND ===== */`, `/* ===== ACHTERGROND LAND ===== */`) that group related tokens — preserve these when editing for readability.
- The stylesheet is linked in the repository with `<link rel="stylesheet" href="style.css">` placed immediately after the `</head>` tag (before `<body>`). When modifying markup, keep awareness of this placement.
- Layout sizing is explicit: `main` has `min-height: 800px` and `max-width: 800px`; `margin-top: 100px`. Visual changes often involve adjusting these values.

**Developer workflows (concrete commands):**
- Quick preview in default macOS browser: `open index.html`
- Lightweight local server (recommended for relative-path testing): `python3 -m http.server 8000` then visit `http://localhost:8000`
- If you prefer an npm-based static server: install and run `npx serve` or `npx live-server` (not required by the project).
- There are no tests or CI configuration present in the repo; do not search for test folders.

**Project-specific editing guidance (what to change where):**
- To change colors or theme: edit the `:root` variables at the top of `style.css` (e.g. `--duck-color-body`). This is the single place that controls palette values.
- To change content or headings: edit `index.html` (the `<header><h1>` contains the title `Hugo the duck`).
- To adjust page sizing or centering: edit rules under `main` in `style.css` (e.g. `min-height`, `max-width`, `margin-top`).

**Conventions to follow:**
- Preserve the CSS variable names and grouping comments — they are the canonical tokens for this project.
- Keep edits minimal and focused: this repo is intentionally small; large refactors should be discussed first.

**Integration points & dependencies:**
- None detected. There is no `package.json`, build pipeline, or external API usage in the repository.

**When merging/updating this file:**
- If an existing `.github/copilot-instructions.md` exists, merge by keeping any project-specific notes and append the `:root` and markup examples shown above.

If anything here is incorrect or you want additional guidance (e.g., preferred CSS style rules, target browsers, or adding a local dev server script), tell me what to include and I will update this file.
