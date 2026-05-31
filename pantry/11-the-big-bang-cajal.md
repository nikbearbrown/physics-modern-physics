# CAJAL Figure Intelligence — Ch 11: The Big Bang

**Source:** `chapters/11-the-big-bang.md`
**Mode:** `/scan`
**Author pre-architecture:** **5 figures already placed inline (Figs 11.1–11.5).**
**Domain note:** Three-pillars framing — Hubble expansion, Big Bang nucleosynthesis, CMB — converging on a single cosmological history. Lithium problem flagged. Hubble tension, dark energy mystery, inflation as open questions.

---

## Density Recommendation

**5 figures, Mechanistic density** — author has set the density well. Each figure serves one of the three pillars or the synthesis. CAJAL validates.

---

## Figure-by-Figure Validation

### Fig 11.1 — Hubble's Law
- **Type:** Statistical / quantitative. **Verdict:** Keep.
- **SCOPE:** X: distance (Mpc, 0 to ~30 for original 1929 data; or 0 to ~500 for modern). Y: recession velocity (km/s). Linear fit. Show Hubble's actual 1929 data points if possible (sparse and scattered), with the modern best-fit line overlaid. Mark slope as H₀ ≈ 70 km/s/Mpc.
- **P:** Single line + data scatter. Okabe-Ito sky-blue line, vermillion 1929 points, orange modern points if both shown. Y-axis from zero.
- **Caption hook:** Author's caption is good.

### Fig 11.2 — Big Bang Nucleosynthesis Reaction Network
- **Type:** Process flowchart / reaction network.
- **SCOPE:** Flowchart showing nuclear reactions: free protons + neutrons → deuterium → tritium / He-3 → He-4. Arrow weights proportional to reaction rates. Show why the chain stops at He-4 (no stable mass-5 or mass-8 nuclei). Trace amounts of Li-7 indicated as a side branch.
- **P:** 6-7 nodes (p, n, D, T, He-3, He-4, Li-7) + arrows. Okabe-Ito sky-blue for stable nuclei, vermillion for unstable intermediates. Annotate the freeze-out ratio (1 n : 6 p) and the resulting He-4 mass fraction (~25%).
- **Verdict:** Keep. Caption is good.

### Fig 11.3 — Planck Satellite Full-Sky CMB Map
- **Type:** Annotated photograph / data visualization.
- **SCOPE:** The famous Mollweide-projection CMB temperature map from Planck. Color scale showing ΔT/T variations on the order of 10⁻⁵. Annotate galactic plane mask, dipole removal note, scale of fluctuations.
- **P:** The actual Planck image. **CAJAL flag on color choice:** the standard NASA/ESA CMB rendering uses red-blue diverging palette, which is not colorblind-safe. Recommend re-rendering with a viridis or Okabe-Ito diverging palette (orange-blue) for accessibility. Alternatively, present a grayscale version with annotations.
- **Caption hook:** Author's caption is excellent.

### Fig 11.4 — CMB Angular Power Spectrum
- **Type:** Statistical / quantitative.
- **SCOPE:** X: multipole moment ℓ (log scale or linear, 2 to ~2500). Y: ΔT² × ℓ(ℓ+1)/(2π) in μK². Show data points (Planck or WMAP+Planck combined) with error bars, and the calculated ΛCDM curve overlaid. Mark the first three acoustic peaks (geometry, baryon density, dark-matter density).
- **P:** Data points (vermillion) + theory curve (sky-blue). Y-axis from zero. Annotate the three peaks with their physical meanings.
- **Caption hook:** Author's caption captures the agreement perfectly.

### Fig 11.5 — Cosmic Timeline
- **Type:** Timeline. **Verdict:** Keep.
- **SCOPE:** Logarithmic time axis from Planck time (10⁻⁴³ sec) through inflation (10⁻³⁶) through electroweak transition (10⁻¹¹) through BBN (1 sec – 3 min) through recombination (380,000 yr) through first stars (~200 Myr) through now (13.8 Gyr). Annotate each with the relevant physics.
- **P:** 7–8 events on a horizontal log axis. Okabe-Ito sky-blue for confirmed events, vermillion shading for speculative regions (before 1 sec). Cross-reference: matches Ch 6 Fig 6.5 (cosmological timeline) — coordinate the two so they share a backbone.
- **Caption:** Author's caption is precise on what is directly observable vs. inferred vs. speculative.

---

## Architectural Notes

- **Three-pillars synthesis table** at lines 117–121 (Measurement Type / Physical Observable / Key Number / Agrees) is well-formed and could either stay as a table or be promoted to Fig 11.6 (a panel showing the three independent lines of evidence converging on the same baryon density / age). Strong synthesis figure candidate — recommend Fig 11.6 as the close.

**Proposed Fig 11.6 — Three Pillars Converge:**
- **C** — Comparison panels with a shared synthesis axis.
- **O** — Three small panels showing each measurement (Hubble curve, BBN abundance predictions, CMB peaks) — each with an arrow pointing to the same shared output box: "ordinary matter density ≈ 4.9%; age ≈ 13.8 Gyr."
- **Justification:** The three-pillars argument is the chapter's central thesis. Without a single figure showing the convergence visually, the argument lives in prose only.

**New density recommendation:** **6 figures, Mechanistic density** (with Fig 11.6 added).

---

## Cross-Chapter References

- **Fig 11.5 (cosmic timeline)** ↔ **Ch 6 Fig 6.5 (cosmological timeline)** — must coordinate. Ch 6 emphasizes force unification thresholds; Ch 11 emphasizes structure formation. Different annotations on the same backbone.
- **Fig 11.2 (BBN network)** ↔ **Ch 7 Fig 7.7 (periodic table by origin)** — Ch 7 shows which elements came from BBN vs. stars vs. r-process. Cross-reference.
- **Fig 11.4 (CMB peaks)** — Ch 16 (frontiers) on dark matter / dark energy can cite back.
- **Cosmic energy pie** (5% / 27% / 68%) — Ch 6 Fig 6.6 establishes the pie. Cite back rather than redraw.

---

## Video Candidate Pass

**Two strong candidates:**

1. **CMB temperature map zoom-in** (Fig 11.3 animated) — start with full sky; zoom progressively into a small patch; show the temperature fluctuations growing visible as the color scale is rescaled. The "1 part in 10⁵" abstraction becomes concrete. ~25 seconds.
2. **Cosmic timeline play-through** (Fig 11.5 animated) — animate forward through cosmic history with relevant physics labels appearing as each threshold is crossed (forces unify/split, nuclei form, atoms form, first stars ignite, structure grows). ~45 seconds. The chapter's signature visual narrative.

Hubble's law (Fig 11.1) is a third candidate (data points appearing as more galaxies are measured over time) but is well-served by static.
