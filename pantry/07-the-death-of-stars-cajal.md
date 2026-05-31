# CAJAL Figure Intelligence — Ch 7: The Death of Stars

**Source:** `chapters/07-the-death-of-stars.md`
**Mode:** `/scan`
**Author pre-architecture:** **7 figures already placed inline (Figs 7.1–7.7).** Substantially pre-architected.
**Domain note:** SN 1987A opener, white dwarfs + Chandrasekhar limit, core-collapse supernovae, neutron stars, pulsars (Bell Burnell), Type Ia vs Type II, periodic table by nucleosynthesis.

---

## Density Recommendation

**7 figures, Mechanistic density** — author has set the density. CAJAL validates and refines.

---

## Figure-by-Figure Validation

### Fig 7.1 — SN 1987A Event Timeline
- **Type:** Timeline. **Verdict:** Keep.
- **SCOPE:** Horizontal time axis spanning ~3 hours (neutrino burst at T=0, optical brightening 3 hours later). Mark: core collapse, neutrino arrival at Kamiokande/IMB (T+0 to T+13 sec, 20 neutrinos), photons begin breakout, naked-eye visibility from Chile (~T+3 hr).
- **P:** 5 events. Okabe-Ito sky-blue for neutrino marker, orange for optical. Annotate "20 neutrinos detected from a flood of 10⁵⁸." Vertical axis indicates flux on log scale (or omit; this is a timeline, not a magnitude curve).
- **Caption hook:** "The neutrinos arrived three hours before the light. From 160,000 light-years, twenty particles told us a star had died."

### Fig 7.2 — White Dwarf Mass-Radius Relationship
- **Type:** Statistical / quantitative. **Verdict:** Keep — central pedagogical figure.
- **SCOPE:** Y: radius (in Earth radii or km). X: mass (in solar masses, 0 to 1.5). Single curve showing radius decreasing with increasing mass (counterintuitive — more massive WDs are smaller). Vertical asymptote at the Chandrasekhar limit (~1.4 M_☉).
- **P:** One curve + vertical asymptote (vermillion) + label "Chandrasekhar limit." Y-axis from zero. Annotate "calculated at age 20 on a ship from India to England."
- **Caption hook:** Author's caption is excellent; preserve.

### Fig 7.3 — Cross-Section of a Massive Star Near the End
- **Type:** Mechanism cross-section. **Verdict:** Keep — but **fix caption truncation**.
- **SCOPE:** Onion-shell cross-section: H-burning shell (outermost), He shell, C shell, O/Ne shell, Si shell, iron core (innermost). 5-6 layers. Annotate burning timescale beside each (H: Myr, He: 100 kyr, C: 1000 yr, O: 1 yr, Si: 1 day).
- **P:** Use Okabe-Ito family for the layers, ordered so the iron core stands out (vermillion). Each layer labeled. Avoid red/green pairing.
- **Caption:** "Each layer burns faster than the one outside it. The Si shell lasts a day. Then the core is iron, and fusion stops — because iron is the most tightly bound nucleus, there is no more energy to extract."

### Fig 7.4 — Core Collapse Sequence
- **Type:** Cycle / sequential diagram. **Verdict:** Keep.
- **SCOPE:** 5 panels: (1) iron core forms, (2) collapse begins (Earth-size → 20 km in ~1 sec), (3) inner core bounces, shockwave forms, (4) shockwave stalls in overlying material, (5) neutrino energy revives the shock, explosion launches. Annotate timescale on each (10⁻¹ sec for collapse; seconds for the whole sequence).
- **P:** 5 horizontal panels. Sky-blue for plasma, vermillion for the shockwave front, gray for neutrinos (as small arrows escaping outward in panel 5). Scale bar on each panel.
- **Caption hook:** "The neutrinos are the hidden mechanism. Without their tiny push, the shockwave dies and the star doesn't explode."

### Fig 7.5 — Pulsar Lighthouse Model
- **Type:** Mechanism cross-section / rotation diagram.
- **SCOPE:** Neutron star at center, rotation axis vertical, magnetic axis tilted ~30° from rotation axis. Twin beams of radio emission emerging from magnetic poles. Earth in the path of one beam. Sweep arrow.
- **P:** 6 components: neutron star, rotation axis, magnetic axis, two emission beams, Earth, sweep indicator. Sky-blue beams. Tilt is essential — without it, no pulse seen from Earth.
- **Verdict:** Keep. Caption is good.

