# AWDD FontAwesome Widget Pack — Notion-Optimized

These widgets are specifically designed for embedding inside Notion using public URLs
(GitHub Pages, Netlify, Vercel, etc.).

## Why Notion-Optimized Versions?

Notion iframes:
- compress padding
- restrict width
- ignore some CSS resets
- clip overflow
- scale fonts slightly smaller

These versions solve those issues by:
- reducing padding
- simplifying gradients
- tightening spacing
- using embed-safe borders
- ensuring no overflow occurs

## How to Use

1. Host this repository on GitHub Pages, Netlify, or Vercel.
2. Open any `*-notion.html` file in your browser.
3. Copy the public URL.
4. Paste into Notion → “Create Embed”.

## Shared Styles

All Notion widgets use:
- `notion-base.css` for shared rules
- AWDD palette variables
- Inter font family

## Widget Categories

- Navigation
- Icons
- Headers
- Sections
- Badges

Each category has its own Notion-optimized HTML and CSS files.
