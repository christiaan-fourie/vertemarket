# VerteMarket

Static landing page for VerteMarket, a cross-border procurement and logistics platform.

## Contents

- `vertemarket.html`: Main site file

## Usage

Open `vertemarket.html` directly in a browser, or serve the directory with any static file server.

## GitHub Pages

This repo includes a GitHub Actions workflow that publishes the site from `main`.

After pushing, set the repository Pages source to `GitHub Actions` in GitHub settings once. The workflow copies `vertemarket.html` to `index.html` during deployment so the site loads at the Pages root.

## Notes

- The HTML file is intentionally kept as a single self-contained page.
- No build step is required.
