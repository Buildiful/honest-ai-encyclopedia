# Honest AI Encyclopedia

This public repository serves as the knowledge base for the Honest AI encyclopedia layer on Buildiful.

## Structure

- `index.json` — the master alphabetical index used by the site
- `entries/` — one markdown file per encyclopedia entry

## Entry format

Each entry should:
- use a lowercase slug
- live at `entries/<slug>.md`
- begin with a top-level heading
- contain public-facing, human-reviewed content only

Example:
- `index.json` item:
  `{ "slug": "xylophone", "label": "xylophone" }`
- entry file:
  `entries/xylophone.md`

## Rules

- Add new entries manually
- Keep `index.json` alphabetized
- Keep slugs lowercase and stable
- Update `index.json` whenever a new entry is added

## Purpose

The Buildiful site reads from this repo to provide a curated encyclopedia experience with exact-match suggestions and public entry rendering.
