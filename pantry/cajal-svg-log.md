# CAJAL SVG Generation Log — Physics +1: Modern Physics

**Book:** Physics +1: Modern Physics
**Slug:** `physics-modern-physics`
**Style:** Brutalist D3 (per `book-style.md`)
**Generated:** 2026-05-25
**Author:** Humanitarians AI

---

## Summary

| Metric | Value |
|---|---|
| Chapters with figures | 16 (Ch 01–16) |
| Total SVGs | **105** |
| Total PNGs (300 DPI) | **105** |
| Cajal source files | 20 (`pantry/*-cajal.md`) |
| Conversion script | `SCRIPTS/svg-to-png.mjs` (sharp @ density 300) |

---

## Per-Chapter Figure Counts

| Chapter | Slug | Figs | Status |
|---|---|---|---|
| 01 | special-relativity | 6 | done |
| 02 | the-sun-a-garden-variety-star | 13 | done |
| 03 | the-sun-a-nuclear-powerhouse | 6 | done |
| 04 | the-quantum-nature-of-light | 7 | done |
| 05 | the-atom | 6 | done |
| 06 | particle-physics | 6 | done |
| 07 | the-death-of-stars | 7 | done |
| 08 | black-holes-and-curved-spacetime | 8 | done |
| 09 | special-relativity (dup) | 8 | done |
| 10 | quantum-physics | 8 | done |
| 11 | the-big-bang | 5 | done |
| 12 | atomic-physics | 5 | done |
| 13 | radioactivity | 7 | done |
| 14 | medical-physics | 4 | done |
| 15 | particle-physics (dup) | 5 | done |
| 16 | frontiers-of-physics | 4 | done |
| **Total** | | **105** | |

---

## Batch History

| Batch | Scope | Figs |
|---|---|---|
| A | Ch 01 Special Relativity | 6 |
| B | Ch 02 Sun: garden-variety star | 13 |
| C | Ch 03 Sun: nuclear powerhouse + Ch 04 Quantum nature of light | 13 |
| D | Ch 05 The Atom + Ch 06 Particle Physics | 12 |
| E | Ch 07 Death of Stars + Ch 08 Black Holes | 15 |
| F | Ch 09 SR-dup + Ch 10 Quantum Physics | 16 |
| G | Ch 11 Big Bang + Ch 12 Atomic Physics + Ch 13 Radioactivity | 17 |
| H | Ch 14 Medical + Ch 15 Particle-dup + Ch 16 Frontiers | 13 |
| **Total** | | **105** |

---

## Cross-References

Several chapters duplicate or recall figures from earlier chapters (Option B per cajal specs — write them all, let editors decide later):

- **Ch 09** Special Relativity duplicate: cites Ch 1 figures (light clock, simultaneity, Lorentz factor, mass-energy equivalence).
- **Ch 12** Atomic Physics: cites Ch 5 figures (Bohr model, hydrogen spectral series, Pauli exclusion in shells).
- **Ch 15** Particle Physics duplicate: cites Ch 6 figure (Standard Model table, cosmic energy pie).
- **Ch 16** Frontiers: cites Ch 6 (cosmic pie), Ch 8 (LIGO + GW150914), Ch 11 (Hubble's law).

The recurrence is pedagogically deliberate — the cosmic pie appears in Ch 6, Ch 15, and Ch 16 as the running closing argument of the book.

---

## Style Notes

All figures follow the Brutalist D3 system:

- **Canvas:** `#FFFFFF` white, `#2a1a0e` ink, 32px margins
- **Highlight:** `#C8102E` red — used sparingly, single per figure
- **Secondary:** `#545454` grey, `#56B4E9` sky-blue, `#C8860E` ochre, `#3AAE3A` green, `#7B61A8` purple
- **Typography:** EB Garamond (titles), Inter (body/labels), JetBrains Mono (numerics, code, technical labels)
- **Required SVG envelope:** HTML comment header, `<metadata>` with `cajal:` namespace, `role="img"`, `aria-labelledby`, `<title>`, `<desc>`
- **CAJAL identifiers never render as visible text** — metadata only.

One controlled exception: the visible-light spectrum (Ch 04 Fig 04, "Visible Spectrum") uses the rainbow palette because it's depicting the actual phenomenon.

---

## Conversion

PNGs generated via `SCRIPTS/svg-to-png.mjs` using the `sharp` library at `density: 300` (300 DPI raster output suitable for print).

```bash
cd books/physics-modern-physics
node SCRIPTS/svg-to-png.mjs
```

The script skips PNGs that are newer than their source SVG, so re-running is idempotent.

---

## Sources

All figures derived from `pantry/*-cajal.md` (CAJAL Figure Intelligence specifications). The `source-file` attribute in each SVG's `<metadata>` block points to the originating cajal file.

---

*End of log.*
