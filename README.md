# Bottini Fuel — Website Clone

A front-end recreation of the Bottini Fuel corporate website, built as a
responsive design and CSS architecture exercise. The clone is re-skinned
under a fictional brand ("Pixel Perfect Fuel") with new logos and images.

## Stack

HTML5 · CSS3 · JavaScript (vanilla) · Lato (Google Fonts) · Font Awesome 6

## Running it

No build step — open `index.html` in a browser, or:

```bash
python -m http.server 8000
```

## What's in it

**Sections:** top utility bar, logo strip, full nav with dropdowns, hero,
CTA blocks, services cards (oil, propane, heating, cooling), mobile app
promo, testimonials, footer.

**CSS (`css/style.css`)** is organized with a table of contents and uses
custom properties throughout for colors, spacing, and typography. Follows a
mobile-first approach with BEM-style class naming. Two button variants
are documented — a skewed CTA button and a standard secondary button.

**JS (`js/main.js`)** handles:
- Anchor link scrolling
- Mobile hamburger menu toggle
- Required-field form validation
- Accordion expand/collapse
- Page load time logging to console

## Project structure

```
bottini-fuel-clone/
├── index.html
├── css/
│   ├── style.css       # Main styles (~table of contents at top)
│   └── utilities.css   # Helper classes
├── js/
│   └── main.js
└── img/                # Recreated assets (logos, hero, service icons)
```

## Notes

The original Bottini site uses no smooth scrolling — this clone matches
that intentionally (`behavior: 'auto'`). Navigation dropdowns are HTML/CSS
only; the hamburger menu is wired up in JS but the mobile nav markup is
ready to go.
