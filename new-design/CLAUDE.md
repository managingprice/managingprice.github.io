# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML website for the book "Managing Price: Negotiation Tools for Procurement Professionals", hosted on GitHub Pages at managingprice.com.

## Development

**No build system** - This is a pure static site with HTML and CSS files served directly.

- Edit HTML files in the root directory
- All styles are in `styles.css`
- Commit and push to `master` branch for automatic GitHub Pages deployment

## Architecture

**Pages (5 HTML files):**
- `index.html` - Homepage with book description, author bios, and endorsements
- `buyTheBook.html` - Amazon purchase links
- `tableOfContents.html` - Book table of contents organized by the 4 phases
- `resources.html` - External resources (economic indicators, contract terms, recommended books)
- `contact.html` - Author contact information

**Styling:**
- Single stylesheet: `styles.css`
- Modern, responsive design with CSS Grid and Flexbox
- Color scheme: Light background (#f7f7f5), dark text (#2d3748), accent red (#9b2c2c)
- System font stack for fast loading

**Navigation:** All pages share a sticky header with logo and navigation. The active page is marked with class `active`. When modifying navigation, update all 5 HTML files.

**Images:**
- `CoverFrontOnly.png` - Book cover (1800x2700px, can be scaled down)
- `redpricetag.ico` - Favicon

**Affiliate Links:** Amazon links include tracking tag `tag=manapric-20`.
