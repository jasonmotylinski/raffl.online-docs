# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a documentation site for [Raffl.online](https://raffl.online) built with MkDocs and the Material theme. The site is hosted on GitHub Pages and deployed automatically via GitHub Actions.

## Commands

### Development

```bash
# Install dependencies
pip install -r requirements.txt

# Start local development server (watch for changes)
mkdocs serve
```

The development server runs on `http://localhost:8000` by default.

### Build

```bash
# Build static site for production
mkdocs build
```

Output is generated in the `site/` directory.

### Deployment

```bash
# Deploy to GitHub Pages (pushes gh-pages branch)
mkdocs gh-deploy
```

This command is run automatically by GitHub Actions on push to `main` or `master`.

## Architecture

**Static site structure:**
- `docs/` - Source markdown files organized by section
- `docs/index.md` - Homepage
- `docs/Account Setup/` - Account-related documentation
- `docs/Raffles/` - Raffle creation and management docs
- `docs/stylesheets/` - Custom CSS for Material theme override

**Configuration:**
- `mkdocs.yml` - Site configuration (site name, theme, analytics, nav structure)
- `requirements.txt` - Python dependencies (mkdocs-material)

**Deployment:**
- `.github/workflows/ci.yml` - Automated deployment workflow that builds and pushes to gh-pages branch on every push to main/master

**Theme:**
- Material theme with custom CSS overrides in `docs/stylesheets/extra.css`
- Primary color is set to custom (defined in `extra.css`)
- Navigation expanded by default

## Key Points

- The site uses a Material theme that automatically generates navigation based on the directory structure in `docs/`
- Custom styling is applied via `docs/stylesheets/extra.css` referenced in `mkdocs.yml`
- Google Analytics is configured (ID: G-NHB27Z7BSP)
- The build process is fully automated via GitHub Actions on push
- No tests are run in the CI/CD pipeline—only build and deploy

## Markdown Features

The Material theme supports extended markdown via `pymdown-extensions` including:
- Code highlighting with syntax themes
- Admonitions (note, warning, tip, etc.)
- Tabs and collapsible sections
- LaTeX math rendering
- Footnotes and abbreviations

See mkdocs-material documentation for full feature list.
