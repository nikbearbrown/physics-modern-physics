# CAJAL Figure Intelligence — Ch 6: Particle Physics

**Source:** `chapters/06-particle-physics.md`
**Mode:** `/scan`
**Author pre-architecture:** None (no inline `![]()` markers).
**Domain note:** Standard Model overview — force-strength comparison, force-carriers, quarks/leptons/three generations, Higgs mechanism, electroweak unification, early-universe cosmology, what the SM doesn't explain (dark matter, dark energy, gravity, baryogenesis).

**Editorial flag:** Ch 15 is also titled "Particle Physics." Before producing finals, confirm with author whether Ch 6 = the conceptual / Standard-Model overview and Ch 15 = the experimental / accelerator / detector side, or whether they should be consolidated. The figure architecture here assumes Ch 6 = the conceptual overview.

---

## Density Recommendation

**6 figures, Mechanistic density.** The chapter is structured around five conceptual blocks (forces-as-exchange, Standard Model inventory, Higgs, unification, what's missing) each of which begs for a visual. Without a Standard Model chart, readers cannot keep 17 particles straight. Without an early-universe timeline, the unification story is abstract.

---

## Figure 6.1 — Four Forces Comparison

- **C** — Statistical / quantitative comparison.
- **O** — Table-style chart, 4 rows (gravity, weak, electromagnetic, strong), 4 columns (relative strength, range, carrier particle, carrier mass).
- **P** — Use Okabe-Ito to color-code the carrier-particle row: sky-blue (photon), orange (W/Z), vermillion (gluons), gray (hypothetical graviton). Strength column as a log-scale bar chart in the cell (spanning 10⁰ to 10³⁸). Range column with scale icons (∞ vs. 10⁻¹⁸ m vs. 10⁻¹⁵ m).
- **E** — Numerical relative strengths in cells (gravity = 1, strong ≈ 10³⁸).
- **Caption:** "Gravity is 10³⁸ times weaker than electromagnetism — yet runs the universe at large scales because it does not cancel. Strong forces dominate inside the nucleus and vanish outside it. The carrier's mass determines the force's range, via the uncertainty principle."

## Figure 6.2 — Feynman Diagram: Electron-Electron Exchange

- **C** — Process flowchart / mechanism diagram.
- **O** — Time axis vertical (upward). Two incoming electron lines from below; one virtual photon (wavy) exchanged between them; two outgoing electron lines above. Label vertices, lines, exchanged particle.
- **P** — 6 components: 2 incoming electrons, vertex 1, virtual photon, vertex 2, 2 outgoing electrons. Black lines for electrons (with arrowheads showing fermion direction), sky-blue wavy line for the photon. Time arrow on the side.
- **E** — Note in caption: each diagram is a term in a calculation; QED predicts to 10+ decimal places.
- **Caption:** "Two electrons repel by exchanging a virtual photon. The diagram is not a cartoon — it is a term in a sum that gives the calculated probability of the interaction. Quantum electrodynamics built on these diagrams is the most precisely-tested theory in physics."

## Figure 6.3 — The Standard Model Inventory

- **C** — Hierarchy / structural map. The classic SM chart.
- **O** — Grid: rows = particle types (quarks, leptons, gauge bosons, scalar). Columns = generations (I, II, III) for the fermions; bosons in a fourth column. 17 particles total.
- **P** — Use Okabe-Ito categorically: orange (quarks: u/d/c/s/t/b), sky-blue (leptons: e/μ/τ + 3 neutrinos), vermillion (gauge bosons: γ, g, W, Z), yellow (Higgs). Each cell shows symbol + name + mass + charge. Same cell size throughout.
- **E** — Masses in caption (electron 0.511 MeV, top quark 173 GeV — span of 6 orders of magnitude).
- **Caption:** "Seventeen particles for everything you can touch. Three generations of matter (the second and third are heavier copies of the first, all unstable), four force-carriers, and the Higgs. This single chart is the complete inventory of fundamental matter — except gravity, dark matter, and dark energy."

## Figure 6.4 — Higgs Mechanism: Mass from a Field

- **C** — Conceptual map / mechanism diagram.
- **O** — A particle moving through "empty" space, except the space is filled with the Higgs field (rendered as a textured background). Three particles shown: a photon (passes through unaffected, massless), a light fermion (slight drag, light mass), a top quark (heavy drag, heavy mass). Each labeled with its mass.
- **P** — 6 components: 3 particles + 3 trajectory drag indicators + textured Higgs background. Sky-blue for the photon, orange for the light fermion, vermillion for the top. Avoid the temptation to render the Higgs field with literal molasses imagery (cliché and misleading); use a uniform stipple/dot pattern instead.
- **E** — Caption explains: mass is the coupling strength to the field.
- **Caption:** "Mass is not an intrinsic property — it is how strongly a particle interacts with the Higgs field that fills all of space. The photon does not interact; it is massless. The top quark interacts strongly; it is the heaviest known particle. You weigh what you do because your quarks and electrons couple to a field discovered in 2012."

## Figure 6.5 — Cosmological Timeline of Unification

- **C** — Timeline.
- **O** — Logarithmic time axis from 10⁻³⁶ s (inflation, GUT scale) through 10⁻¹¹ s (electroweak transition) through 10⁻⁶ s (quark confinement) through 3 min (BBN) through 380,000 yr (CMB / atom formation) through 13.8 Gyr (now). Energy scale shown on a parallel axis.
- **P** — 6-7 events. Sky-blue markers, log axis explicitly noted in caption (this is a log-time figure; standard zero-baseline rule doesn't apply because zero on log time = the Big Bang singularity). Annotate each event with the relevant physics (forces unified, forces split, particles formed).
- **E** — Temperatures noted (~10²⁸ K at GUT scale down to 2.7 K today).
- **Caption:** "The universe is a particle-physics record. Each cooling threshold marks a point where forces became distinct. We cannot recreate the GUT scale in a lab; we can read it in the cosmic background."

## Figure 6.6 — What the Standard Model Doesn't Explain

- **C** — Conceptual map / pie chart of cosmic energy content.
- **O** — Single pie or stacked bar showing the universe's energy content: 5% ordinary matter (Standard Model territory), 27% dark matter, 68% dark energy. Annotate the SM slice with "described to 12 significant figures" and the other two slices with "unknown."
- **P** — Okabe-Ito sky-blue (SM), gray (dark matter), light gray with hatching (dark energy). Avoid pie if the small slice is hard to read — stacked bar is fine. Optional secondary panel: a short list of other gaps (gravity, baryogenesis, three generations, hierarchy problem).
- **E** — None on figure.
- **Caption:** "The Standard Model is one of the most tested theories in physics — and it accounts for 5% of the universe's energy content. The other 95% is dark matter (gravitationally evident, otherwise invisible) and dark energy (causing accelerated expansion, otherwise mysterious). The frontier is the unmapped majority."

---

## Validation Pass

- **Cross-reference flags:**
  - **Fig 6.5 (cosmological timeline)** — Ch 11 (the Big Bang) will need a parallel timeline figure. Coordinate: Ch 6 emphasizes unification thresholds; Ch 11 emphasizes structure formation. Different axes/annotations, but same backbone.
  - **Fig 6.3 (SM chart)** — Ch 15 (particle physics dup) will also want it. If Ch 15 is the experimental chapter, defer the chart to Ch 6 and let Ch 15 use detector / collision-event figures instead.
  - **Fig 6.6 (cosmic energy pie)** — Ch 11 (Big Bang) and Ch 16 (frontiers) will both need this. Treat Fig 6.6 as canonical; reference back.
  - Force-strength comparison (Fig 6.1) could also serve Ch 16 (frontiers) if it discusses quantum gravity.

---

## Video Candidate Pass

**Two strong candidates:**

1. **Cosmological timeline animated** (Fig 6.5 animated) — temperature drops as time advances; forces unify and split visibly as each threshold is crossed. Most students don't get a visceral feel for "10⁻¹¹ seconds" — animation makes the cooling cascade legible. ~30 seconds.
2. **Higgs mechanism with adjustable coupling** (Fig 6.4 animated) — slider for "Higgs coupling strength"; particle drag through the field visibly increases as the slider rises; mass numbers update. ~20 seconds. Conveys what "acquiring mass" actually means without the molasses misconception.

The Feynman diagram (Fig 6.2) is a third candidate but static reads cleanly.
