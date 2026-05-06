# Taste Knobs

Use this before choosing layout patterns or visual recipes. The goal is to create a distinct design direction from adjustable decisions, not to reuse a template.

## Core Rule

Set the knobs first, then design. References and recipes are examples of knob combinations, not layouts to copy.

For any new site, app screen, dashboard, card set, or redesign, define a short taste profile:

```md
Taste profile:
Scale: compact | standard | editorial | poster
Density: sparse | balanced | operational | dense
Surface: flat | bordered | soft-depth | glass | immersive
Contrast: low | medium | high | stark
Grid: strict | editorial | canvas | dashboard | poster
Motion: still | subtle | responsive | cinematic
Proof: screenshot | workflow | diagram | metric | narrative | object | image
Accent: none | status-only | CTA-only | brand-moments | expressive
Personality: quiet | technical | luxury | playful | art-directed
Containment: none | section | row | list | screenshot | tool-surface | card | panel | modal
```

Do not expose this full list to the user every time. Use it internally, then mention only the important choices if useful.

## Knob Defaults

Default senior-design posture:

- Scale: `standard`, capped and calm.
- Density: `balanced`, with purposeful whitespace.
- Surface: `flat` or `bordered`; move to `soft-depth` only for focal cards or proof.
- Contrast: `medium`; one high-contrast zone is enough.
- Grid: `strict` for product trust, `editorial` for portfolios, `canvas` for tools.
- Motion: `subtle`; interactive controls can be `responsive`.
- Proof: product-native before decorative.
- Accent: `CTA-only` or `status-only`.
- Personality: `quiet` unless the domain needs stronger voice.
- Containment: default to `none`, `section`, `row`, `list`, or `screenshot`. Use `card`, `panel`, or `modal` only when the content needs a boundary.

## Scale Knob

Scale controls typographic confidence and object size.

- Compact: dashboards, dense tools, mobile flows, app chrome.
- Standard: clean product sites, SaaS pages, portfolios, most landing pages.
- Editorial: personal sites, brand launches, culture pages, writing-heavy pages.
- Poster: campaign graphics, art-directed launches, explicit dramatic direction.

Guardrails:

- Default desktop hero max: `54px`.
- Clean product sites: usually `40-56px`.
- Personal/editorial sites: usually `38-54px`.
- Dashboards and app shells: page headings usually `22-32px`.
- Use `64px+` only when the user asks for cinematic, poster, or brand-drama work.

## Density Knob

Density controls how much the page asks the user to process at once.

- Sparse: one idea per section, wide margins, strong pacing.
- Balanced: clear sections, useful proof, readable body copy.
- Operational: persistent navigation, filters, status, compact controls.
- Dense: expert tools, tables, timelines, editors, multi-pane workflows.

Do not use sparse density as an excuse for oversized type. Use spacing, proof, and pacing.

## Surface Knob

Surface controls material language.

- Flat: editorial pages, clean docs, light portfolios.
- Bordered: product websites, dashboards, settings, lists.
- Soft-depth: focused CTA cards, modal-like surfaces, premium dark panels.
- Glass: only when translucency supports atmosphere or layered state.
- Immersive: brand/editorial/cinematic scenes where the background is part of the concept.

Most interfaces should use one primary surface language plus one accent surface.

## Contrast Knob

Contrast controls visual authority.

- Low: calm, luxury, ambient, background systems.
- Medium: most product UI and marketing.
- High: hero zones, CTAs, important proof.
- Stark: brutalist, poster, launch graphics, or sharp editorial moments.

Avoid making every section high-contrast. It destroys hierarchy.

## Grid Knob

Grid controls the page skeleton.

- Strict: Swiss product pages, developer tools, compliance/security/finance.
- Editorial: portfolios, essays, studios, narrative marketing.
- Canvas: builders, spatial tools, creative workspaces.
- Dashboard: operational systems, analytics, admin products.
- Poster: social cards, launch graphics, visual campaigns.

Changing the grid is the fastest way to avoid template repetition.

## Motion Knob

Motion controls how alive the interface feels.

