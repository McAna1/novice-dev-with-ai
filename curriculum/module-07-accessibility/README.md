# Module 7 — Web Accessibility

**Duration:** 2 class sessions  
**Prerequisites:** Module 6 — Responsive Design milestone complete  
**Next module:** Module 8 — Introduction to JavaScript

---

## What Students Learn

- What web accessibility is and who it affects
- The four principles of WCAG: Perceivable, Operable, Understandable, Robust
- Screen readers and how they navigate pages (landmarks, headings, links)
- Alt text: meaningful vs decorative images
- Form accessibility: labels, fieldsets, error messages
- Heading hierarchy as a navigation tool (not just visual styling)
- Color contrast: 4.5:1 minimum ratio for normal text
- Keyboard navigation: Tab, Shift+Tab, Enter, Space, arrow keys
- Focus management: `:focus-visible`, never remove without replacing
- Skip navigation links
- ARIA roles — when they're needed (rarely) and when native HTML is better
- Testing tools: WAVE, Lighthouse, keyboard-only navigation

## Key Concept — Semantic HTML IS Accessibility

Most accessibility problems are solved by using correct semantic HTML.
If you have completed Modules 1–6 with proper semantics, you are already
ahead of most websites on the internet.

Accessibility is not a feature you add at the end.
It is the result of writing good HTML from the beginning.

## The 4 WCAG Principles (POUR)

| Principle | Meaning | Example |
|---|---|---|
| **P**erceivable | Users can see/hear the content | Alt text for images |
| **O**perable | Users can navigate and interact | Keyboard-accessible buttons |
| **U**nderstandable | Content is clear and predictable | Descriptive labels on forms |
| **R**obust | Works with current and future tools | Valid semantic HTML |

## Files in This Module

```
module-07-accessibility/
├── README.md
├── lesson-notes.md
└── exercises/
    ├── exercise-01-audit-your-page.md
    ├── exercise-02-fix-alt-text.md
    ├── exercise-03-keyboard-navigation.md
    └── exercise-04-color-contrast.md
```

## Milestone

Run a WAVE audit on your project page.
Identify 5 accessibility issues (minimum).
Fix all 5 and explain each fix in your pull request description.
WAVE must report zero errors after fixes.
