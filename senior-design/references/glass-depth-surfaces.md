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

## Subtle Card Depth Recipe

Use this for premium dark cards, beta-access panels, command surfaces, modal-like CTAs, and focused hero cards.

- Surface: near-background fill, only `3-8%` lighter or darker than the page.
- Border: `1px` low-contrast stroke, usually `rgba(255,255,255,.10-.18)` on dark or `rgba(0,0,0,.08-.14)` on light.
- Inner highlight: optional `inset 0 1px 0 rgba(255,255,255,.06-.12)` on dark surfaces.
- Shadow: broad and soft, not a hard drop shadow. Example: `0 24px 80px rgba(0,0,0,.28)`.
- Radius: modest and mature. Use `14-22px` for large cards; avoid bubbly radii.
- Text: keep the headline calm and centered only when the card is a focused CTA.
- Buttons: one filled primary, one quiet secondary. Do not turn every link into a button.

Example dark card:

```css
.premium-card {
  background: rgba(255,255,255,.045);
  border: 1px solid rgba(255,255,255,.14);
  border-radius: 18px;
  box-shadow:
    inset 0 1px 0 rgba(255,255,255,.08),
    0 28px 90px rgba(0,0,0,.32);
}
```

Avoid:

- Large blurred backgrounds that hurt performance.
- Text over highly varied imagery.
- Multiple stacked glass panels with no hierarchy.
- Purple-blue glow as the whole design language.
- Heavy black shadows that make cards look pasted on.
- High-contrast borders that outline every container equally.

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
