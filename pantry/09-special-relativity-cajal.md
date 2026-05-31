# CAJAL Figure Intelligence — Ch 9: Special Relativity (DUPLICATE TOPIC)

**Source:** `chapters/09-special-relativity.md`
**Mode:** `/scan`
**Author pre-architecture:** **8 figures already placed inline (Figs 9.1–9.8).**
**Domain note:** Substantially the same arc as Ch 1 — Michelson-Morley, two postulates, simultaneity, time dilation, length contraction, velocity addition (NEW), E = γmc², Newtonian limit, spacetime interval invariant (NEW).

---

## ⚠️ EDITORIAL FLAG — HIGHEST PRIORITY

**Ch 1 and Ch 9 are both titled "Special Relativity" and cover overlapping ground.** Before any art is produced for Ch 9, an editorial decision is required:

**Option A — Consolidate.** Fold Ch 9 into Ch 1, lifting only the additions (Michelson-Morley experimental detail, velocity addition formula, spacetime-interval invariance). Drop Ch 9 entirely.

**Option B — Split by depth.** Ch 1 = conceptual introduction (two postulates, time dilation, length contraction, mass-energy). Ch 9 = mathematical mechanics (full velocity addition, Lorentz transforms, spacetime intervals, invariants). Re-title Ch 9 → "The Geometry of Spacetime" or similar.

**Option C — Split by audience.** Ch 1 = the narrative chapter (Einstein/Michelson-Morley story). Ch 9 = the worked-derivations chapter (algebra, Pythagoras, Lorentz transformation derivations). Re-title to make the distinction obvious.

**My recommendation:** Option B. Ch 9 has two genuinely new contributions (velocity addition, the invariant interval / Minkowski perspective) that deserve a chapter. The 8 figures the author placed are largely duplicates of Ch 1's needs — but Figs 9.6 (velocity addition) and 9.8 (Minkowski diagram) are NEW and Ch 1 should not duplicate them.

This editorial decision determines which figures are needed. The validation below assumes **Option B** (split by depth).

---

## Density Recommendation Under Option B

**6 figures effective, Mechanistic density.** Drop or downgrade Figs 9.1–9.5 (Michelson-Morley, simultaneity, light clock, γ curve, muon survival) since Ch 1 already has them. Keep Figs 9.6 (velocity addition), 9.7 (mass-energy), and 9.8 (Minkowski diagram) as the new material. Add 1–2 figures for Lorentz transformations explicitly.

---

## Figure-by-Figure Validation (assuming Option B)

### Fig 9.1 — Michelson-Morley Interferometer
- **Type:** Mechanism cross-section. **Verdict:** **Demote to a small inset within Fig 9.2 of Ch 1**, or keep in Ch 9 only if Ch 1 does not show it. Decide as part of editorial consolidation.
- **SCOPE if kept:** Top-down view of the apparatus. Light source, beamsplitter, two perpendicular arms with end mirrors, recombination at detector. Annotate the predicted-vs-observed fringe shift.

### Fig 9.2 — Train-and-Embankment Simultaneity
- **Verdict:** **Duplicate of Ch 1 Fig 1.2.** Drop from Ch 9; cite Ch 1.

### Fig 9.3 — Light-Clock Time Dilation Derivation
- **Verdict:** **Duplicate of Ch 1 Fig 1.1.** Drop from Ch 9; cite Ch 1.

### Fig 9.4 — γ as a Function of v/c
- **Verdict:** **Duplicate of Ch 1 Fig 1.3.** Drop from Ch 9; cite Ch 1. **Also fix caption truncation** ("Γ as a function of v/c").

### Fig 9.5 — Muon Survival
- **Verdict:** **Duplicate of Ch 1 Fig 1.4.** Drop from Ch 9; cite Ch 1.

### Fig 9.6 — Relativistic vs. Classical Velocity Addition  ⭐ NEW
- **Type:** Statistical / quantitative. **Verdict:** Keep. New content not in Ch 1. **Fix caption truncation** ("Relativistic vs").
- **SCOPE:** Plot u (combined speed) vs. u' (object speed in moving frame) for a fixed v = 0.5c. Two curves: classical u = v + u' (straight line, exceeds c), relativistic u = (v + u′)/(1 + vu′/c²) (curve asymptoting to c). Mark u = c as a horizontal limit.
- **P:** Two curves. Okabe-Ito sky-blue (classical), vermillion (relativistic). Horizontal dashed line at u = c.
- **Caption:** "Classical velocity addition lets speeds exceed c. Relativistic addition saturates at c. The formula recovers classical addition for v, u' ≪ c and preserves the second postulate exactly when u' = c."

