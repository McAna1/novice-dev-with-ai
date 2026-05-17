# Module 4 — Layouts with Flexbox

**Duration:** 2–3 class sessions  
**Prerequisites:** Module 3 — CSS intro milestone complete  
**Next module:** Module 5 — CSS Grid

---

## What Students Learn

### Container Properties (Phase 1 — Teach First)
- `display: flex` — activating flexbox
- `flex-direction`: row (default) vs column
- `justify-content`: flex-start, center, flex-end, space-between, space-around, space-evenly
- `align-items`: stretch, center, flex-start, flex-end, baseline
- `gap`: shorthand for row-gap and column-gap
- `flex-wrap`: nowrap, wrap, wrap-reverse

### Item Properties (Phase 2 — After Container Is Mastered)
- `flex-grow`, `flex-shrink`, `flex-basis`
- `flex: 1` shorthand — what it really means
- `align-self`: override container's align-items for one item
- `order`: change visual order without changing DOM order

## Key Concept

Flexbox arranges items in **one direction at a time** — either a row OR a column.

```
Main axis →  [item] [item] [item]   (flex-direction: row)
Cross axis ↕

Main axis ↓  [item]                 (flex-direction: column)
             [item]
Cross axis →  [item]
```

`justify-content` controls spacing along the MAIN axis.
`align-items` controls spacing along the CROSS axis.

## Projects in This Module

1. **Centered hero section** — center text and button both horizontally and vertically
2. **Navigation bar** — logo left, links right, vertically centered
3. **Card row** — 3 equal cards in a row with gap, wrapping on small screens

## Files in This Module

```
module-04-flexbox/
├── README.md
├── lesson-notes.md
└── exercises/
    ├── exercise-01-flex-container.md
    ├── exercise-02-justify-and-align.md
    ├── exercise-03-flex-items.md
    └── exercise-04-nav-and-cards.md
```

## Milestone

Demonstrate live: center any element on screen using Flexbox.
Build a responsive navigation bar (logo left, links right) and a 3-card row.
All layout achieved with Flexbox only — no Grid, no positioning.
