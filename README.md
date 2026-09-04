# RTN Brand Assets

Canonical home for the Run The Numbers® brand system. The full spec lives in [`DESIGN.md`](./DESIGN.md) in this repo (raw URL: <https://raw.githubusercontent.com/RTN-Digital/rtn-brand-assets/main/DESIGN.md>). This repo also hosts the visual files, logos, icons and covers referenced across rtn.digital and RTN's automated deliverables.

> **Canonical source.** `DESIGN.md` in this repo is the single source of truth for the RTN brand system. The `rtn-branding` skill in `RTN-Digital/rtn-cowork` is a fast-loading cache of this spec; if anything in the skill contradicts `DESIGN.md`, the canonical wins.

Moved from Notion to GitHub on 20 May 2026. The Notion workspace has since been decommissioned entirely, so this repo is the only source.

## V2 Ledger design system (13 May 2026)

Primary accent: Ledger Blue `#2B4A7C`. Dark surface `#142544`. Canvas `#FAF7F2` (warm cream, never pure white). Text `#1B1A17` (warm near-black, never pure black). Replaces V1 (green / gunmetal / Nourd).

## Logo

The mark is "RTN" set in Fraunces, monogram only: variable weight 700, opsz 144, SOFT 0, WONK 0. No descriptor is baked into the SVG. The full "RUN THE NUMBERS®" descriptor is composed live in HTML or CSS on the surfaces that need it, so there is no exported full-lockup asset.

Canonical files live in [`logo-redesign/svg/`](./logo-redesign/svg/):

| File | Hex | Use on |
|---|---|---|
| `RTN_Logo_Warm_Ink.svg` | `#1B1A17` | Default for Canvas Cream and other light surfaces |
| `RTN_Logo_Ledger_Blue.svg` | `#2B4A7C` | Brand-forward placement, hero sections, primary marketing |
| `RTN_Logo_Canvas_Cream.svg` | `#FAF7F2` | Reversed out on dark or photographic backgrounds |
| `RTN_Logo_Black.svg` | `#000000` | Pure black for mono print |
| `RTN_Logo_White.svg` | `#FFFFFF` | Pure white for dark backgrounds where Canvas Cream washes out |

Raw URL pattern:

```
https://raw.githubusercontent.com/RTN-Digital/rtn-brand-assets/main/logo-redesign/svg/RTN_Logo_{Variant}.svg
```

PNG raster fallbacks at X1/X2/X4 sit in [`logo-redesign/png/`](./logo-redesign/png/) for the three brand-coloured variants. Black and White PNGs are still a gap. See [`logo-redesign/README.md`](./logo-redesign/README.md) for the working summary and outstanding refinement items.

Superseded naming: the earlier `rtn-wordmark-*.svg` and `rtn-lockup-*.svg` sets no longer exist. Any link to them, or to `logo-redesign/test-bench.html`, is dead.

## Icons

34 hand-drawn-style SVG icons in Ledger Blue (`#2B4A7C`), rendered with rough.js to match the cover artwork. 64×64 viewBox, single-pass strokes, slug-cased filenames.

| Folder | Count |
|---|---|
| `icons/teamspace/` | 7 |
| `icons/database/` | 7 |
| `icons/wiki/` | 10 |
| `icons/record/` | 10 |

The accent blue is baked in. For a neutral variant, find-and-replace `#2B4A7C` with `#1B1A17` (text). PNG versions of the same set are in `icons-png/`. See [`icons/README.md`](./icons/README.md) for regeneration settings and known limitations. These were cut for the Notion workspace, which is retired, so treat them as a general-purpose set rather than Notion assets.

## Favicons

V2 Ledger favicons: cream RTN (`#FFFFF5`) on a Ledger Blue (`#2B4A7C`) rounded square (20% corner radius), set in DejaVu Serif Bold. All files live in [`favicons/`](./favicons/).

| File | Size | Use |
|---|---|---|
| `favicon.ico` | 16 + 32 + 48 | Multi-resolution ICO for legacy browsers |
| `favicon-16x16.png` | 16×16 | Browser tab icon (standard) |
| `favicon-32x32.png` | 32×32 | Browser tab icon (HiDPI) |
| `favicon-48x48.png` | 48×48 | Windows site icon |
| `apple-touch-icon.png` | 180×180 | iOS and macOS home screen and bookmarks |
| `webclip-512x512.png` | 512×512 | PWA manifest, Open Graph fallback |

## Covers

Six cover images in [`covers/`](./covers/), all V2 Ledger colourways.

## Rules

- Never stretch, distort, recolour outside the five variants, add effects, or use below 80px wide.
- Never typeset "RTN" by hand as a substitute for the official SVG.
- Full spec in [`DESIGN.md`](./DESIGN.md).

## Repo history

Transferred from `dean-yates` to the `RTN-Digital` organisation with the rest of the RTN estate. The transfer reset the repo to private, which silently 404'd every raw asset URL across the skill library until it was made public again on 4 September 2026. This repo must stay **public**: the raw URLs above are consumed by automated deliverables that have no other way in.

## License

© 2026 RTN Digital Ltd. "Run The Numbers" and the RTN logo are registered trademarks (Company No. 16200602). Public hosting for technical purposes only; use requires permission.
