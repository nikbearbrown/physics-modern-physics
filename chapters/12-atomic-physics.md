# Chapter 12 — Atomic Physics

**Suggested titles**

1. Atomic Physics
2. Bohr's Model and the Rules of Atomic Architecture
3. Why the Periodic Table Looks the Way It Does

**TL;DR.** Quantum mechanics applied to the simplest atom (hydrogen) gives Bohr's model — discrete electron orbits whose energies are quantized by the standing-wave condition $n\lambda = 2\pi r$. The model successfully predicts the hydrogen spectrum (Balmer, Lyman, Paschen series) using one constant — the Rydberg $R = 1.097 \times 10^7 \text{ m}^{-1}$. Extending to multi-electron atoms requires four quantum numbers ($n, \ell, m_\ell, m_s$) and one rule — the Pauli exclusion principle (no two electrons share the same quantum state) — which together explain the periodic table, the chemistry of every element, and the characteristic X-rays each atom emits.

---

## Manchester, March 1911

Hans Geiger and Ernest Marsden are graduate students in Ernest Rutherford's lab at the University of Manchester. They have been bombarding a thin gold foil with alpha particles (helium nuclei, which are heavy, fast, and positively charged), expecting them to pass straight through the foil with at most tiny deflections. The expectation comes from J. J. Thomson's "plum pudding" model — atoms as diffuse balls of positive charge with electrons embedded in them like raisins. In that model, alpha particles barreling through atoms should rarely encounter anything dense enough to deflect them noticeably.

Mostly, that's what the students see. Alphas zip through the foil and continue on their way. But every once in a while — about one alpha in 8000, by their later estimate — an alpha bounces back, almost retracing its path, *as if it had hit something solid*.

Rutherford, when shown the data, said it was "as if you had fired a 15-inch shell at a piece of tissue paper, and it had come back and hit you."

His interpretation, published in 1911: the atom is mostly empty space. Almost all its mass and all its positive charge are concentrated in a tiny dense *nucleus* — about $10^{-15} \text{ m}$ in size, $10^5$ times smaller than the atom itself. Electrons, much lighter and somehow distributed in the larger surrounding region, account for the volume but almost none of the mass.

This is the *nuclear atom* — the picture every chemistry student now learns first day of class. But it has a problem. Classical electromagnetism says any accelerating charge radiates energy. Electrons orbiting a nucleus would be continuously accelerating (centripetally), so they should radiate, lose energy, and spiral into the nucleus within about $10^{-11}$ seconds. Atoms should be unstable. But they aren't.

Two years later, in 1913, a young Danish physicist named Niels Bohr, working in Rutherford's lab in Manchester, proposes a fix. Electrons orbit only in *certain allowed orbits*, and they do not radiate while in those orbits. They radiate only when they jump from one orbit to another — releasing or absorbing a photon whose energy equals the difference between the two orbital energies. The allowed orbits are those for which the angular momentum is an integer multiple of $h/2\pi$.

Bohr's quantization rule was completely arbitrary in 1913. By 1924 — after de Broglie's matter-wave hypothesis and the Davisson-Germer confirmation — it had a beautiful interpretation: the allowed orbits are those for which an integer number of electron de Broglie wavelengths fit around the orbit. Standing waves on a circle. The electron in a stable atom is a standing wave.

This chapter is about how that picture, plus the four quantum numbers and one exclusion rule, explains the entire periodic table and most of chemistry.

**Learning objectives.** By the end of this chapter you should be able to:

1. Describe Rutherford's gold-foil experiment, identify what it ruled out (Thomson's plum-pudding model) and established (the nuclear atom), and apply Bohr's planetary model with quantized angular momentum $L = n h/(2\pi)$.
2. Derive (or apply) the Bohr formula for hydrogen energy levels $E_n = -13.6 \text{ eV}/n^2$ and use the Rydberg formula $1/\lambda = R(1/n_f^2 - 1/n_i^2)$ to compute the wavelengths of hydrogen spectral lines.
3. Identify the four quantum numbers ($n, \ell, m_\ell, m_s$), state the allowed values of each, and apply the Pauli exclusion principle to determine ground-state electron configurations.
4. Use the periodic-table structure (rows = $n$, blocks = $\ell$) to predict the ground-state electron configuration of any element through Z = ~36 (krypton).
5. Explain how characteristic X-rays are produced (inner-shell vacancy plus refilling), apply $E = qV$ for the maximum bremsstrahlung X-ray energy, and connect spectral identification to elemental analysis.

**Prerequisites.** Chapter 24 ($c = f\lambda$). Chapter 27 (interference, standing waves). Chapter 29 (photons, $E = hf$, de Broglie wavelength, Heisenberg uncertainty). Chapter 28 (mass-energy equivalence, used briefly).

**Why this chapter matters.** This is the chapter where quantum mechanics becomes *chemistry*. The periodic table — every property of every element — is a direct consequence of the four quantum numbers and the Pauli exclusion principle. Why oxygen is reactive, why neon is inert, why iron is magnetic, why silicon is a semiconductor — all of it sits here. Without this chapter, chemistry is a list of rules with no underlying logic. With it, chemistry becomes physics.

---

## Concept 1 — From Rutherford to Bohr: the planetary atom and its quantum rescue

### A scintillation screen in Manchester, 1909

