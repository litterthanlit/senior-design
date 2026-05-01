# Product Dashboard UI

Use this for dashboards, SaaS apps, admin tools, agent workspaces, developer tools, product operations, analytics, planning, issue tracking, review tools, and internal product surfaces.

## Reference Set

Study Linear and Cursor for density, hierarchy, and product realism. Use Vercel for technical surfaces like deploys, logs, metrics, and infrastructure status. Do not copy their brands, exact layouts, or UI text.

## Core Feel

Dashboards should feel operational, not decorative.

- Dense but calm.
- Rows, panels, tabs, sidebars, inspectors, timelines, and command surfaces.
- Stable layout with persistent context.
- Low-contrast borders and separators.
- Clear active, selected, loading, empty, and error states.
- Realistic data density.
- Useful defaults visible without scrolling.

## Layout Patterns

Good dashboard structures:

- Sidebar + main list + detail panel.
- Top command/search bar + content grid/list.
- Kanban/list hybrid with status columns and detail drawer.
- Timeline or roadmap with left labels and right schedule.
- Agent/task workspace with transcript, files, status, and actions.
- Metrics overview above a table only when the table is the real work.

Avoid:

- Four big stat cards as the whole dashboard.
- Marketing cards pretending to be product UI.
- Oversized empty panels.
- Centered hero copy inside an app surface.
- Random floating cards with no workflow relationship.

## Product Chrome

Use realistic app chrome:

- Navigation labels.
- Search or command input.
- Breadcrumb or workspace context.
- Tabs, filters, and sorting controls.
- Row actions and status chips.
- Avatars or ownership where relevant.
- Timestamps, IDs, priorities, labels, and counts.
- Empty/loading/error states near the affected surface.

Every control should imply an actual workflow.

## Typography

- App UI typography is smaller than marketing typography.
- Base UI text: `13-15px`.
- Table/list labels: `12-14px`.
- Panel headings: `16-22px`.
- Dashboard page heading: `22-32px`.
- Use `400-560` weights for most text.
- Use tabular numbers for metrics.
- Do not use giant display type inside dashboards.

## Color And Surface

- Start neutral: black/near-black, white/near-white, or muted gray.
- Accent color marks state, selection, priority, status, or primary action.
- Borders should be visible but quiet.
- Background contrast should separate levels without making every panel a card.
- Avoid glassmorphism unless blur represents layered app chrome.

## Data And Content

Use plausible product data.

- Developer tools: builds, branches, PRs, logs, files, agents, latency, regions.
- Product tools: issues, projects, cycles, roadmaps, labels, owners, priorities.
- AI tools: prompts, sources, agent status, confidence, review output, files touched.
- Analytics: tables, trends, filters, segments, anomalies, annotations.

Fake data should still describe a real job.

## Motion

- Use motion to reveal state changes, not to decorate.
- Hover should clarify affordance.
- Selected rows, tabs, and side panels should respond quickly.
- Avoid animated charts unless the animation helps comparison.

## QA

Before shipping:

- Can a user tell what job the dashboard supports?
- Is there a primary workflow, not just a collection of widgets?
- Are controls sized like real software?
- Do rows, panels, and statuses align cleanly?
- Is the dashboard still credible without gradients or glow?
