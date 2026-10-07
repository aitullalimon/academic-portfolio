# Limon Aitulla Labib — Research & Engineering Portfolio

A responsive academic and engineering portfolio featuring explainable AI, machine learning, LLM evaluation, and applied software projects.

## Open the live portfolio

[Open the portfolio](https://aitullalimon.github.io/academic-portfolio/) — available publicly without running a local server.

## Features

- 16 portfolio entries, including 12 public GitHub repositories reviewed in October 2026
- Short project descriptions and accessible project detail dialogs
- Category filters and technology-aware search
- Light and dark themes with browser-local preference storage
- Animated research illustration with reduced-motion support
- Responsive layouts and keyboard focus indicators
- Direct GitHub, email, and Upwork links

## Featured PhD prototype

[Bangladesh Early Warning — live demo](https://aitullalimon.github.io/bangladesh-early-warning-prototype/?v=voyager) · [Source and research notes](https://github.com/aitullalimon/bangladesh-early-warning-prototype)

Demonstrates flood and lightning warning communication, all 8 divisions and 64 districts, preparedness checklists, citizen feedback, a support-team dashboard, and Condition A versus Condition B evaluation. Warnings are synthetic, guidance is scripted, and requests remain in the same browser; the demo does not run a live LLM or dispatch assistance.

## Project structure

```text
index.html                  Page structure and academic profile
style.css                   Responsive design and themes
app.js                      Project data and interactive behavior
.github/workflows/pages.yml GitHub Pages deployment
```

## Run locally (optional, for development)

No dependencies or build step are required. From the project folder, run:

```sh
python3 -m http.server 8000
```

After starting the command above, open `http://localhost:8000` on the same computer. This development address is available only while the local server is running. To view the published website, use the live portfolio link above.

## Publish on GitHub Pages

In the repository’s **Settings → Pages**, choose **GitHub Actions** as the source. The included workflow deploys the root website when changes are pushed to `main`, or when manually triggered.

## Update portfolio content

Edit the `projects` array in `app.js` to add entries, change descriptions, or adjust repository links. Edit `index.html` for biography, research interests, and contact information. Repository scaffolds and collaboration profiles are identified in their descriptions; project demo availability is not implied by source links.

## Checks

```sh
node --check app.js
```

The gallery was checked for rendering, category filtering, search, empty results, and project detail opening. The published website was also visually inspected, and its search and project details were checked in the browser.

## Author

**Limon Aitulla Labib** · Kyoto, Japan
GitHub: https://github.com/aitullalimon

This repository contains portfolio code and descriptions. Linked projects retain their own licensing terms.