Geiger and Marsden are in a darkened laboratory, eyes adjusted, watching a zinc-sulfide-coated glass screen. Each time an alpha particle hits the screen, it produces a tiny flash of light. They count flashes. Most of the alphas appear at the expected angles — small deflections from straight-through. But some appear at angles greater than 90 degrees. Some appear *behind* the gold foil — bouncing back the way they came.

For a year they refine the experiment, rotating the detector to map the angular distribution of scattered alphas. The rate of large-angle scattering is small but non-zero. By 1911 they have enough data for Rutherford to compute, mathematically, what the source of the large deflections must be: a small, dense, positively charged nucleus, with linear dimensions of order $10^{-14}$ to $10^{-15}$ m. The atom is something like the solar system — a tiny dense Sun (the nucleus) surrounded by light orbiting bodies (the electrons) in a vastly larger empty volume.

But classical physics breaks the model immediately. An orbiting electron is accelerating (centripetally). Maxwell's equations say accelerating charges radiate. The electron should radiate away its kinetic energy and spiral into the nucleus in microseconds. Atoms should be unstable. They aren't.

Bohr's 1913 fix is two postulates:

1. Electrons exist only in certain allowed orbits and do not radiate while in those orbits.
2. Radiation is emitted or absorbed only when an electron jumps from one allowed orbit to another, with energy $hf = |E_i - E_f|$.

The allowed orbits, Bohr postulated, are those for which the electron's orbital angular momentum is an integer multiple of $h/2\pi$:

$$L = m_e v r = n \frac{h}{2\pi} \quad (n = 1, 2, 3, \ldots).$$

This was a bold guess in 1913. In 1924, de Broglie gave it physical meaning.

### The mechanism — Bohr's hydrogen atom and the Rydberg formula

Combine three pieces of physics for hydrogen:

**(a) Coulomb attraction provides centripetal force.**

$$\frac{k e^2}{r^2} = \frac{m_e v^2}{r},$$

where $k = 8.988 \times 10^9 \text{ N} \cdot \text{m}^2/\text{C}^2$ is Coulomb's constant.

**(b) Bohr's quantization condition.** $m_e v r_n = n h/(2\pi)$.

**(c) Total energy.** $E_n = KE + PE = \tfrac{1}{2} m_e v^2 - k e^2 / r_n$.

Working through the algebra (eliminating $v$ between equations a and b, then substituting into c) gives:

$$\boxed{r_n = n^2 a_0, \quad a_0 = \frac{h^2}{4\pi^2 m_e k e^2} = 5.29 \times 10^{-11} \text{ m},}$$

where $a_0$ is the *Bohr radius* — the radius of the ground-state orbit. And:

$$\boxed{E_n = -\frac{13.6 \text{ eV}}{n^2}.}$$

The ground state ($n = 1$) has energy $-13.6 \text{ eV}$ — the *ionization energy* of hydrogen. Higher energy levels are at $-3.4 \text{ eV}$ ($n=2$), $-1.51 \text{ eV}$ ($n=3$), and so on, asymptoting to 0 (an unbound electron).

### The Rydberg formula

When an electron jumps from level $n_i$ to lower level $n_f$, it emits a photon of energy

$$hf = E_i - E_f = -\frac{13.6}{n_i^2} - \left( -\frac{13.6}{n_f^2} \right) = 13.6 \left( \frac{1}{n_f^2} - \frac{1}{n_i^2} \right) \text{ eV}.$$

In terms of wavelength ($f = c/\lambda$):

$$\boxed{\frac{1}{\lambda} = R \left( \frac{1}{n_f^2} - \frac{1}{n_i^2} \right),}$$

