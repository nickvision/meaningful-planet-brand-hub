# Meaningful Planet – Brand Guidelines

The definitive reference for how Meaningful Planet looks, sounds, and communicates – across every touchpoint, channel, and team.

**Version:** 1.1  
**Last updated:** February 2026

## What's Included

- **Brand overview** – mission, vision, elevator pitch, strategic pillars, The Meaningful Way principles
- **Logo** – all variants (colour on light/dark, mono black, mono white) with usage rules
- **Colour palette** – Moss, Pine, Sapling, Mist, Chalk, Clay, Grove with roles by context
- **Typography** – Figtree primary typeface, serif display face (website only), full type scale
- **Voice & tone** – brand personality, messaging themes, tone by context, words to avoid
- **Copy rules** – capitalisation, British English, punctuation, terminology
- **Website patterns** – section anatomy, buttons, photography, trust signals
- **Applications** – email templates, Milo platform, partner materials, social media

## Project Structure

```
brand-guidelines/
├── index.html              # Full brand guidelines (single-page)
├── copy-style-guide.md     # Standalone copy style guide (Markdown)
├── package.json            # Project config
├── vite.config.js          # Vite static site config
├── public/
│   ├── logo-light.svg      # Colour mark – light backgrounds
│   ├── logo-dark.svg       # Colour mark – dark backgrounds
│   ├── logo-black.svg      # Mono black mark
│   ├── logo-white.svg      # Mono white mark
│   └── milo-logo.png       # Milo product wordmark
└── README.md
```

## Running Locally

```bash
npm install
npm run dev
```

Opens at `http://localhost:5173`.

## Building for Deployment

```bash
npm run build
```

Output in `/dist`. Deploy to any static hosting (Vercel, Netlify, GitHub Pages, Loveable).

## Deploying to Loveable

1. Push this repo to GitHub
2. In Loveable, import from the GitHub repository
3. Loveable will detect the Vite config and deploy automatically
4. Optionally connect a custom domain (e.g., `brand.meaningfulplanet.co.uk`)

## Linking from Notion

Once deployed, embed the live URL in your Notion workspace:

- Add a **Web Bookmark** block with the deployed URL for quick access
- Add a **Full-page Embed** for inline viewing within Notion
- Keep the **Copy Style Guide** (Markdown) as a native Notion page for easier team editing

## Colour Palette Quick Reference

| Name    | Hex       | Role                                          |
|---------|-----------|-----------------------------------------------|
| Moss    | `#032D10` | Primary dark – headlines, headers, buttons    |
| Pine    | `#256751` | Secondary green – accents, links              |
| Sapling | `#D2FF85` | Accent – CTAs on dark, emphasis               |
| Mist    | `#C4F5DC` | Light accent – stat cards, badges             |
| Chalk   | `#F8F3EC` | Warm neutral – page/email backgrounds         |
| Clay    | `#D98042` | Warm accent – warnings, sparingly             |
| Grove   | `#021B11` | Deepest dark – footers, overlays              |

## Key Rules

- **British English** exclusively – never US spellings
- **Title case** for headings, nav, buttons, CTAs
- **Sentence case** for labels, descriptions, body text
- **En dashes (–)** – never em dashes (—)
- **Oxford comma** – always
- **Figtree** – brand typeface across all channels
- **Serif display** – website marketing headlines only

---

© 2026 Meaningful Planet. Internal use.
