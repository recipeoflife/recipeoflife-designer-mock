# Recipe of Life site mock handoff

This folder contains a local HTML/CSS mock for sharing redesign direction with a designer.

## First read

Open these files first:

1. `designer-guide.html`
2. `designer-brief.md`
3. `reference-copy-notes.md`

## Important rule

Do not rewrite the production copy.

The text from the existing STUDIO pages and CodePen references should remain the source of truth. The mock pages in this folder demonstrate layout, hierarchy, grouping, CTA placement, spacing, and visual direction. Some text in the mock was summarized by Codex for structural demonstration only.

`reference-copy-notes.md` stores those Codex-generated summary/copy ideas separately. Treat it as reference only, not approved production copy.

## Pages in this mock

- `index.html`: Top page mock. The top page should follow the original STUDIO structure, while improving text color, CTA, spacing, image balance, and readability.
- `about.html`: About information structure sample.
- `service.html`: Service information structure sample.
- `works.html`: Works index sample. Works should include small photos or banner areas, but the text structure remains the main focus.
- `works-villa.html`: Works detail / case study sample. This should follow the CodePen case-study layout direction.
- `designer-guide.html`: Browser-readable guide for the designer.
- `designer-brief.md`: Written handoff brief.
- `reference-copy-notes.md`: Codex-generated reference copy notes, not production copy.

## Design direction

- Text color: `#3a3a38` across all pages and sections.
- Avoid `#63676b`.
- Background: `#ffffff`, with `#f5f2e9` used for section contrast.
- Accent: `#b4a785` for buttons, lines, and small accents.
- Photos should support the text, not dominate it.
- Works / Works detail pages should not be photo-free, but photos or banners must remain small and secondary.
- Every page must end with a Contact CTA.

## Local preview

If serving locally:

```bash
python3 -m http.server 5173
```

Then open:

```text
http://localhost:5173/designer-guide.html
```

## Suggested review order

1. `designer-guide.html`
2. `index.html`
3. `service.html`
4. `works.html`
5. `works-villa.html`
6. `about.html`

