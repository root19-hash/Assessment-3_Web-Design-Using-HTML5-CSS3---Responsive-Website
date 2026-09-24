# Assessment 3 Test Report

## Static checks

- All five HTML pages link to `style.css`.
- All five pages include a keyboard skip link targeting `#main-content`.
- Local image, video, favicon, and page references resolve from the repository.
- `git diff --check` passes.
- No JavaScript or external CSS framework was added.

## Responsive browser checks

The integrated browser was checked at requested viewport settings corresponding to mobile (`375px`), tablet (`768px`), and desktop (`1200px`). The browser surface reported effective CSS widths of approximately `300px`, `615px`, and `960px`; the responsive rules were evaluated against those effective widths.

- Mobile: navigation stacks vertically, content grids use one column, and no horizontal overflow was detected.
- Tablet-sized check: no horizontal overflow was detected; the browser's effective width remained below the `640px` tablet breakpoint.
- Desktop-sized check: navigation uses a row layout, hero/content grids expand, and no horizontal overflow was detected.
- Keyboard: the first Tab focus reaches the visible skip link and its focus outline is present.

## Publication

The redesign was published to the configured `origin main` remote through sequential milestone commits. `README.md` was intentionally left untouched during this redesign as requested.
