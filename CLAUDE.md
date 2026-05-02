# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Purpose

Personal astrology website for Jason Edelman, a humanistic astrologer. The primary call to action is booking an initial consult, with the goal of converting visitors into long-term clients.

Jason's approach is pedagogical: he uses the birth chart as a compass to guide clients through their own inner/outer journey, developing perspective, empathy, and agency — rather than delivering predictions top-down.

## Commands

```bash
npm run dev      # dev server at localhost:4321
npm run build    # production build → dist/
npm run preview  # preview the production build
```

## Tech Stack

This project has not been scaffolded yet. When implementing:
- **Astro 4** static site (`src/pages/index.astro` is the single page)
- `src/layouts/Layout.astro` holds the HTML shell, Google Fonts import, and all global CSS custom properties
- Page-scoped CSS lives in `<style>` blocks inside each `.astro` file
- Images go in `public/images/` and are referenced as `/images/filename.jpg`

## Key Content & Design Constraints

- The site should communicate Jason's humanistic, client-centered approach (see `SPEC.md`)
- Primary CTA: book an initial consult
- Tone should be warm, grounded, and intellectually serious — not mystical or sensationalist
- Long-term client relationships are the business goal, so trust-building content matters more than conversion pressure
