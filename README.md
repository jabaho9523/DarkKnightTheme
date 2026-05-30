# Gotham Noir — an Obsidian theme

A city-at-night theme for [Obsidian](https://obsidian.md). Deep blacks, signal
gold, and steel-blue accents, with a noir red reserved for errors and
unresolved links.

## Palette

| Token             | Hex       | Used for                                  |
| ----------------- | --------- | ----------------------------------------- |
| Midnight Black    | `#0a0a0c` | Primary background                        |
| Night Sky         | `#14141a` | Secondary surfaces, modals, tab strip     |
| Asphalt           | `#1c1c24` | Inputs, buttons, embedded blocks          |
| Steel             | `#2a2a35` | Borders, dividers                         |
| Signal Gold       | `#f5c518` | Accent, headings, links, active states    |
| Steel Blue        | `#4a6b8a` | Secondary accent, italic, code functions  |
| Noir Red          | `#c8252c` | Errors, unresolved links, danger          |
| Patina Green      | `#4a8b4a` | Success, strings in code                  |

H1–H3 use the gold gradient; H4–H6 fall back to steel blue and fog so heading
hierarchy stays legible at a glance.

## Install

### Manually

1. Copy this folder into your vault at `<vault>/.obsidian/themes/Gotham Noir/`
   — the folder must contain `manifest.json` and `theme.css`.
2. In Obsidian: **Settings → Appearance → Themes → Gotham Noir**.

### From the community directory

Not yet listed. PRs welcome.

## Compatible with

- Obsidian 1.4+
- Default core plugins (Graph, Outline, Tags, Search, Bookmarks)
- Light mode included (the city at dawn — softened cream + gold)

## Notes

- Headings, links, tags, and the active tab are picked out in signal gold.
- Code blocks use a near-black background with gold keywords and green strings.
- Blockquotes get a gold left bar and a faint glow — the "signal" motif.
- Noir red is reserved for unresolved links and destructive actions, so it
  stays meaningful when you see it.
