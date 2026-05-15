# Chapter 10 — Quantum Physics

**Suggested titles**

1. Quantum Physics
2. Photons, Electrons, and the End of Smooth Reality
3. Why Light Comes in Lumps and Matter Is Also a Wave

**TL;DR.** Classical physics describes light as a continuous wave (Chapter 27) and matter as discrete particles (Chapters 2–8). Both pictures are partially wrong. Light comes in discrete packets called photons with energy $E = hf$; this is what made the photoelectric effect explainable in 1905 and what made blackbody radiation calculable in 1900. Matter has wave properties with de Broglie wavelength $\lambda = h/p$; this was confirmed by electron diffraction in 1927. Heisenberg's uncertainty principle places a fundamental floor on simultaneous measurement of position and momentum: $\Delta x \, \Delta p \geq h/4\pi$. The world at small scales is not classical, and the corrections are not small.

---

## Bell Labs, 1927: electrons in a crystal

Clinton Davisson and Lester Germer have been bombarding a nickel crystal with electrons in a vacuum chamber at Bell Telephone Laboratories in New Jersey. They have been at this since 1923. The original goal was to study the surface of nickel for telephone-relay applications. An accidental laboratory mishap — air leaks into the vacuum chamber, oxidizing the nickel sample — forces them to anneal the sample to remove the oxide. The annealing recrystallizes the previously polycrystalline nickel into a small number of large crystal regions. They resume the experiment.

The pattern they detect is no longer the diffuse scatter expected from polycrystalline metal. It is a sharp, peaked angular pattern — the unmistakable signature of *diffraction*. Electrons, the supposedly indivisible particles of matter, are interfering with themselves on a nickel crystal as if they were a wave whose wavelength is set by something they cannot yet name.

Across the Atlantic, in 1923, a French graduate student named Louis de Broglie had submitted a doctoral thesis arguing that *all matter has wave properties*, with a wavelength given by

$$\lambda = \frac{h}{p}.$$

The thesis was so radical that the examining committee was unsure whether to accept it. Einstein, asked to weigh in, told them de Broglie's idea was "of fundamental importance." They awarded the doctorate. Davisson and Germer's electrons, in 1927, scattered off the nickel crystal with exactly the wavelengths de Broglie's formula predicted. The 1929 Nobel Prize went to de Broglie. The 1937 Nobel went to Davisson and (independently) G. P. Thomson, son of the man who had discovered the electron three decades earlier and called it a particle.

By the late 1920s, classical physics was in pieces. Light was both a wave (Young's two-slit experiment, Chapter 27) and a particle (Einstein's 1905 photoelectric paper). Matter was both a particle (every chemical experiment for two centuries) and a wave (Davisson-Germer 1927). The new quantum mechanics, developed primarily by Heisenberg, Schrödinger, Born, Dirac, and Pauli between 1925 and 1928, accommodated both descriptions and replaced them with a single mathematical framework — *the wavefunction* — whose squared magnitude gives the *probability* of finding a particle in any region.

This chapter is about the experimental and conceptual core of that revolution. Three concepts: the quantization of energy and the photon (1900-1905), the wave nature of matter and the de Broglie wavelength (1924-1927), and the Heisenberg uncertainty principle (1927). The world is not classical at small scales. The corrections are not small.

**Learning objectives.** By the end of this chapter you should be able to:

1. Explain why blackbody radiation and the photoelectric effect cannot be accounted for by classical wave optics, and use $E = hf$ (the *Planck-Einstein relation*) to compute photon energies.
2. Apply photon energy and momentum relations ($E = hf$, $E = hc/\lambda$, $p = h/\lambda$) to compute photon properties for any frequency or wavelength.
3. Apply the de Broglie relation $\lambda = h/p$ to compute the wavelength of any matter particle (electron, neutron, atom) and explain why the wave nature of matter is invisible for everyday objects.
4. Apply Heisenberg's uncertainty principle ($\Delta x \, \Delta p \geq h/4\pi$ and $\Delta E \, \Delta t \geq h/4\pi$) to estimate fundamental limits on simultaneous measurements.
5. Identify wave-particle duality as a complete description (not a paradox) and use the correspondence principle to verify that quantum predictions reduce to classical ones in the appropriate limit.

**Prerequisites.** Chapter 24 (electromagnetic spectrum, $c = f \lambda$). Chapter 27 (interference, diffraction, the diffraction limit). Chapter 28 (special relativity, $E = pc$ for massless particles). Comfort with $E = hf$ as a relation that pairs frequency to energy.

**Why this chapter matters.** Every modern physical and chemical theory rests on quantum mechanics. The structure of atoms (Chapter 30), the binding of nuclei (Chapter 31), the operation of LEDs and lasers, the behavior of semiconductors that run every computer on Earth, the photosynthesis of every plant — all are quantum-mechanical at their core. Without this chapter, none of the chapters that follow makes sense.

---

## Concept 1 — Photons: light in discrete packets

### Berlin, December 14, 1900

