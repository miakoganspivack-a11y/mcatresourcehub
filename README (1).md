# MCAT Resource Hub

A single-page, self-contained web app that helps MCAT students browse and compare
prep resources and build a personalized, editable study plan.

## What's here
- **index.html** — the entire app (HTML + CSS + JS in one file). No build step, no dependencies.
- **.nojekyll** — tells GitHub Pages to serve files as-is (skip Jekyll processing).

## How it's hosted
Served as a static site on GitHub Pages from the repository root.
Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/(root)`.

## Editing
Edit `index.html` directly. Everything (resource catalog, quiz logic, study-plan engine,
editable calendar) lives in that one file. Students' plans save in their own browser
(localStorage) and can be exported as a `.json` backup or an `.ics` calendar file.
