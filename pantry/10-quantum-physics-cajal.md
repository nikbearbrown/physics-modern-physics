# CAJAL Figure Intelligence — Ch 10: Quantum Physics

**Source:** `chapters/10-quantum-physics.md`
**Mode:** `/scan`
**Author pre-architecture:** **8 figures already placed inline (Figs 10.1–10.8).**
**Domain note:** Three-experiments framing — blackbody / photoelectric / electron diffraction — plus uncertainty principle and atomic stability as application. Substantial overlap with Ch 4 (quantum nature of light) and Ch 5 (the atom).

---

## ⚠️ Editorial Cross-Chapter Flag

This chapter overlaps significantly with two earlier chapters:
- **Ch 4 (quantum nature of light)** covers blackbody, photoelectric, Compton, de Broglie, double slit.
- **Ch 5 (the atom)** covers the uncertainty principle and atomic stability via the same Bohr-radius argument that appears at the end of this chapter.

Ch 10's relative emphasis (per the chapter intro: "three experiments that demolished classical physics, and what replaced it") is on the *historical sequence* and the *Schrödinger/matrix-mechanics synthesis* as the resolution. This framing is distinct enough to merit its own chapter, but the figure architecture must avoid duplicating Ch 4 and Ch 5.

**Recommendation:** treat Ch 10 figures as syntheses or refinements of Ch 4 / Ch 5 figures, not first appearances. Most should cite back rather than redraw.

---

## Density Recommendation

