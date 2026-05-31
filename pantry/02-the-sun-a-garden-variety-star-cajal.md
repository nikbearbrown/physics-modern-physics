# CAJAL Figure Intelligence — Ch 2: The Sun (Garden-Variety Star)

**Source:** `chapters/02-the-sun-a-garden-variety-star.md`
**Mode:** `/scan`
**Author pre-architecture:** **13 figures already placed inline (Figs 2.1–2.13).** Heavily pre-architected.
**Domain note:** Solar physics narrative chapter — Carrington Event opener, composition (Payne-Gaposchkin), energy, radiative zone, convection, dynamo, sunspot cycle, corona, flares + CMEs, 2012 near-miss, life cycle.

---

## Density Recommendation

**13 figures, Mechanistic density** — the author has already pre-specified the density. CAJAL's job here is validation, refinement of specifications, and flagging redundancy.

---

## Figure-by-Figure Validation

### Fig 2.1 — Sun–Earth Timeline for the Carrington Event
- **Type:** Timeline. **Verdict:** Keep.
- **SCOPE:** Horizontal time axis (T=0 flash, T+17h CME arrival). Mark 8-min light arrival, X-ray ionization, CME impact, geomagnetic storm peak. 6 events max. Okabe-Ito orange for solar events, sky-blue for terrestrial effects. No red/green.
- **Caption hook:** "Two arrivals at Earth from one solar event — light in 8 minutes, plasma in 17 hours. The gap is everything."

### Fig 2.2 — Solar Absorption Spectrum (Fraunhofer Lines)
- **Type:** Annotated example / spectrum strip. **Verdict:** Keep.
- **SCOPE:** Continuous rainbow gradient as background, vertical black absorption lines at characteristic wavelengths. Label the prominent H, Ca, Fe, Mg, Na lines (6 callouts max). No text labels inside the bar itself — labels above/below with leader lines.

### Fig 2.3 — Solar Composition Pie Chart
- **Type:** Statistical / quantitative (pie or stacked bar). **Verdict:** Keep — but **switch to stacked horizontal bar instead of pie**. Pie charts with one slice at 73%, one at 25%, and one at 2% read poorly; the 2% slice disappears. Stacked bar lets the reader see all three. Okabe-Ito orange (H), sky-blue (He), gray (everything else with a callout listing C/N/O/Fe).

### Fig 2.4 — Random Walk vs. Straight Line
- **Type:** Comparison panels. **Verdict:** Keep — but **rebuild the caption** ("Random walk vs" is truncated).
- **SCOPE:** Panel (a) straight-line photon at c, 2-second trip. Panel (b) zigzag random walk, ~100,000-year trip. Same start/end points. Sky-blue path. 5-6 random-walk segments shown schematically (not literal 10²⁶ steps). Caption full sentence: "A photon's straight-line trip from core to surface would take 2 seconds. The actual random walk through dense plasma takes ~100,000 years."

### Fig 2.5 — Cross-Section of the Sun's Interior
- **Type:** Mechanism cross-section. **Verdict:** Keep — central reference figure.
- **SCOPE:** Cutaway sphere showing 4 zones: core (red-orange, fusion), radiative zone (yellow, photon diffusion), tachocline (thin dashed boundary), convection zone (textured, convection cells), photosphere (thin surface). 5 labels with leader lines. Y-axis not applicable; just radial fraction marks (0, 0.25, 0.7, 1.0).

### Fig 2.6 — Photospheric Granulation Photograph
- **Type:** Annotated photograph. **Verdict:** Keep.
- **SCOPE:** Real DKIST or SDO granulation image. Annotate 2-3 granules with the bright/dark lane structure. Scale bar (1000 km). One callout: "8-minute lifetime per cell."

### Fig 2.7 — Differential Rotation Winding the Magnetic Field
- **Type:** Cycle diagram (sequence). **Verdict:** Keep.
- **SCOPE:** 4 panels showing the Babcock-Leighton picture: (a) initial poloidal field N-S, (b) equator rotates faster, field stretches, (c) field wound into toroidal flux ropes, (d) flux ropes buoyantly rise → sunspot pairs. 4 panels in a 2×2 grid. Okabe-Ito blue for field lines. Black arrows for plasma motion.

### Fig 2.8 — Sunspot Cycle Time Series
- **Type:** Statistical / quantitative. **Verdict:** Keep — but **fix the caption truncation** ("Monthly smoothed sunspot number vs").
- **SCOPE:** Y-axis: smoothed sunspot number (starts at 0). X-axis: years from ~1900 to 2025 (so the reader sees ~10 cycles). Mark Solar Cycle 25. Mark the deep minima (Maunder is too old for this window; mark 2008–09 minimum). Sky-blue line on white. No red/green.

