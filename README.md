# Bunk Room Planner

An interactive 3D plan of a shared bunk room, built to test furniture arrangements
before moving anything physically.

**Live: https://ghbe0.github.io/room-planner/**

## The room

| | |
|---|---|
| Window wall (back wall) | 134″ — 11′ 2″ |
| Side wall (depth) | 176″ — 14′ 8″ |
| Ceiling | 96″ (assumed) |
| Window | 30″ wide × 77″ tall (6′ 5″) |
| Wall pier on the back wall | 30″ wide × 14″ deep, floor to ceiling, starting 26″ from the left wall |
| Built-in brown closet | bottom-left corner, built into the wall |
| Grey closets | 4 doors × 19″ |

Measurements of the back wall, side wall, window, wall pier and closet doors were taken
with a tape / the iPhone Measure app. Ceiling height, furniture sizes and the exact
horizontal position of the window are estimates.

## Using it

- **Drag an item** to move it along the floor
- **Drag the floor** to orbit
- **Two fingers** (or right-drag) to pan, **pinch** or scroll to zoom
- **R** or the Rotate button turns the selected piece 90°
- **Top view** switches to a plan view — the clearest way to judge a layout
- **Walls** toggles the walls off

Items turn **red** when they clash with each other, with the built-in closet, with the
wall pier, with the doorway, or with the gold zone in front of the window, which is the
space the casement needs to swing inward.

## The four presets

1. **As photographed** — the current arrangement
2. **Closets by the hallway** — both grey closets moved to the hallway end, a bunk against their fronts
3. **Open centre** — a bunk on each side wall, widest walking aisle
4. **Window nook** — everything pushed to the entry half, window end left as open floor

## Built with

Plain HTML and [three.js](https://threejs.org/) r128. No build step — `index.html` is the
whole application. Textures are generated procedurally on a canvas at load time, so there
are no image assets.