**5 effective figures, Mechanistic density** (downgrade from author's 8). Many of the author-placed figures are duplicates of Ch 4. Keep the synthesis figures (Fourier uncertainty, hydrogen energy balance) and the figures that show Ch 10's distinctive contribution (electron diffraction at Davisson-Germer scale).

---

## Figure-by-Figure Validation

### Fig 10.1 — Blackbody Spectrum
- **Verdict:** **Duplicate of Ch 4 Fig 4.1.** Drop or cite back. If kept, the figure must look identical to Ch 4 Fig 4.1 to reinforce cross-chapter recognition — same axes, same temperature, same color scheme. No reason to draw twice.

### Fig 10.2 — Why Quantization Cuts Off High-Frequency Modes
- **Verdict:** **Near-duplicate of Ch 4 Fig 4.2** (minimum-wage / hf > kT mechanism). Drop and cite back, or merge with Ch 4 Fig 4.2 as the single canonical version.

### Fig 10.3 — The Photoelectric Effect (Millikan's Graph)
- **Type:** Statistical / quantitative. **Verdict:** Keep — but **make it distinctly Millikan's measurement plot**, not a redraw of Ch 4 Fig 4.3.
- **SCOPE:** X: frequency of incident light (Hz). Y: maximum kinetic energy of ejected electrons (eV). Single linear line: KE_max = hf − φ. Slope = h. Y-intercept = −φ. Annotate the threshold frequency f₀ where line crosses zero.
- **P:** Single line + data points (use Millikan's actual 1916 data if possible). Okabe-Ito sky-blue line, vermillion data dots. Y-axis from zero (KE) — when line dips below zero on left, dashed extrapolation indicates the work function intercept.
- **Caption hook:** Author's caption is excellent — "Millikan measured this graph in 1916 trying to disprove Einstein. He confirmed him instead." Preserve.

### Fig 10.4 — Compton Scattering
- **Verdict:** **Duplicate of Ch 4 Fig 4.5.** Drop and cite back.

### Fig 10.5 — Davisson-Germer Electron Diffraction
- **Type:** Statistical / quantitative + mechanism inset. **Verdict:** Keep — Ch 10 distinctive content.
- **SCOPE:** Polar plot or angular intensity plot showing the sharp peak at 50° for 54-eV electrons on nickel. Inset: schematic of the apparatus (electron gun, nickel target with crystal planes, detector at varying angle).
- **P:** Polar plot in sky-blue. Inset mechanism in black/gray.
- **Caption hook:** Author's caption is good.

### Fig 10.6 — de Broglie Wavelength Across Scales
- **Type:** Statistical / quantitative.
- **SCOPE:** Log-log plot. X: momentum (kg·m/s, from 10⁻³⁰ to 10³). Y: de Broglie wavelength (m, from 10⁻³⁵ to 10⁻⁶). Single line at slope −1. Mark: electron at 100 eV (0.12 nm), neutron at room T (0.18 nm), C₆₀ buckyball (0.003 nm), 1 kg ball (10⁻³⁵ m). Shaded "observable" region (wavelengths > atomic spacing).
- **P:** Single line + 4–5 marker points. Sky-blue line; vermillion markers. Log-log flagged.
- **Caption:** "Wave behavior is universal. It just doesn't matter macroscopically — h is small enough that a thrown ball has a wavelength a trillion trillion times smaller than a proton. For electrons, wavelengths are atomic. For molecules of a few hundred atoms, wavelengths are still measurable."

### Fig 10.7 — The Fourier Uncertainty
- **Type:** Conceptual / comparison panels.
- **SCOPE:** Two pairs of plots showing wave packets and their momentum spectra. Pair 1: narrow position Gaussian + broad momentum spectrum. Pair 2: broad position Gaussian (long sine wave) + narrow momentum spike. Δx × Δp annotated as constant.
- **P:** 4 plots in 2×2 grid. Sky-blue for waves, gray for Gaussian envelopes.
- **Verdict:** Keep. Important — Ch 5 Fig 5.5 makes the same point at the atomic-stability level; Ch 10 Fig 10.7 makes it at the Fourier-mathematics level. The two complement, not duplicate.

### Fig 10.8 — Hydrogen Atom Total Energy vs. Radius
- **Verdict:** **Duplicate of Ch 5 Fig 5.6.** Drop and cite back to Ch 5 — or, since this is the synthesis at the close of Ch 10, keep as the closing figure with explicit "see Ch 5 Fig 5.6 for the same physics in atomic context" cross-reference.
- **If kept:** caption truncation ("Hydrogen atom total energy vs") needs fixing.

---

## Architectural Notes

**Caption truncations:** Fig 10.8 has "Hydrogen atom total energy vs" — incomplete.

**Strong recommendation:** **Drop Figs 10.1, 10.2, 10.4, 10.8 outright as duplicates of Ch 4/5**, with explicit cross-references in the prose. Keep Figs 10.3 (Millikan's distinctive measurement), 10.5 (Davisson-Germer), 10.6 (de Broglie across scales), 10.7 (Fourier uncertainty). That leaves 4 figures, Mechanistic density — appropriate for a synthesis / consolidation chapter.

If author wants to keep 8 figures, the captions must explicitly position each as a refinement of the corresponding Ch 4/Ch 5 figure (e.g., "Fig 10.1 reproduces Ch 4 Fig 4.1 with annotations for the historical sequence …").

---

## Cross-Chapter References

- **Ch 4 (quantum nature of light)** — heavy overlap. Figs 10.1, 10.2, 10.4 are duplicates.
- **Ch 5 (the atom)** — overlap on Fig 10.8 (atomic stability).
- **Ch 5 Fig 5.5 (uncertainty principle)** vs **Ch 10 Fig 10.7 (Fourier uncertainty)** — coordinate: Ch 5 = physical intuition, Ch 10 = mathematical statement. Different angles, not duplicates.

---

## Video Candidate Pass

**One strong candidate (since most other content has already been covered in Ch 4):**

1. **Davisson-Germer rotating detector** (Fig 10.5 animated) — the detector arm rotates; intensity is shown as a real-time polar plot; the sharp peak emerges at 50° once enough electrons accumulate. ~20 seconds. Distinctive to Ch 10.

If Fig 10.7 (Fourier uncertainty) is kept, the trade-off can be animated nicely as a slider that morphs the position Gaussian and shows the momentum spectrum respond. ~15 seconds.
