# FreightSimple — Homepage redesign prototype v2.1

Visual prototype of the proposed homepage redesign.
Single HTML file, no dependencies, works on GitHub Pages.
**100% compliant with the official Brand Book v1.0 (April 2026).**

## Design direction

Refined minimalism with personality. The identity comes from:

- **Dark hero** as the dramatic opening moment
- **Bold offset shadows** on cards and visual elements — tactile, modern, playful
- **Hand-drawn underline squiggle** under "Zero surprises" in the hero
- **Scroll reveal animations** — content fades up as you scroll
- **Rich hover states** — cards lift with offset shadow, icons rotate, buttons transform
- **Dotted connecting line** between How It Works steps
- **Gold as a rare moment** — only appears in logo, hero accent, partners callout, final CTA
- **Official FS logo icon** integrated as inline SVG (geometric blue + gold shapes)

No floating shapes. No decorative diagonal lines. No background noise. Clean sections with purposeful accents.

## What's here

- `index.html` — complete prototype of all 13 sections
- `logo-icon.png` — official FreightSimple logo icon (transparent background)
- Toggle in the top-right to switch between **DARK** hero (default) and **LIGHT** hero
- All copy is the final version from the Homepage Copy doc
- Placeholders visible where real assets (screenshots, logos, animation) still need production

## Publishing to GitHub Pages

Upload **all three files together** to the repo root:
- `index.html`
- `logo-icon.png`
- `README.md`

The HTML references the logo as `./logo-icon.png` (relative path), so both files must live in the same directory.

## Brand compliance

All colors sourced directly from the official Brand Book v1.0:

| Color | Hex | Use |
|---|---|---|
| FreightBlue (Primary) | `#4C62EA` | CTAs, links, accent copy, brand elements |
| FreightGold (Accent) | `#facc0b` | Logo accent, hero accent copy, partners callout, final CTA highlight |
| FreightDark | `#1a1d23` | Hero, Anomaly section, Final CTA, Footer |
| White | `#FFFFFF` | Primary section backgrounds |
| Blue Light | `#EEF1FD` | Hover states, UI accents only (not section backgrounds) |
| Muted Gray | `#6b7185` | Secondary text |
| Success Green | `#1D9E75` | Compare table positive indicators |
| Error Red | `#E24B4A` | Compare table negative indicators |
| Warning Amber | `#BA7517` | Compare table limited indicators |

**Typography:** Plus Jakarta Sans 800 (display) + Inter (body) + JetBrains Mono (labels) — per Brand Book.

**Section treatment:** Dark accents only (Hero by default, Anomaly, Final CTA, Footer). Gold moment in Partners callout. Everything else clean white. Light-and-airy brand identity preserved.

## How to review

1. Open `index.html` in any browser, or publish to GitHub Pages
2. Scroll through the full homepage
3. Click "DARK" / "LIGHT" toggle in the top-right to compare hero treatments
4. Hero animation cycles through 4 frames simulating the 10s production animation
5. Hover over cards to see offset-shadow interactions
6. Scroll slowly to see fade-up reveal animations

## What's NOT real yet (visible as placeholders)

- Product screenshots in the 3 pillar sections → simulated with styled UI mockups
- Customer logos in trust bar → styled text placeholders
- Hero 10s animation → simulated with cycling frames; final would use Lottie or video
- Anomaly detection map → SVG sketch of the concept
- Face photos in testimonials → initials avatars

## Tagline decision

This prototype uses **"Smarter LTL. Zero surprises."** as the H1 hero copy.
This differs from the tagline in Brand Book v1.0 ("Save money. Prevent problems. Automate everything.").
**This is a pending decision** — Chris will need to approve either:
- Update Brand Book to v1.1 with the new tagline, or
- Replace hero H1 with the existing tagline

## Purpose

This is a **proposal for Chris**, not a production deliverable.
Nothing here has been merged to the main FreightSimple repo.
This lives separately on GitHub Pages to preview the concept.

## Built by

Daniela Perea · Marketing Lead · April 2026
