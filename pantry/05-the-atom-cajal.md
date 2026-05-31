# CAJAL Figure Intelligence — Ch 5: The Atom (Structure, Energy, Uncertainty)

**Source:** `chapters/05-the-atom.md`
**Mode:** `/scan`
**Author pre-architecture:** None (no inline `![]()` markers).
**Domain note:** Bohr-to-Schrödinger arc — Rutherford scattering, Bohr quantization, Balmer series, de Broglie waves, Schrödinger orbitals, uncertainty principle as the stabilizer of matter, periodic-table connection.

---

## Density Recommendation

**6 figures, Mechanistic density.** Five distinct mechanisms (Rutherford geometry, Bohr ladder + transitions, standing-wave orbits, orbital shapes, uncertainty trade-off) plus one synthesis figure showing atomic-scale numbers. The chapter does heavy lifting and benefits from visual scaffolding at each conceptual pivot.

---

## Figure 5.1 — Rutherford Scattering Geometry

- **C** — Comparison panels, two atomic models tested by the same alpha-particle beam. Panel (a) Thomson's plum-pudding: diffuse positive charge sphere, alpha particles deflected slightly. Panel (b) Rutherford's nuclear atom: concentrated nucleus, most alphas pass through, a few bounce back from near-direct hits.
- **O** — Two panels side-by-side. Same incoming alpha beam (from left). Same atomic outline (gray dashed). Different internal structure. Trajectories drawn with curvature proportional to the local Coulomb force.
- **P** — 6-7 components per panel: atomic outline, incoming beam, scattered trajectories (5-6 sample paths each), nucleus (in panel b), backscatter marker, deflection angles. Okabe-Ito vermillion for the alpha trajectories; black for atomic structure. Avoid red/green.
- **E** — Caption notes the empirical fraction (1 in 8,000 backscattered) and the scale revelation (nucleus 100,000× smaller than atom).
- **Caption:** "Thomson's atom predicted small deflections; Rutherford's data showed backscatter. Same beam, two models, different geometries. The only model that fits is one where positive charge is packed into a region 10⁻¹⁵ m across — 100,000 times smaller than the atom."

## Figure 5.2 — Bohr Energy-Level Ladder + Balmer Transitions

- **C** — Hierarchy / energy-level diagram with overlaid transitions.
- **O** — Vertical energy axis from −13.6 eV (n=1, bottom) to 0 (n=∞, top). Horizontal lines at n=1, 2, 3, 4, 5, 6. Downward arrows from n=3, 4, 5, 6 to n=2 — the four visible Balmer transitions. Each arrow labeled with the photon wavelength (656, 486, 434, 410 nm).
- **P** — 6 levels + 4 transition arrows + axis. Arrows colored matching their emission wavelength (red, cyan, violet, deep violet). Energy axis labeled. **Y-axis exception:** energy is negative for bound states; floor is −13.6 eV, ceiling is 0. Note the exception in the brief — energy diagrams legitimately use a non-zero baseline; this is not a y-axis-from-zero violation because the axis is signed and zero is the ionization reference.
- **E** — ΔE = 13.6 eV (1/n_f² − 1/n_i²) in caption.
- **Caption:** "Each downward jump produces one photon at one specific wavelength. The four arrows ending at n=2 are the Balmer series — the four lines you see when hydrogen glows. The spectrum is discrete because the ladder is discrete."

## Figure 5.3 — Standing Wave on a Circular Orbit (de Broglie Justification)

- **C** — Mechanism diagram, three panels.
- **O** — Three circular orbits, each with a wave drawn around the circumference. Panel (a) n=1: one full wavelength fits. Panel (b) n=2: two wavelengths. Panel (c) "forbidden": non-integer wavelengths, wave fails to close on itself, drawn faded.
- **P** — 6 components: 3 orbital circles, 3 wave traces, fraction-of-wavelength annotations. Sky-blue waves. The "forbidden" wave should visibly mismatch.
- **E** — λ = h/p in caption. Note: nλ = 2πr is Bohr's quantization condition recovered.
- **Caption:** "Bohr's mysterious quantization condition has a simple visual cause. An electron wave around the nucleus has to close on itself or destructively interfere with itself and vanish. Only integer wavelengths survive — and that is exactly Bohr's rule."

## Figure 5.4 — Hydrogen Orbital Shapes (1s, 2s, 2p)

