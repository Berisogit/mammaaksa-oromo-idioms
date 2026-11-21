# Mammaaksa — Oromo Idioms & Cultural Explorer

![Validate idioms.json](https://github.com/berisogit/mammaaksa-oromo-idioms/actions/workflows/validate-idioms.yml/badge.svg)

An interactive, offline-ready **Material Design 3 Progressive Web App (PWA)** preserving Afaan Oromoo idioms (*Mammaaksa*), literal poetic imagery, *Safuu* cultural context, and natural English equivalents.

## Live App
Once GitHub Pages is enabled in **Settings → Pages**, your app will be live at:
`https://berisogit.github.io/mammaaksa-oromo-idioms/`

## Features
- **Double-Tap 3D Flipping Flashcards:** Afaan Oromoo phrase & phonetic guide on the front; English equivalent, literal metaphor, cultural background, and example usage on the back.
- **Offline PWA Support:** Powered by `manifest.json` and `sw.js` so travelers, students, and diaspora families can install it on Android/iOS home screens and use it offline.
- **Reactions, Favorites & Local History:** Like/dislike reactions, saved favorites, local browser history, zoom controls (`85%`–`120%`), speech pronunciation, and PNG card export.
- **Community Contributions:** Add idioms directly in the browser and export formatted JSON for GitHub Pull Requests.

## Repository Structure
- `index.html` — Complete Material 3 frontend & Service Worker registration
- `idioms.json` — Structured open-source dataset of Oromo idioms
- `manifest.json` — PWA home-screen install metadata
- `sw.js` — Offline caching Service Worker
- `icons/` — `icon-192.png` and `icon-512.png` app icons
- `.github/workflows/validate-idioms.yml` — Automated PR schema validation
