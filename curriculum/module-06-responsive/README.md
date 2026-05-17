# Module 6 — Responsive Design

**Duration:** 2–3 class sessions  
**Prerequisites:** Module 5 — Grid milestone complete  
**Next module:** Module 7 — Accessibility

---

## What Students Learn

- What responsive design means and why it matters
- Mobile-first approach — start small, add complexity for larger screens
- The viewport meta tag (already in boilerplate — now students understand why)
- Media queries: `@media (min-width: Xpx) { ... }`
- Common breakpoints and when to use each
- Responsive typography: `clamp()` introduction
- Responsive images: `max-width: 100%`, `height: auto`, `<picture>` element
- Testing with Chrome DevTools device toolbar (Ctrl+Shift+M)
- Fluid layouts vs fixed-width layouts
- `min-width` vs `max-width` in media queries

## Key Concept — Mobile First

Mobile-first means: write your base styles for the SMALLEST screen.
Then use `min-width` media queries to add styles for LARGER screens.

```css
/* Base: mobile (no media query needed) */
.card { width: 100%; }

/* Add a media query to EXPAND for larger screens */
@media (min-width: 640px) { .card { width: 48%; } }
@media (min-width: 1024px) { .card { width: 30%; } }
```

This is the opposite of how many beginners start (desktop-first).
Mobile-first is correct because most users are on mobile.

## Common Breakpoints

| Breakpoint | Target Devices |
|---|---|
| `480px` | Small phones |
| `640px` | Large phones, small tablets |
| `768px` | Tablets |
| `1024px` | Small laptops, desktops |
| `1280px` | Wide desktops |

## Files in This Module

```
module-06-responsive/
├── README.md
├── lesson-notes.md
└── exercises/
    ├── exercise-01-viewport-and-media-queries.md
    ├── exercise-02-responsive-nav.md
    ├── exercise-03-responsive-grid.md
    └── exercise-04-full-page-responsive.md
```

## Milestone

Submit a pull request: make your existing project (from Modules 1–5) fully responsive.
Must work on: 375px mobile, 768px tablet, 1280px desktop.
Tested and confirmed working with Chrome DevTools device toolbar.
