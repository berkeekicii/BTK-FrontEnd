# BTK-FrontEnd

A responsive, multi-page real-estate listing website built with plain HTML, Bootstrap 5 and SCSS. I put it together while working through front-end training material, to practise layout, components and responsive design.

**Live demo:** https://berkeekicii.github.io/BTK-FrontEnd/

## Pages

| Page | Description |
| --- | --- |
| `index.html` | Landing page: hero section, property cards, city sections, content blocks and footer |
| `liste.html` | Listing page with a category/filter sidebar and a grid of property cards |

## Built with

- HTML5 and CSS3 (SCSS source in `assets/scss/`, compiled to `assets/css/style.min.css`)
- [Bootstrap 5.3.3](https://getbootstrap.com/) for the grid, navbar and form components
- [Swiper 11](https://swiperjs.com/) for sliders
- [lazysizes](https://github.com/aFarkas/lazysizes) for lazy image loading
- SVG icons in `assets/img/icon/`

## Project structure

```text
.
├── index.html
├── liste.html
└── assets/
    ├── css/    # compiled stylesheet
    ├── scss/   # SCSS source
    └── img/
        ├── icon/    # SVG and PNG icons
        └── image/   # photos
```

## Run locally

No build step is needed. Clone the repository and open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- This is a front-end practice project, not a working product. The listings, prices and addresses are placeholder content, and there is no backend or search logic.
- The layout follows a "JustHome" real-estate template style that I used as a learning reference, so the design is not my original concept; the implementation and file organisation are my own practice work.
- Some navigation links point to `#` because those pages do not exist yet.

## Author

Berke Ekici, Computer Engineering student at Mersin University.
[GitHub](https://github.com/berkeekicii)
