# AGENTS.md / CLAUDE.md

Guidance for Codex and Claude Code in this Jekyll site. Keep this file byte-identical at the repo root.

## Project Context

This is a GitHub Pages / Jekyll site. Source content lives in Markdown collections and site config; `_site/` and `.jekyll-cache/` are generated output.

## Workflow

- Edit source Markdown, layouts, includes, assets, and `_config.yml`; do not edit `_site/` directly.
- Follow existing collection naming conventions for posts, pages, publications, and assets.
- Run the smallest relevant Jekyll/build check available in the repo before reporting completion.

## Context Hygiene

- Do not intentionally read generated `_site/`, `.jekyll-cache/`, bundle/vendor output, or secret files unless debugging the generated site.
- Treat `.claudeignore` as the shared exclusion list for Claude and as Codex guidance; Codex has no stable `.codexignore` equivalent in this setup.
