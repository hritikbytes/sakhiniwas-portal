# Sakhi Niwas Hostel Portal

A responsive multi-page website and accommodation brochure for Sakhi Niwas, a student and working women's hostel based in Ranchi, Jharkhand.

**Live Demo:** [https://sakhiniwas-portal.vercel.app](https://sakhiniwas-portal.vercel.app)

---

## Preview

| Desktop Home | Mobile View |
|:---:|:---:|
| ![Landing Page](./screenshots/home.png) | ![Mobile Facilities](./screenshots/mobile.png) |

---

## Overview

This project is a digital brochure and enquiry portal built to showcase the hostel's rooms, facilities, location, and student life. Visitors can check accommodation rates, see animated amenities, view photos, get map directions, and submit an enquiry directly to the hostel management.

### Pages & Sections
- **Home (`index.html`)**: Hero presentation, photo collage, highlight cards, CSS marquee testimonials, room pricing preview, and Google Maps embed.
- **Rooms (`rooms.html`)**: Detailed breakdowns for Double Sharing (₹12,500/mo) and Triple Sharing (₹10,000/mo) accommodations including inclusions and amenities.
- **Facilities (`facilities.html`)**: Grid of 12 hostel amenities (24/7 CCTV, doctor on call, RO water, WiFi, power backup, etc.) animated with Lottie JSON players.
- **Gallery (`gallery.html`)**: Bento-style photo grid of hostel living spaces and student activities.
- **Contact (`contact.html`)**: Contact details, direct WhatsApp/Call links, and a functional enquiry form connected to Formspree.

---

## Tech Stack

- **Markup & Layout:** HTML5 (multi-page structure)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/) via `@tailwindcss/cli`
- **Typography:** Google Fonts (*Lato* and *Satisfy*)
- **Scripting:** Vanilla JavaScript (`script.js` for mobile menu toggle and accessibility)
- **Animations:** [LottieFiles Web Player](https://lottiefiles.com/) for lightweight SVG vector animations
- **Form Handling:** [Formspree](https://formspree.io/) for serverless form submissions
- **Deployment:** [Vercel](https://vercel.com/) (automatic builds configured via `vercel.json`)

---

## Implementation Details

- **Static Multi-Page Architecture:** For an informational brochure and booking enquiry site, static HTML with Tailwind CSS delivers instant page loads and zero JavaScript bundle overhead compared to a heavy client-side SPA.
- **CSS-Only Testimonial Marquee:** The resident reviews on the home page use a pure CSS `@keyframes` translate animation across duplicate card sets. A CSS `mask-image` gradient creates smooth edge fade-outs, and the marquee pauses on `:hover`.
- **Accessible Mobile Navigation:** A lightweight vanilla JavaScript toggle manages `aria-expanded` and `aria-hidden` attributes, closes when tapping outside or pressing Escape, and automatically hides after clicking a link.

---

## Local Setup & Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hritikbytes/sakhiniwas-portal.git
   cd sakhiniwas-portal
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Watch Tailwind CSS changes during development:**
   ```bash
   npm run dev
   ```

4. **Build Tailwind CSS for production:**
   ```bash
   npm run build
   ```

5. **View the site:**
   Open `index.html` directly in your browser, or start a local static server:
   ```bash
   npx serve .
   # or
   python3 -m http.server 3000
   ```

---

## Project Status

This is an independently developed personal project and live demo. The site is deployed and hosted on Vercel.

---

## Contact

- **Developer:** Hritik Sharma
- **GitHub:** [@hritikbytes](https://github.com/hritikbytes)
- **LinkedIn:** [Hritik Sharma](https://www.linkedin.com/in/hritiksharma0608/)
- **Email:** hritiksharma.0608@gmail.com
