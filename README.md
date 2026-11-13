# Polish Roots — Luxury Beauty & Hair Salon

A modern, responsive, and elegant website for **Polish Roots**, a premier beauty and hair salon specializing in precision haircutting, custom coloring (balayages and highlights), restorative treatments, and professional makeup artistry.

---

## Table of Contents

- [Overview](#overview)
- [Live Demo & Pages](#live-demo--pages)
- [Brand Philosophy](#brand-philosophy)
- [Key Features](#key-features)
- [Contact & Alternative Details](#contact--alternative-details)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [Deployment](#deployment)
- [License & Credits](#license--credits)

---

## Overview

**Polish Roots** provides an immersive digital experience for clients seeking premium salon and beauty services. The platform is crafted with a chic aesthetic, dynamic interactive components, and smooth parallax effects that showcase salon artistry, portfolio transformations, and provide frictionless appointment booking.

---

## Live Demo & Pages

The website consists of four dedicated, cohesive pages:

| Page | File | Description |
| :--- | :--- | :--- |
| **Home** | [`index.html`](index.html) | Brand introduction, signature services, curated portfolio preview, animated metrics counter, and appointment booking form. |
| **About** | [`about.html`](about.html) | Story of Polish Roots, master stylist philosophy, certifications, and dedication to root-to-tip hair health. |
| **Work** | [`work.html`](work.html) | High-definition visual gallery showcasing bridal styles, vibrant colorings, balayages, and makeup makeovers. |
| **Contact** | [`contact.html`](contact.html) | Direct message inquiry form, salon address, primary contact info, and alternative contact channels. |

---

## Brand Philosophy

> *"Your look is a part of your story, and our goal is to bring your vision to life."*

At **Polish Roots**, we believe great beauty begins with care and intention. Every cut, color formulation, and cosmetic styling is customized to highlight individuality, enhance natural features, and promote lasting hair vitality.

---

## Key Features

- **Responsive Design**: Flawlessly adapts to smartphones, tablets, laptops, and wide desktop screens.
- **Appointment Scheduling**: Built-in interactive datepicker (`bootstrap-datepicker`) allowing clients to select appointment dates with ease.
- **Interactive Metric Counters**: Animated client satisfaction and service statistics powered by jQuery Waypoints and `jquery.animateNumber`.
- **Media Gallery & Lightbox**: Rich portfolio previews equipped with Magnific Popup for full-screen image viewing.
- **Parallax & Motion Effects**: Smooth visual depth via Stellar.js and Scrollax.
- **Direct Inquiry Forms**: Netlify-ready contact and booking forms (`data-netlify="true"`).
- **Dual Contact Channels**: Primary and alternative contact numbers and emails to guarantee seamless client communication.

---

## Contact & Alternative Details

To ensure clients and partners always have an active line of communication, Polish Roots maintains both primary and alternative contact channels:

| Channel | Primary Detail | Alternative Detail |
| :--- | :--- | :--- |
| **Address** | 1244 Heritage Way, Suite 200, Pembroke Pines, FL 33028 | — |
| **Phone** | **+1 (954) 555-0188** | **+1 (954) 555-0189** |
| **Email** | **contact@polishroots.com** | **support@polishroots.com** |
| **Website** | [www.polishroots.com](https://polishroots.com) | — |
| **Hours** | Monday – Sunday: 10:00 AM – 6:00 PM | Extended appointments upon request |

---

## Technology Stack

- **Markup & Layout**: HTML5, CSS3, SCSS (SASS)
- **CSS Framework**: Bootstrap v4.1.0
- **Typography & Icons**: 
  - [Montserrat](https://fonts.google.com/specimen/Montserrat) via Google Fonts
  - Flaticon, Icomoon, Ionicons, and Open Iconic Bootstrap
- **JavaScript & Libraries**:
  - [jQuery](https://jquery.com/) (v3.2.1)
  - [Popper.js](https://popper.js.org/)
  - [Bootstrap JS](https://getbootstrap.com/)
  - [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/)
  - [Magnific Popup](https://dimsemenov.com/plugins/magnific-popup/)
  - [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)
  - [Stellar.js](https://markdalgleish.com/projects/stellar.js/) & [Scrollax](https://github.com/ustimoff/scrollax)
  - [Bootstrap Datepicker](https://github.com/uxsolutions/bootstrap-datepicker) & Timepicker

---

## Project Structure

```text
Polish-Roots/
├── about.html              # About Polish Roots, history, and stylists
├── contact.html            # Contact information, alternative details, and message form
├── index.html              # Homepage with hero, services, counters, and booking form
├── work.html               # Portfolio gallery showcasing salon styles and makeup
├── prepros-6.config        # Prepros build configuration for SCSS compilation
├── README.md               # Project documentation
├── css/                    # Compiled and vendor stylesheets
│   ├── style.css           # Core compiled stylesheet
│   ├── bootstrap.min.css   # Bootstrap 4 stylesheet
│   ├── animate.css         # CSS animation keyframes
│   ├── aos.css             # Animate On Scroll styles
│   ├── owl.carousel.min.css# Owl Carousel slider styles
│   └── magnific-popup.css  # Lightbox modal styles
├── scss/                   # SASS source stylesheets
│   ├── style.scss          # Primary SCSS file
│   └── bootstrap/          # Bootstrap SASS components
├── js/                     # Scripts and plugins
│   ├── main.js             # Site interaction, carousel, and scroll handlers
│   ├── google-map.js       # Google Maps helper
│   ├── jquery-3.2.1.min.js # jQuery library
│   └── bootstrap.min.js    # Bootstrap scripts
├── fonts/                  # Web font files (Flaticon, Icomoon, Ionicons, Open Iconic)
└── images/                 # Image assets and background textures
```

---

## Getting Started

### Prerequisites

No backend runtime or database is strictly required to view the site; it runs out of the box in any modern web browser.

### Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Polish-Roots.git
   cd Polish-Roots
   ```

2. **Open directly**:
   Double click [`index.html`](index.html) or open it with your browser.

3. **Using a local development server** (recommended for asset paths and Google Maps):
   - **VS Code Live Server**: Right-click `index.html` and select **"Open with Live Server"**.
   - **Python 3**:
     ```bash
     python -m http.server 8000
     ```
     Navigate to `http://localhost:8000` in your web browser.
   - **Node / npx**:
     ```bash
     npx serve .
     ```

---

## Customization

### Updating Contact & Alternative Details
Contact information can be updated across the following templates:
- [`index.html`](index.html#L201-L222): In the `.appointment-info` card located beside the booking form.
- [`contact.html`](contact.html#L71-L95): In the `.contact-info` block with primary and alternative lines.

### Modifying Brand Name or Logo
- Search for the `<title>` tags and `.navbar-brand` elements across all HTML pages.
- The hero logo text is located inside `<a href="index.html" class="logo"><h1>Polish Roots</h1></a>`.

### Styling & Theme Colors
The theme accent color is `#fa5bdd`. To recompile or modify:
1. Edit variables in [`scss/style.scss`](scss/style.scss#L10).
2. Compile SCSS into `css/style.css` using Prepros, Sass CLI (`sass scss/style.scss css/style.css`), or VS Code Live Sass Compiler.

---

## Deployment

### Netlify
1. Connect your repository to [Netlify](https://www.netlify.com/).
2. Set build command to empty (static HTML) and publish directory to `.`.
3. The contact and appointment forms automatically capture submissions using the `data-netlify="true"` attribute.

### GitHub Pages
1. Push your repository to GitHub.
2. Go to **Settings > Pages**.
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.

---

## License & Credits

- Original template baseline crafted by [Colorlib](https://colorlib.com) under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
- Customized and branded for **Polish Roots**.
