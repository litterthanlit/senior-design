# Moodboard Analysis Workflow

Use this when the user provides a moodboard, Cosmos collection, screenshots, visual references, or asks to expand the skill's taste from references.

## Goal

Extract reusable design principles. Do not copy exact images, brands, layouts, text, or artwork.

## Analysis Pass

For each reference or visible group, identify:

- Product category: SaaS site, app screen, editor, checkout, icon system, dashboard, component card.
- Hierarchy: what reads first, second, third.
- Density: sparse, medium, dense, or tool-like.
- Typography: display/body relationship, scale, weight, rhythm.
- Color/material: white, dark, glass, soft neutral, saturated accent, photo-led.
- Interaction surface: form, card, toolbar, menu, canvas, map, timeline, phone screen.
- Composition: centered, split, grid, masonry, device frame, floating panel, stacked cards.
- Motifs: blur, screenshots, device mockups, icon grids, gradients, panels, cursor states, maps.
- Risk: what would become generic or copied if used literally.

## Translation Rules

- Convert repeated reference signals into principles.
- Preserve product realism: screens, controls, states, and data should feel usable.
- Use references to choose taste, not content.
- Avoid overfitting to one image when the board shows several directions.
- Prefer adding a focused reference file when a pattern will recur.

## Output Shape

When updating this skill from a moodboard:

- Keep `SKILL.md` as routing and core behavior.
- Put detailed taste guidance in `references/`.
- Name references by reusable design surface, not by the source board.
- Include positive rules, anti-patterns, and QA checks.

## Cosmos UX Board Signals

The visible UX board suggests these reusable directions:

- Airy white product pages with real UI screenshots.
- Compact mobile and payment flows.
- Editor/canvas interfaces with sidebars, handles, panels, layers, and export states.
- Glass, blur, and atmospheric surfaces.
- Icon and symbol systems.
- Soft gradients used as material or light, not decoration.
- Dark product mocks used selectively, usually with concrete UI chrome.

Use these as taste inputs only.
