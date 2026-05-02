# Taste Heuristics

Use this reference when designing from scratch, redesigning an interface, or improving visual quality.

## 1. Read The Product

Design starts with the domain.

- SaaS, CRM, analytics, finance, healthcare ops: calm, dense, scannable, fast to repeat.
- AI tools: show trust, state, source material, controllability, and recoverability.
- Creative tools: prioritize canvas, direct manipulation, precise controls, and visible state.
- Venture, studio, portfolio, editorial: confident hierarchy, selective proof, strong writing, space.
- Commerce: product clarity, comparison, reassurance, and conversion without noise.
- Games and playful experiences: vivid feedback, delight, motion, and strong visual identity.

If the visual language could fit any startup, it is not specific enough.

Default for modern SaaS and developer products: simple first, product-real first, decoration last.

Before choosing a visual pattern, set the taste knobs from `taste-knobs.md`. This prevents references from turning into templates.

## 2. Establish Hierarchy

Before adding style, make the reading order obvious.

- One dominant idea per screen.
- One primary action per decision moment.
- Strong contrast between headline, supporting copy, metadata, and controls.
- Related items share alignment, spacing, and visual treatment.
- Secondary information is available without competing.

Good hierarchy should survive if color is removed.

## 2.5 Set The Knobs

Use knobs to create difference before adding detail:

- Scale: compact, standard, editorial, or poster.
- Density: sparse, balanced, operational, or dense.
- Surface: flat, bordered, soft-depth, glass, or immersive.
- Contrast: low, medium, high, or stark.
- Grid: strict, editorial, canvas, dashboard, or poster.
- Motion: still, subtle, responsive, or cinematic.
- Proof: screenshot, workflow, diagram, metric, narrative, object, or image.
- Accent: none, status-only, CTA-only, brand-moments, or expressive.
- Personality: quiet, technical, luxury, playful, or art-directed.
- Card treatment: naked, hairline, soft-depth, inset, glass, or brutal.

Default to restrained scale, balanced density, medium contrast, product-native proof, and subtle motion.
Vary at least two knobs from the closest reference before designing so the result has its own identity.

## 3. Compose With Intent

Use layout to communicate importance.

- Editorial sites need rhythm: narrow/wide passages, image breaks, proof sections, and pacing.
- Operational tools need stable grids, predictable controls, compact density, and persistent context.
- Dashboards need comparison-first layout, not decorative cards everywhere.
- Landing pages need first-viewport clarity and a hint of what comes next.
- Mobile screens need ruthless sequencing; do not shrink a desktop composition.
- Product websites need a product-native proof surface: app chrome, code, workflow, dashboard, or screenshot.

Avoid nested cards, random floating panels, and equal-weight sections.

## 4. Make Typography Carry The Design

Treat type as the main interface material.

- Pick typefaces for the product's voice, not trendiness.
- Use scale deliberately, but default to restrained headline sizes. Most product and marketing sites should feel premium, not poster-sized.
- For clean product websites, desktop hero headlines usually sit around `40-64px`.
- For desktop hero headlines generally, start around `44-72px`; exceed this only for explicitly editorial/art-directed pages.
- For personal portfolios and update feeds, editorial does not automatically mean giant type; start around `38-54px` desktop and treat `54px` as the normal upper bound.
- For section headings, start around `28-48px`; keep compact panels, cards, sidebars, and dashboards smaller.
- For dashboards, page headings usually sit around `22-32px`, with app UI text around `13-15px`.
- For mobile hero headlines, start around `30-38px`; avoid huge wrapping stacks that dominate the screen.
- Keep most weights between `400-560`. Use `600-650` only for controls, labels, or rare emphasis. Avoid `700+` as a default.
- Keep line length comfortable.
- Use numbers with tabular alignment in data-heavy views.
- Avoid negative letter spacing and viewport-based font scaling.
- Make body copy useful and specific; vague copy weakens design.

If the page feels bland, improve type, spacing, and content before adding effects.

## 5. Use Color Sparingly

Color should encode meaning or establish tone.

- Start with a neutral foundation that supports content.
- Use accents for action, status, category, or brand signal.
- Avoid one-note palettes where every surface is the same hue family.
- Avoid default purple-blue gradients unless the brand truly demands them.
- Avoid random blobs, orbs, auroras, and glow fields in clean product work.
- Check contrast for text and controls.
- Let real imagery or product visuals carry color when appropriate.

Senior design often feels richer because it uses less color with more purpose.

## 6. Design The Interaction State

A polished interface includes the states people actually hit.

- Loading: preserve layout with structural skeletons when possible.
- Empty: show one clear next action.
- Error: place the message near the failed action.
- Success: confirm without blocking the next step.
- Hover/focus/pressed: make controls feel responsive but not jumpy.
- Disabled: explain why if the reason is not obvious.
- Mobile: make tap targets reliable and controls reachable.

Do not design only the happy path.

## 7. Use Motion With Restraint

Motion should clarify, not decorate.

- Animate opacity and transform where possible.
- Keep interaction feedback fast.
- Use entrance motion to establish sequence, not to entertain.
- Avoid looping motion unless it is central to the product.
- Respect reduced-motion preferences.
- Do not animate layout in ways that make controls move under the cursor.

One good motion idea is better than ten small distractions.

## 8. Work With References

References are for extracting principles.

Ask:

- What is the site trying to make the viewer believe?
- What is emphasized first?
- What is deliberately omitted?
- How does the layout create confidence?
- Where does proof appear?
- What is the relationship between copy, media, and navigation?

For a First Star-style reference, note the useful principles: conviction-first headline, sparse navigation, spacious editorial pacing, founder/company proof, and confident restraint.

## 9. Self-Critique Before Finishing

Run this pass before calling the design done:

- Is the first screen immediately understandable?
- Does the design fit the domain, or just look generically polished?
- Is there a clear visual thesis?
- Are headlines comfortably scaled, or are they shouting?
- Are font weights calm, or is everything bold?
- Is the main visual product-native, or just decorative?
- Are typography, spacing, and alignment consistent?
- Are cards used only where they frame repeated items or tools?
- Does the UI work at mobile and desktop widths?
- Does text fit without overlap or awkward wrapping?
- Are accessibility basics handled?
- Did every decorative element earn its place?

Remove weak ideas before adding new ones.
