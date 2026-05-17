# Module 2 — Semantic HTML5

**Duration:** 2–3 class sessions  
**Prerequisites:** Module 1 — boilerplate milestone complete  
**Next module:** Module 3 — Introduction to CSS

---

## What Students Learn

- Why semantic HTML matters (accessibility + SEO + code readability)
- Page landmark elements: `<header>`, `<nav>`, `<main>`, `<footer>`
- Content grouping: `<section>`, `<article>`, `<aside>`
- Text elements: `<h1>`–`<h6>`, `<p>`, `<strong>`, `<em>`, `<blockquote>`
- Lists: `<ul>`, `<ol>`, `<li>`, `<dl>`, `<dt>`, `<dd>`
- Links: `<a href="">` — absolute vs relative URLs
- Images: `<img src="" alt="">` — alt text is required and explained
- Forms: `<form>`, `<input>`, `<label>`, `<button>`, `<select>`, `<textarea>`
- When to use `<div>` (and when NOT to)

## Key Concept

The difference between:
```html
<div class="nav">...</div>        <!-- describes appearance -->
<nav>...</nav>                    <!-- describes meaning -->
```

Screen readers, search engines, and other developers understand `<nav>`.
They do not understand `<div class="nav">` — it's just a generic box.

## Files in This Module

```
module-02-semantic-html/
├── README.md
├── lesson-notes.md
└── exercises/
    ├── exercise-01-page-structure.md
    ├── exercise-02-text-and-lists.md
    ├── exercise-03-links-and-images.md
    └── exercise-04-forms.md
```

## Milestone

Build a complete 4-region page (`<header>`, `<nav>`, `<main>`, `<footer>`) using
only semantic elements. Zero `<div>` elements allowed. HTML validator must pass.
