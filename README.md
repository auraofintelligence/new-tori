# Aura Torus Sandbox

<!-- github-organisation:start -->

## Project links and history

- First substantive build: 7 October 2025.
- GitHub repository: [new-tori](https://github.com/auraofintelligence/new-tori).
- Public site: [visit the public site](https://auraofintelligence.github.io/new-tori/).

## Related public projects

Each link below reflects an evidenced family, lineage or direct connection. This project has 7 relevant public connections.

### Aura interface, geometry and capture architecture

- [aura-components](https://github.com/auraofintelligence/aura-components) - [public page](https://auraofintelligence.github.io/aura-components/) - later build; aura-components is earlier, ordered build lineage, shared technical architecture.
- [aura-data-mapping](https://github.com/auraofintelligence/aura-data-mapping) - [public page](https://auraofintelligence.github.io/aura-data-mapping/) - earlier build; aura-data-mapping is later, ordered build lineage, shared technical architecture.
- [aura-horn-torus](https://github.com/auraofintelligence/aura-horn-torus) - [public page](https://auraofintelligence.github.io/aura-horn-torus/) - earlier build; aura-horn-torus is later, ordered build lineage, shared technical architecture.
- [aura-of-intelligence-web-app](https://github.com/auraofintelligence/aura-of-intelligence-web-app) - shared technical architecture.
- [aura-scan-pipeline](https://github.com/auraofintelligence/aura-scan-pipeline) - [public page](https://auraofintelligence.github.io/aura-scan-pipeline/) - shared technical architecture.
- [aura-spatial-perception](https://github.com/auraofintelligence/aura-spatial-perception) - [public page](https://auraofintelligence.github.io/aura-spatial-perception/) - earlier build; aura-spatial-perception is later, ordered build lineage, shared technical architecture.
- [aura-toy](https://github.com/auraofintelligence/aura-toy) - [public page](https://auraofintelligence.github.io/aura-toy/) - later build; aura-toy is earlier, ordered build lineage, shared technical architecture.

<!-- github-organisation:end -->

Aura Torus Sandbox is a compact Three.js experiment for arranging and
interacting with faceted torus rings in a web browser.

## Public page

- [Open the torus sandbox](https://auraofintelligence.github.io/new-tori/)

## What it does

- Renders the torus geometry as an interactive 3D scene.
- Supports orbit controls for rotating, zooming and inspecting the model.
- Provides screenshot, event-export and reset controls.
- Keeps the complete experiment in `index.html`.

The exported event log uses newline-delimited JSON (`.ndjson`). It records
interactions from the current browser session; it is not a shared data service.

## Open locally

The page imports Three.js as a browser module, so use a small local server:

```powershell
python -m http.server 4173
```

Then open `http://localhost:4173/`.

## Status and boundaries

This is a visual interaction sandbox, not the canonical Aura geometry model or
a finished design tool. Treat exported observations as experiment records, not
scientific measurements or automatic interpretations.

## Licence

See [LICENSE](LICENSE). This repository uses the Strange But True Public Source
Licence.
