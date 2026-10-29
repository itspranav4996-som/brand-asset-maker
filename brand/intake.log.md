# Intake log

Date: 2026-10-29. Brand input: the Figma link in [sources.md](sources.md), Page 3 only (the Design N Build Excellence brand guide). The file also holds a Source Architecture brand on its "Website Style Guide" page; the owner said to use Page 3 only, so nothing from that page is used.

## The ten questions

| # | Item | Asked? | Answer | What it gave |
|---|---|---|---|---|
| 1 | Logo and wordmark | yes (second logo) | Owner: the second logo is the Lilac / Apricot / Marigold mark | `assets/logo.svg` = Graphite D\B mark (the guide's mark on light grounds); `assets/logo-reversed.svg` = three-colour mark. Wordmark "DESIGNNBUILD EXCELLENCE PVT LTD" read from the lockups: we guessed |
| 2 | Primary colour | no | read from the guide: Lilac #BA9ED1 leads (30%) | `--brand-accent`: we guessed (role), hex from the guide |
| 2b | Text colour | yes | Owner: "Charcoal #262626" | `--brand-ink`: you said |
| 2c | Text on Lilac | yes | Owner: "Charcoal on Lilac" (the guide shows a white logo on Lilac; white text there is 2.36:1) | `--brand-accent-ink`: you said |
| 3 | Fonts | no | the guide names Archivo (primary) and DM Sans (secondary); no files | `fonts.md` path (b), free OFL fonts |
| 4 | Who it is for | asked, not answered | — | drafted from the about text: we guessed |
| 5 | How it sounds | yes | Owner: "Confident, expressive, contemporary" | `voice.md` tone words: you said |
| 6 | Never say | asked, not answered | — | drafted: no guaranteed jobs or placements: we guessed |
| 7 | Posts, layouts, guides | — | the brand guide (Page 3). It holds stationery and graphic elements, no social post layouts | no `coverage.md`: there are no layouts to encode; BAM's sample layouts apply |
| 8 | Photographs | no | none supplied | no photograph layouts |
| 9 | Where they run | no | blank | BAM default: 1:1, 4:5, 9:16: we guessed |
| 10 | Character | no | blank | no `expression.json` |

Also asked, not answered: corner radius → `--brand-radius: 0px`, we guessed.

## Read from the guide, worth checking

- The colour usage page labels the 7%, 3% and 2% bars "PLASTER", but their colours are Porcelain, Clay and Graphite. Source: [usage hierarchy](sources/figma/p15-colour-usage-hierarchy.png).
- The secondary palette lists "Charcoal 2" as #000000. Not used here. Source: [secondary palette](sources/figma/p14-colour-secondary.png).
- Contrast (WCAG, measured): Charcoal on Plaster 15.13:1; Charcoal on Lilac 6.41:1; Graphite on Lilac 4.89:1; Charcoal on Apricot 6.40:1; Charcoal on Marigold 11.10:1; Plaster on Lilac 2.36:1 (fails text); Plaster on Apricot 2.36:1 (fails text).
- On the ink scheme (Charcoal ground) the Graphite logo will nearly vanish. The reversed logo is there for that; which scheme shows it is decided when a sheet shows it (`skills/bam--intake.md` step 5c).
