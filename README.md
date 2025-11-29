# Mudafuka Static Assets Repository

This repository contains the static, versioned, CDN-accelerated assets used across
Mudafuka’s public-facing properties. All assets in this repository are intended to be:

- **Immutable**
- **Globally cacheable**
- **Directly referenceable via Statically.io CDN**
- **Independent of any backend or build pipeline**

## Usage

All files in `/assets/` are served via:

`https://cdn.statically.io/gh/<ORG>/<REPO>/<BRANCH>/assets/...`

Do not rename or delete versioned files that are already referenced publicly.  
Introduce new versions by adding new files (e.g., `hanko-overlay-v2.webp`).

## Contribution Rules

- **Never rewrite or overwrite existing asset files.**
- **Use versioned filenames for updates.**
- **Do not add code, secrets, or environment data.**
- **Do not enable GitHub Pages for this repository.**

## Branch Strategy

- Default branch: `main`
- All production assets must reside on `main` for CDN stability.

## License

See `LICENSE` for details.
