# Marketing And Component Cards

Use this when designing marketing cards, feature cards, launch tiles, social cards, carousel slides, component cards, Bento-style product panels, or modular card systems.

For poster-like campaign graphics with hard labels, halftone/dither textures, arrows, collage, and Swiss/brutalist composition, also use `graphic-launch-visuals.md`.

## Card Purpose

Cards are not small pages. Each card needs one clear job:

- Brand card: establish the product's point of view.
- Feature card: explain one capability.
- Proof card: show adoption, metrics, trust, or reach.
- Workflow card: show a step in a sequence.
- Conversion card: drive one action.
- Component card: demonstrate a UI primitive, canvas, export, layer, code block, or system behavior.

Do not use cards as decorative filler.

## System Anatomy

Build a repeatable system before making individual cards:

- Fixed aspect ratio, usually square or 4:5.
- Consistent safe area and internal padding.
- Repeated brand chrome: logo, card number, label, tiny nav dots, or footer path.
- Shared type families and scale.
- Shared visual motifs: particles, grids, layers, canvas handles, arrows, code panels, maps, node fields.
- Controlled palette rotation across cards.
- One dominant visual idea per card.

The set should feel collectible, not templated.

## Composition Patterns

Use 2-4 patterns across a card set:

- Big type left, abstract visual cropped from right or bottom.
- Top brand chrome, centered headline, product visual anchored low.
- Light card with technical diagram and small legend.
- Dark card with one accent word and large particle field.
- Component card with UI screenshot/mockup, handles, layers, toolbar, or code block.
- Metric/proof card with map, count, or scale visualization.
- CTA card with large color field and one clear action.

Avoid placing the same headline-card-image stack on every card.

## Typography

- Use display serif for expressive product promises.
- Use clean sans for labels, metadata, numbers, navigation, and UI chrome.
- Keep card headlines short; 2-6 words is usually strongest.
- Use line breaks deliberately.
- Let one accent word change color when it sharpens meaning.
- Keep body copy small, practical, and secondary.
- Never let text touch card edges or collide with artwork.

Card text must remain readable at thumbnail size.

## Palette

Good palettes for this pattern:

- Near-black, white, electric blue, signal orange.
- White, ink, cobalt, pale technical blue.
- Cobalt field with white type and orange detail.
- Charcoal cards with low-contrast borders and vivid particles.

Rules:

- Use no more than 1-2 strong accents per card.
- Rotate background color intentionally across a set.
- Keep brand accent consistent.
- Avoid rainbow variety. Variation should feel system-led.

## Product-Native Visual Motifs

Choose visuals that explain the product:

- Particle fields for references, taste, memory, discovery, or signal.
- Layer stacks for export, publishing, or versioning.
- Canvas grids for design tools and builders.
- Code blocks for markup, handoff, and ownership.
- Maps for global teams or adoption.
- Node diagrams for workflows or integrations.
- Toolbars, handles, bounding boxes, and inspectors for real creative work.

Do not use abstract art unless it has a product meaning.

## Component Card Details

For cards showing UI components:

- Make the component anatomy believable: toolbar, layers, handles, selection boxes, panels, file types, code syntax, export list.
- Use simplified UI, not full screenshots.
- Keep details crisp enough to read, but do not overcrowd.
- Use shadows, borders, and grid lines subtly.
- Put the visual in the lower half or right side when the headline leads.
- Make the component state clear: selected, exporting, connected, applied, shared, shipped.

## Numbered Card Sets

For sequences, use small card numbers:

- Keep numbers in a consistent corner.
- Use labels like `+ REFERENCES`, `+ CANVAS`, `+ EXPORT`.
- Let each number correspond to a distinct capability.
- Make the set work as a carousel or grid.

Do not make numbering the main visual event.

## Marketing Card Copy

Use compact, sharp copy:

- "Collect anything. Make it useful."
- "Your taste, amplified by AI."
- "From references to execution."
- "Real markup. No lock-in."
- "Shared taste. Stronger products."
- "The future starts here."

Adapt the structure, not the exact words.

## Implementation Notes

For web implementation:

- Use CSS grid for card sets.
- Use `aspect-ratio` for stable card shapes.
- Use SVG, CSS gradients, canvas, or generated bitmap assets for detailed motifs.
- Keep text and UI labels code-native when possible.
- Use generated bitmap assets only when the visual complexity deserves it.
- Verify cards at desktop, tablet, mobile, and thumbnail-like sizes.

## QA Checklist

Before finishing:

- Does every card have one clear job?
- Does the set feel like one brand system?
- Are card headlines readable at a glance?
- Are visuals meaningful to the product?
- Is there enough variation without chaos?
- Do repeated elements align across cards?
- Does text stay inside safe areas on mobile?
- Are cards attractive individually and stronger as a set?
