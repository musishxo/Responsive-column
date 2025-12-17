I created three small demos that showcase element-scoped responsiveness and modern layout patterns.

## Files
- [index.html](index.html) — demo of the custom element/class [`ResponsiveColumns`](index.html) with a slider-driven container resize.
- [index2.html](index2.html) — reusable two-column web component implemented as class [`TwoColumn`](index2.html) and template [`two-column-template`](index2.html); supports the `min-width` attribute.
- [index3.html](index3.html) — dashboard-style demo using CSS Container Queries and simple UI scripts (see [`menuToggle`](index3.html), [`settingsLink`](index3.html), [`btnDark`](index3.html)).

## Quick start
1. Open any of the HTML files in your browser, or serve the folder:
   ```sh
   npx serve .
   ```
2. Interact with the demos to see element-level responsiveness and container queries in action.

## Notes
- Use [index2.html](index2.html) as a copy-pasteable web component for projects.
- [index3.html](index3.html) demonstrates container queries for adaptive grids and simple theme toggling.