### Fig 2.9 — Temperature vs. Altitude in the Solar Atmosphere
- **Type:** Statistical / quantitative. **Verdict:** Keep — caption truncation again.
- **SCOPE:** Y-axis: temperature (log scale, 10³ to 10⁷ K — **explicitly log; y-axis-from-zero rule does not apply to log scales but flag this in the caption**). X-axis: altitude above photosphere (km, 0 to 10,000). Mark photosphere min (~4400 K), chromosphere (~10⁴ K), transition region (steep jump), corona (10⁶ K). One curve.

### Fig 2.10 — Magnetic Reconnection Sequence
- **Type:** Cycle / sequence diagram. **Verdict:** Keep.
- **SCOPE:** 3 panels: (a) two oppositely-oriented field loops approach, (b) field lines break and reconnect at X-point, (c) post-reconnection loops eject plasma + radiation. Sky-blue and vermillion for the two field orientations (deliberately avoiding the obvious magnetic-pole red/blue but using a colorblind-safe pair). Annotate the X-point.

### Fig 2.11 — Earth's Magnetosphere During CME Impact
- **Type:** Mechanism cross-section. **Verdict:** Keep.
- **SCOPE:** Side view, Sun on left, Earth on right, magnetosphere bow shock compressed on day side, magnetotail elongated on night side. CME plasma cloud arriving. Field-line connection (reconnection) on the day side if CME field is southward. 5 labels max.

### Fig 2.12 — Major Solar Events Timeline
- **Type:** Timeline. **Verdict:** Keep — caption truncated again ("on a").
- **SCOPE:** Horizontal axis: 1850 to 2025. Mark Carrington (1859), Quebec blackout (1989), Halloween 2003, 2012 near-miss, Solar Cycle 25 peak (2024-25). 5-6 events, height of marker proportional to estimated intensity. Sky-blue markers, vermillion for "missed Earth" entries.

### Fig 2.13 — Sun's Life Cycle Timeline
- **Type:** Timeline. **Verdict:** Keep.
- **SCOPE:** Horizontal axis: log time from -4.6 Gyr (formation) to +7 Gyr (white dwarf). Mark formation, present (with "we are here" arrow), main sequence end, red giant phase, planetary nebula, white dwarf cool-down. Size icons proportional to Sun's relative size at each stage. 6 stages.

---

## Architectural Notes

**Caption truncation:** 4 captions show truncation artifacts (Figs 2.4, 2.8, 2.9, 2.12). Confirm with author whether these are placeholders awaiting full text, or whether the markdown is corrupted. Either way, finalize before art production.

**Density check:** 13 figures in ~6,000 words is high but justified — this is the showcase chapter for the Sun. Every figure earns its place.

**Y-axis from zero exception:** Fig 2.9 (temperature vs. altitude) needs log y-axis; Fig 2.8 (sunspot number) starts at zero; Fig 1.3-style γ-curves would start at 1 but no such figure here. Document the log-scale exception in the figure brief.

---

## Cross-Chapter References

- **Fig 2.5 (interior cross-section)** is the canonical Sun-anatomy figure. Cite it from Ch 3 (nuclear powerhouse) and Ch 7 (death of stars) rather than redrawing.
- **Fig 2.10 (reconnection)** — Ch 16 (frontiers) on tokamak fusion may want a reconnection reference; cite back rather than redraw.
- **Fig 2.13 (life cycle)** — Ch 7 (death of stars) will expand the red-giant/white-dwarf end; treat 2.13 as a teaser and let Ch 7 redraw with stellar-mass branching.

---

## Video Candidate Pass

**Three strong candidates:**

1. **Differential rotation winding (Fig 2.7 animated)** — the only way to actually convey what "wound up over 5 years" means. Time-lapse of a poloidal field becoming toroidal. ~20 seconds.
2. **Random walk vs. straight line (Fig 2.4 animated)** — two photons race from core to surface. The direct one arrives in 2 seconds; the zigzag one is still bouncing when the video ends. ~15 seconds with a "100,000 years later" punchline.
3. **CME approaching Earth (Fig 2.11 animated)** — solar eruption → plasma travels across 1 AU → magnetosphere compression → reconnection cascade. ~30 seconds. High pedagogical payoff because it makes the Carrington-Event chain of causation visible.

Magnetic reconnection (Fig 2.10) is a fourth candidate but is well-served by static panels.
