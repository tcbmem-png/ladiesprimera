# Ladies Primera Cleaning — Brand Asset Pack

Production-ready logo system and brand guidelines for **Ladies Primera Cleaning**.

---

## What's inside

```
ladies-primera-brand/
├── ladies-primera-brand-guidelines.pdf   ← 4-page brand book (start here)
├── svg/        ← 19 vector files  (web, print, infinitely scalable)
├── png/        ← 19 raster files  (transparent where applicable)
└── pdf/        ← 19 single-asset print-ready PDFs
```

Every variant is provided in **SVG + PNG + PDF**.

---

## Logo system

| Lockup | When to use |
|---|---|
| **Horizontal** | Default. Headers, business cards, email signatures. |
| **Stacked** | Square or portrait spaces, social profile headers, signage. |
| **Icon** | Avatars, app tiles, anywhere the wordmark would be too small. |
| **Mini** | Wordmark only ("Ladies Primera" — no "CLEANING"). For tight horizontal bars. |
| **Favicon** | Simplified mark (no sparkle, no base curve, single figure) for ≤ 32px. |

### File naming

| Filename | Background |
|---|---|
| `ladies-primera-logo-horizontal` | transparent |
| `…-horizontal-cream` | `#F5F1EA` cream |
| `…-horizontal-dark` | `#6F8576` green |
| `…-stacked` / `-cream` / `-dark` | (same scheme) |
| `…-icon` / `-cream` / `-dark` | (same scheme) |
| `…-social-light` / `-social-dark` | 1024×1024 social tiles |
| `…-favicon-512` / `-32` / `-16` | favicon export sizes |
| `…-logo-white` / `-logo-charcoal` | monochrome wordmarks |
| `…-icon-white` / `-icon-charcoal` | monochrome icons |

---

## Color palette

| Token | HEX | Use |
|---|---|---|
| Green | `#6F8576` | Primary brand color, icon fill |
| Gold | `#C8A46B` | Accent, figures, highlights |
| Terracotta | `#C77B5A` | Sparkle / decorative accent |
| Cream | `#F5F1EA` | Default background |
| Charcoal | `#2E2E2E` | Body text, monochrome mark |

---

## Typography

- **Heading Serif** — *Playfair Display, Italic 500.* The wordmark ("Ladies Primera") and editorial display copy.
- **Clean Sans** — *Montserrat, Medium 500, 0.42em letter-spacing.* The descriptor ("CLEANING"), navigation, captions.

Both fonts are free on Google Fonts:
<https://fonts.google.com/specimen/Playfair+Display> · <https://fonts.google.com/specimen/Montserrat>

---

## Clear space & minimum sizes

- **Clear space** — preserve a margin equal to the height of the centre figure on all four sides of the mark.
- **Minimum size** — Horizontal: 24mm wide / 96px. Icon: 16mm / 64px. Favicon used below 32px.

## Don'ts

Do not stretch, recolour, add effects, rotate, or place the mark on busy imagery without a tinted overlay.

---

## Importing into Figma

1. Create three pages: `01_Master`, `02_Exports`, `03_Icons`.
2. On `02_Exports`, create a frame for each filename in `svg/` and drop the matching SVG inside.
3. Set frame backgrounds:
   - `*-cream` frames → `#F5F1EA`
   - `*-dark` frames → `#6F8576`
   - all others → transparent
4. On `01_Master`, place the master SVGs (horizontal, stacked, icon, mini, favicon) and convert each to a Component.
5. Add color & text styles using the values above.

---

## Web usage

```html
<!-- Favicon -->
<link rel="icon" type="image/png" sizes="32x32" href="/brand/png/ladies-primera-favicon-32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/brand/png/ladies-primera-favicon-16.png">
<link rel="apple-touch-icon" href="/brand/png/ladies-primera-favicon-512.png">

<!-- Inline logo -->
<img src="/brand/svg/ladies-primera-logo-horizontal.svg" alt="Ladies Primera Cleaning" />
```

---

## Version

**v1.0** — initial release.
Generated as part of the Ladies Primera Cleaning brand identity system.
