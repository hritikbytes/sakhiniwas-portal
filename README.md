# Sakhi Niwas

A responsive website for Sakhi Niwas, a student and working women's hostel in Ranchi.

**Live:** https://sakhiniwas-portal.vercel.app/

| Desktop Home | Mobile View |
|:---:|:---:|
| ![Landing Page](./screenshots/home.png) | ![Mobile Facilities](./screenshots/mobile.png) |

The site gives prospective residents a quick way to explore the hostel, compare room options, view facilities and photos, check the location, and send an enquiry.

- Room options and pricing
- Facilities and amenities
- Photo gallery
- Embedded location map
- WhatsApp and phone contact links
- Enquiry form through Formspree
- Responsive layout across desktop and mobile

## Built with

HTML · Tailwind CSS v4 · JavaScript · Lottie · Formspree

## A couple of things I worked on

The testimonial section uses a CSS-only marquee. The cards are duplicated and moved with `@keyframes`, with the animation pausing on hover. No JavaScript scroll listener is needed.

The mobile menu is handled with a small vanilla JavaScript module. It takes care of opening/closing the menu, Escape key handling, outside clicks, and the relevant ARIA attributes.

The facility illustrations use Lottie web components, while Formspree handles the enquiry form without needing a separate backend.

## Run locally

    git clone https://github.com/hritikbytes/sakhiniwas-portal.git
    cd sakhiniwas-portal
    npm install
    npm run dev

`npm run dev` watches the Tailwind source and rebuilds the CSS.

To preview the site locally, open `index.html` or use a local static server such as:

    npx serve .

## Status

Personal project / deployed demo.
