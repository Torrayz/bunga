# BLOOMING GARDEN ✿

An interactive CSS flower garden rebuilt from an early creative-web experiment.

## Highlights

- Original multi-layer CSS garden preserved
- Smooth floral motion and glow effects
- Accessible pause / resume control
- Respect for `prefers-reduced-motion`
- Improved mobile layout and introduction screen
- No account, backend, or database required

## Run

Open `index.html` from a static server, or publish with GitHub Pages. Continue to `flower.html` for the interactive garden.

## What changed

Previously, `css/main.css` ended with a rule that paused every descendant animation. The rule now applies only when the garden has the `is-paused` class. `garden-controls.js` manages the class and honors reduced-motion preferences.

The old autoplay audio element was removed. This release does not reproduce or stream any third-party music.

## Structure

- `index.html` — entry page
- `flower.html` — original flower structure with controls
- `css/main.css` — original flower animation
- `css/controls.css` — accessible floating controls
- `garden-controls.js` — pause/resume behavior
- `scss/main.scss` — retained editable Sass source

## Next

- Accessibility/browser visual QA
- Optional original, user-owned audio experience
- Theme selection and shareable garden scenes
