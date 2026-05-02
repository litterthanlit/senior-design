---
name: senior-design
description: Senior-level product and web design guidance for Codex. Use when creating, redesigning, styling, animating, or reviewing websites, landing pages, dashboards, SaaS tools, mobile screens, UI components, visual systems, or any frontend work where the user asks for better taste, polish, premium quality, editorial design, stronger hierarchy, motion, micro-interactions, or designer-grade critique.
---

# Senior Design

Use this skill to make Codex behave like a senior product designer, not a decoration engine. Treat design as strategy expressed through layout, typography, hierarchy, interaction, and restraint.

## Core Workflow

1. Identify the product, audience, job-to-be-done, and desired emotional tone.
2. Set the taste knobs before choosing patterns: scale, density, surface, contrast, grid, motion, proof, accent, personality, and card treatment.
3. Choose one clear design thesis before touching UI code.
4. Extract principles from any reference the user provides; do not copy its surface.
5. Build the first screen as the real experience, not a marketing placeholder.
6. Critique the result against hierarchy, rhythm, density, typography, copy, accessibility, and responsiveness.
7. Iterate until the interface feels intentional at desktop and mobile sizes.

When the task is a real design/build request, read `references/taste-heuristics.md` before making design decisions.

For any new site, app screen, dashboard, card set, or redesign, read `references/taste-knobs.md` before using visual recipes. Recipes are examples of knob settings, not templates.

For any broad UI creation, redesign, or critique task where the user asks for senior taste, also read `references/design-operating-model.md`.

When the user provides a moodboard, inspiration board, Cosmos collection, screenshots, visual references, or asks to expand taste from references, also read `references/moodboard-analysis-workflow.md`.

When the user asks for a clean product website, SaaS landing page, developer tool, AI product, infrastructure product, simple marketing site, or product-led website, also read `references/clean-product-websites.md`.

When the user asks for dashboards, SaaS apps, admin tools, product surfaces, agent workspaces, analytics, planning tools, issue tracking, review tools, or internal tools, also read `references/product-dashboard-ui.md`.

When the user asks for a premium dark SaaS, AI product, creator tool, operating system, studio tool, or dark high-end landing page, also read `references/premium-dark-saas.md`.

When the user asks for clean light SaaS, product marketing, white/neutral product pages, onboarding-style pages, or screenshot-led software pages, also read `references/light-product-saas.md`.

When the user explicitly asks for cinematic SaaS heroes, gradient/optical backgrounds, abstract product marketing, finance/wellness/commerce SaaS landing pages, or large hero visuals with product overlays, also read `references/cinematic-saas-heroes.md`. Do not use cinematic effects as the default SaaS direction.

When the user asks for an agency site, portfolio, brand launch, culture site, art-directed campaign, immersive website, or Basement-style direction, also read `references/brand-editorial-immersive.md`.

When the user asks for personal sites, founder/designer portfolios, update feeds, journals, writing indexes, lightweight blogs, or Dantase-style editorial pages, also read `references/personal-editorial-feeds.md`.

When the user asks for mobile app screens, app flows, onboarding, checkout, payments, widgets, device mockups, or compact app UI, also read `references/mobile-app-flows.md`.

When the user asks for editor UI, canvas tools, productivity workspaces, command surfaces, inspectors, sidebars, layers, exports, or builder interfaces, also read `references/editor-canvas-ui.md`.

When the user asks for glass, blur, depth, frosted surfaces, soft UI, translucent panels, or atmospheric product surfaces, also read `references/glass-depth-surfaces.md`.

When the user asks for icon systems, glyph sets, component libraries, visual systems, symbol grids, UI kits, or component cards, also read `references/icon-component-systems.md`.

When the user asks for marketing cards, feature cards, component cards, social launch tiles, carousel slides, product story cards, or modular card systems, also read `references/marketing-component-cards.md`.

When the user asks for poster-like launch visuals, campaign graphics, social tiles, art-directed cards, Swiss/brutalist UI collage, halftone/dither/particle visuals, or graphics like the provided references, also read `references/graphic-launch-visuals.md`.

When the user asks for motion, animation, micro-interactions, scroll reveals, animated cards, hero motion, hover/press polish, or to make an interface feel more alive, also read `references/motion-polish.md`.

## Design Thesis

State the direction briefly before implementation. Pick one primary taste mode:

- Cursor mode: product-led, calm, useful, interface-as-proof.
- Linear mode: dark operational system, dense, precise, workflow-first.
- Vercel mode: clean grid, technical clarity, product/platform confidence.
- Basement mode: art-directed, immersive, brand-first.
- Graphic launch mode: poster-like, cropped, labeled, textured, campaign-first.
- Personal editorial mode: spare, writerly, identity-forward, feed-first.

Then include:

