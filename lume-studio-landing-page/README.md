# Lumé Studio — Responsive Marketing Landing Page

A responsive, single-page marketing website for a fictional fashion brand. Built with semantic HTML5 and custom CSS.

## Features

- Semantic HTML landmarks and accessible labels
- Responsive navigation with a mobile menu
- CSS Grid and Flexbox layouts
- Responsive breakpoints for desktop, tablet, and mobile
- Product/collection cards and marketing sections
- Keyboard focus styles and reduced-motion support
- No horizontal page scrolling intended at supported viewport widths
- No build tools or JavaScript framework required

## Project files

- `index.html` — page content and semantic structure
- `style.css` — design, layout, and responsive rules

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a browser.

For a local development server, open the project folder in VS Code and use the Live Server extension, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Responsive testing checklist

Test at widths around 320px, 360px, 390px, 768px, 1024px, and 1440px.

- [ ] No horizontal scrollbar appears.
- [ ] Navigation opens and closes on mobile.
- [ ] Product cards stack on small screens.
- [ ] Text and buttons remain readable and usable.
- [ ] Images scale without overflowing.
- [ ] Links move to the correct page sections.
- [ ] Test in Chrome and at least one other browser.

## Publish with GitHub Pages

1. Create a new public repository on GitHub, for example `lume-studio-landing-page`.
2. Upload `index.html`, `style.css`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. The URL will be shown in the Pages settings.

## Customization

Replace the fictional brand name, copy, product descriptions, and image URLs with your own choices. The images and Google Fonts are loaded from external services, so an internet connection is needed for those assets to appear.

## Credits

Portfolio practice project created for a frontend development task. Product photography is loaded from Unsplash image URLs; the images remain hosted by Unsplash.
