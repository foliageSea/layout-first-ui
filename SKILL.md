---
name: layout-first-ui
description: Design, implement, or review dashboards and other UIs that communicate through layout rather than redundant copy. Use when asked to simplify interface text, remove unnecessary labels, or let the layout do the explaining.
---

# Layout-first UI

Avoid unnecessary secondary labels and descriptions. Let the layout do the explaining.

## Workflow

1. Identify what users need to find, compare, or act on. Put the most important information first; group related items with proximity, shared alignment, and consistent component patterns.
2. Check each heading, subtitle, badge, and helper line. If removing it leaves the purpose, meaning, and next action clear, remove it. If removal exposes ambiguity, try improving grouping or placement before adding copy.
3. Keep the shortest explicit label that prevents misunderstanding. Preserve units, scope, comparison baselines, data provenance (such as demo data), form labels, and actionable errors when they affect interpretation or decisions. Do not replace these with color alone or hover-only text. Retain accessible names for icon-only controls.
4. Review the actual rendered UI at desktop and narrow widths. Check that reflow preserves grouping and reading order, and that essential meaning remains available without color, hover, or visual layout alone.

## Examples

- A row of clearly named KPI cards needs no extra “Key Metrics Overview” heading. “Compared with the previous period” stays if the change otherwise has no baseline.
- A chart titled “Response time” with an axis in ms and P95/P99 legend needs no caption repeating what it plots.
- Align a warning with the affected table row; keep a textual status so color isn't the only signal.
