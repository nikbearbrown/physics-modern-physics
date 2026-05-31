# CAJAL Figure Intelligence — Ch 1: Special Relativity

**Source:** `chapters/01-special-relativity.md`
**Mode:** `/scan`
**Author pre-architecture:** None (no inline `![]()` markers).
**Domain note:** Foundational SR chapter — Michelson-Morley, two postulates, simultaneity, time dilation, length contraction, E = mc², Newtonian limit.

---

## Density Recommendation

**6 figures, Mechanistic density.** This is a derivation-heavy chapter built on three thought experiments (train-simultaneity, light-clock, muon-from-two-frames) plus a γ-curve and a mass-energy diagram. The prose is dense with geometry that begs to be drawn. Without figures the muon section and the Pythagorean derivation lose the reader.

**Editorial flag:** Ch 9 is also titled "Special Relativity." Before producing finals, decide whether Ch 1 = postulates/dilation/contraction/E=mc² and Ch 9 = spacetime diagrams/four-vectors/twin paradox, or whether Ch 9 should be folded into Ch 1. The figure architecture here assumes Ch 1 = the geometric introduction.

---

## Figure 1.1 — The Light Clock (Time Dilation Geometry)

- **C** — Process flowchart / mechanism cross-section hybrid. Two side-by-side panels: (a) rest frame — vertical light path, height *h*, period 2*h/c*. (b) Moving frame — diagonal light path forming the hypotenuse of a right triangle with legs *h* and *v*Δ*t*/2. Both panels share the same clock object.
- **O** — Two panels, horizontal. Same scale. Same clock geometry rotated/shifted. Arrows show light direction. Right-triangle decomposition labeled in panel (b).
- **P** — 6 callout components max: top mirror, bottom mirror, light pulse, vertical leg (*h*), horizontal leg (*v*Δ*t*/2), hypotenuse (*c*Δ*t*/2). Okabe-Ito blue for light path. Black for clock structure. Gray dashed for the triangle decomposition.
- **E** — No equations on the figure. No numeric γ values. Caption carries the algebra link.
- **Caption:** "The same clock seen from two frames. In its own frame (a) the light travels 2*h*; in a frame where the clock moves at *v* (b) the light travels the longer diagonal path. Because *c* is the same in both frames, the longer path takes longer — time dilation is the geometric consequence."

## Figure 1.2 — Relativity of Simultaneity (Train + Lightning)

- **C** — Comparison panels, two frames. Train car, observer A at center; observer B on platform. Two lightning strikes at car ends. Panel (a) train frame: light reaches A at same instant. Panel (b) platform frame: train moves right; front-strike light has shorter path to B, arrives first.
- **O** — Two stacked panels, same horizontal axis (the train). Time arrows beneath each. Equal spacing between strikes and observer in both.
- **P** — 7 components: train car, observer A, observer B, two strike points, two light rays, time-arrow. Use Okabe-Ito orange/sky-blue for the two light rays. No text inside the figure.
- **E** — None. Symmetry must be visually obvious. No red/green.
- **Caption:** "Simultaneity is frame-dependent. Both observers correctly account for finite light travel time, both reason carefully, both disagree about whether the strikes happened together. The disagreement is built into spacetime, not a measurement error."

## Figure 1.3 — The Lorentz Factor γ vs. v/c

- **C** — Statistical / quantitative. Single curve, γ on y-axis (1 to ~10), v/c on x-axis (0 to 0.99).
- **O** — Linear x-axis, linear y-axis. Mark γ = 1, 2, 7, 10 on y. Mark v/c = 0, 0.5, 0.87, 0.95, 0.99 on x with vertical dotted drop-lines to the curve.
- **P** — 1 curve, 4 marker points, gridlines light gray. Y-axis starts at 1 (the rest-frame value), not zero — this is a γ chart, not a counting chart; explicitly note in caption that 1 is the floor. Sky-blue curve.
- **E** — Formula box in caption: γ = 1/√(1 − v²/c²). Annotate the asymptote at v = c.
- **Caption:** "At everyday speeds γ ≈ 1 to twenty decimal places. The blow-up is sudden: γ = 7 at 0.99c, γ = 70 at 0.9999c, γ → ∞ at c. This single curve is why an infinite-energy barrier sits at the speed of light."

