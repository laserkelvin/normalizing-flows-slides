
# Reveal.js template

Meant to be a quick and simple workflow for setting up a reveal.js slide deck.

## Key features

### Styling

- Generally speaking, the minimialist approach to slide creation is realized with `dist/theme/minimalist.css`, and colored theming is done by inheriting from that file and overriding the color variables.
- Most recent one is `pastel.css`&mdash;honestly not an accurate reflection, but it's "Intel colors"

### Layout

- Use `x-col` and `x-grid` liberally for grid based layouts

### Chalkboard

- Use 'c' to do live markups
- Use 'b' to toggle chalkboard (see the chalkboard plugin)
- Press 'del' to clear the screen, and 'backspace' to delete a chalkboard
- Configuration for the chalkboard can be found at the bottom of `Reveal.initialize`.
- [See the repository for details.](https://github.com/rajgoel/reveal.js-plugins/tree/master/chalkboard)

