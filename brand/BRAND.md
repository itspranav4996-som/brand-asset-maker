# Design & Build Excellence: encoded brand

Interior design institute. Everything here is copied from `tokens.css`, `locked.json`, `fonts.md`, `voice.md` and `brand.json`; where they disagree, those files win.

Source: [Figma Page 3 brand guide](sources.md).

## 1. Visual

| Token | Value | Name in the guide | Status |
|---|---|---|---|
| `--brand-paper` | `#FFFFFF` | Plaster | we guessed (derived) |
| `--brand-ink` | `#262626` | Charcoal | you said (locked) |
| `--brand-accent` | `#BA9ED1` | Lilac | we guessed |
| `--brand-accent-ink` | `#262626` | Charcoal | you said |
| `--brand-muted` | `#393939` | Graphite | we guessed |
| `--brand-accent-2` | `#FF875F` | Apricot | we guessed |
| `--brand-accent-3` | `#FDD97E` | Marigold | we guessed |
| `--brand-accent-4` | `#E8F3F4` | Porcelain | we guessed |
| `--brand-accent-5` | `#FFDCDC` | Clay | we guessed |
| `--brand-font-display` | `"Archivo", "Helvetica Neue", Arial, sans-serif` | Archivo | you said |
| `--brand-font-body` | `"DM Sans", "Helvetica Neue", Arial, sans-serif` | DM Sans | you said |
| `--brand-weight-display` | `700` | Archivo Bold | you said |
| `--brand-weight-body` | `300` | DM Sans Light | you said |
| `--brand-weight-label` | `400` | DM Sans Regular | you said |
| `--brand-tracking-display` | `0em` | (not in the guide) | we guessed |
| `--brand-radius` | `0px` | (not in the guide) | we guessed |

Hex values are the guide's own (Source: [primary palette](sources/figma/p13-colour-primary.png)). "We guessed" on a colour means its job (paper, accent, muted) is our reading, not the hex. No scheme overrides and no `--brand-logo-variant` yet.

Contrast (measured): Charcoal on Plaster 15.13:1, Charcoal on Lilac 6.41:1, Graphite on Plaster 11.55:1. White text on Lilac or Apricot is 2.36:1 and fails, which is why text on Lilac is Charcoal.

## 2. Fonts

- Display: **Archivo**, Bold 700 (headlines), Medium 500 (small headings).
- Body: **DM Sans**, Light 300 (body), Regular 400 (labels, eyebrow).
- Path: (b) named free fonts, SIL OFL 1.1, from Google Fonts. Files are not committed; download them into `brand/fonts/` (names in `fonts.md`).
- Fonts status: we guessed (`derived`) until a post that loads them is approved.

Source: [fonts.md](fonts.md).

## 3. Voice

- Tone: confident, expressive, contemporary (you said).
- Audience: people who want to study interior design through hands-on, studio-driven making (we guessed).
- Approved lines: none yet.
- Never claims: guaranteed jobs, placements or salaries (we guessed).

**Refuse.** Swap the headline to any face other than Archivo, or body text to anything other than DM Sans ("make the headline Playfair"): refuse, it breaks `role-face`. Promise a job, placement or salary ("100% placement guaranteed"): refuse, the brand never claims it.

Source: [voice.md](voice.md).

## 4. You said vs we guessed

You said is `locked` and we guessed is `derived` in `locked.json`; approving a post (you pick one) is the only thing that turns a guess into something you said.

- **You said:** ink Charcoal, text on Lilac Charcoal, Archivo and DM Sans with their weights, both logo files, the tone words.
- **We guessed:** Plaster as paper, Lilac as accent, Graphite as muted, the order of Apricot / Marigold / Porcelain / Clay, tracking 0, square corners, the wordmark spelling, the audience, the never-claim, the formats (1:1, 4:5, 9:16), the fonts status.

## 5. Files

| Use | File |
|---|---|
| Logo on light grounds (Plaster, Lilac, Porcelain, Clay, Marigold, Apricot) | `brand/assets/logo.svg` (Graphite D\B mark) |
| Second logo, for Charcoal grounds | `brand/assets/logo-reversed.svg` (Lilac / Apricot / Marigold D\B mark) |
| Wordmark | "DESIGNNBUILD EXCELLENCE PVT LTD" (we guessed, from the lockup) |
| Descriptor | "INTERIOR DESIGN INSTITUTE" |
| Tokens | `brand/tokens.css` |
| Fonts | `brand/fonts.css` → `brand/fonts/` |
| Where every value came from | `brand/sources.md`, `brand/sources/figma/` |
