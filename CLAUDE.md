# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static marketing landing page for **Numina**, a payment and compliance infrastructure platform for AI agents. The product focuses on accounting automation - specifically reconciliation, flagging, and research for financial compliance.

## Architecture

**Single-page HTML site** with:
- Inline CSS styling in `<style>` tags
- No JavaScript framework or build system
- Static assets referenced from `assets/` directory
- SVG icons and graphics embedded inline or loaded from assets folder

**Key sections in index.html:**
- Header with logo and CTA button (line 253-260)
- Hero section with main headline and Y Combinator badge (line 262-289)
- Feature sections using grid layouts (grid-3, grid-4, grid-2 classes)
- Security/compliance section with certifications
- Footer with social links and navigation

## Design System

**Brand colors:**
- Primary purple: `#4101f6`
- Light purple: `#c2bbff`
- Dark text: `#1b1b1c`
- Gray text: `#505153`
- Border gray: `#e5e5e5`

**Layout patterns:**
- `.container` - max-width 1200px, centered
- `.section-spacing` - 80px mobile, 120px desktop padding
- `.card` - white background with border, hover effect changes border to primary color
- `.grid-3`, `.grid-4`, `.grid-2` - responsive grid layouts

**Typography:**
- System font stack (San Francisco, Segoe UI, etc.)
- Hero: 84px, font-weight 300
- Section headings: 48px, font-weight 300
- Cards: 20px headings, 15px body text

## Development

**No build process** - edit HTML directly and open in browser.

To view: Open `index.html` in a web browser.

## Content Notes

- Company name: **Numina**
- Tagline: "Books close themselves. Numina makes it right."
- Main value prop: AI agents for accounting reconciliation, compliance flagging, and regulation research
- hero.txt contains copy drafts/alternatives