where $R = 1.097 \times 10^7 \text{ m}^{-1}$ is the *Rydberg constant*. This is the formula Johann Balmer found empirically in 1885 (for $n_f = 2$, what's now called the Balmer series — visible spectral lines), and that Lyman ($n_f = 1$, UV), Paschen ($n_f = 3$, IR), Brackett ($n_f = 4$, IR), and Pfund ($n_f = 5$, IR) extended in the early 20th century.

Bohr's model derives the Rydberg constant from first principles:

$$R = \frac{m_e k^2 e^4}{4\pi h^3 c} = 1.097 \times 10^7 \text{ m}^{-1}.$$

Plug in fundamental constants and you get the experimentally measured value to four significant figures. This was the triumph of Bohr's 1913 paper — derivation of an empirical formula that had defied explanation for nearly thirty years.

### The wave interpretation

In 1924, de Broglie's matter-wave hypothesis (Chapter 29) gave Bohr's quantization rule a beautiful interpretation. The condition $L = nh/(2\pi)$ is equivalent to:

$$2\pi r_n = n \lambda,$$

where $\lambda = h/p = h/(m_e v)$ is the electron's de Broglie wavelength. The allowed orbits are those for which an integer number of electron wavelengths fit around the orbit's circumference. The electron is a standing wave on a circle. Anything else interferes destructively with itself and is not allowed.

### The trade-off

Bohr's planetary model trades **conceptual simplicity for accuracy beyond hydrogen.** The model is exact (with relativistic and spin corrections) for hydrogen and other one-electron systems (He+, Li2+, etc.), where the picture of one electron orbiting one nucleus applies cleanly. For multi-electron atoms, the planetary picture breaks down — electrons interact with each other, and the proper quantum-mechanical treatment requires solving the multi-electron Schrödinger equation. The orbitals you learn in chemistry (s, p, d, f shapes) are not Bohr orbits but full quantum-mechanical solutions. Bohr's model is the simpler, schematic ladder; the full theory is Schrödinger's wave equation.

### Worked example — the Balmer series and the Lyman-α line

**(a) The Balmer-α line of hydrogen ($n_i = 3 \to n_f = 2$).** Apply Rydberg:

$$\frac{1}{\lambda} = R \left( \frac{1}{2^2} - \frac{1}{3^2} \right) = (1.097 \times 10^7)(0.25 - 0.111) = (1.097 \times 10^7)(0.139),$$

$$\frac{1}{\lambda} = 1.524 \times 10^6 \text{ m}^{-1}, \quad \lambda = 656 \text{ nm}.$$

This is the bright red Balmer-α line — the most famous line in stellar spectroscopy, the characteristic red glow of any plasma containing hydrogen, from a hydrogen-discharge lamp in your physics lab to the corona of the Sun.

**(b) Lyman-α ($n_i = 2 \to n_f = 1$).**

$$\frac{1}{\lambda} = R \left( 1 - \frac{1}{4} \right) = (1.097 \times 10^7)(0.75) = 8.23 \times 10^6 \text{ m}^{-1},$$

$$\lambda = 122 \text{ nm}.$$

In the far UV. We met this in Chapter 29 — it's the same number.

**Sanity check.** The Lyman series (UV) corresponds to transitions ending on $n_f = 1$ (the deepest energy well). The Balmer series (visible) corresponds to $n_f = 2$. Each subsequent series ends in IR. The pattern matches measured atomic spectra to many decimal places. Bohr's model — for hydrogen — is exact.

### Common misconceptions

- *"Electrons orbit the nucleus like planets orbit the Sun."* The picture is useful (Bohr's whole insight) but partially wrong. Electrons in atoms are described by wavefunctions (Chapter 29) — probability clouds, not classical orbits. Bohr's circular orbits are a schematic.
- *"Bohr's model is wrong; quantum mechanics replaced it."* Bohr's model is *limited*. It is exact for one-electron atoms (hydrogen, He+, Li2+, etc.) and gives the correct hydrogen spectrum. For multi-electron atoms, you need full quantum mechanics. Bohr's planetary picture remains the easiest pedagogical entry into atomic structure.

↳ **Dig Deeper — Why electrons don't fall into the nucleus**

*The chapter notes that classical electromagnetism predicts orbiting electrons should radiate and spiral in. Quantum mechanics forbids this — but why exactly? The answer involves the Heisenberg uncertainty principle (Chapter 29) and the kinetic-energy cost of localizing the electron near the nucleus.*

**Prompt:**
> Explain why quantum mechanics forbids the electron from collapsing into the proton in a hydrogen atom. Use the uncertainty principle: if the electron were squeezed to within $\Delta x$ of the nucleus, its momentum uncertainty would be at least $\hbar/(2\Delta x)$, giving kinetic energy at least $\hbar^2/(8 m_e \Delta x^2)$. Show that as $\Delta x \to 0$, this kinetic energy grows faster than the potential energy ($-ke^2/\Delta x$) becomes negative — meaning collapse would *cost* energy, not release it. The equilibrium position (minimum total energy) is the Bohr radius. End with one sentence on why this same argument applies to every bound atomic system.

**What to do with the output:** Save it. The "atom doesn't collapse because of uncertainty" argument is one of the cleanest physical arguments in introductory quantum mechanics, and a beautiful application of Heisenberg's principle.

---

## Concept 2 — Quantum numbers and the Pauli principle

### Wolfgang Pauli, Hamburg, 1924

Wolfgang Pauli, age twenty-four, working at the University of Hamburg, is wrestling with the periodic table. The rough pattern is clear: shells fill in order, lower-energy first. But why do shells *close* at the numbers they do — 2, 8, 18, 32 electrons per shell? Why does the second period have 8 elements rather than 4, or 16? Why does carbon have 4 valence electrons and oxygen 6, with chemistry that follows from those numbers?

In 1925, Pauli proposes a single rule that explains all of it:

*No two electrons in an atom can simultaneously occupy the same quantum state.*

This is the *Pauli exclusion principle*. Combined with the four quantum numbers that label every quantum state ($n$, $\ell$, $m_\ell$, $m_s$), it predicts the entire structure of the periodic table.

In 1925, the same year as Pauli's principle, two graduate students named George Uhlenbeck and Samuel Goudsmit propose the existence of a fourth quantum number — *spin* — to explain certain anomalies in atomic spectra. Spin is a kind of intrinsic angular momentum that has no classical analogue; an electron's spin can be either "up" ($m_s = +1/2$) or "down" ($m_s = -1/2$) along any chosen axis. With spin included, each spatial orbital can hold *two* electrons (one spin-up, one spin-down) and the periodic table's shell-closing numbers (2, 8, 18, 32) are explained by counting allowed quantum states.

### The mechanism — four quantum numbers

Every electron in an atom is described by four quantum numbers:

**1. Principal quantum number $n$.** Sets the energy and approximate distance from the nucleus. Allowed values: $n = 1, 2, 3, \ldots$. Larger $n$ = farther from nucleus = higher (less negative) energy. For hydrogen, the energy depends only on $n$: $E_n = -13.6 \text{ eV}/n^2$.

**2. Angular momentum quantum number $\ell$.** Sets the magnitude of orbital angular momentum: $L = \sqrt{\ell(\ell+1)} \, h/(2\pi)$. Allowed values: $\ell = 0, 1, 2, \ldots, n-1$. Names: $\ell = 0$ (s), $\ell = 1$ (p), $\ell = 2$ (d), $\ell = 3$ (f). For $n = 1$, only $\ell = 0$ (1s); for $n = 2$, $\ell = 0$ or $1$ (2s, 2p); for $n = 3$, $\ell = 0, 1, 2$ (3s, 3p, 3d); etc.

**3. Magnetic quantum number $m_\ell$.** Sets the $z$-component of orbital angular momentum: $L_z = m_\ell \cdot h/(2\pi)$. Allowed values: $m_\ell = -\ell, -\ell+1, \ldots, +\ell$ — that is, $2\ell + 1$ values. For an s orbital ($\ell = 0$), $m_\ell = 0$ (1 orbital). For p ($\ell = 1$), $m_\ell = -1, 0, +1$ (3 orbitals). For d ($\ell = 2$), $m_\ell = -2, -1, 0, +1, +2$ (5 orbitals). For f ($\ell = 3$), 7 orbitals.

**4. Spin quantum number $m_s$.** Allowed values: $m_s = +1/2$ or $-1/2$ (spin up or spin down).

### The Pauli exclusion principle and shell capacities

No two electrons in an atom share all four quantum numbers. Each spatial orbital ($n, \ell, m_\ell$) can hold up to *two* electrons — one with $m_s = +1/2$, one with $m_s = -1/2$.

Counting: in shell $n$, the number of distinct ($\ell, m_\ell$) combinations is $\sum_{\ell=0}^{n-1}(2\ell + 1) = n^2$. So shell $n$ can hold $2n^2$ electrons. That gives 2, 8, 18, 32 — the magic numbers of the periodic table.

### Building the periodic table

Electrons fill orbitals in order of increasing energy (ignoring fine structure for now), starting from the lowest. The order is approximately:

$$1s < 2s < 2p < 3s < 3p < 4s < 3d < 4p < 5s < 4d < 5p < 6s < 4f < 5d < 6p < \ldots$$

(The 4s comes before 3d because of detailed energy-shielding effects; this is why transition metals begin with scandium at $Z = 21$ rather than at $Z = 19$.)

Reading the periodic table: rows correspond roughly to shell number $n$; blocks correspond to which subshell is being filled. The s-block (groups 1-2) fills $\ell = 0$ subshells. The p-block (groups 13-18) fills $\ell = 1$. The d-block (transition metals) fills $\ell = 2$. The f-block (lanthanides and actinides) fills $\ell = 3$.

Every chemical property of an element — its atomic radius, ionization energy, electron affinity, valence, magnetic behavior, color of its ions in solution — derives from its electron configuration. Hydrogen reacts with everything because its 1s electron wants to pair up. Helium is inert because its 1s shell is full. Sodium is reactive because it has one lonely 3s electron. Argon is inert because its 3p subshell is full. The periodic table's entire structure is the Pauli principle plus four quantum numbers.

### The trade-off

Quantum-number labeling trades **classical-orbit intuition for predictive power across the periodic table.** The cost: four numbers per electron, careful bookkeeping to apply the exclusion principle, and the abandonment of the classical "electron at this point" picture in favor of probability distributions. The benefit: the entire periodic table — chemistry, materials science, biology — becomes predictable from a small set of rules.

### Worked example — the electron configuration of carbon (Z = 6)

Carbon has 6 electrons. Filling orbitals in order:

- $1s^2$: 2 electrons (filling shell n = 1).
- $2s^2$: 2 more electrons (filling 2s subshell).
- $2p^2$: remaining 2 electrons go into 2p subshell.

Configuration: $1s^2 \, 2s^2 \, 2p^2$.

Of the 2p electrons: the 2p subshell has three orbitals ($m_\ell = -1, 0, +1$). By Hund's rule (a refinement that says electrons prefer to occupy separate orbitals and have parallel spins when possible — a consequence of Pauli exclusion plus electron-electron repulsion), carbon's two 2p electrons go into two different 2p orbitals with parallel spins.

Carbon's outermost shell (n = 2) has 4 electrons total ($2s^2 \, 2p^2$). It can form four bonds — the entire basis of organic chemistry. The valence-4 nature of carbon is direct consequence of the four quantum numbers and Pauli exclusion.

**Sanity check.** Silicon (Z = 14, configuration $1s^2 \, 2s^2 \, 2p^6 \, 3s^2 \, 3p^2$) has the same outer-shell structure as carbon ($s^2 p^2$), and indeed silicon also forms four bonds and has a similar (though not identical) chemistry. This is why silicon makes semiconductors and silicates.

### Common misconceptions

- *"Electrons orbit in shells like nested spheres."* Bohr's circular orbits were a useful schematic. The actual electron distribution in a multi-electron atom is described by the orbital wavefunctions — s orbitals are spherical, p orbitals are dumbbell-shaped, d orbitals have more complex shapes. "Shell" is more of an energy label than a spatial structure.
- *"Pauli exclusion is a special property of electrons."* It's a property of all *fermions* — particles with half-integer spin. Protons, neutrons, and quarks are also fermions and obey Pauli exclusion. This is what makes neutron stars stable against gravitational collapse to black holes (up to a mass limit).

↳ **Dig Deeper — Hund's rule and ferromagnetism**

*The chapter mentions Hund's rule — that electrons in a partially-filled subshell prefer parallel spins. This rule, plus exchange interactions, is the microscopic reason iron, cobalt, and nickel are ferromagnetic. The unpaired electron spins in 3d subshells of these atoms align spontaneously below the Curie temperature.*

**Prompt:**
> Explain how the Pauli exclusion principle plus Hund's rule lead to ferromagnetism in iron, cobalt, and nickel. (a) Show that Fe (Z = 26, $\ldots 3d^6 4s^2$) has 4 unpaired 3d electrons in its ground state by Hund's rule. (b) Explain (briefly) why the spins of these electrons can align cooperatively across many atoms below the Curie temperature ($T_C = 1043 \text{ K}$ for iron), via the exchange interaction. (c) Connect this to the macroscopic magnetic field of a permanent magnet and to the operation of a hard-disk drive read head. End with one sentence on why elements just before iron (chromium, manganese) and just after (cobalt, nickel) also have related magnetic properties but with different transition temperatures.

**What to do with the output:** Save it. Ferromagnetism is a beautiful illustration of how microscopic quantum rules (Pauli, Hund) produce macroscopic magnetic behavior — the basis of electric motors, transformers, magnetic data storage, and MRI machines.

---

## Concept 3 — Atomic spectra: characteristic X-rays and identification

### Henry Moseley, Oxford, 1913–1914

Henry Moseley, age twenty-six, English physicist working at Oxford, has been systematically firing electrons at metal targets and measuring the X-ray frequencies emitted. He notices a pattern: the square root of the X-ray frequency is linear in the atomic number $Z$ of the target element — independent of which element it is, as long as you order them correctly.

This discovery — *Moseley's law* — let him reorder the periodic table by atomic number rather than by atomic mass, fixing several inconsistencies (e.g., cobalt and nickel had been swapped because Co has the larger mass but smaller $Z$). It also predicted gaps in the periodic table that hadn't yet been filled, and gave an experimental method for identifying any element from its characteristic X-ray spectrum — a technique still routinely used today in X-ray fluorescence (XRF) spectroscopy for forensic analysis, art authentication, and environmental monitoring.

Moseley enlisted in 1914 and was killed at Gallipoli in 1915, age twenty-seven. The Nobel committee was widely expected to recognize his work in 1916; that year, no Physics or Chemistry Nobel was awarded.

### The mechanism — bremsstrahlung and characteristic X-rays

Inside an X-ray tube, electrons are accelerated through a high voltage $V$ (typically tens of kV) and slammed into a metal target (the *anode*, often tungsten or molybdenum). Two distinct processes generate X-rays.

**Bremsstrahlung** (German: "braking radiation"). When an energetic electron decelerates in the strong electric field near a target nucleus, it radiates EM energy in a continuous spectrum. The maximum X-ray photon energy occurs when the electron loses *all* its kinetic energy in a single emission:

$$E_{\max} = qV = h f_{\max}.$$

A 100-kV X-ray tube produces bremsstrahlung up to 100 keV photon energy — corresponding to wavelengths down to about 12.4 pm. The intensity is a smooth distribution from low energies up to the cutoff.

**Characteristic X-rays.** When an incoming electron knocks out an inner-shell electron (say, a 1s electron), the resulting vacancy is filled by an electron from a higher shell ($n = 2$ or higher), which emits a photon equal to the energy difference. Because inner-shell energy levels depend strongly on the nuclear charge $Z$ — they scale roughly as $-13.6 \, Z_{\text{eff}}^2 / n^2$ eV — these "characteristic" X-rays have energies that are signature of the element.

The specific lines have names: $K_\alpha$ (an n=2 → n=1 transition), $K_\beta$ (n=3 → n=1), $L_\alpha$ (n=3 → n=2), and so on. The K-series are the highest-energy and most energetically distinct.

### Moseley's law

Moseley found that the frequency of $K_\alpha$ (for a target of atomic number $Z$) follows

$$\sqrt{f} = \text{const} \times (Z - 1),$$

where the $-1$ comes from approximate screening of the nuclear charge by the second 1s electron. This square-root-frequency-vs-$Z$ relation made it possible to order the periodic table by $Z$ rather than by atomic mass and to predict undiscovered elements.

### Worked example — characteristic X-ray from tungsten

A tungsten anode ($Z = 74$) has $K_\alpha$ characteristic X-rays from $n = 2 \to n = 1$ transitions. Estimate the photon energy.

Approximate the $K_\alpha$ energy by treating the inner electron as if in a hydrogen-like atom with effective nuclear charge $Z_{\text{eff}} = Z - 1 = 73$ (one $1s$ electron screens the nuclear charge slightly):

$$E_{K_\alpha} \approx 13.6 \text{ eV} \times Z_{\text{eff}}^2 \times \left( \frac{1}{1^2} - \frac{1}{2^2} \right) = 13.6 \times 73^2 \times 0.75 \approx 5.4 \times 10^4 \text{ eV} = 54 \text{ keV}.$$

The measured $K_\alpha$ energy of tungsten is $59 \text{ keV}$, in good agreement (the approximation is order-of-magnitude). This X-ray penetrates several centimeters of tissue and is the standard energy for medical chest X-rays.

**Sanity check.** Compare to the corresponding hydrogen Lyman-α at 10.2 eV. Tungsten's characteristic X-ray is about $5000 \times$ more energetic. The factor $(Z_{\text{eff}})^2 \approx 5000$ is the same scaling.

### The trade-off

X-ray production trades **electron energy (and substantial heat) for short-wavelength EM radiation.** A typical X-ray tube converts only ~1% of input electrical energy to X-rays; the rest becomes heat in the anode (which is why anodes are water-cooled and rotated). The benefit: short-wavelength radiation able to image inside dense materials (medical imaging, airport security, materials analysis).

### Common misconceptions

- *"All X-rays are the same."* Bremsstrahlung is a continuous spectrum; characteristic X-rays are sharp lines specific to the anode material. The total spectrum from an X-ray tube is the sum of both.
- *"Higher voltage = more X-rays."* Higher voltage produces *higher-energy* X-rays (with shorter wavelength, hence more penetrating). The total *intensity* depends on tube current. In medical imaging, both must be controlled — voltage for penetration and contrast, current for total dose.

↳ **Dig Deeper — X-ray crystallography and the structure of DNA**

*The chapter mentions X-ray diffraction in passing. The technique — using X-ray photons of wavelength comparable to interatomic spacing to diffract off crystal lattices — was the key to determining the structure of DNA in 1953. Rosalind Franklin's "Photo 51" and the underlying physics are a beautiful chapter in 20th-century science.*

**Prompt:**
> Explain the physics of X-ray crystallography and how it was used to determine the double-helix structure of DNA. (a) Describe Bragg's law $n\lambda = 2d \sin\theta$ for diffraction from crystal planes spaced $d$ apart. (b) Explain why X-rays (wavelength ~0.1 nm) are needed for atomic-resolution structures, while visible light is useless. (c) Describe Rosalind Franklin's "Photo 51" (1952) — the X-ray diffraction pattern showing the helical signature of DNA. (d) Briefly explain how Watson and Crick used Franklin's pattern (and Maurice Wilkins's contributions) to deduce the double-helix structure. End with one sentence on why X-ray crystallography remains the dominant technique for determining protein structures today.

**What to do with the output:** Save it. X-ray crystallography is the most consequential application of atomic-physics-derived radiation in 20th century biology, and the politics around the 1953 DNA-structure discovery are themselves a historical lesson.

---

## Synthesis — quantum mechanics meets the periodic table

Step back. Three concepts braid together:

**Concept 1** introduced the nuclear atom (Rutherford 1911) and Bohr's planetary model (1913) with quantized orbits. The standing-wave interpretation (de Broglie, 1924) gave Bohr's quantization condition physical meaning. The Rydberg formula derived from Bohr's model exactly reproduces the hydrogen spectrum.

**Concept 2** extended quantum mechanics to multi-electron atoms via four quantum numbers ($n, \ell, m_\ell, m_s$) and the Pauli exclusion principle. Together, these predict the structure of the periodic table — every shell-closing number, every block of elements, every chemistry.

**Concept 3** examined atomic spectra in the X-ray regime — bremsstrahlung from decelerating electrons and characteristic X-rays from inner-shell transitions. Moseley's law lets us identify elements from their X-ray spectra, and X-ray diffraction lets us determine atomic structures.

The deepest single fact: **the entire periodic table is two rules — the four quantum numbers and Pauli exclusion — applied to the simple Coulomb problem of electrons orbiting nuclei.** Hydrogen is computable from first principles. Multi-electron atoms require approximation methods (Hartree-Fock, density functional theory) but the basic framework is the same. The complexity of chemistry — every reaction, every material, every biological molecule — is built on top of this small set of quantum rules.

### A worked example using all three concepts — sodium D-line and the design of street lamps

Sodium (Na, Z = 11) has electron configuration $1s^2 \, 2s^2 \, 2p^6 \, 3s^1$. Its outermost electron is a single 3s electron, well-screened from the nucleus by the inner 10 electrons.

**Concept 1 — Bohr-like analysis.** The 3s electron sees an effective nuclear charge $Z_{\text{eff}} \approx 1$ (rough). Treating it as a hydrogen-like electron in $n = 3$ gives an energy of roughly $-13.6/9 \approx -1.5 \text{ eV}$. The actual sodium ionization energy is $5.14 \text{ eV}$ — substantially larger because the screening is imperfect (the 3s electron penetrates the inner shells somewhat) and the angular structure of the orbital matters.

**Concept 2 — quantum-number structure.** The $3s \to 3p$ transition is allowed (selection rule $\Delta\ell = \pm 1$), and 3p is split by spin-orbit coupling into two close levels ($j = 3/2$ and $j = 1/2$). The two corresponding emission lines — sodium D2 (at 589.0 nm) and sodium D1 (at 589.6 nm) — are extremely close together and look like a single yellow-orange line to the naked eye.

**Concept 3 — characteristic spectrum.** The sodium D-line is the fingerprint of sodium. Heat sodium vapor in a discharge tube and you get a brilliant yellow glow at 589 nm. The same wavelength colors low-pressure sodium street lamps (which operate by exciting sodium vapor in a discharge), which were widely used for street illumination from the 1930s through the 2010s before being replaced by LED lamps. Their nearly monochromatic yellow output — almost all of it from the sodium D doublet — is why they wash out colors of objects illuminated by them.

**Scale shift.** That same principle — atoms emit characteristic spectral lines — lets astronomers identify the chemical composition of stars billions of light-years away. The 589-nm sodium D-line absorption pattern in the Sun's spectrum (one of the original Fraunhofer lines, identified in 1814) tells us the Sun contains sodium. The same lines in distant stars confirm they too contain sodium. Spectroscopy is how we know what stars and galaxies are made of.

---

## Exercises

### Warm-up

**30.1** *(LO 1)* In Rutherford's gold-foil experiment, alpha particles were observed to bounce back from the foil at large angles. What did this rule out and what did it establish about atomic structure?

**30.2** *(LO 2)* Compute the wavelength of the Balmer-β line of hydrogen ($n_i = 4, n_f = 2$).

**30.3** *(LO 3)* List the four quantum numbers, their allowed values, and the meaning of each.

**30.4** *(LO 3)* Apply the Pauli exclusion principle to determine the maximum number of electrons in (a) the n = 1 shell, (b) the n = 3 shell, (c) the 3p subshell.

### Application

**30.5** *(LO 2)* The ionization energy of hydrogen is 13.6 eV. (a) Compute the wavelength of a photon that just barely ionizes a ground-state hydrogen atom. (b) In which region of the EM spectrum does this lie?

**30.6** *(LO 4)* Write the ground-state electron configurations for (a) nitrogen (Z = 7), (b) silicon (Z = 14), (c) iron (Z = 26).

**30.7** *(LO 4)* Why are noble gases (He, Ne, Ar, Kr, Xe) chemically inert? Explain in terms of their electron configurations.

**30.8** *(LO 5)* An X-ray tube operates at 80 kV. Find (a) the maximum X-ray photon energy, (b) the corresponding minimum wavelength.

### Synthesis

**30.9** *(LO 2, LO 5)* The Sun's spectrum shows strong absorption at the wavelengths of the Balmer-α (656 nm), Balmer-β (486 nm), and Balmer-γ (434 nm) lines of hydrogen. (a) Verify these wavelengths using the Rydberg formula. (b) What does the presence of these absorption lines tell us about the Sun's composition?

**30.10** *(LO 3, LO 4)* Use the Pauli exclusion principle to explain why the second period of the periodic table has 8 elements (Li through Ne), the third period also has 8, but the fourth has 18.

**30.11** *(LO 5)* A sample of unknown composition emits characteristic X-rays at $E_{K_\alpha} \approx 8.0 \text{ keV}$. Use Moseley's-law approximation $E_{K_\alpha} \approx 13.6 \, (Z-1)^2 \times 0.75 \text{ eV}$ to estimate the atomic number. What element is this likely to be? (Hint: it's a common metal with $Z$ in the high 20s.)

