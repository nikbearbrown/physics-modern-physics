# CAJAL Figure Intelligence — Ch 3: The Sun (Nuclear Powerhouse)

**Source:** `chapters/03-the-sun-a-nuclear-powerhouse.md`
**Mode:** `/scan`
**Author pre-architecture:** None (no inline `![]()` markers).
**Domain note:** The fusion mechanism chapter — Darwin's problem, why chemistry/gravity fail, Coulomb barrier, quantum tunneling, pp-chain, photon random walk, solar neutrinos / Davis experiment / oscillation, hydrostatic thermostat.

---

## Density Recommendation

**6 figures, Mechanistic density.** Five distinct mechanisms need visual support (Coulomb barrier + tunneling, pp-chain sequence, photon vs. neutrino journey, neutrino oscillation, hydrostatic feedback loop). The chapter's central pedagogical move — "rare events × enormous numbers = steady output" — also wants a quantitative figure.

---

## Figure 3.1 — Energy Source Comparison: Chemistry vs. Gravity vs. Fusion

- **C** — Statistical / quantitative comparison. Horizontal bar chart: estimated solar lifetime under each energy source.
- **O** — 3 bars: chemical burning (~5,000 yr), gravitational contraction (~100 Myr), nuclear fusion (~10 Gyr). Log x-axis (mandatory — span is 6 orders of magnitude). X-axis starts at 1 yr; log scale flagged in caption.
- **P** — 3 bars, Okabe-Ito sky-blue / vermillion / orange. Label each with the numerical lifetime. Vertical dotted line at 4.5 Gyr ("Earth's age") with annotation.
- **E** — Caption only. Lifetime calculations not shown on figure.
- **Caption:** "Three candidate energy sources for the Sun, compared against the geological floor (Earth is 4.5 billion years old). Chemistry fails by a factor of ~10⁶. Gravity fails by a factor of ~50. Fusion gives the right answer with billions of years to spare. The log axis is required because the span is too large for linear."

## Figure 3.2 — The Coulomb Barrier and Quantum Tunneling

- **C** — Mechanism cross-section. Energy diagram with potential-energy curve.
- **O** — x: separation between two protons (fm). y: potential energy. Curve rises steeply (Coulomb repulsion) toward a peak at r ≈ 1 fm, then plunges into a deep well (strong force binding). Horizontal line marking thermal energy at 15 MK (well below the peak).
- **P** — 6 components: potential curve, thermal-energy line, "classical turn-around" marker, tunneling-region shaded with hatched pattern, wave function (small amplitude on far side), label arrows. Sky-blue potential curve. Vermillion thermal-energy line. Hatched tunneling region in gray.
- **E** — No equations on figure. Caption notes the probability is ~10⁻²⁰ per collision.
- **Caption:** "Two protons cannot classically reach the strong-force well — their thermal energy is millions of times too small. Their wave function leaks through the barrier with vanishing probability. Multiplied by 10⁵⁷ protons and constant collisions, vanishing becomes 600 million tonnes per second."

## Figure 3.3 — The Proton-Proton Chain (Three Steps)

- **C** — Process flowchart / cycle diagram. Three reaction steps arranged in a triangle or staircase.
- **O** — Step 1 (rate-limiting, slow): ¹H + ¹H → ²H + e⁺ + ν. Step 2 (fast, seconds): ²H + ¹H → ³He + γ. Step 3 (fast): ³He + ³He → ⁴He + 2¹H. Inputs and outputs shown as labeled icons (proton = small filled circle, neutron = small open circle, neutrino = arrow with ν, positron = small + sign, gamma = wavy arrow).
- **P** — 6-7 components: 3 reaction boxes, mass-deficit annotation (0.7%), energy-released annotation (26.7 MeV total), waiting-time annotation on step 1 ("billions of years per proton"). Okabe-Ito sky-blue for input/output protons, vermillion for the helium-4 product. No red/green.
- **E** — Reaction equations beside each step.
- **Caption:** "Four protons in, one helium-4 out, 0.7% of the mass converted to energy. Step 1 is the bottleneck — it requires both quantum tunneling and a weak-force conversion (proton → neutron), and gates the entire chain."

## Figure 3.4 — Photon Random Walk vs. Neutrino Straight-Line

- **C** — Comparison panels, two-frame race.
- **O** — Two stacked panels showing same cross-section of the Sun. Panel (a) photon: born at core, jagged random walk path through 700,000 km, exits surface ~100,000–1,000,000 years later, then 8 minutes to Earth. Panel (b) neutrino: born at core, straight line through Sun and through Earth, total ~2 seconds.
- **P** — 6 components per panel: solar interior, core, exit point, path trace, time label, particle icon. Sky-blue for photon path, orange for neutrino. Same time-axis annotation.
- **E** — None on figure.
- **Caption:** "Same fusion event, two messengers. The photon spends nearly a million years bouncing through the dense plasma; the neutrino is gone before the photon has moved a millimeter. The light on your face was born when Homo sapiens was first leaving Africa."