- Positioning: what this interface should feel like and why.
- Taste profile: the key knob settings that will make this design distinct.
- Layout model: editorial, dense operational, portfolio-led, immersive, tool-first, commerce-first, etc.
- Type behavior: quiet utility, sharp editorial, technical precision, luxury restraint, playful display.
- Color behavior: neutral foundation, limited accent, high-contrast editorial, data-coded, image-led.
- Signature moment: the one memorable interaction, composition, image treatment, or content structure.

Avoid vague directions like "modern and clean." Replace them with concrete choices.
Do not reuse a recipe until the knobs have been set; vary at least two knobs from the closest reference so the result does not look cloned.

## Senior Taste Rules

- Prefer fewer, stronger ideas over many decorative moves.
- Let the subject matter lead the visual language.
- Treat references as knob combinations, not templates.
- Use real content, real hierarchy, and real workflows early.
- Start simple and product-real. Add atmosphere only after the product surface works.
- Make spacing feel designed: consistent rhythm, deliberate breaks, no random padding.
- Use typography as the primary visual system before adding effects, but keep headline scale controlled. Avoid billboard-sized hero type unless the user explicitly asks for poster/editorial drama.
- Keep most UI and marketing font weights between `400-560`. Use heavy weights sparingly.
- Use motion only when it clarifies state, focus, or sequence.
- Give every accent a job: navigation, state, emphasis, category, or conversion.
- Remove anything that only proves effort.

## Visual Kill List

Avoid these unless the user explicitly asks and the product context supports them:

- Huge hero headlines as the default move.
- Random gradient blobs, orbs, auroras, or glow fields.
- Generic glassmorphism.
- Fake metric cards that do not model a workflow.
- Evenly weighted card grids as the main solution.
- Bold font everywhere.
- Decorative dashboards that do not explain the product.
- Abstract visuals before product-native visuals.

## Reference Handling

When the user gives a reference site, image, app, or brand:

- Inspect what it is doing structurally: hierarchy, pacing, density, copy posture, navigation, proof, media, interaction.
- Translate those principles into the user's domain.
- Do not reproduce exact layout, copy, visual assets, or brand identity.

Example from `https://firststar.vc/`: use it as a lesson in editorial restraint, conviction-led copy, sparse navigation, real portfolio proof, and calm confidence. Do not copy the brand, page structure, or text.

Example from Cursor: use it as a lesson in product-led clarity, quiet type, simple navigation, and real interface proof. Do not copy the logo, copy, UI, or specific screenshot composition.

Example from Linear: use it as a lesson in dark operational density, precise app chrome, low-contrast borders, real workflows, and status-rich dashboards. Do not copy the brand, exact interface, or copy.

Example from Vercel: use it as a lesson in clean grid systems, platform confidence, restrained black/white UI, technical product proof, and disciplined spectacle. Do not copy the brand, triangle motif, copy, or exact optical art.

Example from Basement Studio: use it as a lesson in art direction, immersive scenes, strong brand attitude, and authored motion. Use this only for brand/editorial sites, not normal SaaS dashboards.

Example from Dantase updates: use it as a lesson in personal editorial restraint, identity-first navigation, oversized serif/sans contrast, tiny metadata chips, long-form feed pacing, and confident white space. Do not copy the exact copy, personal brand, nav, or content structure.

Example from a premium dark SaaS reference: use it as a lesson in cinematic black canvas, serif/sans contrast, electric accent color, abstract product-native visuals, proof logos, modular feature cards, and calm conversion flow. Do not copy the brand, claims, logos, or exact particle art.

Example from marketing/component card references: use them as lessons in square composition, repeated brand chrome, numbered sequences, strong typographic contrast, product-native abstract art, and palette variation across a single system. Do not copy the exact brand, copy, logo, or artwork.

Example from graphic launch references: use them as lessons in hard text blocks, monospace labels, directional arrows, red signal accents, image collage, perspective grids, dither/halftone/particle texture, and square poster composition. Do not copy the exact artwork, brands, copy, or layout.

Example from motion references: use spring-based, physically grounded motion, subtle blur-in reveals, tight stagger, small movement distances, and responsive hover/press feedback. Do not add motion that competes with the content.

Example from a UX moodboard: extract product UI principles such as airy screenshot-led SaaS, mobile flow realism, editor/canvas chrome, glass depth, compact payment widgets, and disciplined icon systems. Do not copy the exact screenshots, brands, or artwork.

Example from cinematic SaaS references: study the optical background, center-weighted hierarchy, restrained navigation, pill CTAs, product overlay placement, and the relationship between soft atmosphere and crisp UI. Do not copy the exact brand, gradient, logo, or copy.

## Output Standards

For implementation tasks:

- Ship working UI, not only advice.
- Respect the existing stack, components, and design system first.
- Prefer accessible primitives for interactive controls.
- Verify responsive behavior and text fit.
- Check the actual rendered result when a browser/dev server is available.

For review tasks:

- Lead with the most important design problems.
- Explain the practical impact in plain language.
- Give specific fixes, not abstract taste commentary.
