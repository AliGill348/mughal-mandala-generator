# Mughal Mandala Generator

A generative art tool built with **p5.js** (JavaScript + Canvas API). Every seed produces a unique, reproducible mandala inspired by Mughal geometry (lotus petals, pointed arches, star patterns), rendered with a layered, embossed metallic look.

## Features

- Seeded randomness: the same seed always gives the same design
- Weighted traits for rarity: 5 colour palettes, 4 symmetry levels, 3 motifs, 3 string-art web densities, 3 finishes (Standard, Gold Foil, Eclipse) and a rare glow effect
- Pseudo-3D rendering with gradients, bevels, drop shadows and glossy beads, all done with the Canvas 2D API
- Export a 1000x1000 PNG and a metadata JSON (traits) for any seed

## Run it

Open `index.html` in a browser (needs internet for the p5.js CDN), or paste `sketch.js` into the [p5.js web editor](https://editor.p5js.org).

## Controls

| Key | Action |
| --- | --- |
| N | Next seed |
| B | Previous seed |
| S | Save PNG |
| J | Save metadata JSON |

## Tech

JavaScript (ES6), p5.js 2.x, HTML5 Canvas

## Samples

Add some of your exported PNGs to an `images/` folder and show them here:

```md
![Seed 1](images/mughal-001.png)
```
