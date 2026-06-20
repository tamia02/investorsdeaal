# Investors Deaal — Premium Real Estate Landing Page

A single-page, luxury real estate landing page designed to capture and convert high-intent property buyers and investors in Delhi NCR. Inspired by premium architectural sites, this landing page features a dark, cinematic design with elegant typography, bold stat counters, interactive listing cards, and smooth scroll animations.

## Directory Structure

```
investors-deaal/
├── index.html          # Main application file (HTML, CSS, JS)
├── assets/
│   ├── logo.svg        # Placeholder brand logo SVG
│   └── hero-bg.jpg     # Cinematic city night skyline background
└── README.md           # Documentation
```

## Features Implemented

1.  **Navbar:** Sticky top bar with custom blurring on scroll and a mobile-responsive menu overlay.
2.  **Hero Section:** Fullscreen viewport display with a dark overlay, Ken Burns slow zoom visual effect, and a continuous ticker loop.
3.  **Trust Bar (Stats Strip):** Auto-counting statistics with custom delay triggers using `IntersectionObserver`.
4.  **Services:** Interactive property card grid emphasizing Plots, Flats, Farm Houses, and Village land.
5.  **Why Choose Us:** Structured split layout detailing listing verification and ROI metrics.
6.  **Featured Listings:** Flexible grid with a double-width primary spotlight card, badge overlays, and specs.
7.  **How It Works:** Step-by-step progress guide featuring interactive dashed gold connects.
8.  **Awards & Recognition:** Infinite sliding awards track simulating SYY Infra's corporate slider.
9.  **Testimonials:** Premium styled rating cards with decorative custom quotations.
10. **Areas We Cover:** responsive hover grid with glow borders.
11. **Lead Form & CTA:** High-conversion intake form with validation, alongside a dedicated WhatsApp redirect button.
12. **Footer:** Comprehensive site details including full RERA information, location details, and structured menus.

## Customization & Setup

This landing page requires **no build steps or servers** to run. You can open `index.html` directly in any web browser.

### Configuring WhatsApp & Contact Details
To update contact routes:
1. Open `index.html` in an editor.
2. Search for the following strings and replace them with your actual details:
   - **Phone Number:** Search for `+91 XXXXX XXXXX` and replace with your phone number (e.g., `+91 99999 99999`).
   - **Email:** Search for `info@investorsdeaal.com` and replace with your email.
   - **Office Address:** Search for `[Full Office Address]` and replace with your location.
   - **RERA Registration Number:** Search for `[XXXXXXXXXX]` and replace it with your license ID.
   - **WhatsApp Link:** Look for `href="https://wa.me/91XXXXXXXXXX"` and update with your exact mobile number (format: `91` followed by 10 digits).

### Adding Real Property Images
To replace listing placeholders:
- Update the source attribute `src` in `.listing-image` elements (currently pointing to generated gradient placeholders) with actual URL links or local asset paths.
