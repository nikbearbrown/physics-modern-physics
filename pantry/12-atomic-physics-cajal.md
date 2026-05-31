# CAJAL Figure Intelligence — Ch 12: Atomic Physics

**Source:** `chapters/12-atomic-physics.md`
**Mode:** `/scan`
**Author pre-architecture:** **5 figures already placed inline (Figs 12.1–12.5).**
**Domain note:** Bohr model derivation, de Broglie standing-wave justification, quantum numbers + Pauli + periodic table, Moseley's law and characteristic X-rays, sodium street lamp closing example.

---

## ⚠️ Editorial Cross-Chapter Flag

This chapter substantially overlaps with **Ch 5 (The Atom)**, which already covers Rutherford scattering, Bohr model, energy levels, de Broglie standing waves, orbital shapes, and the uncertainty principle as atomic stabilizer.

The distinct contributions of Ch 12 vs. Ch 5:
- **Ch 5:** conceptual / philosophical arc, ending at uncertainty principle.
- **Ch 12:** quantitative / derivational. Full Bohr radius derivation. Four quantum numbers. Pauli exclusion. Multi-electron atoms. Moseley + characteristic X-rays. Sodium D-line worked example. Periodic table as theorem.

This is a real distinction and Ch 12 deserves its own chapter — but the figure architecture must avoid duplicating Ch 5.

---

## Density Recommendation

**5 figures, Mechanistic density.** Author has set the density well, but Figs 12.1, 12.2, 12.3 partially duplicate Ch 5 content and need re-positioning rather than redrawing.

---

## Figure-by-Figure Validation

### Fig 12.1 — Scale Comparison of Atom vs. Nucleus
- **Type:** Annotated example / scale comparison. **Verdict:** Keep — but **fix caption truncation** ("Scale comparison of atom vs").
- **SCOPE:** Concentric circles or side-by-side renderings. Atom (10⁻¹⁰ m) at full scale; nucleus (10⁻¹⁴ m, 10,000× smaller) shown both at proportional scale (essentially invisible dot) and in a magnified inset. Author's "fly in a cathedral" metaphor referenced in caption.
- **P:** 2-3 components: atom outline (gray), nucleus dot (vermillion), magnified inset. Scale bars.
- **Verdict:** Keep — and reposition Ch 5's Rutherford-scattering Fig 5.1 to focus on the *scattering geometry*, while Ch 12 Fig 12.1 focuses on the *scale revelation*. Two different angles, not duplicates.

### Fig 12.2 — Hydrogen Energy Level Diagram
- **Verdict:** **Duplicate of Ch 5 Fig 5.2.** Drop or cite back.
- **If kept:** Ch 12 version must be more complete — show all three series (Lyman in UV, Balmer in visible, Paschen in IR), not just Balmer. Make this the canonical "full Rydberg series" figure; let Ch 5 Fig 5.2 remain the simplified "Balmer only" introductory version.

### Fig 12.3 — Standing Waves on a Circular Orbit
- **Verdict:** **Duplicate of Ch 5 Fig 5.3.** Drop and cite back to Ch 5.

### Fig 12.4 — X-ray Tube Spectrum  ⭐ NEW
- **Type:** Statistical / quantitative. **Verdict:** Keep — distinctive Ch 12 content.
- **SCOPE:** X: photon wavelength (pm) or energy (keV). Y: intensity. Two superimposed features: (1) continuous bremsstrahlung background — broad curve with a sharp cutoff at λ_min = hc/(qV); (2) sharp characteristic peaks (Kα, Kβ) sitting on the background. Annotate the cutoff and the peaks with their physics.
- **P:** Two curves. Okabe-Ito sky-blue (bremsstrahlung), vermillion (characteristic peaks). Y-axis from zero. Annotate "tube voltage = 60 kV; cutoff = 0.021 nm" or similar.
- **Caption hook:** Author's caption captures it.

