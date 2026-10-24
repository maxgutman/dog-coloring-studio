# Dog Coloring Studio

A browser-based prototype: paint a side-view dog and see the colors on an animated 3D character.

## Features

- Live mirrored 2D-to-3D painting
- Brush palette, custom colors, eraser, undo and rainbow example
- Idle, walk, investigate and playful animations
- Download the coloring page or paint texture
- No artwork uploads or server storage; artwork remains in page memory until downloaded

## Run

Open `index.html` in a modern browser with WebGL. Internet access is required to load Three.js from unpkg.com. For GitHub Pages, serve the repository root from the deployment branch.

## Asset ownership

The embedded dog originates from the IT Happy animal pack supplied by the project owner. The third-party model remains subject to its original license; this repository does not grant rights to extract or redistribute it. Application code and third-party asset licensing are separate. No blanket open-source license is applied to the embedded asset.

## Prototype limits

Coloring uses side-projection UVs mirrored to both sides, with stretching possible on the back and belly. Eyes, nose, mouth and collar remain separate. The animations are prototypes, not a complete Unreal AI system. Paper scanning is not included.
