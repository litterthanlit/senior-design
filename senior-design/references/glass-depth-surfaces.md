# Glass And Depth Surfaces

Use this for glass, blur, frosted panels, translucent surfaces, soft depth, atmospheric product pages, and layered UI.

## Core Feel

Glass should create hierarchy and focus. It should not be a default decoration.

- Use blur only when something meaningful sits behind it.
- Use translucency to separate layers, not to hide weak layout.
- Combine blur with border, tint, and shadow so edges remain legible.
- Keep text contrast high.
- Use depth to clarify foreground, background, and active surfaces.

## Good Uses

- Floating command palette over content.
- Payment or login card over a soft background.
- Media controls over imagery.
- Inspector or popover over canvas.
- Status panel over map or gradient material.
- Modal or sheet where background context should remain visible.

## Material Recipe

Start with:

- Slightly transparent surface.
- Low-contrast border.
- Small shadow or ambient elevation.
- Local blur, not full-screen blur.
- Optional noise texture to avoid plastic smoothness.

Avoid:

- Large blurred backgrounds that hurt performance.
- Text over highly varied imagery.
- Multiple stacked glass panels with no hierarchy.
- Purple-blue glow as the whole design language.

## Layout Rules

- Keep glass panels smaller than the surface behind them.
- Use glass for overlays, controls, and focused cards.
- Use solid panels for dense forms, tables, and long reading.
- Maintain visible focus and hover states.
- Respect reduced transparency if the platform or design system supports it.

## QA

- Is every glass surface serving a hierarchy purpose?
- Is text readable on every background?
- Does blur stay performant?
- Are focus states visible?
- Would a solid surface work better?
