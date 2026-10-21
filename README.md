# Thiranex Task 2 — Advanced CSS3 & Responsive Architecture

A polished, mobile-first portfolio landing page built with semantic HTML5, modern CSS3, and vanilla JavaScript. It demonstrates CSS Grid, Flexbox, responsive breakpoints, CSS custom properties, and a persistent light/dark theme.

## Features

- **Responsive layouts:** CSS Grid for page sections and project cards; Flexbox for navigation, buttons, skill tags, and metadata.
- **Mobile-first navigation:** accessible menu toggle on smaller screens, which closes after a navigation item is selected.
- **Light/dark theme:** CSS variables power both themes. The selected theme is saved in `localStorage`; the first visit respects the operating-system preference.
- **Responsive breakpoints:** tablet and mobile layouts, including compact-screen refinements.
- **Semantic and accessible HTML:** landmarks, descriptive links, keyboard focus indicators, skip link, button labels, and reduced-motion support.
- **No framework required:** plain HTML, CSS, and JavaScript; Google Fonts are an optional online enhancement.
- **Decorative project mockups:** CSS-built visuals avoid large external image downloads.

## Project structure

```text
thiranex-task2-responsive-portfolio/
├── index.html
├── README.md
├── css/
│   └── styles.css
└── js/
    └── script.js
```

## Run locally

1. Download and extract the project ZIP.
2. Open the project folder.
3. Double-click `index.html` to open it in a browser.

For a local development server, open the folder in VS Code and use the **Live Server** extension, or run:

```bash
python -m http.server 5500
```

Then visit `http://localhost:5500`.

## Customize before submission

This project uses **Alex Morgan** and sample contact links as demonstration content. Replace these details with your own:

1. Update the page title, name, introduction, skills, and project descriptions in `index.html`.
2. Replace `hello@example.com` with an email address you want to receive messages at.
3. Replace the GitHub, LinkedIn, and Instagram profile URLs with your actual profile URLs.
4. Keep the project descriptions accurate; only claim skills and experience you can explain.
5. Preview at mobile, tablet, and desktop widths before submitting.

## Requirement checklist

- [x] CSS Grid for two-dimensional layouts
- [x] Flexbox for component alignment
- [x] Mobile-first responsive media queries
- [x] CSS custom properties for theme colors and surfaces
- [x] Working light/dark theme toggle
- [x] Theme persistence through `window.localStorage`
- [x] Responsive navigation menu
- [x] Semantic HTML and keyboard focus styling
- [x] Reduced-motion preference support
- [x] Submission README and documented folder structure

## Deploy to Netlify

### Option A: Netlify Drop

1. Extract the ZIP.
2. Open Netlify Drop: <https://app.netlify.com/drop>.
3. Drag the extracted project folder (containing `index.html`) into the drop area.
4. Wait for the deployment to finish and open the generated public URL.
5. Test the URL on a phone and desktop, then submit that URL if the portal accepts live links.

### Option B: GitHub + Netlify

1. Create a GitHub repository and upload `index.html`, `css/`, `js/`, and `README.md`.
2. In Netlify, choose **Add new site / Import an existing project** and connect the repository.
3. Since this is a static site, leave the build command blank and set the publish directory to the repository root (`.`).
4. Deploy and test the generated URL.

## Browser support

Designed for current versions of Chrome, Edge, Firefox, and Safari. Google Fonts require an internet connection; the page remains usable with fallback fonts if the font service is unavailable.

## Notes

- This is a frontend portfolio template; it does not include a backend or a contact form submission service.
- All sample identity and project content should be personalized before claiming the project as your own.
