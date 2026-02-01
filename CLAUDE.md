# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the website for the Java Doer Library (https://github.com/doer-lib/doer). It's a simple static HTML/CSS site deployed to GitHub Pages.

## Structure

- `index.html` - Landing page with GitHub link and tools section
- `doer-diagram.html` - Interactive SVG diagram comparison tool (uses D3.js)
- `styles.css` - Styles for the landing page

## Development

Open `index.html` directly in a browser to preview changes locally.

## Security

External scripts must include `integrity` and `crossorigin` attributes (SRI).

## Deployment

Automatically deployed to GitHub Pages on push to `main` via `.github/workflows/static.yml`.
