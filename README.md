# Imperium

A grimdark gothic theme for [Obsidian](https://obsidian.md): blackened iron, gilded brass, crimson wax and old vellum. It was made for long-form study notes, with extra touches for law and case-brief notes.

![Imperium, dark mode: home dashboard](screenshots/dark-home.png)

## Features

- **Two modes.** *Night* (dark) and *Parchment* (light).
- **FIRAC case briefs.** In a note with `## Facts`, `## Issue`, `## Rule`, `## Application` and `## Conclusion` headings, those headings are numbered I–V and the note gets a "Case File" header.
- **Verbatim Text vellum slabs.** A `## Verbatim Text` section (and any `[!quote]` callout) is set on a vellum slab with a wax seal. The note header reads "Lex Scripta".
- **Wax seals.** Seals hang from title cards, close out notes and mark `[!warning]` callouts.
- **Hazard to-dos.** `[!todo]` callouts get hazard-striped borders.
- **Dataview readouts.** Dataview lists and tables are styled as auto-indexed readouts in a monospaced terminal face.
- **Ornamental dividers.** `---` becomes a gilded rule with a centred cross.
- **Record-style inline title.** Notes that open with `# Title` show the inline title as a small record header, so the title doesn't appear twice.
- **Sidebar icons.** Folders named `Cases`, `Statutes`, `Notes`, `Literature`, `templates` and `Archive` get icons such as scales, scroll, quill, book, cog and skull.
- **Gothic type throughout.** Cinzel and UnifrakturMaguntia for headings, EB Garamond for body text, Share Tech Mono for code and readouts.

Section-aware styling (FIRAC numbering, Verbatim Text slabs) uses Reading View. Live Preview gets the palette, type, callouts and headings.

## Screenshots

| Dark (Night) | Light (Parchment) |
| --- | --- |
| ![Dark: home](screenshots/dark-home.png) | ![Light: home](screenshots/light-home.png) |
| ![Dark: case brief](screenshots/dark-case-brief.png) | ![Light: case brief](screenshots/light-case-brief.png) |
| ![Dark: statute note](screenshots/dark-statute.png) | ![Light: statute note](screenshots/light-statute.png) |

## Installation

**From Obsidian:** Settings → Appearance → Themes → Manage → search for **Imperium** → Install and use.

**Manually:** copy `theme.css` and `manifest.json` into `<your vault>/.obsidian/themes/Imperium/`, then pick Imperium under Settings → Appearance.

## Privacy and network access

Imperium makes **no network requests**. All fonts are embedded in `theme.css` as base64 WOFF2, and all icons are inline SVG data URIs. The only `http` strings in the file are SVG `xmlns` namespace identifiers, which are never fetched.

## Font credits

Imperium embeds these fonts. Each is licensed under the [SIL Open Font License, Version 1.1](https://openfontlicense.org):

| Font | Designer |
| --- | --- |
| Cinzel | Natanael Gama |
| Cinzel Decorative | Natanael Gama |
| UnifrakturMaguntia | J. "Mach" Wust |
| EB Garamond | Georg Duffner, Octavio Pardo |
| Share Tech Mono | Carrois Apostrophe |

The OFL allows these fonts to be bundled and redistributed with software as long as they aren't sold on their own. The fonts stay under the OFL; the MIT license below doesn't cover them.

## License

Theme code: [MIT](LICENSE) © 2026 Leo Lloyd A. Catalan.
Embedded fonts: SIL Open Font License 1.1 (see above).
