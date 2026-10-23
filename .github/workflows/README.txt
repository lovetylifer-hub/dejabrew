# Deja Brew Website

A responsive single-page website for the Deja Brew marketing campaign. The website uses HTML, CSS, and JavaScript in one `index.html` file.

## Run locally
Open `index.html` in a modern browser.

## Publish on GitHub Pages
1. Upload `index.html` to the root of a public GitHub repository.
2. Open Settings → Pages.
3. Select Deploy from a branch, choose `main` and `/(root)`, then save.
4. Wait for the published URL to appear.

## Features
- Semantic sections and anchor navigation
- Responsive layouts intended for 375px mobile and 1280px desktop
- Three priced menu products and an interactive demo tray
- November 1–30, 2026 campaign countdown with an expired state
- Three clearly labeled fictional sample testimonials
- Name/email/consent form with client-side validation and simulated success only
- No backend, payment processing, or personal-data storage/transmission

## Suggested test report
1. At 375px viewport: layout stacks and no horizontal page overflow.
2. At 1280px viewport: hero, product cards, campaign, and testimonials display in desktop layout.
3. Navigation links scroll to their matching sections.
4. Add menu products: item count and total update correctly; clear tray returns total to ₱0.
5. Submit empty form: required-field validation message appears.
6. Submit malformed email: email validation message appears.
7. Submit valid name/email without consent: consent message appears.
8. Submit valid name/email with consent: simulated success appears; no information is transmitted or stored.
9. Test countdown before November 1, during November 1–30, and after December 1, 2026; expired state must display “Offer ended”.
