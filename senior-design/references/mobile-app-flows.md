# Mobile App Flows

Use this for mobile app screens, onboarding, checkout, payment widgets, compact app UI, device mockups, and app-flow marketing.

## Core Feel

Mobile UI should feel held, tappable, and stateful. Do not scale desktop UI into a phone frame.

- Clear top-level task per screen.
- Large enough tap targets.
- Compact hierarchy.
- Realistic system spacing.
- Visible state: selected, pending, paid, verified, failed, empty, confirmed.
- Device frames only when they help explain the product.

## Flow Types

- Onboarding: goal, permissions, profile setup, first action.
- Payment: amount, method, confirmation, security, receipt.
- Dashboard widget: key status, next action, compact chart or list.
- Creator tool: media, controls, timeline, export, preview.
- Messaging/collaboration: participants, comments, status, unresolved items.

## Layout Rules

- One primary action per screen.
- Avoid crowding the safe areas.
- Use bottom actions for frequent next steps.
- Keep forms short and grouped.
- Use cards for grouped transactional content, not every line.
- Show status where the user acts.

## Visual Treatment

- Use soft depth sparingly: shadows, blur, panels, or device glass.
- Use color to signal status and action.
- Use realistic content; placeholder labels make app screens feel fake.
- Avoid tiny unreadable UI inside marketing mockups.

## Monochrome Audio And Tuning Apps

Use this pattern for radio, audio, music discovery, tuner, location station, and focused utility apps.

- Use a strict monochrome base: white, black, warm gray, cool gray.
- Add one tiny signal accent, often red, orange, or cobalt.
- Treat the phone screen as a designed object with generous rounded corners.
- Use oversized functional typography for values like frequency, station, speed, time, or count.
- Pair large numbers with small descriptive labels.
- Use ruler scales, tick marks, waveform bars, dials, or vertical needles as product-native controls.
- Use tab pills or segmented controls for compact mode switching.
- Put transport controls in large thumb-friendly zones.
- Let one dense technical element contrast with large calm whitespace.

Avoid turning the screen into a generic music player. The interface should feel specific to tuning, listening, scanning, or selecting.

## Monochrome Audio Layout Moves

- Discovery screen: country/city list, search, menu, count summary, premium card.
- Listening screen: giant frequency or track value, station label, scale control, favorite/share, transport controls.
- Brand/landing screen: sparse place labels, measurement scale, dark lower panel, oversized product word.
- Use rounded cards with hard black/white contrast and one soft gray material surface.
- Keep accent dots tiny; do not let red or blue become the whole palette.

## Health And Wellness Analytics Apps

Use this pattern for sleep, fitness, habit, biometrics, recovery, wellness, and quantified-self app screens.

- Use a calm light app surface with soft gray cards and dark controls.
- Pair a quiet top bar with one strong data readout.
- Use dot-matrix or segmented numerals for measured values when the product should feel technical.
- Use compact segmented controls for time ranges: day, week, month, year.
- Give selected segments a clear pill state.
- Show charts as product-native information, not decorative shapes.
- Use one hot accent for important data, often red-orange for deep sleep, strain, alert, or active state.
- Use neutral tones for secondary states: light, REM, awake, rest, inactive.
- Keep chart legends close to the chart and visually tied to marks.
- Use rounded white cards over pale gray backgrounds for analysis blocks.

Avoid generic wellness gradients, oversized motivational quotes, and fake charts with no interpretable states.

## Wellness Analytics Layout Moves

- Header: back control, centered section title, system status or time.
- Time range: full-width segmented pill under the header.
- Key metric: large measured value plus units and label.
- Analysis card: date, chart controls, legend, chart, axis labels.
- Insight card: one plain-language recommendation tied to the data.
- Chart marks: bars, blocks, stepped sleep stages, rings, or timelines with clear color mapping.
- Marketing composition: device frame over dark tactile background only when it reinforces hardware, sleep, fitness, or sensor context.

## Device Mockups

- Prefer 1-3 screens over a wall of phones.
- Stagger screens only when comparing states.
- Do not let the frame become more important than the UI.
- Make the screen content code-native when implementing interactive UI.

## QA

- Can the user tell what the screen does in 3 seconds?
- Are actions tappable?
- Is the state clear?
- Does the mobile flow feel real, not decorative?
- Does the visual system use scale, controls, and states specific to the app category?
- Are charts and metrics interpretable, with labels and legends close to the data?
- Does text fit at actual mobile width?
