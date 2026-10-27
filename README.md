# CampusFind — Sample Midterm Demo

A small, accessible, responsive, multi-page website for demonstrating **GitHub Pages deployment**. Built with plain HTML, CSS, and JavaScript.

## Pages
- `index.html`: browse, search, and filter items
- `report.html`: report an item using a validated form
- `details.html`: view a specific report

## How to run
Open `index.html` in a browser. No build step or API keys are needed.

## How to publish with GitHub Pages
1. Create a **new public repository** named `campus-lost-found-demo` (do not overwrite your existing portfolio repository).
2. Upload **all** the files in this folder to the repository root.
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. Wait for publishing. Your URL will look like `https://YOUR-USERNAME.github.io/campus-lost-found-demo/`.
6. Test all three pages, form submission, search/filtering, mobile layout, and keyboard navigation.

## Important limitations
- This is a **front-end demonstration**, not a real campus service.
- New reports use **localStorage**, so they are visible only in the same browser/device. They are not shared with other users.
- Sample contact addresses are fictional. Do not enter real personal information in the demo.
- Accessibility features include labels, semantic landmarks, keyboard focus indicators, skip link, form validation, and live results count. Students should still perform manual accessibility testing.

## Suggested recording sequence
1. Show the three HTML pages and shared CSS/JS files.
2. Open `index.html`, search and filter, open item details.
3. Submit a test report; explain localStorage.
4. Resize browser to mobile width; tab through controls with keyboard.
5. Create a separate GitHub repository and upload the files.
6. Enable GitHub Pages and open the live project URL.
7. Explain how a project site coexists with an existing portfolio site.
