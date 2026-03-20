# IHS Data Hub — Master Data Management Wireframe

A single-page web application wireframe for **Infinity Home Services** — a specialty exterior remodeling company managing 25 brands and product purchasing across three distributors (ABC Supply, QXO, and SRS/BMCA). The tool provides a merchandising team with four core views: an **Item Master** for browsing and inline-editing all 15 GAF roofing SKUs with governed price, floor, ceiling, and GM threshold controls; an **Anomaly Dashboard** that surfaces pricing deviations as color-coded cards (red >10%, amber 5–10%, yellow <5%) with one-click Approve/Escalate actions; a **Brand Price Sheet** with a per-brand cost/margin table and PDF export via `window.print()`; and a **Settings** panel for editing GM thresholds, tolerance bands, and managing brands and distributors — all persisted to `localStorage` with no back-end required. The entire application is a single `index.html` file with inline CSS and JavaScript; open it directly in a browser or deploy to GitHub Pages without any build step.

## Usage

Open `index.html` in any modern browser. All data is saved automatically to your browser's local storage.

## Deploy to GitHub Pages

Push this repository to GitHub, then enable **Settings → Pages → Deploy from branch → main / root**.