## Figure 1.4 — The Muon Story from Two Frames

- **C** — Comparison panels, paired. Panel (a) Earth frame: 15 km atmosphere column, muon at top moving down at 0.99c, clock dilated by γ ≈ 7, label "muon's 2.2 μs becomes 15 μs in our frame, enough to reach the ground." Panel (b) muon frame: atmosphere contracted to ~2 km, muon at rest, Earth rushing up, label "atmosphere only 2 km thick, crossed in 2.2 μs."
- **O** — Two vertical columns, same atmospheric column rendered at two different lengths. Single muon icon. Annotations align horizontally.
- **P** — 6 components: atmosphere column, muon, Earth surface, clock readout, distance label, velocity label. Okabe-Ito vermillion for the muon path. Black for the atmosphere outline.
- **E** — Numbers in callouts (15 km / 2 km, 2.2 μs / 15 μs). No equations on the figure.
- **Caption:** "Same particle arriving at the same detector, derived two different ways. Time dilation in Earth's frame, length contraction in the muon's frame. Both correct; both required for relativity to be internally consistent."

## Figure 1.5 — Length Contraction Mechanism

- **C** — Mechanism cross-section. A long ruler/rod moving rightward at v. Two observers: ruler frame (top) and lab frame (bottom). Lab frame marks both ends simultaneously (in its frame); ruler frame disagrees about simultaneity of the marks.
- **O** — Two horizontal strips, stacked. Time arrow horizontal. Mark events labeled.
- **P** — 6 components: rod, two end-marks, ruler-frame clock, lab-frame clock, velocity vector. Sky-blue for rod, black for marks, gray for clocks.
- **E** — L = L₀/γ in caption only.
- **Caption:** "Length contraction is a consequence of the relativity of simultaneity. The lab observer marks both ends 'at once'; the ruler's frame says one end was marked before the other. The shorter measurement is real, not a mistake."

## Figure 1.6 — Energy Decomposition: γmc² vs. mc² + ½mv²

- **C** — Statistical / quantitative. Plot of total energy / rest energy as a function of v/c. Three curves overlaid: (1) Newtonian KE + mc², (2) relativistic γmc², (3) rest energy mc² (horizontal line at y = 1).
- **O** — x: v/c from 0 to 0.99. y: E/(mc²) from 1 to ~7. Two curves diverge dramatically above v/c ≈ 0.5.
- **P** — 3 curves max. Okabe-Ito vermillion (relativistic), sky-blue (Newtonian), gray (rest). Y-axis starts at 1 (the rest-energy floor) — note in caption. Shaded region between curves where Newtonian fails.
- **E** — Formula box: E = γmc² and Eₙ = mc² + ½mv². Note that they agree to first order in v²/c².
- **Caption:** "Newton is not wrong — he is a low-speed limit. The two curves are indistinguishable below v ≈ 0.1c and diverge to infinity vs. a finite quadratic above 0.5c. The mc² term was always there; it just never mattered until mass started not being conserved."

---

## Validation Pass

- **Cross-reference flags:** Ch 4 (quantum nature of light) uses E = hf and p = h/λ for photons — the photon momentum / massless-particle case should reference Fig 1.6's discussion of γ → ∞ for massless particles. Ch 8 (curved spacetime) will return to time dilation; the light-clock figure can be cited.
- **No duplicates** within this chapter.
- **Editorial:** confirm Ch 9 split before final art.

---

## Video Candidate Pass

**Two strong candidates:**

1. **Light-clock animation** (Fig 1.1 in motion) — the diagonal lengthening as v increases is the chapter's central intuition. Perfect for a 30-second loop. Aligns with the chapter's "thought-experiment demonstration" LLM exercise (student records their own walkthrough).
2. **Muon-from-two-frames split-screen** (Fig 1.4 in motion) — atmosphere contracting in real time as v dial slides toward c, with the muon's lifetime countdown in both frames simultaneously. Strongest pedagogical payoff in the chapter.

The simultaneity-train (Fig 1.2) is a third candidate but is well-served by static panels; animation adds less.
