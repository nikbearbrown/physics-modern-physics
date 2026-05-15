# TIKTOC.md — Physics +1, Modern Physics

## Physics +1 Series · Modern Physics

**Author:** Nik Bear Brown
**Series:** Physics +1
**Format:** $1 Kindle · Brutalist D3 + Claude Code
**Brutalist reference:** brutalist-d3-x-claude
**Series prototype:** quantum-mechanics-plus-one
**Source chapters:** _src_* files in chapters/ (college-physics + physics + astronomy cold opens)

---

## Series contract (every chapter)

Every chapter in order: mechanism deep-dive · exercises · "What would change my mind" · "Still puzzling" · LLM Exercise (D3 simulation) · AI Wayback Machine · bridge

---

## D3 simulation character: Intuition

Modern physics simulations provide the only available intuition for objects with no classical analog. The student cannot see a relativistic muon or a collapsing stellar core. Every simulation is the primary intuition-builder — there is no physical experience to fall back on. Simulations should make the impossible visible.

---

## Chapter list

### Chapter 1 — Special Relativity

**Source:** _src_ college-physics ch28 + _src_ physics ch10
**D3 simulation:** Lorentz transformation animator — vary v/c, watch length contraction and time dilation; light clock visualization; twin paradox spacetime diagram
**Core concepts:** Postulates of special relativity, time dilation, length contraction, relativistic momentum and energy, E=mc²
**Research focus:** Why the speed of light is constant (what experiment forced Einstein's hand — Michelson-Morley accessible version); muon decay as experimental proof; E=mc² meaning (mass-energy equivalence, not "mass converts to energy"); CLAUDE.md failure mode: Lorentz factor formula errors

### Chapter 2 — The Quantum Revolution — Light as Particles

**Source:** _src_ college-physics ch29 + _src_ physics ch21
**D3 simulation:** Photoelectric effect — vary frequency and intensity; show threshold frequency, stopping voltage, Einstein's equation; blackbody radiation curve with ultraviolet catastrophe
**Core concepts:** Blackbody radiation, ultraviolet catastrophe, Planck's hypothesis, photoelectric effect, photons, Compton scattering
**Research focus:** Why the ultraviolet catastrophe was a crisis (accessible version); why Einstein won the Nobel for photoelectric effect, not relativity; CLAUDE.md failure mode: photoelectric current depends on frequency (threshold), not intensity

### Chapter 3 — Atomic Physics — The Bohr Model and Beyond

**Source:** _src_ college-physics ch30 + _src_ physics ch22
**D3 simulation:** Bohr model + spectral lines animator — select element (H, He, Li); show electron transitions; emit/absorb photon; watch spectral line appear in emission/absorption spectrum
**Core concepts:** Rutherford's nuclear model, Bohr model, energy levels, emission and absorption spectra, de Broglie wavelength
**Research focus:** Why Bohr's model works despite being wrong (semi-classical accident); best cold open (neon lights, stellar spectroscopy, laser); connection to full QM in QM+1 volume; CLAUDE.md failure mode: energy level diagrams with wrong sign convention

### Chapter 4 — The Sun as a Nuclear Powerhouse

**Source:** _src_ astronomy ch15-16 (cold open + narrative) + college-physics nuclear sections
**D3 simulation:** Solar interior cross-section — show layers (core, radiative zone, convective zone); proton-proton chain; show energy production rate vs radius; photon random walk from core to surface
**Core concepts:** Stellar structure, nuclear fusion, proton-proton chain, solar neutrinos, helioseismology
**Research focus:** Why the solar neutrino problem was a crisis (and how it was resolved — neutrino oscillations); how we know what's inside the Sun (helioseismology); the random walk of a photon from core to surface (takes ~100,000 years)

### Chapter 5 — Radioactivity and Nuclear Physics

**Source:** _src_ college-physics ch31
**D3 simulation:** Decay chain animator — show alpha, beta, gamma decay; half-life slider; show daughter nuclei; N(t) = N₀ e^(-λt) plotted live; carbon-14 dating mode
**Core concepts:** Nuclear structure, radioactive decay, alpha/beta/gamma, half-life, nuclear reactions, binding energy
**Research focus:** Why alpha particles are stopped by paper but gamma rays penetrate lead (interaction mechanisms); carbon dating accuracy and limits; binding energy per nucleon curve (iron peak — why stars can't fuse beyond iron)

### Chapter 6 — Medical Applications of Nuclear Physics

**Source:** _src_ college-physics ch32
**D3 simulation:** Dose/decay visualizer — show penetration depth for different radiation types; PET scan coincidence detection; radiation dose units (Gy vs Sv) compared
**Core concepts:** Radiation dose, biological effects, medical imaging (X-ray, CT, PET, MRI), radiation therapy
**Research focus:** Why MRI is NMR (historical name change); how PET scanning works (annihilation radiation); linear no-threshold model controversy — good "what would change my mind" material; real dose comparisons (chest X-ray vs background)

### Chapter 7 — The Death of Stars

**Source:** _src_ astronomy ch23 (primary) + college-physics nuclear sections
**D3 simulation:** Stellar remnant router — input stellar mass, watch evolutionary endpoint: white dwarf (M < 8M☉), neutron star (8–20M☉), black hole (>20M☉); Chandrasekhar limit visualization; neutron star density comparison
**Core concepts:** White dwarfs, Chandrasekhar limit, neutron stars, pulsars, supernovae, black hole formation
**Research focus:** Why the Chandrasekhar limit is 1.4 solar masses (electron degeneracy pressure — accessible version); pulsar discovery story (Jocelyn Bell Burnell — excellent Wayback Machine figure); why a neutron star has the density of atomic nuclei

### Chapter 8 — Black Holes and Curved Spacetime

**Source:** _src_ astronomy ch24 (primary)
**D3 simulation:** Geodesic visualizer — show spacetime curvature around a massive object; light bending around the Sun; event horizon — show photon sphere, Schwarzschild radius; gravitational redshift
**Core concepts:** General relativity (qualitative), spacetime curvature, Schwarzschild radius, event horizon, gravitational waves, Hawking radiation
**Research focus:** Einstein's equivalence principle (elevator thought experiment); first image of a black hole (EHT 2019 — M87*); gravitational wave detection (LIGO) — Kip Thorne Wayback Machine; Hawking radiation as "still puzzling" (never detected)

### Chapter 9 — Particle Physics and the Standard Model

**Source:** _src_ college-physics ch33 + _src_ physics ch23
**D3 simulation:** Standard Model particle explorer — interactive table; click particle to show properties (mass, charge, spin); show fundamental interactions (EM, weak, strong, gravity); show quark combinations for common hadrons
**Core concepts:** Quarks, leptons, bosons, fundamental forces, Standard Model, Higgs boson, antiparticles
**Research focus:** Why the Standard Model is incomplete (no gravity, dark matter, dark energy); Higgs discovery 2012; best cold opens (why matter dominates antimatter — still unsolved); CLAUDE.md failure mode: confusing quarks and leptons as the same category

### Chapter 10 — The Big Bang and Cosmology

**Source:** _src_ astronomy ch29 (primary) + college-physics ch34
**D3 simulation:** Hubble diagram — plot recession velocity vs distance for real galaxy data; fit Hubble's law; CMB spectrum visualizer — show 2.7K blackbody; timeline of universe from Big Bang to now
**Core concepts:** Hubble's law, expanding universe, Big Bang, cosmic microwave background, dark matter, dark energy
**Research focus:** Why Hubble's constant is still contested (H₀ tension — good "still puzzling"); what the CMB actually is (relic radiation, not explosion debris); dark energy as the biggest unsolved problem in physics

### Chapter 11 — Life in the Universe and the Frontiers of Physics

**Source:** _src_ astronomy ch30 + _src_ college-physics ch34
**D3 simulation:** Drake equation interactive — vary each parameter (R*, fp, ne, fl, fi, fc, L), watch N change over enormous range; show uncertainty bars; connect to SETI
**Core concepts:** Drake equation, conditions for life, exoplanet detection methods, open problems in physics (dark matter, quantum gravity, matter-antimatter asymmetry)
**Research focus:** Why the Drake equation is useful despite huge uncertainties (Fermi estimation pedagogy); best open problems for "still puzzling" (quantum gravity, dark matter identity, consciousness); connection to QM+1 volume (quantum foundations as frontier)
