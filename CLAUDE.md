# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

HoloPro is a static marketing website for a holographic display technology company based in South Africa. The tagline is "Think Inside THE BOX."

## Architecture

This is a single-page static site with no build tools, frameworks, or dependencies:

- **`index.html`** — The entire website: markup, inline CSS (via `<style>`), no JavaScript. All styling uses CSS custom properties defined in `:root`.
- **`attachments/`** — PDF proposals and brochure documents with corresponding PNG preview images in `attachments/images/`.

## Development

Open `index.html` directly in a browser. No build step, no dev server required.

## Design System

- **Color scheme:** Dark theme with teal/green accent (`--primary: #00D4AA`). All colors defined as CSS custom properties in `:root`.
- **Typography:** Inter font from Google Fonts, weights 300-800.
- **Layout:** Responsive via CSS Grid with `auto-fit`/`minmax`. Mobile breakpoint at 768px.
- **Components:** Cards, steps, stats — all styled with consistent border-radius (16-24px), subtle borders, and hover animations.
