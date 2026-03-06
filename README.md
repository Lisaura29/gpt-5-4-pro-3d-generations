# GPT-5.4-Pro Extended HTML Generations

A small collection of self-contained interactive HTML scenes generated with GPT-5.4-Pro Extended.

Each example includes:

- a standalone `.html` file in [`generations/`](./generations/)
- the exact prompt used to generate it

## Examples

| Example | HTML | Prompt | Highlights |
|---|---|---|---|
| Ancient Athens: Acropolis | [`generations/ancient-athens-acropolis.html`](./generations/ancient-athens-acropolis.html) | [`prompts/ancient-athens-acropolis.md`](./prompts/ancient-athens-acropolis.md) | Parthenon, rock plateau, olive trees, time-of-day controls |
| Golden Gate Bay Atmosphere | [`generations/golden-gate-bay.html`](./generations/golden-gate-bay.html) | [`prompts/golden-gate-bay.md`](./prompts/golden-gate-bay.md) | Weather presets, fog bank, traffic, waves, whales, comet |
| Angkor Wat at Sunrise | [`generations/angkor-wat-sunrise.html`](./generations/angkor-wat-sunrise.html) | [`prompts/angkor-wat-sunrise.md`](./prompts/angkor-wat-sunrise.md) | Reflection pools, sunrise silhouette, mist, Khmer architecture |
| Petra Treasury: Al-Khazneh | [`generations/petra-treasury-al-khazneh.html`](./generations/petra-treasury-al-khazneh.html) | [`prompts/petra-treasury-al-khazneh.md`](./prompts/petra-treasury-al-khazneh.md) | Rose-red sandstone facade, plaza view, time-of-day controls |
| Ancient Roman City Centre | [`generations/ancient-roman-city-centre.html`](./generations/ancient-roman-city-centre.html) | [`prompts/ancient-roman-city-centre.md`](./prompts/ancient-roman-city-centre.md) | Procedural voxel city, Colosseum centerpiece, roads, terrain |

## Viewing

Open any file in [`generations/`](./generations/) in a modern browser to explore the scene locally. No build step is required.

## Repository Layout

```text
.
├── generations/
│   └── *.html
└── prompts/
    └── *.md
```

The [`generations/`](./generations/) folder contains the runnable scenes. The [`prompts/`](./prompts/) folder contains the matching generation prompts.
