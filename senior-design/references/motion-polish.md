# Motion Polish

Use this when designing or implementing interface motion, scroll reveals, hero entrances, hover states, animated cards, micro-interactions, or high-polish UI transitions.

## Motion Thesis

Motion should make the interface feel physical and easier to understand. It should not decorate weak layout.

Good motion feels:

- Weighted, not floaty.
- Fast enough to keep momentum.
- Subtle enough that content remains the focus.
- Consistent across repeated elements.
- Respectful of reduced-motion preferences.

## Core Rules

- Prefer spring-based transitions for React/Next interfaces using `framer-motion` or `motion/react`.
- Use duration-based CSS only for small immediate feedback such as hover, active, color, or shadow changes.
- Keep entrance movement small: usually `y: 12-24px`.
- Add subtle blur-in on premium reveals: `blur(2px)` for small UI, `blur(4px)` for content, `blur(6-8px)` for dramatic hero moments.
- Keep stagger tight: `0.04s-0.08s` between items.
- Animate once for scroll reveals unless there is a strong reason to replay.
- Animate compositor-friendly properties first: `transform`, `opacity`; use `filter: blur()` sparingly and locally.

Avoid generic fade-in-up with long easing curves, large travel distances, slow stagger, looping decoration, and animation that shifts controls under the pointer.

## Spring Defaults

Use these as starting values:

```tsx
transition: {
  type: "spring",
  stiffness: 100,
  damping: 30,
  mass: 1,
}
```

Tuning:

- Snappy UI elements: `stiffness: 220-300`, `damping: 20-26`
- Content reveals: `stiffness: 80-120`, `damping: 25-35`
- Hero or large CTA: `stiffness: 55-80`, `damping: 22-30`

## Reusable React Pattern

Use a small helper instead of rewriting motion values everywhere.

```tsx
import { useReducedMotion } from "framer-motion";

function useFadeUp(delay = 0) {
  const reduced = useReducedMotion();

  return {
    initial: reduced
      ? { opacity: 1, y: 0, filter: "blur(0px)" }
      : { opacity: 0, y: 20, filter: "blur(4px)" },
    whileInView: { opacity: 1, y: 0, filter: "blur(0px)" },
    viewport: { once: true, margin: "-80px" },
    transition: {
      type: "spring" as const,
      stiffness: 100,
      damping: 30,
      mass: 1,
      delay,
    },
  };
}
```

For `motion/react`, keep the same values and import shape expected by the project.

## Hero Motion

Use hero motion sparingly:

- Reveal headline words or lines with tight stagger.
- Let the visual system enter slightly after the copy.
- Do not delay the primary CTA too long.
- Keep the total perceived entrance under a second.
- Do not animate huge background layers unless performance is verified.

Good headline reveal:

```tsx
{words.map((word, i) => (
  <motion.span
    key={word + i}
    initial={{ opacity: 0, y: 16, filter: "blur(4px)" }}
    whileInView={{ opacity: 1, y: 0, filter: "blur(0px)" }}
    viewport={{ once: true }}
    transition={{
      type: "spring",
      stiffness: 120,
      damping: 30,
      delay: 0.08 + i * 0.06,
    }}
  >
    {word}
  </motion.span>
))}
```

## Cards And Grids

Card sets should enter as a coordinated group.

- Use `delay: i * 0.05` or a row/column diagonal delay.
- Hover lift should be small: `y: -3px` to `-5px`.
- Press should compress quickly: `scale: 0.97-0.99`.
- Shadow/border changes should support the physical movement.

```tsx
<motion.div
  {...useFadeUp(i * 0.06)}
  whileHover={{ y: -4, transition: { type: "spring", stiffness: 300, damping: 20 } }}
  className="transition-shadow"
>
  ...
</motion.div>
```

## Heading Reveals

For editorial sections, clip-path reveals can feel more designed than simple fades.

```tsx
<motion.h2
  initial={{ clipPath: "inset(100% 0 0 0)", y: 8 }}
  whileInView={{ clipPath: "inset(0% 0 0 0)", y: 0 }}
  viewport={{ once: true }}
  transition={{ type: "spring", stiffness: 80, damping: 30 }}
>
  Section title
</motion.h2>
```

Use this selectively. Too many masked headings become mannered.

## CTA Motion

Large CTA bands can scale in subtly:

```tsx
initial={{ opacity: 0, scale: 0.98, filter: "blur(4px)" }}
whileInView={{ opacity: 1, scale: 1, filter: "blur(0px)" }}
transition={{ type: "spring", stiffness: 60, damping: 25 }}
```

Keep buttons immediately usable; do not make conversion wait for elaborate animation.

## Accessibility And QA

Always:

- Respect `prefers-reduced-motion` or `useReducedMotion`.
- Check mobile performance.
- Verify no text becomes unreadable during motion.
- Verify focus states are visible.
- Avoid motion that causes layout shift.
- Keep looping or ambient animation paused/off-screen when possible.

Motion passes only when it improves clarity, tactility, or sequence.
