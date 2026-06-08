# Changelog

All notable changes to the Dark Knight theme are documented here.
This project follows [Semantic Versioning](https://semver.org/).

## [1.1.4] — 2026-06-08

### Changed
- **Pane / sidebar resize handles** now use a dimmed, end-fading gold gradient
  that's identical on both sides, instead of the solid accent-gold Obsidian
  applies by default (which read as too strong and asymmetric left vs. right).
- **Horizontal rules** keep their top spacing but hug the box that follows them
  (`margin: 1.8em 0 0.6em`), so the line reads as belonging to the content below.

## [1.1.3] — 2026-06-08

### Fixed
- **Settings toggle switches no longer break** (#4). Checkbox styling was
  applied globally and overlaid a box on Obsidian's toggle switches, which use
  a hidden `<input>` inside `.checkbox-container`. Checkbox styling is now
  scoped to Markdown task lists (`.markdown-preview-view` / `.markdown-source-view`),
  with an explicit guard restoring native appearance for toggle inputs.
- **No more underlines between code-block lines** (#5). In Live Preview the
  `.HyperMD-codeblock-bg` element is applied per line, so a `1px` border drew a
  box around every line. The border now lives only on the Reading-view `<pre>`;
  Live-Preview lines get the background without a per-line border.

## [1.1.0] — 2026-06-08

### Added
- **Full light-mode parity** ("Gotham at dawn"). Structural CSS is now driven
  by palette tokens via `:is(.theme-dark, .theme-light)`, so the light variant
  gets the same gold heading rules, signal blockquotes, styled tables,
  callouts, scrollbars, and tags as dark — not just recolored defaults.
- New `--dk-*-rgb` tokens so glows, backgrounds, and callouts resolve to the
  correct accent color in each mode.
- Styling for the Properties / metadata editor, search results, and Canvas.
- Coverage for the Dataview and Tasks community plugins.
- Keyboard `:focus-visible` rings for accessible navigation.

### Changed
- Lifted faint and code-comment text contrast toward WCAG AA on Gotham black.
- `mod-cta` buttons and checkbox markers now use a contrast-aware
  `--text-on-accent` color, so gold buttons stay readable in light mode.

## [1.0.2] and earlier

- Initial Gotham-noir dark theme with light variant, core-plugin support,
  callouts, graph view, and code syntax highlighting.

[1.1.4]: https://github.com/jabaho9523/DarkKnightTheme/releases/tag/1.1.4
[1.1.3]: https://github.com/jabaho9523/DarkKnightTheme/releases/tag/1.1.3
[1.1.0]: https://github.com/jabaho9523/DarkKnightTheme/releases/tag/1.1.0
