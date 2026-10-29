# Fonts

**Policy path: (b) named free fonts.** The guide names both typefaces; no font files were supplied, so `brand/fonts/` is not committed (the fork is public).

| Role | Family | Weights the guide uses | Licence | Source URL |
|---|---|---|---|---|
| Display (`h1`–`h3`, `data-snippet`) | Archivo | Bold 700 (Large Heading 96pt), Medium 500 (Small Heading 40pt) | SIL Open Font License 1.1 | https://fonts.google.com/specimen/Archivo |
| Body (`body`, `label`) | DM Sans | Light 300 (Body 24pt, Subtext 16pt), Regular 400 (Eyebrow 20pt) | SIL Open Font License 1.1 | https://fonts.google.com/specimen/DM+Sans |

Source: [type hierarchy](sources/figma/p20-type-hierarchy.png), [Archivo page](sources/figma/p18-type-archivo.png), [guide text](sources/figma/page3-text.md).

**To render posts:** download both families from the links above and put these files in `brand/fonts/` (the names `fonts.css` expects): `Archivo-Medium.ttf`, `Archivo-Bold.ttf`, `DMSans-Light.ttf`, `DMSans-Regular.ttf`. Until then the `font-loaded` check fails.

Status: we guessed (`derived`) until a post that renders these fonts is approved.
