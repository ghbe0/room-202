# Room 202

Interactive 3D plan of a shared bedroom, built to test furniture arrangements before
moving anything physically.

**Live: https://ghbe0.github.io/room-202/**

## Measured

| | |
|---|---|
| Back wall (window wall) | 134″ — 11′ 2″ |
| Side wall (depth) | 176″ — 14′ 8″ |
| Window | 30″ wide × 77″ tall (6′ 5″) |
| Pier on the back wall | 30″ wide × 14″ deep, floor to ceiling, 26″ from the left wall |
| Grey closet doors | 4 × 19″ |
| Gap between the left-wall bed and the built-in closet | 27″ |

The depth closes on its own measurements:
`14″ pier + 37″ bed + 18″ nightstand + 80″ bed + 27″ gap = 176″`

Estimated, not measured: ceiling height (96″), the window's horizontal position along the
back wall, and individual furniture sizes.

## What's in the room

Two bunk beds, two nightstands, two grey 2-door closets, the built-in brown closet running
the full width of the entry wall to the hallway, and a folding tripod stool. The desk is an
addition being tested, not something already there.

## Using it

- **Drag an item** to move it along the floor
- **Drag the floor** to orbit · **two fingers** to pan · **pinch** or scroll to zoom
- **R** or the Rotate button turns the selected piece 90°
- **Top view** gives a plan view — the clearest way to judge a layout
- **Walls** toggles the walls off

Items turn **red** when they clash with each other, run into the wall pier, block the
doorway, block the window's inward swing, or stand in the door swing of either the built-in
closet or a grey closet. The grey closets carry their swing zone with them as you drag.

## The four layouts

1. **As photographed** — the room as it stands
2. **Closets by the hallway** — grey closets slide south, freeing the window half
3. **Beds apart** — beds on opposite walls, closets cross to the left
4. **Window end clear** — both beds in the lower half, window end left as open floor

## Built with

Plain HTML and [three.js](https://threejs.org/) r128. No build step — `index.html` is the
whole application, and every texture is drawn procedurally on a canvas at load time, so
there are no image assets.
