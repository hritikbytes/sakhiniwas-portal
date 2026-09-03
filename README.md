# Sakhi Niwas Hostel Portal

A responsive multi-page website and accommodation brochure for Sakhi Niwas, a student and working women's hostel based in Ranchi, Jharkhand.

**Live Demo:** [sakhiniwas-portal.vercel.app](https://sakhiniwas-portal.vercel.app)

| Desktop Home | Mobile View |
|:---:|:---:|
| ![Landing Page](./screenshots/home.png) | ![Mobile Facilities](./screenshots/mobile.png) |

## What this project is

I built this site as a clean, responsive web presence for a local hostel. It lets prospective residents check room options (twin and triple sharing), explore facilities through animated cards, browse photos, locate the campus via an embedded map, and send direct enquiries via WhatsApp or the contact form.

### Pages
- **Home (`index.html`)**: Overview of the hostel, photo collage, key benefits, student review marquee, room rates, and location map.
- **Rooms (`rooms.html`)**: Pricing, inclusions, and amenity comparisons between Double Comfort and Triple Social rooms.
- **Facilities (`facilities.html`)**: Showcase of 12 hostel amenities (24/7 CCTV, security guard, doctor on call, RO water, WiFi, etc.) with animated Lottie vector icons.
- **Gallery (`gallery.html`)**: Visual tour of living spaces, study areas, and community life.
- **Contact (`contact.html`)**: Location details, direct phone/WhatsApp quick actions, and a Formspree-backed enquiry form.

## Tech Stack & Notable Details

- **Static Multi-Page HTML + Tailwind CSS v4:** Built without a heavyweight framework like React. For an accommodation brochure and enquiry site, static HTML with Tailwind CLI keeps the bundle size negligible and loading instant.
- **CSS-Only Testimonial Marquee:** The reviews on the home page use a pure CSS `@keyframes` transform over duplicate cards with a `mask-image` gradient for faded edges, pausing on hover without any JavaScript scroll listeners.
- **Lottie Vector Animations:** Facility cards use `@lottiefiles/lottie-player` web components to play lightweight JSON vector animations.
- **Accessible Mobile Navigation:** A minimal vanilla JavaScript handler in `script.js` manages mobile hamburger toggling, ARIA attributes, escape-key dismiss, and outside-click closing.
- **Formspree:** Used for form submissions on the contact page without needing a dedicated backend server.
- **Hosting:** Hosted on Vercel with automatic builds configured through `vercel.json`.

## Local Development

```bash
# Clone the repository
git clone https://github.com/hritikbytes/sakhiniwas-portal.git
cd sakhiniwas-portal

# Install Tailwind dependencies
npm install

# Watch styles during development
npm run dev

# Build production CSS
npm run build
```

To preview, open `index.html` directly in your browser or run `npx serve .` or `python3 -m http.server 3000`.

## About

- **Developer:** Hritik Sharma
- **GitHub:** [@hritikbytes](https://github.com/hritikbytes)
- **LinkedIn:** [Hritik Sharma](https://www.linkedin.com/in/hritiksharma0608/)
- **Email:** hritiksharma.0608@gmail.com
