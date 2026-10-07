# Limon Aitulla Labib — Research & Engineering Portfolio

A responsive academic and engineering portfolio featuring explainable AI, machine learning, LLM evaluation, and applied software projects.

## Features

- 15 portfolio entries, including 11 public GitHub repositories reviewed in October 2026
- Short project descriptions and accessible project detail dialogs
- Category filters and technology-aware search
- Light and dark themes with browser-local preference storage
- Animated research illustration with reduced-motion support
- Responsive layouts and keyboard focus indicators
- Direct GitHub, email, and Upwork links

## Project structure

```text
index.html                  Page structure and academic profile
style.css                   Responsive design and themes
app.js                      Project data and interactive behavior
.github/workflows/pages.yml GitHub Pages deployment
```

## Run locally

No dependencies or build step are required.

```sh
python3 -m http.server 8000
```

Open http://localhost:8000.

## Publish on GitHub Pages

In the repository's **Settings → Pages**, choose **GitHub Actions** as the source. The included workflow deploys the root website when changes are pushed to `main`, or when manually triggered.

## Update portfolio content

Edit the `projects` array in `app.js` to add entries, change descriptions, or adjust repository links. Edit `index.html` for biography, research interests, and contact information. Repository scaffolds and collaboration profiles are identified in their descriptions; project demo availability is not implied by source links.

## Checks

```sh
node --check app.js
```

The portfolio gallery was also checked for initial rendering, category filtering, search, empty results, and project detail opening. Visual browser verification remains outstanding.

## Author

**Limon Aitulla Labib** · Kyoto, Japan  
GitHub: https://github.com/aitullalimon

This repository contains portfolio code and descriptions. Linked projects retain their own licensing terms.