### Fig 9.7 — Mass-Energy Equivalence in Context
- **Type:** Statistical / quantitative. **Verdict:** Keep — but ensure it does not duplicate Ch 1 Fig 1.6 (energy decomposition). Differentiate: Fig 9.7 shows mass-to-energy conversion at real-world scales (gram → joules, fission, fusion, annihilation), not γ-curve geometry.
- **SCOPE:** Horizontal log bar chart. Y-axis: process (1 gram annihilation, 1 gram fission, 1 gram fusion, 1 gram chemical burning, daily Sun loss). X-axis: energy released in joules (log scale, 10⁵ to 10¹⁵). Annotate each with the relevant fraction of mass converted.
- **P:** 5 bars. Okabe-Ito vermillion for nuclear, orange for chemical, sky-blue for full annihilation. Log axis flagged.
- **Caption:** "What c² actually means in practice. Chemical burning converts 10⁻⁹ of the rest mass. Fission converts 10⁻³. Fusion converts 10⁻². Annihilation converts everything. The span from chemistry to annihilation is a factor of a billion."

### Fig 9.8 — Spacetime Diagram (Minkowski)  ⭐ NEW
- **Type:** Mechanism cross-section / structural schematic. **Verdict:** Keep. Central to Option B's "Ch 9 = geometry" framing.
- **SCOPE:** 2D spacetime: x horizontal, ct vertical. Light cones (45° lines). World-line of stationary observer (vertical). World-line of moving observer (tilted). Two events shown — one observer says they are simultaneous (horizontal slice), another says they are not (tilted slice). Spacetime interval s² = (cΔt)² − Δx² annotated as the same on both slices.
- **P:** 6-7 components: x and ct axes, two light-cone lines, two world-lines, two simultaneity slices (in different colors), interval annotation. Okabe-Ito sky-blue for one observer's slice, orange for the other. Black for light cones.
- **Caption:** Author's caption is good — keep.

---

## Additional Figure Suggestion (Option B Only)

### Fig 9.9 (proposed) — Lorentz Transformation Visualized
- **Type:** Mechanism diagram with overlaid coordinate grids.
- **SCOPE:** Same Minkowski plane as Fig 9.8, but show two coordinate grids overlaid: (x, ct) for rest frame and (x', ct') for moving frame. The two grids are "sheared" relative to each other (Lorentz boost = hyperbolic rotation). Show how the same event has different coordinates in each.
- **Justification:** Without this, readers see the interval-invariance claim but not the transformation that makes it visible.

---

## Architectural Notes

- **Malformed table** at lines 186–188 (system / speed / v/c columns with placeholder cells "A concrete checkpoint for applying the chapter concept"). **Promote to Fig 9.10:** a clean comparison table of γ-1 across velocity regimes (car, plane, ISS, GPS, muon, LHC proton). Strong candidate; the 18-orders-of-magnitude span deserves a figure.
- **Caption truncations** on Figs 9.4 and 9.6.

---

## Cross-Chapter References

- **All figures in Ch 9 should cite Ch 1.** Specifically:
  - Fig 9.7 (mass-energy at scale) cites Ch 1 Fig 1.6 (energy decomposition).
  - Fig 9.6 (velocity addition) is new to Ch 9.
  - Fig 9.8 (Minkowski) is new to Ch 9 — and Ch 8 (black holes) Fig 8.4 (light-cone tilt at event horizon) should cite Fig 9.8 as the flat-space precursor.

---

## Video Candidate Pass

**Two strong candidates (Option B):**

1. **Lorentz coordinate transformation** (Fig 9.9 animated) — slide the velocity parameter; the moving frame's grid visibly shears; the spacetime interval remains constant while x and ct components shift. ~25 seconds. The clearest possible way to see invariance.
2. **Velocity-addition saturation** (Fig 9.6 animated) — slider for u'; classical curve runs off-scale at c; relativistic curve asymptotes smoothly. ~15 seconds.

If Option A is chosen (consolidate), Ch 1's video candidates (light clock, muon split-screen) suffice.
