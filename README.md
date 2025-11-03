# CSE134B - Standards Based CSS Use
Standards Based CSS Responsive Web Design - Site Build Out Phase 2

**Website Link:** https://cse134-hw3-vydang.netlify.app/
**GitHub Repo:** https://github.com/kdang002/cse134b_hw3

---

## ✅ Task Checklist

| Task | Done | Score |
|------|------|--------|
| Use CSS Flexbox and/or Grid for layout | X | |
| Use CSS Variables (with fallbacks, 2+ contexts) | X |  |
| Use Custom Fonts (with fallback) | X |  |
| Use Relative Units (em, rem, %, fr, etc.) | X |  |
| Use Dynamic Viewport Units (dvw, dvh, etc.) | X |  |
| Add CSS Animations / Transitions / Transforms | X |  |
| Add Media Queries (responsive design) | X |  | 
| Use Nested and Scoped CSS | X |  |
| Implement a Baseline 2024/2025 CSS Feature + 2-sentence description | X |  |
| Extra Credit: Wider gamut color using `color()` or `color-mix()` | X | +3 |
| Extra Credit: Use new selector like `:has()` | X | +2 |

---

## Baseline 2025/2024 prompt on using content-visibility:auto and align-content: center:
- content-visibility is a CSS property that tells the user agent to defer the rendering of elements until they approach the viewport. For pages with many DOM elements, this can be beneficial, as it means the initial load of a page will kick off less rendering work. Instead, the work happens just before the user needs to see it.

- align-content:center : The once impossible task of centering an item vertically was made easier by flexbox and grid, along with the align-content property. With align-content *NOW AVAILABLE for block layout*, you can achieve vertical alignment without needing to create a flex or grid layout for the property to work. No additional properties are needed as the item remains a block item, the only change is to the alignment. (I,e, previously it wasn't available as a CSS-property for block layout, until recently)