Max Planck stands before the German Physical Society and reports a desperate compromise. For two years he has been wrestling with the problem of *blackbody radiation* — the spectrum of electromagnetic radiation emitted by an idealized hot body. Classical electromagnetism plus classical statistical mechanics had given a prediction that diverged catastrophically at short wavelengths (the "ultraviolet catastrophe") — total energy infinity, plainly wrong. Planck has just discovered that he can derive the *correct* spectrum if he assumes the oscillating atoms in the body can only have *discrete* energies, in steps of size $\Delta E = hf$, where $h$ is a tiny new constant ($h = 6.626 \times 10^{-34} \text{ J} \cdot \text{s}$) and $f$ is the oscillator frequency.

Planck does not believe his own assumption. He calls it a "purely formal" trick, useful for getting the right answer but probably not corresponding to physical reality. He spends years trying to derive the same result without it. He cannot.

In 1905, Albert Einstein takes Planck's quantum hypothesis and does something more radical. He proposes that *electromagnetic radiation itself* is quantized — that light comes not as a continuous wave but as discrete bundles of energy ("photons") with $E = hf$. Einstein's motivation was the *photoelectric effect*: light striking a metal surface ejects electrons, and the *energy* of the ejected electrons depends on the *frequency* of the light, not its intensity. Classical wave physics says intensity should determine energy (more intense light, more energetic ejected electrons). Experiment says no: bright low-frequency light ejects no electrons at all, while dim high-frequency light ejects electrons with substantial energy. The puzzle had been outstanding for two decades.

Einstein's photon explanation: a photon of frequency $f$ carries energy $hf$. When a photon hits a metal, it can transfer all its energy to a single electron. If $hf$ exceeds the energy required to free the electron from the metal (the *work function* $\phi$), the electron is ejected with kinetic energy $KE = hf - \phi$. If $hf < \phi$, no electron is ejected — no matter how intense the light. Increasing intensity increases the *number* of photons, hence the *number* of ejected electrons, but not their individual energy.

Einstein's 1905 paper on the photoelectric effect won him the 1921 Nobel Prize. (His relativity papers from the same year did not — the Nobel committee considered them still too controversial. The photoelectric paper was the safer choice.)

### The mechanism — quantized energy and the photon

**Planck's relation.** A harmonic oscillator at frequency $f$ has energy levels

$$E_n = \left( n + \tfrac{1}{2} \right) hf \quad \text{for } n = 0, 1, 2, \ldots$$

It can absorb or emit energy only in discrete steps of $\Delta E = hf$. The constant $h = 6.626 \times 10^{-34} \text{ J} \cdot \text{s}$ is *Planck's constant*, the numerical value that sets the scale of all quantum effects.

**The photon.** Electromagnetic radiation of frequency $f$ comes in discrete packets, each carrying

$$\boxed{E = hf = \frac{hc}{\lambda}.}$$

A useful unit conversion: $hc = 1240 \text{ eV} \cdot \text{nm}$, so a 500 nm green photon has $E = 1240/500 = 2.48 \text{ eV}$ — the convenient energy scale for atomic and chemical processes.

A photon also carries momentum:

$$\boxed{p = \frac{h}{\lambda} = \frac{E}{c}.}$$

This is consistent with the relativistic energy-momentum relation $E^2 = (pc)^2 + (mc^2)^2$ from Chapter 28: setting $m = 0$ gives $E = pc$, confirming that photons are *massless* and travel at exactly $c$.

**The photoelectric equation.** A photon of energy $hf$ hitting a metal with work function $\phi$ can eject an electron with maximum kinetic energy

$$KE_{\max} = hf - \phi.$$

