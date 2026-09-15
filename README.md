# Room 202

Interactive 3D plan of a shared bedroom, built to test furniture arrangements before
moving anything physically.

**Live: https://ghbe0.github.io/room-202/**

## The room is not a rectangle

| | |
|---|---|
| Back wall (window wall), corner to corner | 132″ — 11′ 0″ |
| Main room width, once the right wall steps back in | 108″ — 9′ 0″ |
| Depth | 176″ — 14′ 8″ |
| Alcove — right wall steps out near the window | 24″ out × 32″ along the wall |
| Pier projecting off the back wall | 30″ wide × 14″ deep, floor to ceiling, 26″ from the left wall |
| Window | 30″ wide × 77″ tall (6′ 5″) |
| Grey closet doors | 4 × 19″ |
| Gap between the left-wall bed and the built-in closet | 27″ |

The depth closes on its own measurements:
`14″ pier + 37″ bed + 18″ nightstand + 80″ bed + 27″ gap = 176″`

Estimated, not measured: ceiling height (96″), the window's exact position along the back
wall, and individual furniture sizes.

## What's in the room

Two bunk beds, two nightstands, two grey 2-door closets, the built-in brown closet running
the full entry wall to the hallway, and a folding tripod stool. The desk is an addition
being tested — there isn't one in the room today.

## Using it

- **Drag an item** to move it along the floor
- **Drag the floor** to orbit · **two fingers** to pan · **pinch** or scroll to zoom
- **R** or the Rotate button turns the selected piece 90°
- **Top view** gives a plan view — the clearest way to judge a layout
- **Walls** toggles the walls off

Items turn **red** when they clash with each other, run into the pier, leave the room
(including reaching right of the alcove), block the doorway, block the window's inward
swing, or stand in the door swing of the built-in or either grey closet. The grey closets
carry their 24″ swing zone with them as you drag.

## Layouts

1. **As photographed** — the room as it stands, no desk
2. **Desk by the built-in** — nightstand moves into the alcove, desk slots into the 23″
   strip beside the left-wall bed and runs down to the built-in
3. **Beds apart** — the left-wall bed crosses to the right wall, closets take the left wall

## On desk size

At 9 ft wide the room is tight. With both closets' door swings respected, the largest desk
that fits anywhere is **42″ × 22″**, turned sideways. A standard 48″ desk does not fit.

## Built with

Plain HTML and [three.js](https://threejs.org/) r128. No build step — `index.html` is the
whole application, and every texture is drawn procedurally on a canvas at load, so there
are no image assets.
