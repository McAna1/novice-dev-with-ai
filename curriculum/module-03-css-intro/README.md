# Module 3 — Introduction to CSS

**Duration:** 3–4 class sessions  
**Prerequisites:** Module 2 — semantic HTML milestone complete  
**Next module:** Module 4 — Flexbox

---

## What Students Learn

- How to link an external CSS file to HTML
- CSS syntax: selector { property: value; }
- Selectors: element, class (`.`), ID (`#`) — in that order
- Colors: named → hex → rgb → hsl
- Typography: font-family, font-size (rem), font-weight, line-height, text-align
- The CSS reset: why and how
- **The Box Model**: content, padding, border, margin — taught visually
- `box-sizing: border-box` — why every project uses it
- `width`, `height`, `max-width`, `min-height`
- `display`: block vs inline vs inline-block
- CSS custom properties: `:root { --color-primary: #2563eb; }`
- Background: background-color, background-image, background-size

## Key Concept — The Box Model

Every element is a box. From inside out:
```
[ margin [ border [ padding [ content ] ] ] ]
```

This must be understood before any layout work begins.

## Files in This Module

```
module-03-css-intro/
├── README.md
├── lesson-notes.md
└── exercises/
    ├── exercise-01-linking-css.md
    ├── exercise-02-selectors-and-colors.md
    ├── exercise-03-box-model.md
    └── exercise-04-typography.md
```

## Milestone

Style a complete page from scratch — text, colors, box model, spacing — without
referencing any examples or copying from previous work. CSS validator must pass.