If $hf < \phi$, no electrons are ejected. The threshold frequency is $f_0 = \phi/h$. Above the threshold, the *number* of ejected electrons grows with light intensity (more photons), but the *energy* of each electron grows only with light frequency (each photon's individual energy).

### The trade-off

The photon picture trades **smooth-wave intuition for discrete-quantum reality.** Classical wave optics, with its continuous energy distribution across the wavefront, was a complete description for many phenomena (interference, diffraction, polarization — all of Chapter 27). It failed only when energy transfers to and from individual atomic-scale objects. The cost: physics has to track discrete photons in addition to (and consistent with) continuous wave behavior. The benefit: every photoelectric measurement, every spectroscopic line, every laser, every solar cell, every LED, every camera CCD works *because* light is quantized. Without photons, none of those devices would behave the way they do.

### Worked example — the photoelectric effect

Light of wavelength $\lambda = 400 \text{ nm}$ (violet) shines on a metal with work function $\phi = 2.20 \text{ eV}$. Find (a) the photon energy, (b) the maximum kinetic energy of ejected electrons, (c) the threshold wavelength below which no photons can eject electrons.

**(a) Photon energy.**

$$E = \frac{hc}{\lambda} = \frac{1240 \text{ eV} \cdot \text{nm}}{400 \text{ nm}} = 3.10 \text{ eV}.$$

**(b) Maximum kinetic energy.**

$$KE_{\max} = hf - \phi = 3.10 - 2.20 = 0.90 \text{ eV}.$$

The fastest ejected electron carries 0.90 eV of kinetic energy — about $1.4 \times 10^{-19} \text{ J}$.

**(c) Threshold wavelength.** The threshold occurs when the photon energy just equals the work function:

$$\lambda_0 = \frac{hc}{\phi} = \frac{1240}{2.20} = 564 \text{ nm}.$$

Light with wavelength longer than $564 \text{ nm}$ (yellow, orange, red, IR) cannot eject any electrons from this metal, no matter how intense. Light shorter than $564 \text{ nm}$ (green, blue, violet, UV) ejects electrons with kinetic energy that grows linearly with frequency.

**Sanity check.** Common photoelectric metals (cesium, sodium, potassium) have work functions of $\sim 2 \text{ eV}$, with threshold wavelengths in the visible. Solar cells operate on similar principles — silicon has a band gap of about 1.1 eV, so photons with $\lambda < 1130 \text{ nm}$ (visible and near-infrared) can liberate electrons in silicon and contribute to the photovoltaic current.

### Common misconceptions

- *"More intense light should always eject electrons faster."* Classical wave physics says yes; experiment says no. Below the threshold frequency, no electrons are ejected at any intensity. This is one of the cleanest failures of classical wave optics.
- *"Photons are little bullets of light."* They have particle properties (discrete energy, momentum, individual interactions) but also wave properties (interference, diffraction). The "particle" picture is useful but incomplete; the full description is the wavefunction.
- *"Planck's constant is just a unit conversion."* No, it sets the *scale* of quantum effects. If $h$ were larger, quantum effects would be visible at macroscopic scales. The smallness of $h$ is why quantum mechanics is hidden from everyday life.

↳ **Dig Deeper — Compton scattering and photon momentum**

*The chapter introduces photon momentum $p = h/\lambda$. Arthur Compton's 1923 experiment scattering X-rays off electrons in a target produced direct experimental evidence: the scattered X-rays had longer wavelength (lower energy) than the incident X-rays, exactly the amount predicted by treating the collision as a relativistic collision between two particles, photon and electron.*

**Prompt:**
> Walk me through the Compton scattering experiment. (a) Set up the kinematics: an X-ray photon with wavelength $\lambda_0$ scatters off an electron at rest, deflecting by angle $\theta$ and emerging with longer wavelength $\lambda$. The Compton formula gives $\Delta\lambda = (h/m_e c)(1 - \cos\theta)$, where $h/m_e c \approx 2.43 \text{ pm}$ is the *Compton wavelength* of the electron. (b) Show that this comes from energy and momentum conservation in a relativistic collision, treating the photon's momentum as $p = h/\lambda$ and energy as $E = hc/\lambda$. (c) Compute the wavelength shift for X-rays scattered at $90°$. End with one sentence on why Compton's experiment was decisive evidence that photons are real particles, not just bookkeeping for wave intensity.

**What to do with the output:** Save it. Compton scattering is the cleanest demonstration in physics that photons carry both energy and momentum like particles, and the calculation is a beautiful application of the relativistic kinematics from Chapter 28.

---

## Concept 2 — Matter waves: de Broglie and the Davisson-Germer experiment

### Davisson and Germer, take two — November 1927

Back to the nickel crystal at Bell Labs. Now we have the framework. In 1924, de Broglie proposed that any particle with momentum $p$ has an associated wavelength $\lambda = h/p$. For an electron accelerated through a potential difference $V$, the kinetic energy is $eV$ (where $e$ is the electron charge), so the momentum is $p = \sqrt{2 m_e e V}$, and the de Broglie wavelength is

$$\lambda = \frac{h}{\sqrt{2 m_e e V}}.$$

For an electron accelerated through 54 V (a typical Davisson-Germer setting), this gives $\lambda \approx 0.167 \text{ nm}$ — comparable to the spacing between atomic planes in a nickel crystal (~0.215 nm for the relevant planes). When such electrons strike the crystal, they should diffract — and the angles of the diffraction maxima should obey Bragg's law $n\lambda = 2d \sin\theta$, the same equation that describes X-ray diffraction off crystals.

Davisson and Germer measured the diffraction angles. They matched de Broglie's prediction. Electrons are waves.

In 1927, G. P. Thomson at the University of Aberdeen did the analogous experiment by passing electrons through a thin gold foil and observing the diffraction rings on a film behind. Same result. Electrons diffract like X-rays.

By the late 1920s, every kind of subatomic particle had been shown to have wave properties: electrons, then atoms, then small molecules. By the 2010s, experimenters had demonstrated double-slit interference for molecules with hundreds of atoms (the Vienna group of Anton Zeilinger demonstrated interference with $C_{60}$ buckminsterfullerene molecules in 1999, and later with molecules of $\sim 800$ atoms). The wave nature of matter is universal.

### The mechanism — the de Broglie wavelength

The de Broglie hypothesis: every material particle of momentum $p$ has wavelength

$$\boxed{\lambda = \frac{h}{p}.}$$

For a slow ($v \ll c$) particle, $p = mv$, so $\lambda = h/(mv)$. For a relativistic particle, use the full relativistic momentum $p = \gamma m v$ from Chapter 28.

Why don't we see matter wave behavior in everyday life? Because $h$ is tiny and macroscopic momenta are huge. A 3-kg bowling ball moving at 10 m/s has momentum 30 kg·m/s and de Broglie wavelength

$$\lambda = \frac{6.63 \times 10^{-34}}{30} \approx 2 \times 10^{-35} \text{ m}.$$

That's $10^{20}$ times smaller than the diameter of a proton. To see wave effects (e.g., diffraction) you'd need an aperture comparable to that wavelength — far smaller than any object known. The bowling ball's wave nature is real but completely undetectable. This is why we get along with classical mechanics for everyday objects.

For an electron at $\sim 100 \text{ eV}$ kinetic energy, $\lambda$ is a fraction of a nanometer — comparable to atomic spacings. Electrons behave wavelike. For a slow neutron at thermal energies (~25 meV), $\lambda$ is a few angstroms — the basis of neutron scattering, a workhorse technique in materials science. At progressively higher energies, $\lambda$ shrinks; at LHC energies, the de Broglie wavelength of a 7 TeV proton is about $10^{-19} \text{ m}$ — the scale at which we probe sub-nucleon structure.

### Wave-particle duality

The recurring fact: every quantum object exhibits both wave and particle properties, depending on what experiment you do. Photons (Concept 1) interfere as waves but transfer energy in discrete particle-like quanta. Electrons (this concept) ricochet off other electrons as particles but diffract through crystals as waves. Atoms can be sent through double slits and produce interference patterns; they can also be detected one-at-a-time as discrete arrivals.

There is no contradiction. There is one description — the *wavefunction* — that has properties of both. The measurement you do determines which set of properties shows up. Trying to ask "is it really a wave or really a particle?" misses the point. It is a quantum object. *Wave* and *particle* are the names for the two classical pictures we are accustomed to; neither is fully accurate, and both are useful in their own regimes.

### The trade-off

The de Broglie picture trades **classical particle intuition for universal wave-particle duality.** The cost: matter is no longer simply "stuff at locations." Matter is also a wave, with a wavelength so tiny for everyday objects that it doesn't matter, but profoundly important at atomic scales. The benefit: a unified description that explains the structure of atoms (Chapter 30), chemical bonding, the conductivity of metals, the operation of every transistor in your phone.

### Worked example — the de Broglie wavelength of an electron

An electron is accelerated through a potential difference of $V = 100 \text{ V}$. Find its de Broglie wavelength. Compare to the wavelength of visible light.

Kinetic energy: $KE = eV = (1.602 \times 10^{-19})(100) = 1.602 \times 10^{-17} \text{ J} = 100 \text{ eV}$.

For nonrelativistic motion ($v \ll c$, valid here since 100 eV is much less than the electron's rest energy of 511 keV):

$$p = \sqrt{2 m_e KE} = \sqrt{2 (9.11 \times 10^{-31})(1.602 \times 10^{-17})} = 5.40 \times 10^{-24} \text{ kg} \cdot \text{m/s}.$$

de Broglie wavelength:

$$\lambda = \frac{h}{p} = \frac{6.63 \times 10^{-34}}{5.40 \times 10^{-24}} = 1.23 \times 10^{-10} \text{ m} = 0.123 \text{ nm}.$$

For comparison, visible light has $\lambda \sim 500 \text{ nm}$ — about $4000$ times longer. This is why electron microscopy (which uses electrons of typically $10$–$300 \text{ keV}$) achieves resolution thousands of times better than the best optical microscope: the electron de Broglie wavelength is much shorter than visible light, so the diffraction limit (Chapter 27) is correspondingly tighter.

**Sanity check.** Modern transmission electron microscopes routinely image individual atoms (~$0.1 \text{ nm}$ spacing), confirming that the operating wavelength matches our prediction.

### Common misconceptions

- *"The wave nature of matter applies only to quantum objects, not real particles."* It applies to *every* particle. The wave is just so short for macroscopic objects that we never see its effects.
- *"An electron going through a double slit splits into two pieces."* No. It is detected at one place on the screen, like a particle. The wavefunction passes through both slits and interferes with itself. Many such electrons, sent one at a time, build up an interference pattern. The "splitting" is in the wavefunction, not the particle.
- *"The wave is a wave of matter density."* No. It's a wave of *probability amplitude*. The squared magnitude of the wavefunction at a point gives the probability density of finding the particle there.

↳ **Dig Deeper — Single-photon and single-electron double-slit experiments**

*The chapter says single particles produce interference patterns when many of them are sent through a double-slit apparatus one at a time. The single-photon and single-electron versions of Young's experiment are among the most striking confirmations of quantum mechanics ever performed.*

**Prompt:**
> Describe the single-electron double-slit experiment, focusing on the empirical result. Walk me through (a) the setup: an electron source, two slits, a detector capable of recording single-electron arrivals. (b) The experimental observation: each electron is detected as one localized spot on the detector (particle-like), but the accumulated pattern over many electrons is the classic interference pattern (wave-like). (c) What changes when you add a "which-slit" detector that observes which slit each electron passed through (the interference pattern disappears). End with one sentence on the famous Tonomura 1989 experiment that imaged this build-up directly with electrons.

**What to do with the output:** Save it. The single-electron two-slit experiment is the cleanest demonstration in physics that wave-particle duality is real, and that measurement disturbs the system being measured. Feynman called it "the only mystery" in quantum mechanics.

---

## Concept 3 — The Heisenberg uncertainty principle

### Werner Heisenberg, Copenhagen, March 1927

Werner Heisenberg, twenty-five years old, is at the Niels Bohr Institute in Copenhagen, drafting a paper that will fundamentally change our understanding of measurement. He has been obsessed for months with a simple-seeming question: when you measure where an electron is, you also disturb its momentum. Light scattered off the electron to locate it carries momentum and pushes the electron around. The smaller the wavelength of the probing light (better position resolution), the higher its photon momentum (more disturbance to the electron's momentum). Heisenberg argues that *no measurement procedure* can simultaneously pin down position and momentum better than a fundamental floor, set by Planck's constant:

$$\Delta x \cdot \Delta p \geq \frac{h}{4\pi} = \frac{\hbar}{2},$$

where $\hbar = h/(2\pi)$ is the *reduced Planck constant*. The OpenStax convention uses $h/4\pi$ rather than $\hbar/2$, but they are the same number.

This is not an experimental limitation that future technology might overcome. It is a property of quantum mechanics itself. Position and momentum are *complementary variables* — knowing one precisely makes the other indeterminate. The same is true for energy and time:

$$\Delta E \cdot \Delta t \geq \frac{h}{4\pi}.$$

Heisenberg's principle is not just a statement about measurement disturbance. It is a statement about what quantum states can exist. Tightly position-localized states have broadly distributed momentum; tightly momentum-localized states have broadly distributed position. Both can't be simultaneously sharp — the math of Fourier transforms (which connects position and momentum representations of the wavefunction) forbids it.

### The mechanism — Heisenberg's two uncertainty principles

**Position-momentum uncertainty.**

$$\boxed{\Delta x \cdot \Delta p \geq \frac{h}{4\pi}.}$$

If you measure position to precision $\Delta x$, the momentum is uncertain by at least $\Delta p \geq h/(4\pi \Delta x)$. The product is bounded below by a fundamental constant.

**Energy-time uncertainty.**

$$\boxed{\Delta E \cdot \Delta t \geq \frac{h}{4\pi}.}$$

A particle's energy can only be known to precision $\Delta E$ over a measurement time interval $\Delta t$ if $\Delta E \, \Delta t \geq h/(4\pi)$. A short-lived state has a corresponding spread in energy ("natural linewidth"). A long-lived state can have a sharp energy.

For small enough $\hbar$, these principles would be invisible at macroscopic scales. The actual numerical value of $h$ ensures that classical objects (large $m$, large $p$) have negligible quantum uncertainty, while atomic-scale objects (small $m$, small $p$) are profoundly constrained. The hydrogen atom's electron, for instance, cannot collapse onto the proton — that would require $\Delta x = 0$, which would force $\Delta p = \infty$ and infinite kinetic energy. The atom's stability *is* the uncertainty principle in action.

### The trade-off

The uncertainty principle trades **simultaneous precise knowledge of complementary variables for the existence of stable atoms.** The cost: there are intrinsic limits to what we can know. The benefit: matter as we know it exists. Without quantum uncertainty, electrons would spiral into nuclei and atoms would collapse. The same principle that "limits" measurement is what makes atoms possible.

### Worked example — locating an electron in an atom

An electron is confined to within an atom (~$10^{-10} \text{ m}$). Estimate its momentum uncertainty and the corresponding kinetic energy.

Position uncertainty: $\Delta x \sim 10^{-10} \text{ m}$.

Minimum momentum uncertainty:

$$\Delta p \geq \frac{h}{4\pi \Delta x} = \frac{6.63 \times 10^{-34}}{4\pi \times 10^{-10}} \approx 5.3 \times 10^{-25} \text{ kg} \cdot \text{m/s}.$$

The electron's momentum must be at least this uncertain — meaning its typical momentum is at least this magnitude.

Corresponding kinetic energy (nonrelativistic):

$$KE \sim \frac{p^2}{2m_e} = \frac{(5.3 \times 10^{-25})^2}{2 (9.11 \times 10^{-31})} \approx 1.5 \times 10^{-19} \text{ J} \approx 0.95 \text{ eV}.$$

A bound electron in an atom must have at least about 1 eV of kinetic energy. The actual binding energies of atomic electrons range from 13.6 eV (hydrogen) to thousands of eV (inner electrons of heavy atoms) — within an order of magnitude of this estimate. The uncertainty principle correctly predicts the order of magnitude of atomic energies.

**Sanity check.** The hydrogen atom's ground state has the electron's expected position spread $\sim 0.5 \text{ Å} = 5 \times 10^{-11} \text{ m}$ and ground-state energy $-13.6 \text{ eV}$ (kinetic energy $\sim 13.6 \text{ eV}$). Our crude estimate is in the right ballpark. The uncertainty principle is the *reason* atoms have the size they have.

### Common misconceptions

- *"Heisenberg's principle is just about measurement clumsiness."* It's a statement about the structure of quantum states themselves, not about experimental technique. Even with perfect, non-disturbing measurement (which doesn't exist, but the principle would still hold), the bound is the same.
- *"Position and momentum are equally undefined."* In a position eigenstate (perfectly localized), momentum is completely undefined; in a momentum eigenstate (plane wave), position is completely undefined. Most real states are intermediate, with both quantities having finite but inversely related uncertainties.
- *"The energy-time uncertainty means time itself is fuzzy."* Time is a parameter, not an observable in standard quantum mechanics. The energy-time relation says that an energy measurement requiring time $\Delta t$ has minimum uncertainty $\Delta E \geq h/(4\pi \Delta t)$. The natural width of a spectral line corresponds to the lifetime of the excited state — short-lived states have broad lines.

↳ **Dig Deeper — Why atoms are the size they are**

*The chapter notes that the uncertainty principle "explains" the size of atoms. Working through the derivation explicitly is one of the cleanest applications of quantum mechanics in introductory physics — it predicts the Bohr radius and the hydrogen ground-state energy from one inequality and minimization.*

**Prompt:**
> Derive the size and ground-state energy of the hydrogen atom from the uncertainty principle alone. Set up the energy as $E = p^2/(2m_e) - ke^2/r$, where $r$ is the typical electron-proton distance and $p$ is the electron's typical momentum. Use the uncertainty relation $r \cdot p \sim \hbar$ to eliminate $p$ in terms of $r$. Minimize $E(r)$ with respect to $r$ to find the equilibrium radius (Bohr radius $a_0 \sim 0.5 \text{ Å}$) and the corresponding ground-state energy ($\sim -13.6 \text{ eV}$). End with one sentence on why this estimate is so close to the exact quantum-mechanical answer (because the actual ground state is the one that minimizes total energy subject to the uncertainty constraint — exactly the calculation you just did).

**What to do with the output:** Save it. This calculation — atom size from uncertainty principle — is one of the most elegant order-of-magnitude estimates in all of physics. It tells you the size of an atom in two lines and a derivative.

---

## Synthesis — quantum mechanics as the new foundation

Step back. Three concepts in this chapter, all built from one observation: at small scales, classical physics fails, and the failures all point to the same fix.

**Concept 1** showed that electromagnetic radiation comes in discrete packets — *photons* — with energy $E = hf$ and momentum $p = h/\lambda$. This was forced by the photoelectric effect (Einstein 1905) and the blackbody spectrum (Planck 1900).

**Concept 2** showed that matter has wave properties, with wavelength $\lambda = h/p$. This was proposed by de Broglie in 1924 and confirmed by Davisson-Germer in 1927. Wave-particle duality is universal.

**Concept 3** showed that complementary variables (position-momentum, energy-time) have intrinsically related uncertainties: $\Delta x \, \Delta p \geq h/(4\pi)$. This is not a measurement limitation but a structural property of quantum states.

The deepest single fact: **Planck's constant $h$ sets the scale of all quantum effects.** For any physical situation, compute typical values of $h/p$ and $h/(4\pi \Delta x \Delta p)$ — if these come out comparable to the relevant scales, you must use quantum mechanics. If they come out far smaller, classical physics is essentially exact. The smallness of $h$ in macroscopic units is *the* reason we can do classical physics for cars and bridges. The non-zero-ness of $h$ is *the* reason we cannot do classical physics for atoms.

Quantum mechanics is not "weird physics" reserved for esoteric experiments. It is the underlying physics of every chemical bond, every transistor, every laser, every spectral line, every solid material we have ever built. We will spend the next chapters (30–33) seeing what it looks like applied to atoms, nuclei, and the elementary particles.

### A worked example using all three concepts — a hydrogen atom

Consider a hydrogen atom: one proton, one electron. We want to predict its size, ground-state energy, and the wavelength of light it emits when an electron transitions between energy levels.

**Concept 3 — uncertainty bounds the size.** The uncertainty principle plus Coulomb attraction gives the Bohr radius $a_0 \sim 0.5 \text{ Å} = 5.3 \times 10^{-11} \text{ m}$ and ground-state energy $E_1 = -13.6 \text{ eV}$.

**Concept 2 — the electron is a standing wave.** In Bohr's old model (and exactly true in the modern Schrödinger picture), the electron's de Broglie wavelength fits an integer number of times around the orbit. For the ground state, the orbit's circumference is $2 \pi a_0 \sim 3.3 \text{ Å}$, which is also one electron de Broglie wavelength. The electron is a standing wave around the proton.

**Concept 1 — a photon carries the energy difference.** Energy levels in hydrogen are $E_n = -13.6 \text{ eV} / n^2$ for $n = 1, 2, 3, \ldots$. A transition from $n = 2$ to $n = 1$ releases $|E_1| - |E_2| = 13.6 - 3.4 = 10.2 \text{ eV}$ as a single photon. The photon's wavelength:

$$\lambda = \frac{hc}{E} = \frac{1240 \text{ eV} \cdot \text{nm}}{10.2 \text{ eV}} = 122 \text{ nm}.$$

This is the *Lyman-α* line of hydrogen — a UV emission line observed in any sufficiently energetic hydrogen plasma (the Sun, hot stars, lab discharge tubes). Its wavelength was measured to high precision in the 19th century. Quantum mechanics reproduces it exactly.

**Scale shift.** That same physics, scaled to a different element, predicts the spectral lines of helium, lithium, sodium, every element on the periodic table. Spectroscopy — measuring atomic spectral lines to identify elements — is the basis of stellar astrophysics (we know what stars are made of from their spectra), forensic chemistry, and remote sensing of planetary atmospheres. All of it built on the three concepts in this chapter.

---

## Exercises

### Warm-up

**29.1** *(LO 1, LO 2)* Compute the energy of (a) a $500 \text{ nm}$ green photon, (b) a $1.5 \text{ GHz}$ cell phone photon, (c) a $1 \text{ keV}$ X-ray photon. Report in both joules and eV.

**29.2** *(LO 3)* Compute the de Broglie wavelength of (a) an electron at $200 \text{ eV}$, (b) a $0.20 \text{ kg}$ baseball at $40 \text{ m/s}$. Compare each to the typical wavelength of visible light.

**29.3** *(LO 1)* Light of wavelength $300 \text{ nm}$ shines on a metal with work function $\phi = 2.7 \text{ eV}$. Find the maximum kinetic energy of ejected electrons.

**29.4** *(LO 4)* An electron is localized to within $\Delta x = 1.0 \times 10^{-11} \text{ m}$ (~one-tenth of an atom). Find the minimum momentum uncertainty. Then find the corresponding minimum kinetic energy.

### Application

**29.5** *(LO 1)* The threshold wavelength for ejecting electrons from a certain metal is $540 \text{ nm}$. (a) Find the metal's work function. (b) What is the maximum KE of electrons ejected by light of wavelength $400 \text{ nm}$?

**29.6** *(LO 2)* Find the photon momentum of (a) a $1 \text{ MeV}$ gamma ray, (b) a $500 \text{ nm}$ visible photon. (c) For the visible photon, find the velocity of an electron with the same momentum (use classical $p = mv$).

**29.7** *(LO 3)* Electrons in a transmission electron microscope are accelerated through $200 \text{ kV}$. (a) Find their de Broglie wavelength (use the relativistic momentum since $200 \text{ keV}$ is comparable to the electron's rest energy of $511 \text{ keV}$). (b) Compare to the diffraction-limited resolution of visible-light optics ($\sim 200 \text{ nm}$).

**29.8** *(LO 4)* An excited atomic state has a lifetime of $\tau = 10^{-8} \text{ s}$. Use the energy-time uncertainty relation to estimate the natural linewidth of the corresponding emission line. Convert to a wavelength uncertainty for $\lambda = 500 \text{ nm}$ light.

### Synthesis

**29.9** *(LO 1, LO 5)* Why don't we observe quantum effects in everyday life? Pick a macroscopic object (a baseball, a car, a person) and compute (a) the de Broglie wavelength, (b) the energy uncertainty corresponding to a measurement time of one second. Compare each to atomic scales.

**29.10** *(LO 1, LO 2)* The Sun emits radiation peaking near $500 \text{ nm}$. (a) Find the photon energy in eV. (b) The Sun's total power output is $3.86 \times 10^{26} \text{ W}$. Estimate the rate at which it emits photons (assume monochromatic at the peak wavelength for this estimate). (c) The sun is $1.5 \times 10^{11} \text{ m}$ away. Estimate the photon flux (photons per second per square meter) at Earth.

**29.11** *(LO 3, LO 4)* A neutron in a nucleus is confined to a region of size $\sim 10^{-15} \text{ m}$. Using the uncertainty principle, estimate the neutron's typical kinetic energy. Compare to the nuclear binding energy per nucleon ($\sim 8 \text{ MeV}$). Forward-points to Chapter 31.

### Challenge

**29.12** *(beyond chapter)* Explain in your own words how the photoelectric effect rules out a classical wave description of light. Construct a thought experiment with very dim, low-frequency light (below threshold) and argue that no classical wave story can produce the observed result of zero ejected electrons regardless of intensity.

**29.13** *(beyond chapter)* The double-slit interference pattern is observed when electrons are sent through an apparatus one at a time. (a) Describe what you would see on a screen capable of detecting single electrons after the first 10 electrons have arrived. After 1000 electrons. After 100,000 electrons. (b) Explain in your own words how this is consistent with each electron being a particle, but the cumulative pattern being wave-like. (c) What changes if you put a "which-slit" detector at the slits, and why?

---

## LLM Exercise — Chapter 29: Quantum Physics in Your Anchor Phenomenon

**Project:** Physics Reality Check Logbook
**What you're building this chapter:** A Logbook entry for quantum physics. Like Chapter 28, most everyday phenomena don't visibly involve quantum effects, but every electronic device, every photon-detecting eye, every chemical bond does. You can either compute a quantum-mechanical correction to your phenomenon or write an "exception entry" identifying the most distant quantum connection (often LEDs, displays, or sensors).
**Tool:** Claude Project.

### The Prompt

```
I'm continuing my Physics Reality Check Logbook for College Physics with LLMs. My anchor phenomenon is [paste your 1-sentence description].

For Chapter 29, I want to think about quantum physics. Most everyday phenomena are classical at the macroscopic level, but rely on quantum mechanics in their components (LEDs, screens, sensors, the eye's photoreceptors).

Please:

1. Identify ONE quantum-mechanical aspect of my phenomenon. Examples: for a bike commute — the LED traffic signals (each photon emission is a quantum transition), the photoreceptors in my eye (single-photon detection), the silicon in my smartphone display (quantum band structure). For a coffee maker — the electric heating element (Ohm's law breaks down at quantum level), the LED indicator lights, the chemical bonds in the coffee compounds. For a basketball shot — the gym lighting, the chemical bonds in the basketball's polyurethane, my visual system. For a marathon — the GPS watch's display, the chemical bonds in the energy gels.

2. Apply ONE quantum equation. Compute photon energy from a relevant wavelength: a chip's bandgap energy (silicon ~1.1 eV → ~1100 nm), an LED color, a UV-protective coating. Or compute the de Broglie wavelength of an electron in a transistor.

3. Specify input numbers and uncertainty.

4. Run the calculation. Report value with units.

5. One sentence on what would happen if quantum mechanics were "off" — what specific failures would occur in technology I use.

6. One sentence connecting this to Chapter 30 (atomic physics) — atomic structure is the next chapter.

Save the output as logbook/chapter-29-quantum.md.
```

### What this produces

A Logbook entry that locates the quantum physics in your phenomenon. Often the answer is "every chip and every LED is a quantum device."

### How to adapt this prompt

- *For phenomena heavy on chemistry (food, drink, materials):* Every chemical bond is quantum mechanical. The Pauli exclusion principle (which we'll meet in Chapter 30) is what makes atoms have shells.
- *For ChatGPT/Gemini:* Identical with interface substitutions.
- *For Claude Code:* If you have spectroscopic data (e.g., from a hyperspectral camera image), you can use Claude Code to extract photon energies from observed wavelengths.

### Connection to previous chapters

Builds directly on Chapter 24 (EM spectrum) and Chapter 27 (wave behavior of light). Uses Chapter 28's relativistic energy-momentum relation for massless particles ($E = pc$) and the correspondence principle.

### Preview of next chapter

Chapter 30 (atomic physics) applies quantum mechanics to atoms specifically — Bohr's model, the hydrogen spectrum, quantum numbers, the Pauli principle, and the periodic table.

---

## Chapter summary

Quantum mechanics replaced classical mechanics at small scales between 1900 and the late 1920s. Light comes in discrete photons of energy $E = hf$ and momentum $p = h/\lambda$ (Planck 1900, Einstein 1905). All matter has wave properties with de Broglie wavelength $\lambda = h/p$ (1924, confirmed by Davisson-Germer 1927). Position and momentum cannot both be simultaneously sharp: $\Delta x \, \Delta p \geq h/(4\pi)$ (Heisenberg 1927). Wave-particle duality is universal — every quantum object exhibits both, and the experiment determines which set of properties manifests. Classical physics survives as the limit of quantum mechanics when $h$ is negligible compared to the action scales of the system.

The one idea that matters most: **at scales where Planck's constant $h$ is comparable to the relevant action ($p \times x$ or $E \times t$), classical physics is wrong and quantum mechanics is required.** For everyday objects, classical physics is essentially exact. For atoms, electrons in semiconductors, photons emitted by LEDs, you must use quantum mechanics — and it works.

The common mistake to watch for: **trying to picture a quantum object as either purely particle or purely wave.** It is neither, and both. The wavefunction is the complete description; the experiment determines which classical aspect (particle-like detection or wave-like interference) you observe.

What you should now be able to teach someone else: why the photoelectric effect requires photons, why the Davisson-Germer electron-diffraction experiment supports the de Broglie hypothesis, why the uncertainty principle places a fundamental limit on simultaneous position-momentum knowledge, and why all of this is invisible at macroscopic scales (because $h$ is tiny). If you can also explain why the Sun's spectrum has discrete absorption lines (Chapter 30), you've understood quantum mechanics as the new foundation.

---

## What would change my mind

The chapter argues that quantum mechanics is the correct theory of nature at small scales and that classical mechanics is its $h \to 0$ limit. The argument would need revision if (a) a precision measurement found Planck's constant to vary in time or with location, (b) a macroscopic experiment found wave-particle duality breaking down (e.g., electrons going through a double slit *not* producing interference, or producing interference of the wrong wavelength), or (c) a way to violate the Heisenberg bound were demonstrated. None of these has happened despite a century of intense experimental scrutiny.

## Still puzzling

The deepest unresolved question this chapter raises and does not answer: **what is the wavefunction physically?** Is it a real thing in the world, or just a tool for computing probabilities of measurement outcomes? Different schools of interpretation (Copenhagen, many-worlds, hidden-variables, QBism, relational) give different answers, and the experimental tests proposed to distinguish them have so far been inconclusive. The mathematics of quantum mechanics is not in doubt; what the mathematics *means* remains genuinely unsettled. This is one of the rare places where the philosophy of physics is not yet caught up with the predictive successes of the theory.

---

## Connections forward

Chapter 30 (atomic physics) applies quantum mechanics to atoms — Bohr's model, energy levels, quantum numbers, the Pauli exclusion principle, the periodic table. Chapter 31 (radioactivity) treats nuclear physics — quantum tunneling for alpha decay, the strong nuclear force, half-life, $E = mc^2$ for binding energies. Chapter 32 (medical applications) uses spectroscopy and nuclear physics for medical imaging and therapy. Chapter 33 (particle physics) extends quantum mechanics to relativistic regimes and the standard model. Chapter 34 (frontiers) returns to open questions: dark matter, the cosmological constant, the search for a quantum theory of gravity, the foundations of quantum mechanics itself.

---

**Tags:** quantum-mechanics, photons, photoelectric-effect, de-Broglie, Heisenberg-uncertainty

---

## AI Wayback Machine

**Max Planck** introduced the quantum hypothesis in 1900 — proposing that energy comes in discrete packets to explain blackbody radiation. He spent the rest of his life uncomfortable with what his idea unleashed.

**Run this:**

```
Who was Max Planck, and how does his quantum hypothesis connect to the quantum physics we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about his career or ideas.
```

→ Search **"Max Planck"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to walk through how Planck's quantization assumption resolves the ultraviolet catastrophe.
- Ask it about Planck's quiet resistance to Nazi science policy during the war.

What changes? What gets better? What gets worse?
