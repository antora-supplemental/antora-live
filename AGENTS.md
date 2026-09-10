# Agent notes — antora-live

## Product posture

- **This repo** is the home for Antora Live: a DB-backed concurrent authoring layer beside static Antora generate.
- **Not** a fork of Antora core. **Not** an expansion of `@antora-supplemental/page-edit` (that package only bakes VCS View | Edit links).
- Publish / generate remains git + Antora (Facto stack). Live holds drafts, CRDT ops, presence, and permissions.
- Editor v1 is **AsciiDoc source + preview**, not Confluence-style WYSIWYG over published HTML.

## Canonical docs

- Long design: this component (`docs/`) — Design, Data model, Phases.
- Short hub link for PRs: `docs.antora-supplemental.org` page **Live docs** (`live-docs.adoc` in `antora-supplemental/docs`).
- Related: Site rebuild v1/v2, `@antora-supplemental/serve`, `@antora-supplemental/incremental`.

## Status

Design filing (P0) only until Phases say otherwise. Do not invent a second public Antora site for this product — wire into the org docs hub.
