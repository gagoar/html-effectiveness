# html-effectiveness

A Claude Code skill for generating rich, self-contained HTML documents — beautiful alternatives to markdown, inspired by [thariqs.github.io/html-effectiveness](https://thariqs.github.io/html-effectiveness/).

**Webpage:** [gagoar.github.io/html-effectiveness](https://gagoar.github.io/html-effectiveness)

The skill embeds the exact CSS design language ("Birchline") from the showcase: serif headings, an ivory/clay/slate palette, 1.5px borders, and scroll-snap slide decks — all in a single `.html` file with zero external dependencies.

## Install

Via the [gago-plugins](https://gagoar.github.io/gago-plugins) marketplace:

```
/plugin marketplace add gagoar/gago-plugins
/plugin install html@gago-plugins
/reload-plugins
```

Or standalone:

```
/plugin marketplace add gagoar/html-effectiveness
/plugin install html@html
/reload-plugins
```

## Usage

Invoke the skill in any Claude Code session:

```
/html:doc Make me a one-page status report for week 18
/html:doc Code review for the auth middleware PR
/html:doc Slide deck: why we're moving to microservices
/html:doc Kanban board for the Q3 roadmap
/html:doc Milestone timeline for the v2 launch
```

## Document types

| Type | Description |
|------|-------------|
| **Status / incident report** | Stat-card grids, timeline, pill badges |
| **Code review / PR** | Diff-style blocks, risk table, checklist |
| **Approach comparison** | Side-by-side cards with tradeoff summary |
| **Slide deck** | CSS scroll-snap pages, no JS required |
| **Kanban board** | Drag-and-drop columns (HTML5 native) |
| **Milestone timeline** | Vertical timeline with status pills |
| **Research explainer** | Long-form with callouts and code blocks |

## Design system

All documents use the "Birchline" design tokens:

- **Palette**: ivory `#FAF9F5`, clay `#D97757`, slate `#141413`, oat `#E3DACC`, olive `#788C5D`, rust `#B04A3F`
- **Typography**: `ui-serif / Georgia` headings, `system-ui` body, `ui-monospace` code
- **Borders**: 1.5px, `border-collapse: separate` with `border-radius` + `overflow: hidden`

## License

MIT — Copyright (c) 2026 gagoar
