# Science and the World

Course website, published at https://joymonteiro.github.io/science_and_the_world/

GitHub Pages builds the site with plain Jekyll on every push to `main`; there is
no theme. The look lives in `_layouts/default.html` and `css/site.css`, copied
from [intro_climate_science](https://github.com/JoyMonteiro/intro_climate_science).

## Layout

- `index.md`: the course page and lecture list. Course details (code,
  semester, contact, license) are in its front matter.
- `notes/L0-…md` to `notes/L8-…md`: lecture notes, one page each. The page
  title comes from the `title:` front matter, not a `#` heading. Prev/next
  links follow file-name order, so keep the `L<n>-` prefix.
- `presentation/`: placeholder for the course presentation.

## Publishing the presentation

The course is one canvas built in [pres-sure](https://joymonteiro.github.io/pres-sure/).
Export it, delete `presentation/index.md`, and put the exported `index.html`
(and any images next to it) in `presentation/`. The link on the course page
already points there.