- **C** — Structural schematic / probability cloud rendering.
- **O** — 4-panel grid: 1s (spherical density cloud, dense at center), 2s (spherical with one radial node), 2p_x (dumbbell along x-axis), 2p_z (dumbbell along z-axis). Same scale for all four. Density represented by dot pattern or alpha gradient — denser = higher probability.
- **P** — 4 panels. Sky-blue for high-density regions, white background. Cross-section through the nucleus shown in each. Scale bar (0.1 nm).
- **E** — None on figure.
- **Caption:** "Solutions to Schrödinger's wave equation for a Coulomb potential. The electron is not in orbit — it is spread through space as a wave, and the probability of finding it at any point is the square of the wave amplitude. The shapes are what 'where the electron is' actually means."

## Figure 5.5 — Uncertainty Principle: Position vs. Momentum Trade-off

- **C** — Comparison panels showing wave packets.
- **O** — Two side-by-side wave packets. Panel (a) "well-localized position": tight Gaussian envelope in x, broad spectrum in momentum (shown as a second small inset). Panel (b) "well-defined momentum": long sinusoidal wavetrain in x, narrow peak in momentum (inset). Both panels share x-axis scale.
- **P** — 6 components: two main wave-packet plots, two momentum-spectrum insets, Δx and Δp annotations. Sky-blue wave, gray Gaussian envelope.
- **E** — Δx · Δp ≥ ℏ/2 in caption.
- **Caption:** "Pin a wave down in space and its momentum spectrum spreads out. Pin its momentum down and it spreads out in space. This is not measurement clumsiness — it is what waves are. Electrons are waves. The trade-off is built in."

## Figure 5.6 — Why Atoms Don't Collapse: Energy vs. Confinement

- **C** — Statistical / quantitative.
- **O** — Y-axis: energy. X-axis: confinement radius (log scale, 10⁻¹² to 10⁻⁸ m). Two curves: (a) kinetic energy cost from confinement, rising as 1/r²; (b) Coulomb attractive energy, falling as −1/r. Sum curve has a minimum — the equilibrium radius. Mark the Bohr radius (0.53 × 10⁻¹⁰ m) at the minimum.
- **P** — 3 curves + minimum marker + Bohr radius callout. Okabe-Ito sky-blue (KE), orange (PE), black (sum). **Y-axis exception:** energy is signed; zero is the unbound reference, the minimum is negative.
- **E** — Caption explains: shrink the atom and KE cost explodes; expand it and the attraction can't pay. The minimum is where matter is stable.
- **Caption:** "The uncertainty principle is why you don't fall through the floor. Confining an electron costs kinetic energy that the Coulomb attraction can't pay below a certain radius. The Bohr radius is where the two budgets balance — the size of every atom in your body."

---

## Validation Pass

- **Cross-reference flags:**
  - **Fig 5.2 (Bohr ladder)** overlaps with **Ch 4 Fig 4.7 (hydrogen spectrum strip)** and will overlap again with **Ch 12 (atomic physics)** Lyman/Paschen series. Editorial coordination: Ch 4 shows the spectrum as observed; Ch 5 shows the energy-level cause; Ch 12 generalizes to the full Rydberg formula and multi-electron atoms. Cross-reference, don't duplicate.
  - **Fig 5.5 (uncertainty principle)** — Ch 10 (quantum physics) will revisit. Cite Fig 5.5 as the "physical why" and let Ch 10 develop the formal commutator.
  - **Fig 5.6 (matter stability)** — should be cited from Ch 7 (death of stars) when discussing white dwarf degeneracy pressure as the same physics at a different scale.

- **No duplicates** within this chapter.

---

## Video Candidate Pass

**Two strong candidates:**

1. **Standing-wave orbit fitting** (Fig 5.3 animated) — sliding the wavelength continuously and watching the wave fail to close until it hits n=3, n=4 etc. Most viscerally satisfying way to communicate "quantization comes from waves." ~20 seconds.
2. **Rutherford scattering animation** (Fig 5.1 animated) — alpha particles streaming in; most pass through; one rare backscatter event highlighted. The "1 in 8,000" frequency is dramatic when shown in real time. ~25 seconds.

The Bohr transitions (Fig 5.2) work as a third animated candidate (electron drops down ladder, photon emitted of the right color) but are well-served by static.