- Still: editorial, documentation, portfolio indexes.
- Subtle: most product websites and dashboards.
- Responsive: tools, editors, drag/drop, command surfaces.
- Cinematic: brand launches, immersive hero moments, scroll scenes.

Default to subtle. Increase motion only when it clarifies sequence, state, or spatial logic.

## Proof Knob

Proof controls what makes the design believable.

- Screenshot: product-led SaaS, developer tools, workflow products.
- Workflow: dashboards, agents, operational tools.
- Diagram: infrastructure, systems, technical products.
- Metric: analytics, growth, reliability, adoption.
- Narrative: portfolio, founder, editorial, case study.
- Object: hardware, fashion, luxury, physical products.
- Image: culture, people, place, brand story.

If the proof is weak, the design will feel generic no matter how polished it is.

## Accent Knob

Accent controls color discipline.

- None: editorial restraint, black/white systems.
- Status-only: dashboards, operational tools, health states.
- CTA-only: product marketing and conversion pages.
- Brand-moments: launch pages, portfolios, social cards.
- Expressive: art-directed campaigns and playful products.

Every accent needs a job.

## Personality Knob

Personality controls tone across type, copy, spacing, and interaction.

- Quiet: calm, premium, trustworthy.
- Technical: precise, structured, proof-heavy.
- Luxury: spacious, tactile, low-noise.
- Playful: warmer shapes, clearer delight, more motion.
- Art-directed: authored, surprising, less system-neutral.

Do not mix too many personalities. Pick one primary and one secondary.

## Containment Knob

Containment controls whether content needs a visible box.

- None: content sits directly on the page.
- Section: full-width band or open layout with no card frame.
- Row: scannable repeated content separated by dividers or rhythm.
- List: chronological, editorial, settings, files, tasks, or records.
- Screenshot: product proof inside believable app chrome.
- Tool-surface: canvas, inspector, editor, table, terminal, map, or form.
- Card: repeated object with one job, such as a project, file, feature, plan, or proof item.
- Panel: persistent or floating product UI region, such as sidebar, inspector, ask panel, or drawer.
- Modal: focused temporary decision or confirmation.

Use the lowest containment that keeps the content understandable. Do not put content in a card just to decorate empty space.

Card permission test:

- Is this a repeated object the user compares or scans?
- Is this a bounded tool, state, action, or proof unit?
- Would the content become less clear without the frame?
- Does the card create hierarchy instead of equalizing everything?

If the answer is no, remove the card and use spacing, alignment, typography, dividers, or a real product surface.

## Example Profiles

Clean trust-led product site:

```md
Scale: standard
Density: sparse-balanced
Surface: bounded hero canvas + one soft-depth CTA/proof unit
Contrast: medium with one high-contrast hero canvas
Grid: strict
Motion: subtle
Proof: screenshot/workflow
Accent: CTA-only
Personality: technical + quiet
Containment: sections and screenshots first; one card only for focused proof or CTA
```

Personal portfolio:

```md
Scale: standard-editorial, capped at 54px
Density: sparse
Surface: flat
Contrast: soft-medium
Grid: editorial
Motion: still/subtle
Proof: narrative/project index
Accent: none or brand-moment
Personality: quiet + authored
Containment: naked sections, rows, and feed entries
```

Spatial editor or AI workspace:

```md
Scale: compact-standard
Density: operational
Surface: bordered + soft-depth floating panels
Contrast: medium
Grid: canvas
Motion: responsive
Proof: workflow/canvas state
Accent: status-only
Personality: technical + quiet
Containment: canvas/tool surfaces, panels only where persistent UI needs boundaries
```

Marketing card set:

```md
Scale: standard or editorial per card
Density: balanced
Surface: rotate hairline, flat, soft-depth, and poster
Contrast: vary by card, keep system cohesion
Grid: poster
Motion: still for static, subtle for web cards
Proof: diagram/object/workflow
Accent: brand-moments
Personality: art-directed + technical
Containment: varied only because each card has a distinct job
```

## Anti-Template Check

Before building, answer:

- Which two knobs make this design distinct?
- Which reference pattern is being avoided so it does not look copied?
- What is the product-native proof?
- Where is the single strongest moment?
- Which default SaaS move was removed?

If the answers are vague, reset the knobs before designing.
