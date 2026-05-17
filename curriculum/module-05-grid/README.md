# Module 5 — Layouts with CSS Grid

**Duration:** 2–3 class sessions  
**Prerequisites:** Module 4 — Flexbox milestone complete  
**Next module:** Module 6 — Responsive Design

---

## What Students Learn

- `display: grid` — activating grid
- `grid-template-columns` and `grid-template-rows`
- The `fr` unit — fraction of available space
- `repeat()` function — shorthand for repeated column patterns
- `gap` (row-gap, column-gap)
- `grid-column` and `grid-row` for spanning
- `grid-template-areas` — naming zones and placing items
- `auto-fill` vs `auto-fit` with `minmax()`
- When to use Grid vs Flexbox

## Key Concept — Flexbox vs Grid

```
Flexbox = one direction         Grid = two directions
─────────────────               ────────────────────────────
[nav]  [nav]  [nav]             [header] [header] [header]
                                [sidebar][main   ][main   ]
OR                              [footer] [footer] [footer]

[card]
[card]
[card]
```

- **Flexbox** → you have a line of items and want to arrange them
- **Grid** → you have a page layout and want to place things in rows AND columns

## The `fr` Unit

`fr` = fraction of the available space

```css
grid-template-columns: 1fr 2fr 1fr;
/* ┌────┬────────┬────┐ */
/* │ 1fr│  2fr   │ 1fr│ */
/* └────┴────────┴────┘ */
```

## Files in This Module

```
module-05-grid/
├── README.md
├── lesson-notes.md
└── exercises/
    ├── exercise-01-basic-grid.md
    ├── exercise-02-fr-unit.md
    ├── exercise-03-template-areas.md
    └── exercise-04-photo-gallery.md
```

## Milestone

Submit a pull request with: a 3-column card grid that automatically collapses
to 1 column on screens below 640px. Built with CSS Grid only (no Flexbox for layout).