### Fig 7.6 — Crab Nebula Image
- **Type:** Annotated photograph. **Verdict:** Keep — but **fix caption truncation** ("Hubble Space Telescope or Chandra X-ray image of").
- **SCOPE:** Real Chandra X-ray + Hubble composite of the Crab Nebula. Annotate the central pulsar with arrow, the expanding nebula (radius ~5 light-years), and the year of the explosion (SN 1054, recorded by Chinese astronomers).
- **Caption:** "Nearly 1,000 years after the explosion, the nebula still glows because the central pulsar is shedding rotational energy at a rate matching the nebula's luminosity — 38 nanoseconds of slowing per day powers everything you see."

### Fig 7.7 — Periodic Table by Nucleosynthetic Origin
- **Type:** Hierarchy / annotated structure. **Verdict:** Keep — synthesis figure.
- **SCOPE:** Standard periodic table layout, each element color-coded by primary origin: Big Bang nucleosynthesis (H, He, trace Li), cosmic-ray spallation (Li, Be, B), stellar fusion (C through Fe), s-process (Cu through Bi in red giants), r-process (heavy elements like Au, Pt, U from supernovae + NS mergers).
- **P:** 5-6 origin categories, each with an Okabe-Ito color. Standard table layout. Highlight a few biologically-relevant elements (C, O, N, Ca, Fe) with bolded borders.
- **Caption hook:** "Every element in your body has a different origin. The iron in your blood came from a massive star; the gold in your jewelry, from a neutron-star merger; the carbon, from a low-mass star's red-giant phase. The periodic table is a map of stellar history."

---

## Architectural Notes

**Malformed table:** Lines 132–138 contain a Type Ia vs Type II comparison rendered as a malformed markdown table with placeholder cells ("A concrete checkpoint for applying the chapter concept" and "two columns: Type Ia and Type II"). This is template detritus. **Recommend Fig 7.8 to replace it:** a clean 2-column comparison panel (Type Ia / Type II) with rows for progenitor, trigger, hydrogen in spectrum (yes/no), remnant, peak brightness consistency, use as distance indicator. Suggest the author either fix the table or promote it to a figure.

**Caption truncations:** Figs 7.3 and 7.6 have truncated captions. Finalize before art production.

---

## Cross-Chapter References

- **Fig 7.2 (white dwarf M-R)** — Ch 5 (the atom) Fig 5.6 establishes electron degeneracy pressure as the stabilizer of atoms; Fig 7.2 shows the same physics at the macroscopic scale. Cross-reference.
- **Fig 7.4 (core collapse)** — Ch 8 (black holes) uses the same collapse machinery; cite Fig 7.4 and pick up where it leaves off (when neutron degeneracy pressure also fails).
- **Fig 7.7 (periodic table by origin)** — Ch 11 (the Big Bang) covers BBN; cite back.
- **Fig 7.5 (pulsar lighthouse)** — Ch 16 (frontiers) may discuss pulsar timing arrays for gravitational wave detection; cite back.

---

## Video Candidate Pass

**Three strong candidates:**

1. **Core collapse sequence animated** (Fig 7.4 animated) — Earth-size iron core → 20 km in real time (compressed) → shockwave stall → neutrino revival → explosion. ~30 seconds. The single most dramatic mechanism in the chapter.
2. **Pulsar lighthouse rotation** (Fig 7.5 animated) — neutron star rotates; beam sweeps; Earth detects a pulse on each rotation; a paper-tape recording at the bottom shows the regular spike pattern Bell Burnell saw in 1967. ~15 seconds.
3. **Periodic table illuminated by origin** (Fig 7.7 animated) — start blank; Big Bang elements light up first; stellar-fusion elements illuminate as stars are born and die; r-process elements appear during a supernova flash. ~25 seconds, ties the whole chapter together.

The Crab Nebula image (Fig 7.6) is essentially already at peak — no video adds value.
