# iframe-testing

Static pages (minimal chrome) for OLI Torus **Webpage** blocks.

## Pages

### Root
- `intro-activity.html` — introductory financial statements activity (3-step: match, trace, connect)
- `1st_activity.html` — balance sheet identity activity (5-step progressive comparison)
- `simplified-example.html` — ExampleCo articulation exercise (3-layer, standalone; links to apple/)
- `homework.html` — Homework I
### two-snapshots/
- `two-snapshots1.html` — The Balance Sheet as a Snapshot (activity: Snapshot or Explanation?)
- `two-snapshots2.html` — What Changed Between the Two Dates (activities: Which Statement Explains the Change?, drag-and-drop)
- `two-snapshots3.html` — Recognition, Classification, and Quantification (accordion)
- `three-flow-statements.html` — Three Flow Statements reading page with end-of-page match activity

### apple/
- `apple-example.html` — Apple FY2024 articulation exercise (links back to simplified-example.html)
- `apple-fy25-q3-p1.png`, `apple-fy25-q3-p2.png`, `apple-fy25-q3-p3.png` — source PDF pages

### entity-diagram/
- `entity-diagram.html` — entity boundary diagram (standalone)
- `entity-diagram-prompts.html` — Stuff, Rights, and Promises + writing prompts

### reflect4/
- `reflect4.html` — transaction sequencer
- `reflect4_rick.html` — Rick's original design variant

Shared: `shared.css`, `shared.js`, `config.js`

## GitHub Pages

Deploy from **`main`** / **`/(root)`**, then for example:

- `https://gaodeg-source.github.io/iframe-testing/intro-activity.html`
- `https://gaodeg-source.github.io/iframe-testing/two-snapshots/two-snapshots1.html`
- `https://gaodeg-source.github.io/iframe-testing/two-snapshots/two-snapshots2.html`
- `https://gaodeg-source.github.io/iframe-testing/two-snapshots/two-snapshots3.html`
- `https://gaodeg-source.github.io/iframe-testing/three-flow-statements.html`
- `https://gaodeg-source.github.io/iframe-testing/simplified-example.html`
- `https://gaodeg-source.github.io/iframe-testing/apple/apple-example.html`
- `https://gaodeg-source.github.io/iframe-testing/entity-diagram/entity-diagram.html`
- `https://gaodeg-source.github.io/iframe-testing/entity-diagram/entity-diagram-prompts.html`
- `https://gaodeg-source.github.io/iframe-testing/reflect4/reflect4.html`
- `https://gaodeg-source.github.io/iframe-testing/reflect4/reflect4_rick.html`

## Update

Copy updated files from your prototype and push to `main`.

**Note:** For a second Torus **Webpage** block, point it at `entity-diagram/entity-diagram-prompts.html` if you want prompts on a separate course page. Prompt answers use the same `localStorage` key as before (`prework_reflect_entity`) only when both pages are served from the **same origin** (same GitHub Pages site).