### Challenge

**30.12** *(beyond chapter)* The Bohr radius can be derived from three constants: $h$, $m_e$, $k$, and $e$. Show that the combination $h^2 / (m_e k e^2)$ has units of length, and estimate the order of magnitude using the constants you know. Then refine to get the exact Bohr radius $a_0 = h^2/(4\pi^2 m_e k e^2) = 5.29 \times 10^{-11} \text{ m}$.

**30.13** *(beyond chapter)* The principle that explains the periodic table — Pauli exclusion — applies to all fermions, including protons and neutrons in nuclei. (a) How many neutrons can occupy the ground-state shell of a nucleus, accounting for spin? (b) Why does this lead to "magic numbers" in nuclear physics, analogous to noble gases in atomic physics? (Forward link to Chapter 31.)

---

## LLM Exercise — Chapter 30: Atomic Physics in Your Anchor Phenomenon

**Project:** Physics Reality Check Logbook
**What you're building this chapter:** A Logbook entry connecting atomic physics — spectral lines, X-rays, electron configurations — to your anchor phenomenon. Most everyday phenomena involve specific elements with specific spectra. The connection is usually accessible.
**Tool:** Claude Project.

### The Prompt

```
I'm continuing my Physics Reality Check Logbook for College Physics with LLMs. My anchor phenomenon is [paste your 1-sentence description].

For Chapter 30, I want to apply atomic physics — Bohr's model, quantum numbers, the periodic table, characteristic spectra — to my phenomenon.

Please:

1. Identify ONE atomic-physics aspect of my phenomenon. Examples: for a bike commute — sodium street lamps emitting at 589 nm, LED traffic signals (semiconductor band gaps which derive from atomic structure), the iron in my bike's steel (3d subshell, ferromagnetic). For a coffee maker — spectroscopic identification of caffeine (C, H, N, O atoms), the sodium D-line in the dye of any colored cup, mineral content of water (calcium, sodium, etc.). For a basketball shot — the elements in human muscle (carbon-based chemistry), gym lighting (mercury vapor in fluorescent bulbs at 254 nm; LEDs based on band-gap engineering). For a marathon — caffeine in pre-race coffee, sodium and potassium in electrolyte drinks.

2. Apply ONE atomic-physics calculation. Compute a transition wavelength using the Rydberg formula, predict a spectral line, estimate ionization energy of a key element, identify the electron configuration of a specific atom.

3. Specify input numbers and uncertainty.

4. Run the calculation. Report value with units.

5. One sanity check: does the wavelength match a known spectral line of the right element?

6. One sentence connecting this to Chapter 31 (radioactivity) — moving from atomic to nuclear physics.

Save the output as logbook/chapter-30-atomic.md.
```

