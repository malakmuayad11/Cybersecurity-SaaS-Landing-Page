# SecureFlow 🛡️

SecureFlow is a modern, responsive landing page and SaaS platform built for cybersecurity services. Designed to showcase cutting-edge threat detection, monitoring, and pricing plans, SecureFlow prioritizes performance, accessibility, and clean user experience.

## Features

- Responsive Design: Optimized for mobile, tablet, and desktop devices with a clean mobile navigation toggle.

- Hero Section: Engaging headline, trademark statement, and clear call-to-action (CTA) buttons ("Get Started Free" and "Watch Demo").

- Key Metrics & Statistics: Highlights trust indicators such as active users, threat detection rate, monitoring uptime, and customer satisfaction.

- Feature Showcase: Details core platform capabilities including real-time threat detection, 24/7 monitoring, easy integrations, and detailed reporting.

- Pricing Tiers: Transparent pricing breakdown for Starter, Pro, and Enterprise subscription plans.

- Interactive FAQ Accordion: Clean collapsible sections answering common billing and trial questions using native HTML <details> and <summary> elements.

## Tech Stack

- HTML5: Semantic document structure with accessible markup.

- CSS3: Custom styling, modern layouts (Flexbox/Grid), and typography via Google Fonts (Inter).

- Accessibility (A11y): High-contrast UI elements, logical tab order, and screen-reader-friendly attributes.

## Project Structure

```
Cybersecurity SaaS Landing Page
├── index.html                  # Main HTML landing page document
├── assets/
│   ├── android-touch-icon.png  # Touch icon for Android devices
│   ├── apple-touch-icon.png    # Touch icon for Apple iOS devices
│   ├── favicon.svg             # Scalable vector graphic website favicon
│   └── logo.png                # Primary brand logo image asset
└── styles/
    ├── base.css                # Core element resets and foundational typography styles
    ├── buttons.css             # Reusable button components and interactive states
    ├── cards.css               # Container card component styles
    ├── faq.css                 # Layout and styling for the FAQ section
    ├── features.css            # Styling rules for the features grid and section
    ├── footer.css              # Page footer layout and copyright details
    ├── header.css              # Navigation bar and site header styling
    ├── hero.css                # Hero banner section styling and visual accents
    ├── main.css                # Master stylesheet importing individual CSS modules
    ├── prices.css              # Pricing plan card styles
    ├── print.css               # Print-specific style adjustments and media queries
    └── tokens.css              # Design tokens (CSS custom properties for colors, spacing, etc.)
```

## Getting Started

Follow these steps to run the project locally on your machine:

Clone the repository:

`git clone https://github.com/your-username/secureflow.git`


Navigate to the project directory:

`cd secureflow`


Open the project:

Open `index.html` directly in your favorite web browser, or

Use a live server tool (such as the Live Server extension in Visual Studio Code) for hot reloading.

## Accessibility Improvements & Audits

SecureFlow has been optimized following Lighthouse accessibility guidelines:

- Color Contrast: Foreground text and background elements meet WCAG AA standards (minimum 4.5:1 ratio for regular text and 3:1 for large headings/buttons).

- Keyboard Navigation: Follows a logical DOM tab order allowing keyboard-only users to navigate menus, buttons, pricing cards, and FAQ accordions seamlessly.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