## Figure 3.5 — Neutrino Oscillation (Davis Problem and Sudbury Resolution)

- **C** — Process flowchart with a quantitative bar overlay.
- **O** — Three states along a horizontal path: (1) Sun's core — 100% electron neutrinos, (2) midway — mixture, (3) Earth detector — ~33% electron, ~33% muon, ~33% tau. Above each state a stacked bar showing the flavor composition.
- **P** — 6 components: Sun icon (left), Earth icon (right), three stacked bars at the three sample points, flavor legend (νₑ / νμ / ντ in three colorblind-safe colors — Okabe-Ito sky-blue / orange / yellow), travel arrow. Note: Davis tank "saw" only the sky-blue (νₑ) component; Sudbury saw all three.
- **E** — Caption explains: oscillation requires neutrino mass. Standard Model predicted massless; this is direct evidence to the contrary.
- **Caption:** "The solar neutrino problem looked like a problem with the Sun. It was a problem with the particle. Electron neutrinos born in the core arrive at Earth as a mixture of three flavors — an effect that can only occur if neutrinos have nonzero mass. Two Nobel Prizes resulted (Davis/Koshiba 2002; Kajita/McDonald 2015)."

## Figure 3.6 — Hydrostatic Equilibrium as a Thermostat

- **C** — Cycle diagram. Feedback loop, two directions.
- **O** — Circle of arrows showing the feedback cascade. Top: "core cools slightly" → "fusion slows" → "pressure drops" → "outer layers compress" → "core heats" → "fusion accelerates" → back to top. Second loop, opposite direction: "core heats slightly" → "fusion accelerates" → "pressure rises" → "layers expand" → "core cools" → "fusion slows."
- **P** — 6-8 components: two opposing cycles drawn as concentric or side-by-side loops. Okabe-Ito sky-blue arrows for the cooling-corrects cycle, vermillion for the heating-corrects cycle. Center label: "Self-regulating."
- **E** — None on figure. Caption explains exponential temperature sensitivity is what makes the feedback strong.
- **Caption:** "The Sun is not a bomb. It is a thermostat. The same exponential sensitivity of fusion rate to temperature that makes nuclear energy powerful makes it controllable — perturbations damp themselves in seconds. Life on Earth had 4.5 billion years of steady sunlight as a consequence of this single feedback loop."

---

## Validation Pass

- **Cross-reference flags:**
  - Fig 3.2 (Coulomb barrier / tunneling) — Ch 4 (quantum nature of light) and Ch 10 (quantum physics) will revisit tunneling. Treat Fig 3.2 as the in-context application; let Ch 10 do the general formalism.
  - Fig 3.3 (pp-chain) — Ch 7 (death of stars) will introduce the CNO cycle and triple-alpha; cite Fig 3.3 as the baseline.
  - Fig 3.4 (photon random walk) — Ch 2 already has a "random walk vs. straight line" figure (Fig 2.4). **POTENTIAL DUPLICATE.** Decision: Ch 2 Fig 2.4 is schematic (two paths, generic). Ch 3 Fig 3.4 adds the neutrino comparison and time axis. Keep both, but coordinate visual style so Ch 3 reads as the deepened version. Or: drop Ch 2 Fig 2.4 and lean on Ch 3 Fig 3.4 with a Ch 2 forward-reference.
  - Fig 3.6 (thermostat) — Ch 7 (death of stars) will need to show when the thermostat fails (degenerate cores, runaway). Reference back.

- **No duplicates** within this chapter.

---

## Video Candidate Pass

**Three strong candidates:**

1. **Quantum tunneling animation** (Fig 3.2 animated) — wave function approaching the barrier, most of it reflecting, a tiny amplitude leaking through. Most students have never seen tunneling shown probabilistically rather than as a fixed cartoon. ~20 seconds.
2. **Photon random walk + neutrino straight line race** (Fig 3.4 animated) — split-screen: photon zigzags for "100,000 years" (compressed to 20 seconds), neutrino crosses the Sun in 2 seconds and waits. High dramatic payoff; perfectly aligns with the chapter's two-messenger argument.
3. **Hydrostatic thermostat feedback** (Fig 3.6 animated) — perturb the core, watch the cycle settle. ~15 seconds. Shows what "exponentially sensitive feedback" actually looks like.

The pp-chain (Fig 3.3) is a fourth candidate but reads cleanly as a static flowchart.
