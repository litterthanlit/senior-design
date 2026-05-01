# Editor And Canvas UI

Use this for editor interfaces, canvas tools, productivity workspaces, builders, design tools, command surfaces, inspectors, sidebars, layers, exports, and visual workspaces.

## Core Feel

Editor UI should put the work surface first. Chrome supports the work; it should not dominate it.

- Canvas or document area is the primary surface.
- Toolbars are compact and predictable.
- Inspectors and sidebars use dense but readable controls.
- Selection state is explicit: handles, outlines, active layers, focus rings.
- Export and handoff states feel production-ready.

## Surface Anatomy

Useful regions:

- Top bar: file name, mode, share/export, status.
- Left rail: tools, pages, layers, assets, sources.
- Canvas: grid, artboard, nodes, frames, selected objects.
- Right inspector: properties, variants, constraints, history.
- Bottom/status bar: zoom, cursor, sync, comments, output state.
- Command menu: search, actions, recent commands.

## Visual Rules

- Keep chrome typography small but intentional.
- Use grid lines and handles lightly.
- Use consistent icon size, stroke, and hit areas.
- Separate panels with low-contrast borders.
- Use cards only for objects or repeated assets.
- Do not turn every surface into a floating glass panel.

## Product Proof

Show real tool behavior:

- Selected object with handles.
- Layer stack with active row.
- Export list or output formats.
- Comment or review state.
- Canvas zoom level.
- Drag target, constraint line, or connector.
- Empty state with one clear action.

## Implementation Notes

- Build real controls where the user can interact.
- Use stable dimensions for toolbars, sidebars, grids, and artboards.
- Do not animate layout while users manipulate objects.
- Preserve keyboard and focus behavior with accessible primitives.

## QA

- Is the canvas/work surface the hero?
- Can a user identify the selected state?
- Is chrome dense but not cramped?
- Do controls look real enough to use?
- Does responsive collapse preserve the main task?