### What this produces

A Logbook entry connecting your phenomenon to specific atomic structure or spectroscopy.

### How to adapt this prompt

- *For a phenomenon involving any color:* Color is atomic physics. Identify the atom or molecule responsible.
- *For ChatGPT/Gemini:* Identical with interface substitutions.
- *For Claude Code:* If you have access to a smartphone spectroscope or a recorded spectrum, you can extract the dominant emission lines and identify them by element.

### Connection to previous chapters

Builds directly on Chapter 29 (photons, de Broglie, uncertainty). Uses Chapter 27 (interference for X-ray diffraction) and Chapter 24 ($c = f\lambda$).

### Preview of next chapter

Chapter 31 (radioactivity and nuclear physics) moves from electrons to nuclei. Many of the same principles (quantization, exclusion, characteristic spectra) apply, but at the nuclear scale and at much higher energies (MeV instead of eV).

---

## Chapter summary

The atom is a tiny dense nucleus surrounded by a much larger cloud of electrons in quantized orbits (Rutherford 1911 + Bohr 1913). Hydrogen is exactly solvable: $E_n = -13.6 \text{ eV}/n^2$, with electron transitions producing the Lyman, Balmer, Paschen, and other spectral series. De Broglie's matter-wave hypothesis (1924) gave Bohr's quantization condition the interpretation of standing waves on a circle. Multi-electron atoms require four quantum numbers ($n, \ell, m_\ell, m_s$) and the Pauli exclusion principle (Pauli 1925), which together predict the entire structure of the periodic table. Characteristic X-ray spectra (Moseley 1913) provide a fingerprint for any element and allow elemental identification.

