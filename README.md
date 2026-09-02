# Zorvilla — Website

A fully responsive music theory, ear training &amp; composition coaching website built with plain HTML, CSS and JavaScript (no build step required).

## Structure

```
index.html            Main page (Home, About, Programs, Schedule, Testimonials, Pricing, Contact)
assets/css/style.css   Styles (mobile-first, responsive breakpoints)
assets/js/script.js    Mobile nav, scroll effects, reveal animations, contact form
```

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Features

- Fully responsive layout (mobile, tablet, desktop breakpoints)
- Sticky header with mobile hamburger menu
- Hero, About, Programs, Schedule, Testimonials, Pricing, CTA, and Contact sections
- Scroll-reveal animations (respects `prefers-reduced-motion`)
- Accessible, semantic markup
- Client-side contact form validation with confirmation message
