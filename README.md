# RailBook — Train Ticket Booking Web App

An elegant, retro-modern static train ticket booking web application inspired by vintage split-flap departure boards and classic railway aesthetics.

Live demo or static hosting ready with **zero dependencies** — runs directly in any modern browser.

---

## Features

- **Split-Flap Style Train Search:** Search between major Indian cities (New Delhi, Mumbai Central, Bengaluru City, Chennai Central, Kolkata Howrah, Ahmedabad) with live departure & arrival schedules.
- **Dynamic Pricing & Train Classes:** Supports multiple train tiers (Vande Bharat Express, Rajdhani Express, Shatabdi Express, Superfast Mail) across AC Executive, First AC, and AC Chair Car / 3-Tier classes.
- **Interactive Coach Seat Selection:** Real-time visual seat layout with aisle spacing, booked vs. available seat indicators, and dynamic passenger count enforcement.
- **Instant Boarding Pass Generation:** Generates a vintage railway ticket stub complete with route details, seat numbers, fare total, simulated QR code, and a unique 6-character PNR code.
- **Print & Save Support:** One-click boarding pass printing/export to PDF.
- **Live Digital Railway Clock:** Real-time synchronized railway header clock.
- **Responsive & Accessible Design:** Fully responsive layout with mobile fallback, dark theme, smooth micro-interactions, and accessibility considerations.
- **Zero Build Setup:** Pure Vanilla HTML5, CSS3, and JavaScript — no build steps, bundlers, or external frameworks needed.

---

## Project Structure

```text
.
├── index.html                   # Complete single-page application (UI, styles & logic)
├── .github/
│   └── workflows/
│       └── static.yml           # Automated deployment workflow to GitHub Pages
└── README.md                    # Project documentation
```

---

## Quick Start / Running Locally

Since this is a lightweight static application, you can run it using any of the following methods:

### Option 1: Direct File Open
Double-click [`index.html`](file:///c:/Users/srohi/Downloads/Train-Ticket-booking--main/index.html) or right-click and select **Open with** -> your favorite browser (Chrome, Edge, Firefox, Safari).

### Option 2: Python HTTP Server
If you prefer running via a local web server:

```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

### Option 3: VS Code Live Server
1. Open this folder in VS Code.
2. Install the **Live Server** extension.
3. Click **Go Live** from the bottom status bar.

---

## Deployment (GitHub Pages)

This repository includes a preconfigured GitHub Actions workflow in [`.github/workflows/static.yml`](file:///c:/Users/srohi/Downloads/Train-Ticket-booking--main/.github/workflows/static.yml).

To publish:
1. Push the code to the `main` branch of your GitHub repository.
2. In your GitHub repository settings, go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, choose **GitHub Actions**.
4. The workflow will automatically deploy your site on every push.

---

## Tech Stack

- **HTML5:** Semantic markup and modal dialogs.
- **CSS3:** Custom properties (CSS variables), CSS Grid & Flexbox, smooth animations, and custom print stylesheets.
- **JavaScript (ES6):** Deterministic mock train schedule generator, interactive seat map state manager, form validation, and PNR generator.
- **Typography:** Google Fonts ([DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display), [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono), [Inter](https://fonts.google.com/specimen/Inter)).

---

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