The one idea that matters most: **the periodic table is the Pauli exclusion principle applied to electrons in atoms.** Shell capacities of $2n^2$, the existence of noble gases, the chemistry of every element, the magnetic properties of iron — all are direct consequences.

The common mistake to watch for: **treating Bohr's circular orbits as the actual electron paths.** They are a useful schematic. The actual electron distribution is described by orbital wavefunctions, with shapes (s spherical, p dumbbell, d more complex) that determine chemistry.

What you should now be able to teach someone else: why hydrogen's spectrum has the specific wavelengths it does (Bohr + Rydberg), why the periodic table closes at the numbers 2, 8, 18, 32 (Pauli + four quantum numbers), and how characteristic X-rays let you identify any element. If you can also explain why noble gases are inert and alkali metals are reactive in terms of electron configurations, you've understood this chapter.

---

## What would change my mind

The chapter argues that atomic structure — and hence the periodic table — is a direct consequence of quantum mechanics and the Pauli exclusion principle. The argument would need revision if a precision spectroscopy experiment found atomic energy levels significantly different from quantum-mechanical predictions, or if a chemistry experiment identified an element whose electron configuration violated the standard pattern. Neither has happened in over a century of detailed measurements.

## Still puzzling

The deepest unresolved question this chapter touches but does not answer: **why do exactly three families of fermions exist (electron, muon, tau and their corresponding neutrinos), and why are their masses what they are?** Atomic physics works perfectly with one electron per "row" of the periodic table, but the existence of muons (which can replace electrons to form muonic atoms with vastly smaller radii) and tau particles is unexplained. The mass hierarchy of these three "generations" is one of the most prominent puzzles in particle physics. Chapter 33 returns to this.

