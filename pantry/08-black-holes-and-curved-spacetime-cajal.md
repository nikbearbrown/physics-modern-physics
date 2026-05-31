# CAJAL Figure Intelligence — Ch 8: Black Holes and Curved Spacetime

**Source:** `chapters/08-black-holes-and-curved-spacetime.md`
**Mode:** `/scan`
**Author pre-architecture:** **8 figures already placed inline (Figs 8.1–8.8).** Substantially pre-architected.
**Domain note:** Schwarzschild's 1916 solution, equivalence principle, GR vs. Newton tests, Schwarzschild radius, event horizon as geometry, X-ray binaries, LIGO + GW150914, Event Horizon Telescope (M87 + Sgr A*), no-hair theorem, Hawking radiation, information paradox.

---

## Density Recommendation

**8 figures, Mechanistic density** — author has set the density. CAJAL validates and refines.

---

## Figure-by-Figure Validation

### Fig 8.1 — Timeline of Black Hole Confirmation
- **Type:** Timeline. **Verdict:** Keep.
- **SCOPE:** Horizontal axis from 1916 to 2022. Mark: Schwarzschild solution (1916), eclipse test (1919), Chandrasekhar limit (1930), Cygnus X-1 (1971), Hawking radiation prediction (1974), galactic-center stars (1990s), LIGO GW150914 (2015), EHT M87 (2019), EHT Sgr A* (2022).
- **P:** 8–9 events. Sky-blue markers for theoretical milestones, vermillion for observational confirmations. Annotate each with the institution / observer.
- **Caption hook:** Author's caption is excellent.

### Fig 8.2 — Light Bending in Two Pictures
- **Type:** Comparison panels (Newtonian vs. Einsteinian). **Verdict:** Keep — but **fix caption truncation** ("Two panels").
- **SCOPE:** Panel (a) Newton: light passes near Sun, undeflected (Newton predicts a tiny effect from corpuscular gravity, but historically not the right number). Panel (b) Einstein: light follows curved geodesic through warped spacetime, deflected by 1.75″ at solar limb.
- **P:** 6 components per panel. Sky-blue for light path. Spacetime grid (curved in panel b, flat in panel a) as a faint background. Star at apparent vs. true position labeled. Sun in vermillion.
- **Caption:** "Eddington's 1919 eclipse photographed star positions near the Sun's limb. The stars appeared shifted by exactly Einstein's predicted 1.75 arcseconds. Newton's gravity does not bend light by this amount; only spacetime curvature does."

### Fig 8.3 — Schwarzschild Radius Across Scales
- **Type:** Statistical / quantitative. **Verdict:** Keep — synthesis figure.
- **SCOPE:** Log-log plot. X: mass (kg, from 10²⁴ to 10⁴⁰). Y: Schwarzschild radius (m, from 10⁻³ to 10¹³). Single line at slope 1 (since R_S ∝ M). Mark: Earth (R_S ≈ 9 mm), Sun (3 km), stellar BH 10 M_☉ (30 km), Sgr A* (1.2 × 10¹⁰ m), M87* (10¹³ m), and "you" (10⁻²⁵ m for a 70 kg human — to drive home the spans).
- **P:** Single line + 6 marker points + annotations. Sky-blue line, vermillion markers. **Y-axis exception:** log scale; flag in caption.
- **Caption:** "The Schwarzschild radius depends only on mass — not composition, not temperature, not history. The relation spans 28 orders of magnitude. Every object has a radius below which it would be a black hole; for most things, that radius is laughably smaller than the object itself."

### Fig 8.4 — Light Cone Diagram at the Event Horizon
- **Type:** Mechanism cross-section / spacetime diagram. **Verdict:** Keep.
- **SCOPE:** Radial coordinate horizontal, time vertical. Light cones drawn at three positions: (a) far from BH — symmetric cones, future opens upward, escape possible. (b) at event horizon — cone tilted so future just barely points along the horizon, no outward escape. (c) inside horizon — cone tilted so far that future points entirely inward toward the singularity.
- **P:** 3 light cones + event horizon vertical line + singularity at center. Sky-blue cones. Gray dashed grid for coordinate lines. Annotate "Future has only one direction" inside the horizon.
- **Caption:** Author's caption nails the conceptual point — keep.

