# Graphic Launch Visuals

Use this for poster-like launch graphics, campaign cards, social tiles, product story visuals, editorial hero modules, and image-led marketing systems with Swiss/brutalist/UI-collage energy.

## Core Feel

The visual should feel designed like a sharp poster, not a SaaS card.

- Hard rectangles, labels, arrows, tags, and overprinted text blocks.
- High contrast black/white with one signal accent, often red or orange.
- Cropped frames, offset layers, and deliberate overlaps.
- Bitmap, dither, halftone, particle, contour, or low-res texture systems.
- Small UI-like labels that feel functional, not decorative.
- One bold message, supported by one visual system.

## When To Use

Use for:

- Product launch cards.
- Social announcement graphics.
- Brand campaign panels.
- Creator/art/music/fashion/tool visuals.
- Hero graphics that need a strong editorial point of view.
- Feature cards where the visual language is part of the brand.

Do not use for:

- Operational dashboards.
- Plain SaaS homepages that need product clarity first.
- Accessibility-critical app UI.
- Dense documentation pages.

## Composition Patterns

Strong patterns:

- Light poster: white/off-white field, black headline blocks, one red label, pale construction lines, small image tile.
- Dark gallery: black field, thin perspective grid, stacked image frames, red bracket/corner accent, monospace status tag.
- Soft abstract card: warm or cool color field, blurred organic form, tiny utility label, one large calm line of type.
- Particle object card: black card with dotted/halftone object cropped from the bottom or side.
- Topographic field: blurred image/color base with subtle contour lines and a centered wordmark or label.

Avoid centered headline + icon + generic gradient. The power comes from composition and texture.

## Typography

- Pair clean sans with monospace labels.
- Large type can be used, but keep it graphic and intentional.
- Use boxed text when the box is part of the composition.
- Use tiny labels sparingly: status, category, direction, file, tag, or system state.
- Do not use heavy weight everywhere; contrast comes from block, scale, and placement.
- Keep copy short enough to read instantly.

## Texture And Visual Systems

Good systems:

- Halftone/dither image treatments.
- Particle silhouettes.
- Thin perspective grids.
- Contour/topographic line overlays.
- Low-res or pixelated image crops.
- Red bracket corners, underline rules, and directional arrows.
- Layered gray construction rectangles.

Rules:

- Pick one texture system per visual.
- Keep the texture subordinate to the message.
- Let accents mark structure: underline, bracket, tag, active word, or action.
- Use blur only as material, not as random decoration.

## Color

Reliable palettes:

- White, black, warm gray, signal red.
- Black, white, red, muted image color.
- Peach field with orange/yellow blurred form.
- Sky/green field with subtle contour lines.
- Black card with pale blue/pink particles and small red signals.

Keep palettes sparse. The image/texture can add nuance; UI colors should stay disciplined.

## Implementation Notes

For web/CSS/SVG:

- Use `aspect-ratio` for stable poster cards.
- Use CSS grid and absolute layers for overlaps.
- Use SVG patterns for halftone, dither dots, contour lines, and perspective grids.
- Use masks or `clip-path` for cropped objects.
- Keep real text code-native unless the visual is generated as a bitmap asset.
- Make sure labels remain readable at thumbnail size.

## QA

Before shipping:

- Is there one clear message?
- Does the composition feel intentionally art-directed?
- Are labels functional, not random?
- Is there one texture language, not many?
- Does the accent color have a job?
- Would this still look strong as a square social tile?