### Fig 12.5 — Solar Absorption Spectrum (Fraunhofer Lines)  ⭐ NEW
- **Type:** Annotated spectrum strip. **Verdict:** Keep — distinctive Ch 12 content.
- **SCOPE:** Visible rainbow strip with dark absorption lines superimposed at characteristic Fraunhofer wavelengths (Na D doublet at 589 nm, H Balmer lines at 656/486/434/410, Mg at 518 nm triplet, Ca H/K at 397/393, Fe lines). 6-8 prominent lines labeled with the element responsible.
- **P:** Rainbow gradient background, black absorption lines, callout labels above with leader lines. The Na D doublet should be visibly two close lines.
- **Verdict:** Keep. Author's caption is good. **Cross-reference flag:** Ch 2 Fig 2.2 (solar absorption spectrum / Fraunhofer lines) covers the same ground. Decide: Ch 2 = introduces the technique (Payne-Gaposchkin context); Ch 12 = uses the technique to read element identities atom-by-atom. Coordinate so they don't look like the same figure twice.

---

## Architectural Notes

- **Malformed table** at lines 126–131 (quantum-number table — symbol / allowed values / physical meaning / number of states columns with placeholder cells). This is template detritus. **Strong recommendation: promote to Fig 12.6 — a clean quantum-number reference table** (n, ℓ, m_ℓ, m_s rows; columns for allowed values, physical meaning, count of states; final row showing total = 2n²).

**Proposed Fig 12.6 — Quantum-Number Reference Table:**
- **C** — Structural / reference table.
- **O** — 4 rows (one per quantum number) + 1 summary row. 5 columns (name, symbol, allowed values, physical meaning, states per shell n=1,2,3,4 with cumulative 2n²).
- **Justification:** The Pauli/periodic-table argument lives in this counting rule. Without a clean visual table, the reader has to mentally reconstruct from prose. The author tried to include it but the markdown is malformed.

**Revised density:** **6 figures, Mechanistic** (with Fig 12.6 added; Fig 12.3 dropped to Ch 5).

**Caption truncation:** Fig 12.1 ("Scale comparison of atom vs").

---

## Cross-Chapter References

- **Fig 12.1 (atom vs. nucleus scale)** ↔ Ch 5 Fig 5.1 (Rutherford scattering geometry) — different angles, both useful, coordinate.
- **Fig 12.2 (full Rydberg ladder)** ↔ Ch 5 Fig 5.2 (Balmer-only) ↔ Ch 4 Fig 4.7 (visible spectrum strip) — the **three figures form a progression**: Ch 4 = observed spectrum; Ch 5 = Balmer-level energy explanation; Ch 12 = full Lyman/Balmer/Paschen series. Coordinate explicitly in captions.
- **Fig 12.3 (standing waves on orbit)** — same content as Ch 5 Fig 5.3. **Drop**.
- **Fig 12.5 (Fraunhofer lines)** ↔ Ch 2 Fig 2.2 (solar absorption) — coordinate.
- **Fig 12.6 (quantum number table)** is unique to Ch 12; foundational for any subsequent chemistry-adjacent discussion.

---

## Video Candidate Pass

**Three strong candidates:**

1. **Periodic table filling under Pauli + quantum numbers** (new — relates to Fig 12.6) — animate the periodic table filling from H through Kr, with the four quantum numbers being assigned to each new electron and the shell-closure milestones (He, Ne, Ar, Kr) lighting up. ~40 seconds. Best way to show "periodic table is a theorem."
2. **X-ray tube spectrum building** (Fig 12.4 animated) — start with the continuous bremsstrahlung background; sharp characteristic peaks pop in as the tube voltage exceeds binding-energy thresholds. ~20 seconds.
3. **Fraunhofer absorption building** (Fig 12.5 animated) — start with continuous solar spectrum; dark lines appear one at a time as each element's atoms in the solar atmosphere absorb their characteristic wavelengths. ~25 seconds.

The atom-vs-nucleus scale figure (Fig 12.1) is a fourth candidate (zoom into the nucleus from atomic scale, then keep zooming to reveal proton/neutron substructure) but is well-served by static.