### Fig 8.5 — Stellar Orbits Around Sagittarius A*
- **Type:** Annotated example / orbit plot. **Verdict:** Keep.
- **SCOPE:** Top-down view of the galactic center. Plot the orbits of S2, S0-102, S62, S4711 (the famous tracked stars). Central point marked as Sgr A* (invisible). Scale bar in AU. Time markers along the S2 orbit.
- **P:** 4 orbits in different Okabe-Ito colors (sky-blue, orange, yellow, vermillion — avoid red/green pair). Black star marker for Sgr A*. Faint background grid.
- **Caption hook:** Author's caption is good — keep.

### Fig 8.6 — X-ray Binary Schematic
- **Type:** Mechanism cross-section.
- **SCOPE:** Companion star (left, normal star), Roche lobe filling, mass stream toward compact object, accretion disk around the black hole (right). Inner disk hot, emitting X-rays. Annotate temperatures, orbital plane, X-ray emission cone.
- **P:** 6-7 components. Sky-blue accretion disk gradient (hot → cool), orange companion star, black point for BH (with horizon circle), vermillion X-ray emission arrows.
- **Verdict:** Keep. Caption is good.

### Fig 8.7 — LIGO Schematic + GW150914 Signal
- **Type:** Combined annotated example + statistical chart.
- **SCOPE:** Upper portion: LIGO L-shaped interferometer schematic (4 km arms, beamsplitter, mirrors, detector). Lower portion: GW150914 waveform — strain vs. time, showing inspiral chirp + merger + ringdown. Both Hanford and Livingston traces overlaid with 7 ms offset.
- **P:** Sky-blue for one detector, orange for the other. Strain on y-axis (units: 10⁻²¹), time on x-axis (0.2 sec window). Frequency rising visibly toward merger.
- **Verdict:** Keep. Author's caption is good.

### Fig 8.8 — Event Horizon Telescope Image
- **Type:** Annotated photograph.
- **SCOPE:** The real EHT M87 image. Annotate the bright ring (accretion disk emission, gravitationally lensed), the central shadow (the silhouette of the event horizon), the brightness asymmetry (Doppler-boosted side from rotation), scale bar.
- **P:** Use the actual image. 4-5 annotations with leader lines outside the image proper.
- **Verdict:** Keep. Caption is good.

---

## Architectural Notes

**Malformed tables in source:**
- Lines 63–69 (Newton vs Einstein test table) contains template detritus ("A concrete checkpoint for applying the chapter concept" repeated across cells). Should be either fixed as a proper table or **promoted to Fig 8.9 — a clean 4-row × 4-column comparison** (Newton's prediction / Einstein's prediction / observed / precision) for the four tests (Mercury, light deflection, GR time dilation/GPS, GW speed). Strong candidate.
- Lines 187–194 (black hole class table) contains the same template detritus. Should be either fixed or **promoted to Fig 8.10 — a 3-row × 5-column comparison** (mass range / R_S range / avg interior density / formation pathway / detection method) for stellar / intermediate / supermassive black holes. Also a strong candidate; the counterintuitive density column (supermassive BHs have lower-than-water average internal density) deserves visual emphasis.

**Recommendation:** add Figs 8.9 and 8.10 as cleanup of the malformed tables. New density: **10 figures, Mechanistic** — still defensible given chapter length and conceptual ambition.

---

## Cross-Chapter References

- **Fig 8.2 (light bending)** — Ch 1 (special relativity) discussed *c* as constant; Ch 8 shows it follows curved geodesics. Cite Ch 1 forward to Ch 8.
- **Fig 8.3 (R_S across scales)** — Ch 7 (death of stars) establishes when collapse hits the BH endpoint; cite back to Ch 7 Fig 7.4 (core collapse sequence).
- **Fig 8.7 (LIGO + GW150914)** — Ch 16 (frontiers) on gravitational-wave astronomy may want this; cite back.
- **Fig 8.4 (light cones)** — only place light cones appear in the book; do not duplicate in Ch 9 if Ch 9 = spacetime diagrams (cite back instead).

---

## Video Candidate Pass

**Three strong candidates:**

1. **Light cone tilt approaching event horizon** (Fig 8.4 animated) — observer's light cone rendered as a 3D object; as observer falls inward, cone tilts and finally collapses to point inward. ~30 seconds. The single best way to communicate "the future changes direction."
2. **Stellar orbits around Sgr A*** (Fig 8.5 animated) — three decades of S2 orbital data played in real-time-equivalent. The 16-year orbit collapsing into a 30-second video viscerally proves the central mass. ~25 seconds.
3. **GW150914 chirp** (Fig 8.7 animated) — waveform plays in real time (0.2 sec extended to ~10 sec) with audio sonification (the chirp is actually audible). The merger as both a visual and audio event. ~15 seconds.

The EHT image (Fig 8.8) is essentially the still-frame video already.