---

## Connections forward

Chapter 31 (radioactivity and nuclear physics) extends quantum mechanics to nuclei — protons and neutrons bound by the strong force, with their own version of shell structure and "magic numbers." Chapter 32 (medical applications of nuclear physics) uses the principles of this chapter and the next for medical imaging (X-rays, CT, MRI, PET) and radiation therapy. Chapter 33 (particle physics) decomposes nucleons into quarks and explores the standard model of fundamental interactions. Chapter 34 (frontiers) returns to open questions — why three generations, what determines the periodic-table-like patterns we see at the subatomic level, and what physics still doesn't explain.

---

**Tags:** atomic-physics, Bohr-model, periodic-table, Pauli-exclusion, quantum-numbers

---

## AI Wayback Machine

**Lise Meitner** identified nuclear fission in 1938 — interpreting Otto Hahn's puzzling experimental results during her exile in Sweden. Hahn alone received the Nobel; Meitner's exclusion is one of the most-cited omissions in Nobel history.

**Run this:**

```
Who was Lise Meitner, and how does her work on nuclear fission connect to atomic physics we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about her career or ideas.
```

→ Search **"Lise Meitner"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to walk through Meitner's 1938 calculation of the energy released in uranium fission.
- Ask it about Meitner's refusal to work on the Manhattan Project and what it meant for her career.

What changes? What gets better? What gets worse?
