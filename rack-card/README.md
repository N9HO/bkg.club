# BKG Rack Card

A double-sided rack card for handing out at hamfests. Front = logo + QR (→ https://www.bkg.club);
back = who we are, the 3 Bylaws, and how 2 join. Tone matches bkg.club.

## Print specs

- **Deliverable:** `BKG-rack-card.pdf` — 2 pages (page 1 = front, page 2 = back)
- **Trim size:** 4" × 9" (standard rack card)
- **Document size:** 4.25" × 9.25" (includes 0.125" bleed on all sides)
- **Safe zone:** all text kept ≥ 0.25" inside the trim
- **Color:** full-bleed dark background — tell the printer **no auto-scaling / "actual size"** so the bleed isn't trimmed away
- Send the PDF straight to a print shop (Vistaprint, UPrinting, local, etc.). Choose 4×9 rack card, double-sided.

## Previews

- `preview-front.png`, `preview-back.png` — screen previews (3× resolution)

## Source

- `rack-card.html` — self-contained source (fonts + logo + QR embedded). Open in a browser to tweak.
- `assets/logo-circle.png` — logo with the background knocked out (transparent)
- `assets/qr.png` — QR code → https://www.bkg.club

### Re-rendering after edits

The PDF was rendered from `rack-card.html` with headless Chromium at 4.25" × 9.25", print backgrounds on.
Fonts used: Bangers (headlines), Special Elite (body), Bungee Shade (bylaw numerals).
