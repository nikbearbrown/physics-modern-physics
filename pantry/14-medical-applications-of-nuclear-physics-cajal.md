# CAJAL Figure Intelligence — Ch 14: Medical Applications of Nuclear Physics

**Source:** `chapters/14-medical-applications-of-nuclear-physics.md`
**Mode:** `/scan`
**Author pre-architecture:** **4 figures already placed inline (Figs 14.1–14.4).**
**Domain note:** Hevesy 1913 opener, three imaging windows (X-ray/CT, gamma camera, PET), dose units (activity / absorbed / equivalent), LNT debate, therapy mechanisms (LINAC IMRT, Bragg peak proton therapy, internal alpha emitters).

---

## Density Recommendation

**5 figures, Mechanistic density** — author placed 4; CAJAL recommends adding 1 (a clean imaging-modalities comparison table to replace the malformed prose table).

---

## Figure-by-Figure Validation

### Fig 14.1 — PET Coincidence Detection
- **Type:** Mechanism cross-section. **Verdict:** Keep.
- **SCOPE:** Patient cross-section with ring detector. ¹⁸F nucleus in tissue emits a positron; positron travels ~mm; annihilates with electron; two 511-keV gammas travel in opposite directions; both detected simultaneously at opposing ring elements. The line connecting the two detector hits passes through the annihilation site. Show 3-4 sample coincidence lines crossing through a "hot spot" region.
- **P:** 7 components: detector ring, patient outline, positron emission point, electron, annihilation flash, two gamma rays at 180°, coincidence-line reconstruction. Okabe-Ito vermillion for the gammas, sky-blue for detected hits, orange for the hot-spot region. No text labels in the image.
- **Caption hook:** Author's caption is precise.

### Fig 14.2 — Alpha vs. Gamma Energy Deposition (LET Comparison)
- **Type:** Mechanism cross-section / annotated example. **Verdict:** Keep — but **fix caption truncation** ("Alpha vs").
- **SCOPE:** Two parallel tracks through tissue (rendered as a grid of cells). Panel (a) alpha: dense ionization track terminating within ~50 μm — every cell along the path heavily damaged. Panel (b) gamma: sparse ionization events across centimeters, occasional cell hit isolated. Same total energy deposited; vastly different spatial distribution.
- **P:** 6 components per panel: tissue grid, particle track, ionization markers (dots along track), DNA-damage indicators in affected cells, track length scale bar. Vermillion for alpha (dense damage), sky-blue for gamma (sparse). Avoid red/green.
- **Caption:** Author's caption captures it — the w_R = 20 vs 1 difference becomes visual.

### Fig 14.3 — Radiation Dose Scale
- **Type:** Statistical / quantitative. **Verdict:** Keep — central calibration figure.
- **SCOPE:** Vertical log scale from 0.001 mSv to 10 Sv. Mark reference points: dental X-ray (~0.005 mSv), chest X-ray (0.1), transatlantic flight (0.03), natural background per year (3), chest CT (7), PET-CT (14), full-body CT (20), occupational annual limit (50), acute symptoms threshold (1 Sv), acute lethal range (4-5 Sv). 10-12 reference points.
- **P:** Vertical log axis. Each reference marked with a horizontal tick + label. Shaded color bands: green ("background"), yellow ("diagnostic"), orange ("occupational concern"), vermillion ("acute danger"). Note: avoid red/green pair — use Okabe-Ito sequential palette (sky-blue → orange → vermillion).
- **Caption hook:** Author's caption is good.

### Fig 14.4 — Bragg Peak vs. X-ray Depth-Dose Curve
- **Type:** Statistical / quantitative. **Verdict:** Keep — but **fix caption truncation** ("Bragg peak vs").
- **SCOPE:** X: depth in tissue (cm, 0 to 25). Y: relative dose (0 to 1). Two curves: (a) X-ray beam — peaks at ~3 cm (buildup region), decays exponentially with depth, still substantial at 20 cm; (b) proton beam — low entrance dose, builds gradually, sharp Bragg peak at the tuned depth (e.g., 15 cm), drops to essentially zero beyond. Annotate "tumor location" at peak depth.
- **P:** 2 curves. Sky-blue (X-ray), vermillion (proton). Y-axis from zero. Mark tumor location with vertical band.
- **Caption hook:** Author's caption ("the proton deposits almost nothing before and nothing after the peak") nails the pedagogical point.

---

## Architectural Notes

**Malformed table** at lines 40–43 (imaging-modality comparison) contains template detritus. **Strong recommendation: promote to Fig 14.5 — Imaging Modalities Comparison Table:**
- 4-5 rows (chest X-ray, CT, MRI, gamma camera/SPECT, PET).
- Columns: physical signal detected, structure vs. function, typical dose (mSv), spatial resolution, typical use case.
- Sky-blue / orange / vermillion coding for the three "signal types" (transmitted X-ray, gamma emission, magnetic resonance).

**Caption truncations:** Figs 14.2 and 14.4.

**New density recommendation:** **5 figures, Mechanistic density** with Fig 14.5 added.

---

## Cross-Chapter References

- **Fig 14.2 (alpha vs. gamma)** — Ch 13 Fig 13.2 introduced the three radiation types in terms of charge/mass; Ch 14 Fig 14.2 shows the biological consequence. Cite back.
- **Fig 14.4 (Bragg peak)** — this is the chapter's signature contribution; no overlap with prior chapters.
- **Fig 14.1 (PET coincidence)** — Ch 6 / Ch 15 discuss positron-electron annihilation as a Standard Model process. Cite back from Ch 14 to those chapters for the underlying physics.
- **Fig 14.3 (dose scale)** — Ch 13 discusses isotope half-lives; the activity-to-dose chain runs through Ch 13's decay law. Cite back.

---

## Video Candidate Pass

**Two strong candidates:**

1. **PET coincidence imaging build-up** (Fig 14.1 animated) — start with empty detector ring; positron emissions accumulate; each produces a coincidence line; after enough events, a 3D image of glucose uptake emerges in the patient. ~30 seconds. The "Hevesy's idea, scaled up" pedagogy lands visually.
2. **Bragg peak depth scan** (Fig 14.4 animated) — slider for proton-beam energy; Bragg peak shifts to different depths as energy increases; tumor at fixed depth becomes targeted only when energy is tuned correctly. ~20 seconds. Conveys what "tunable depth" actually means clinically.

Alpha vs. gamma damage patterns (Fig 14.2) is a third candidate — animate the two particles traversing tissue cell-by-cell with damage markers accumulating — but is well-served by static panels.
