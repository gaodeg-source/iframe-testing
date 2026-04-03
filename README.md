# iframe-testing

Static pages (minimal chrome) for OLI Torus **Webpage** blocks.

## Pages

- `reflect4.html` — transaction sequencer
- `entity-diagram.html` — entity boundary diagram (standalone)
- `entity-diagram-prompts.html` — Stuff, Rights, and Promises + writing prompts
- `intro-activity.html` — introductory financial statements activity (3-step: match, trace, connect)
- `1st_activity.html` — balance sheet identity activity (5-step progressive comparison)
- `simplified-example.html` — ExampleCo articulation exercise (3-layer, standalone)
- `apple-example.html` — Apple FY2024 articulation exercise (links from simplified)

Shared: `shared.css`, `shared.js`, `config.js`

## GitHub Pages

Deploy from **`main`** / **`/(root)`**, then for example:

- `https://gaodeg-source.github.io/iframe-testing/reflect4.html`
- `https://gaodeg-source.github.io/iframe-testing/entity-diagram.html`
- `https://gaodeg-source.github.io/iframe-testing/entity-diagram-prompts.html`
- `https://gaodeg-source.github.io/iframe-testing/homework.html`
- `https://gaodeg-source.github.io/iframe-testing/intro-activity.html`
- `https://gaodeg-source.github.io/iframe-testing/1st_activity.html`
- `https://gaodeg-source.github.io/iframe-testing/simplified-example.html`
- `https://gaodeg-source.github.io/iframe-testing/apple-example.html`
- Rick's original design: `https://gaodeg-source.github.io/iframe-testing/reflect4_rick.html`

## Update

Copy updated files from your prototype and push to `main`.

**Note:** For a second Torus **Webpage** block, point it at `entity-diagram-prompts.html` if you want prompts on a separate course page. Prompt answers use the same `localStorage` key as before (`prework_reflect_entity`) only when both pages are served from the **same origin** (same GitHub Pages site).
