# Christian García — Abogado Penalista

Landing page for a (fictional) criminal defense law firm. A frontend showcase built with **vanilla HTML, CSS and JavaScript** — no frameworks, no build step.

## Highlights

- **Editorial design system**: color tokens, serif display (Fraunces) + sans body (Inter), fluid type scale with `clamp()`.
- **Responsive**: from 320px to 1440px, mobile-first, no overflow.
- **Accessible (WCAG 2.1 AA)**: skip link, semantic landmarks, visible focus, labeled form fields, `prefers-reduced-motion`.
- **SEO**: meta description, Open Graph/Twitter cards, JSON-LD `Attorney`, favicon.
- **Performance**: WebP images, no icon fonts (inline SVG), deferred lightweight JS.
- **Sections**: hero, trust strip, practice areas, about, process, testimonials, FAQ, contact.

## Stack

- HTML5
- CSS3 (custom properties, Grid, `clamp()`)
- Vanilla JS (`IntersectionObserver`, accessible nav, form validation)

## Structure

```
index.html
styles.css
main.js
favicon.svg
img/
  fondo-inicio.webp
  fondo-skills.webp
  photo.webp
  photo.png   # fallback
```

## Run locally

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8080
```

Then visit <http://localhost:8080>.

## Live preview

<https://jordanroberto74.github.io/christian-garcia-abg/>

## Notes

- **Demo / fictional content**: name, address, testimonials and stats are illustrative.
- The contact form is **front-end only**: it validates fields and shows a success state; no backend.

## Contact

[jordanroberto74@gmail.com](mailto:jordanroberto74@gmail.com)
