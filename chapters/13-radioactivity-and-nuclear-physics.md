# Chapter 13 — Radioactivity and Nuclear Physics

**Suggested titles**

1. Radioactivity and Nuclear Physics
2. The Curies, Pitchblende, and Energies a Million Times Greater Than Atomic
3. Why Atoms Decay and How We Know

**TL;DR.** Nuclei contain protons and neutrons (collectively *nucleons*) bound by the strong nuclear force. Some nuclei are unstable and decay spontaneously by emitting alpha particles (helium nuclei), beta particles (electrons or positrons from neutron-to-proton or proton-to-neutron conversion), or gamma photons (from nuclear excited states). Each decay releases energy on the order of MeV — millions of times atomic energies — through the conversion of mass to energy via $E = mc^2$. The half-life $t_{1/2}$ characterizes how fast a given isotope decays; it ranges from $10^{-23}$ s to $10^{16}$ years. Nuclear binding energies — typically ~8 MeV per nucleon — and quantum tunneling explain both why nuclei stick together and why some leak particles out.

---

## A Paris laboratory, 1898

Marie Skłodowska Curie, age thirty, is working in a converted shed at the École Supérieure de Physique et de Chimie in Paris. She has chosen, for her doctoral thesis, the topic of Antoine Henri Becquerel's two-year-old discovery: certain rocks containing uranium emit invisible "rays" that can fog photographic plates and ionize gases. Becquerel had moved on; Marie has not. She and her husband Pierre — a respected physicist with a teaching post — have spent months processing tonnes of pitchblende, a uranium ore from Joachimsthal in Bohemia, in the laboratory shed. They are looking for whatever in the pitchblende emits Becquerel's mysterious rays.

The chemistry is brutal. They dissolve, precipitate, recrystallize, separate, and re-separate. The shed has no proper ventilation. Marie writes in her notebook for a typical day's work: "We had no money, no laboratory and no help in the conduct of this important and difficult task." Her hands develop sores that will not heal. She and Pierre are increasingly fatigued, their fingers stained, their skin reddened.

By July 1898 they isolate a new element, more radioactive than uranium, which Marie names *polonium* after her birthplace. By December they isolate a second, *radium* (from the Latin for "ray"), about two million times as radioactive as uranium per gram. The pure radium salt glows a soft blue in the dark. They hand-grind a few decigrams of it for a 1903 demonstration. The 1903 Nobel Prize in Physics goes jointly to Becquerel, Pierre, and Marie. (Marie is the first woman to win a Nobel.) Pierre dies in 1906, run over by a horse-drawn cart. Marie continues, alone. The 1911 Nobel Prize in Chemistry goes to her for the discoveries of polonium and radium. She remains the only person to win Nobel Prizes in two different sciences.

Marie Curie dies in 1934 of aplastic anemia — almost certainly caused by her decades of exposure to radioactivity. Her notebooks from the period are still so radioactive that they are stored in lead-lined boxes at the Bibliothèque Nationale de France, and visitors must sign liability waivers to consult them.

The discoveries the Curies made — that certain elements spontaneously emit radiation a million times more energetic than any atomic process — opened the door to modern nuclear physics. The radiation came from a different layer of matter than chemistry knew about: the *nucleus*. This chapter explains what's down there, why it sometimes flies apart, and how the same physics powers stars, ages rocks, treats cancer, and built the bombs that ended a world war.

**Learning objectives.** By the end of this chapter you should be able to:

1. Identify the components of a nucleus (protons + neutrons = nucleons), apply the standard notation $^A_Z X_N$, and distinguish isotopes (same Z, different N).
2. Describe alpha, beta, and gamma decay, write balanced decay equations, and apply conservation of charge and mass number to predict the daughter nucleus.
3. Apply the radioactive-decay law $N(t) = N_0 e^{-\lambda t}$ and the half-life relation $t_{1/2} = \ln 2 / \lambda \approx 0.693/\lambda$ to compute remaining activity at any time.
4. Calculate nuclear binding energy from atomic mass defects via $\text{BE} = (\Delta m) c^2$ and explain why iron-region nuclei are most tightly bound (the binding-energy-per-nucleon curve).
5. Explain quantum tunneling as the mechanism for alpha decay and why decay rates depend exponentially on the height and width of the Coulomb barrier.

**Prerequisites.** Chapter 28 (special relativity, $E = mc^2$). Chapter 29 (quantum mechanics, wavefunctions, photons, uncertainty principle). Chapter 30 (atomic structure, periodic table, Pauli exclusion). Comfort with exponential decay (Chapter 23).

**Why this chapter matters.** Nuclear physics is the underlying physics of: every star (stellar fusion), the entire periodic table beyond hydrogen and helium (synthesis in supernovae and neutron-star mergers), Earth's interior heat (radioactive decay), the carbon-14 dating that built archaeology, every nuclear power plant and weapon, every PET scan and chemotherapy isotope. Without this chapter, a third of modern medicine and most of energy technology is opaque. Chapter 32 builds directly on it for the medical applications.

---

## Concept 1 — What's in a nucleus, and what comes out when one decays

### Three rays in a magnetic field, 1899

Ernest Rutherford, working in Montreal in 1899 (he had not yet moved to Manchester), takes a sample of radium and asks a simple question: when the radium emits its mysterious rays, are they all the same? He sets up a magnetic field perpendicular to the path of the radiation and watches what happens. The rays separate into three beams.

One beam is unaffected by the field. He calls these the *gamma rays*. They are eventually identified as high-energy photons — electromagnetic radiation with wavelengths shorter than the shortest X-rays.

A second beam bends one way, indicating positive charge. He calls these *alpha particles*. They turn out to be helium nuclei — two protons plus two neutrons, charge $+2e$, mass about 4 atomic mass units.

A third beam bends the other way, indicating negative charge, and bends *much more* than the alphas, indicating much smaller mass. He calls these *beta particles*. They turn out to be high-energy electrons (in $\beta^-$ decay) or positrons (in $\beta^+$ decay).

That's the entire taxonomy of nuclear radiation, established in 1899-1903 by Rutherford and his collaborators with magnets and counters. Three modes of decay. Each turns out to correspond to a specific physical mechanism in the nucleus.

### The mechanism — nuclear structure and the three decays

A nucleus is made of *protons* (charge $+e$, mass 1.0073 u) and *neutrons* (charge 0, mass 1.0087 u). Together, protons and neutrons are *nucleons*. The standard notation:

$$^A_Z X_N$$

where $X$ is the chemical symbol, $Z$ is the *atomic number* (number of protons; determines the element), $N$ is the *neutron number*, and $A = N + Z$ is the *mass number* (total nucleons). Different *isotopes* of an element have the same $Z$ but different $N$ (and hence different $A$). Carbon-12 ($^{12}_6 \text{C}_6$) and carbon-14 ($^{14}_6 \text{C}_8$) are isotopes of carbon. Hydrogen has three: protium ($^1$H, just a proton), deuterium ($^2$H, proton + neutron), and tritium ($^3$H, proton + 2 neutrons; radioactive).

The unified atomic mass unit ($u$) is defined so that one neutral $^{12}\text{C}$ atom has mass exactly 12 u. The conversion to energy:

$$1 \text{ u} = 1.6605 \times 10^{-27} \text{ kg} = 931.5 \text{ MeV}/c^2.$$

So one atomic mass unit converted entirely to energy gives 931.5 MeV — about a quarter of a billion times the energy of a chemical bond.

**Nuclear size.** Radii follow $r \approx (1.2 \text{ fm}) A^{1/3}$, where $1 \text{ fm} = 10^{-15} \text{ m}$. A carbon-12 nucleus has $r \approx 2.7 \text{ fm}$. A uranium-238 nucleus has $r \approx 7.4 \text{ fm}$. Density is roughly constant ($\sim 2 \times 10^{17} \text{ kg/m}^3$) — much greater than ordinary matter. A teaspoon of nuclear matter would weigh about a billion tonnes.

**The strong nuclear force.** What holds protons together against their mutual electrostatic repulsion? A short-range attractive force — *the strong nuclear force* — that acts only between nucleons within about 2 fm of each other. It's strongest between nucleons just touching; effectively zero beyond a few fm; and it is *attractive* between protons and neutrons, between neutron pairs, and between proton pairs. Without it, nuclei larger than $^1$H would not exist.

### Three decay modes

**Alpha decay.** A nucleus emits a $^4_2 \text{He}_2$ nucleus (an alpha particle):

$$^A_Z X_N \to {^{A-4}_{Z-2}} Y_{N-2} + {^4_2 \text{He}_2}.$$

The daughter has 2 fewer protons and 2 fewer neutrons. Example: $^{238}\text{U} \to {^{234}\text{Th}} + \alpha$, with $Z$ going from 92 to 90 (uranium → thorium).

**Beta-minus decay.** A neutron in the nucleus converts to a proton, emitting an electron and an antineutrino:

$$n \to p + e^- + \bar{\nu}_e.$$

In a nucleus, this changes the daughter:

$$^A_Z X_N \to {^A_{Z+1}} Y_{N-1} + e^- + \bar{\nu}_e.$$

$Z$ increases by 1; $N$ decreases by 1; $A$ unchanged. Example: $^{14}\text{C} \to {^{14}\text{N}} + e^- + \bar{\nu}_e$ — the basis of carbon-14 dating.

**Beta-plus decay.** A proton converts to a neutron, emitting a positron and a neutrino:

$$p \to n + e^+ + \nu_e.$$

$Z$ decreases by 1; $N$ increases by 1; $A$ unchanged. Used in PET imaging (Chapter 32).

**Gamma decay.** A nucleus in an excited state drops to a lower-energy state, emitting a gamma photon:

$$^A_Z X_N^* \to {^A_Z X_N} + \gamma.$$

No change in $Z$ or $N$. The gamma photon's energy equals the energy difference between nuclear levels — typically MeV.

### The trade-off

The decay categorization trades **simplicity (three decay modes) for completeness (every observed nuclear decay fits one of these patterns).** The cost is that beta decay required postulating an unobserved particle (the neutrino, hypothesized by Pauli in 1930 to save energy and angular-momentum conservation) — eventually detected experimentally by Cowan and Reines in 1956. The benefit: a complete bookkeeping of charge, mass-number, and energy conservation across every observed decay process.

### Worked example — alpha decay of uranium-238

Write the alpha-decay equation for uranium-238.

$^{238}_{92}\text{U}_{146}$ emits an alpha ($^4_2 \text{He}_2$):

$$^{238}_{92}\text{U}_{146} \to {^{234}_{90} \text{Th}_{144}} + {^4_2 \text{He}_2}.$$

Check: $A$ on left = 238; $A$ on right = 234 + 4 = 238. ✓
$Z$ on left = 92; $Z$ on right = 90 + 2 = 92. ✓

The daughter is thorium-234, which is itself unstable and beta-decays to protactinium-234. The decay continues through 14 steps (the *uranium-238 decay series*) before stabilizing as lead-206.

The kinetic energy released in the alpha decay (the $Q$-value) can be computed from the mass difference:

$$Q = [m(^{238}\text{U}) - m(^{234}\text{Th}) - m(^4\text{He})] \, c^2.$$

Using tabulated atomic masses (in u):

$Q = (238.0508 - 234.0436 - 4.0026)(931.5) \approx 4.27 \text{ MeV}.$

That's about $4 \times 10^6$ eV per atom — roughly a million times typical chemical reaction energies.

**Sanity check.** Measured alpha-particle kinetic energies from $^{238}$U decay are in the range $4.15$–$4.25 \text{ MeV}$ (the alpha carries almost all the kinetic energy because it's much lighter than the recoiling daughter, by momentum conservation), well within the predicted Q-value.

### Common misconceptions

- *"All decays produce gamma rays."* No. Pure alpha and pure beta decays don't necessarily emit gammas. Gammas accompany decays only if the daughter nucleus is left in an excited state and de-excites by photon emission.
- *"Beta decay is just an electron escaping the nucleus."* No. The electron didn't exist before the decay. A neutron converted to a proton, and the new electron and antineutrino were created in the process.
- *"The neutrino is a sort of light particle."* It's almost massless (neutrino mass < 1 eV/$c^2$ as best we currently know — recent measurements suggest sub-eV) and electrically neutral. It interacts only via the weak force, so it can pass through light-years of lead without interacting. It is one of the strangest fundamental particles known.

↳ **Dig Deeper — Why the neutrino had to exist (Pauli's 1930 letter)**

*The chapter mentions that Pauli postulated the neutrino in 1930 to save conservation laws. The original "Open Letter to the Group of Radioactives at the Regional Meeting in Tübingen" is one of the funniest documents in physics history, and the puzzle it solved — beta-decay's continuous energy spectrum, which seemed to violate energy conservation — is worth understanding directly.*

**Prompt:**
> Explain why beta decay seemed to violate energy conservation in the late 1920s, and how Pauli's hypothesis of an unobserved neutral particle (the neutrino) saved conservation. Walk me through (a) the experimental observation: beta particles emitted from a particular decay show a continuous spectrum of kinetic energies, not the single discrete energy expected from a two-body decay. (b) Pauli's 1930 proposal: a third (almost massless, neutral, weakly interacting) particle is also emitted, and it carries away the missing energy. (c) The eventual experimental detection: Frederick Reines and Clyde Cowan, 1956, using nuclear-reactor antineutrinos at Savannah River. End with one sentence on why neutrinos are so hard to detect (cross-section ~$10^{-44}$ cm²).

**What to do with the output:** Save it. The neutrino story is one of the great vindications in physics of insisting on conservation laws even when experiment seems to violate them.

---

## Concept 2 — Half-life, the decay law, and dating

### The Shroud of Turin, 1988

In April 1988, three independent laboratories (in Tucson, Oxford, and Zürich) receive small swatches of cloth from the Shroud of Turin — the linen cloth bearing the faint image of a man, venerated since at least the 14th century. Each lab measures the abundance of carbon-14 in the cloth using accelerator mass spectrometry. The measurement is conceptually simple: living organisms maintain a steady ratio of C-14 to C-12 (the C-14 is replenished by atmospheric interactions); when an organism dies, the C-14 begins to decay with a half-life of $5730$ years; measure the current ratio and back out the time of death.

The three labs report: the cloth dates to between 1260 and 1390 AD, with 95% confidence. The image's existence between 1260-1390 is consistent with the historical record's first mention (a French bishop in 1389 claimed it was a deliberately created forgery). It is inconsistent with a 1st-century origin.

The Shroud has remained venerated for non-scientific reasons. The dating is uncontroversial within the physics community.

This is what radioactive dating *is*: a clock built into matter. The clock ticks at a rate set by quantum-mechanical decay constants, and it works for any process that locks in a measurable starting concentration of a known isotope. Carbon-14 ($t_{1/2} = 5730$ y) for organic material up to ~50,000 years. Potassium-40 ($t_{1/2} = 1.25$ Gy) for rocks from billions of years ago. Uranium-238 ($t_{1/2} = 4.5$ Gy) for the age of the Earth itself. Each isotope is a clock with a different reach.

### The mechanism — exponential decay and half-life

A radioactive sample doesn't decay all at once. Each individual nucleus has the same probability per unit time of decaying — independent of how long it's been around. Mathematically, if $N(t)$ is the number of undecayed nuclei at time $t$:

$$\frac{dN}{dt} = -\lambda N,$$

where $\lambda$ is the *decay constant* (probability per unit time per nucleus). Integrating:

$$\boxed{N(t) = N_0 e^{-\lambda t}.}$$

After one *half-life* $t_{1/2}$, half the original nuclei remain:

$$N_0/2 = N_0 e^{-\lambda t_{1/2}} \implies \lambda t_{1/2} = \ln 2,$$

$$\boxed{t_{1/2} = \frac{\ln 2}{\lambda} \approx \frac{0.693}{\lambda}.}$$

After $n$ half-lives, $N(t) = N_0 / 2^n$. After 10 half-lives, only $1/1024$ of the original sample remains.

Half-lives span a staggering 46 orders of magnitude. The most stable observed unstable nucleus is ${}^{128}$Te with $t_{1/2} \approx 2.2 \times 10^{24}$ years ($10^{14}$ times the age of the universe). The most unstable is at the other extreme: some excited nuclear states have lifetimes around $10^{-23}$ seconds — the time for light to cross a nucleus.

**Activity** is the rate of decay: $A = \lambda N$, measured in *becquerels* (1 Bq = 1 decay/second) or the older unit *curies* (1 Ci = $3.7 \times 10^{10}$ Bq = decay rate of 1 g of radium-226).

### Carbon-14 dating

Atmospheric nitrogen ($^{14}$N) is bombarded by cosmic-ray neutrons, producing $^{14}$C: $n + {^{14}\text{N}} \to {^{14}\text{C}} + p$. The C-14 decays back ($t_{1/2} = 5730$ y) but is replenished, leading to a steady-state atmospheric ratio of about 1 carbon-14 atom per $10^{12}$ carbon-12 atoms.

Living organisms exchange carbon with the atmosphere (via photosynthesis or by eating plants). Their internal C-14/C-12 ratio matches the atmospheric ratio. When the organism dies, no new carbon enters; the C-14 decays away.

To date a sample, measure its current C-14/C-12 ratio. Back-calculate how long ago the ratio matched the atmospheric value. The reach is about 10 half-lives ($\sim 50{,}000$ years); beyond that, too little C-14 remains to distinguish from background.

The technique was developed by Willard Libby in 1949, who won the 1960 Nobel Prize in Chemistry for it.

### The trade-off

Radioactive dating trades **statistical exactness for one stochastic measurement.** Each individual nucleus's decay time is unpredictable (random); only the *ensemble* shows the smooth exponential behavior. The cost: small samples have larger statistical uncertainty (~$\sqrt{N}$). The benefit: a clock that has ticked unbroken since the relevant isotope was created in stars billions of years ago.

### Worked example — carbon-14 dating an artifact

A sample of organic material has C-14 activity of $0.20$ Bq per gram of carbon. A modern sample has activity $0.23$ Bq per gram. How old is the sample?

The activity ratio gives the surviving fraction:

$$\frac{N(t)}{N_0} = \frac{0.20}{0.23} \approx 0.870.$$

Apply the decay law:

$$0.870 = e^{-\lambda t} = e^{-(\ln 2 / 5730 \text{ y}) t}.$$

Solve:

$$-\frac{0.693}{5730} t = \ln(0.870) = -0.139,$$

$$t = \frac{0.139 \times 5730}{0.693} \approx 1150 \text{ y}.$$

The sample is about $1150$ years old.

**Sanity check.** Modern atmospheric C-14 levels are slightly perturbed by 20th-century nuclear tests (which spiked the C-14 inventory) and fossil-fuel burning (which dilutes it with C-12-rich CO₂), so reference activity values must be carefully chosen. For artifacts more than a few thousand years old, calibration curves correct for atmospheric variations.

### Common misconceptions

- *"After two half-lives, all the sample is gone."* No. After two half-lives, $1/4$ remains. After $n$ half-lives, $1/2^n$ remains.
- *"Long-half-life isotopes are dangerous; short ones are safe."* It's the *activity* (decay rate) that determines danger. A short-half-life isotope has high decay rate (high activity per gram) and is dangerous *while it's around*; long-half-life isotopes have low activity but persist for ages. Both can be dangerous in different ways.
- *"Carbon-14 dating works for anything organic."* It works for samples up to ~50,000 years old. Beyond that, too little C-14 remains. It also requires carbon that was alive (atmospheric exchange) — not, e.g., dissolved limestone in fossils, which can be much older than the C-14 ratio suggests.

↳ **Dig Deeper — The age of the Earth from uranium-lead dating**

*The chapter mentions C-14 dating and uranium-238 as a clock for the Earth's age. Patterson's 1956 measurement, using the lead isotope ratios in meteorites, pinned the Earth's age at $4.55 \pm 0.07$ billion years. It is one of the most important quantitative measurements in 20th-century geology.*

**Prompt:**
> Walk me through Clair Patterson's 1956 measurement of the Earth's age. (a) Explain why $^{238}$U → $^{206}$Pb decay (with $t_{1/2} = 4.5$ Gy) provides a clock for ages of billions of years. (b) Explain why Patterson used iron meteorites (which contain almost no initial uranium) to set the *initial* lead isotope ratio at solar-system formation. (c) Briefly describe the obstacle of atmospheric lead contamination — Patterson eventually pioneered ultra-clean-room techniques and discovered the global extent of lead pollution from leaded gasoline. End with one sentence on the modern best estimate of Earth's age (~4.54 Gy).

**What to do with the output:** Save it. Patterson's measurement is a beautiful example of how a single radioactive clock, applied carefully, settles a question that had divided geologists, biologists, and theologians for centuries.

---

## Concept 3 — Binding energy, mass defect, and quantum tunneling

### Iron at the bottom of a curve

If you plot the *binding energy per nucleon* against mass number $A$ for every known stable isotope, you get a remarkable curve. It rises rapidly from hydrogen (BE = 0; one proton has nothing to bind to) to about $A \approx 60$ — the iron region — where it peaks at about $8.8 \text{ MeV/nucleon}$. Beyond iron, it gradually declines; uranium-238 has only about $7.6 \text{ MeV/nucleon}$.

The shape of this curve is the most consequential graph in nuclear physics. It tells you that:

- **Fusion of light nuclei** (going up the curve from H toward Fe) releases energy. This is what stars do — fusing hydrogen into helium, then helium into carbon, and so on, gaining energy at every step until iron stops the process. *Stars stop burning at iron* because there is no further energy gain to be had.
- **Fission of heavy nuclei** (going from U-235 down toward Fe) also releases energy. This is what nuclear reactors and weapons exploit — splitting heavy nuclei into two fragments closer to iron.

The same curve explains why iron is the most abundant element in many star cores at the moment of supernova collapse, why uranium can be split for weapons but iron cannot, and why the Sun's energy ultimately comes from $^4$He having higher binding-energy-per-nucleon than $4 \times {^1}$H.

### The mechanism — binding energy from mass defect

The mass of a bound nucleus is *less* than the sum of the masses of its constituent free nucleons. The difference — the *mass defect* $\Delta m$ — is converted to the binding energy that holds the nucleus together:

$$\boxed{\text{BE} = (\Delta m) c^2 = [(Z m_p + N m_n) - m_{\text{nucleus}}] c^2.}$$

When working with tabulated atomic masses (which include the masses of the $Z$ atomic electrons), use:

$$\text{BE} = \{ Z \, m(^1\text{H}) + N \, m_n - m(^A X) \} c^2.$$

The hydrogen-atom mass on the right cancels the electron masses on the left, simplifying calculations.

### Binding energy for $^4$He

Let's compute it. $Z = 2$, $N = 2$.
- $2 \times m(^1\text{H}) = 2 \times 1.00794 \text{ u} = 2.01588 \text{ u}$
- $2 \times m_n = 2 \times 1.00867 \text{ u} = 2.01734 \text{ u}$
- Sum: $4.03322 \text{ u}$
- Mass of $^4\text{He}$ atom: $4.00260 \text{ u}$
- $\Delta m = 4.03322 - 4.00260 = 0.03062 \text{ u}$
- BE $= 0.03062 \times 931.5 \text{ MeV/u} = 28.5 \text{ MeV}$

That's $28.5/4 \approx 7.13 \text{ MeV/nucleon}$. The most tightly bound nucleus, $^{62}\text{Ni}$ (or by some measures $^{56}\text{Fe}$), reaches about $8.79 \text{ MeV/nucleon}$. Uranium-238 is around $7.57 \text{ MeV/nucleon}$.

### Quantum tunneling and alpha decay

Alpha decay presents a puzzle. An alpha particle inside a nucleus has kinetic energy maybe $5$ MeV. It is held inside by the strong nuclear force, but it "feels" a Coulomb barrier from the rest of the nucleus when it tries to leave: the protons in the daughter nucleus repel it. The Coulomb barrier height is *much* higher than the alpha's energy — typically $\sim 25$ MeV for heavy nuclei.

Classically, an alpha with $5$ MeV cannot escape a $25$ MeV barrier. Yet alpha decay happens. Why?

The answer, supplied by George Gamow in 1928, is *quantum tunneling*. The alpha's wavefunction extends through the classically forbidden region of the barrier, with exponentially decreasing amplitude. The probability of finding the alpha *outside* the barrier — even though it doesn't have enough energy to climb over — is small but nonzero. Eventually, with enough attempts, the alpha tunnels through.

The tunneling probability depends exponentially on the barrier height and width. Small changes in the alpha's energy produce huge changes in the half-life. This is why alpha-decay half-lives span 17 orders of magnitude, from microseconds to billions of years, while alpha-particle energies vary only over a factor of 2 or 3. The Geiger-Nuttall law (1911) — empirically observed before tunneling theory existed — quantifies this dependence.

### The trade-off

Quantum tunneling trades **classical impossibility for quantum possibility, at exponentially suppressed rates.** A higher or wider barrier doesn't *forbid* tunneling — it just makes it exponentially slower. A 5-MeV alpha facing a 25-MeV barrier can still escape; it just has to wait. For some nuclei, the wait is shorter than a microsecond. For others, it's longer than the age of the universe.

### Worked example — binding energy per nucleon for $^{56}$Fe

Iron-56 has $Z = 26$, $N = 30$.
- $26 \times m(^1\text{H}) = 26 \times 1.00794 = 26.2064 \text{ u}$
- $30 \times m_n = 30 \times 1.00867 = 30.2601 \text{ u}$
- Sum: $56.4665 \text{ u}$
- Mass of $^{56}\text{Fe}$ atom: $55.9349 \text{ u}$
- $\Delta m = 56.4665 - 55.9349 = 0.5316 \text{ u}$
- BE $= 0.5316 \times 931.5 = 495.2 \text{ MeV}$
- BE per nucleon = $495.2 / 56 = 8.84 \text{ MeV/nucleon}$

Iron-56 is at the peak of the binding-energy curve. Per nucleon, no other isotope beats it by much. This is why iron is the natural endpoint of stellar fusion.

**Sanity check.** $^{56}$Fe is one of the most abundant heavier elements in the Earth's crust and core, and the dominant constituent of meteorites. Its abundance is a direct consequence of its position at the binding-energy peak — easy to make, hard to destroy.

### Common misconceptions

- *"More mass means more binding."* No. More mass means more nucleons. The relevant quantity is binding energy *per nucleon*, which peaks at iron and falls off in either direction.
- *"Tunneling violates conservation of energy."* No. The alpha has the same total energy on either side of the barrier. The tunneling is a statement about where the particle is *found*, not a violation of energy conservation.
- *"The strong force is the same as the electromagnetic force."* They are completely different. Strong force is short-range ($< 2$ fm), attractive between all nucleons regardless of charge, and 100× stronger than electromagnetic at nuclear scales. Beyond a few fm, it's effectively zero.

↳ **Dig Deeper — Stellar nucleosynthesis: how every element heavier than helium was made**

*The binding-energy curve doesn't just explain why iron is special. It explains the *origin* of every element on Earth. Hydrogen and helium were made in the Big Bang. Everything else was forged in stars, by fusion up to iron, and by neutron capture (s-process and r-process) for elements heavier than iron.*

**Prompt:**
> Outline how the elements were made. (a) Big Bang nucleosynthesis: hydrogen, deuterium, helium-3, helium-4, and trace lithium-7 — produced in the first few minutes after the Big Bang. (b) Stellar fusion: H → He → C → O → ... → Fe in successive star generations. The CNO cycle and triple-alpha process. (c) The s-process (slow neutron capture in red giant stars) for heavier elements. (d) The r-process (rapid neutron capture in supernova explosions and neutron-star mergers) for the heaviest elements (uranium, plutonium, gold). End with one sentence on the recent (2017) detection of gravitational waves and electromagnetic counterparts from neutron-star merger GW170817, which confirmed neutron-star mergers as a major source of heavy elements.

**What to do with the output:** Save it. Stellar nucleosynthesis explains why your body is mostly hydrogen, oxygen, carbon, and nitrogen — the most abundant elements that fusion produces — and why gold, uranium, and plutonium are rare. Carl Sagan's famous "we are made of star stuff" is the literal physics of this concept.

---

## Synthesis — nuclei as quantum-mechanical bound systems

Step back. Three concepts in this chapter, all built on quantum mechanics applied to the strong-nuclear-force-bound system of protons and neutrons:

**Concept 1** identified the nucleus's components (protons, neutrons), the standard notation ($^A_Z X_N$), and the three modes of decay (alpha, beta, gamma) — each with characteristic energy, charge, and conservation behavior.

**Concept 2** introduced the radioactive-decay law $N(t) = N_0 e^{-\lambda t}$ and the half-life $t_{1/2} = \ln 2 / \lambda$, with applications to dating (carbon-14 for organic material, uranium-lead for rocks).

**Concept 3** explained the energy releases of nuclear processes via mass defect $\Delta m$ and binding energy $\text{BE} = \Delta m \cdot c^2$, with the binding-energy-per-nucleon curve peaking near iron-56 explaining why fusion (light nuclei) and fission (heavy nuclei) both release energy. Quantum tunneling explains how alpha particles escape Coulomb barriers larger than their classical energy.

The deepest single fact: **the energy scale of nuclear physics is millions of times the energy scale of atomic physics, because the binding energies per nucleon (~MeV) are millions of times the binding energies per electron (~eV).** The strong nuclear force is much stronger than the electromagnetic force at short range, and the resulting energy releases have powered every star in the universe and every nuclear weapon ever built.

### A worked example using all three concepts — the Sun

The Sun shines via the proton-proton chain, which net-converts 4 protons into 1 helium-4 nucleus plus 2 positrons plus 2 neutrinos plus 26.7 MeV of energy:

$$4 \, ^1\text{H} \to {^4\text{He}} + 2 e^+ + 2 \nu_e + 26.7 \text{ MeV}.$$

**Concept 3 — energy from mass defect.** The mass deficit:

$$\Delta m = 4 \times m(^1\text{H}) - m(^4\text{He}) - 2 m_e - \text{(neutrino mass, ~0)}.$$

Numerically: $\Delta m \approx 4.7 \times 10^{-29}$ kg per cycle. By $E = mc^2$, this is $\sim 26.7$ MeV per cycle.

**Concept 1 — nuclear reaction.** The chain proceeds by individual decays and captures, each obeying conservation of charge, mass number, and lepton number. The neutrinos escape the Sun freely (cross-section ~$10^{-44}$ cm²); the photons take ~100,000 years to diffuse out.

**Concept 2 — half-life of fuel.** The Sun contains $\sim 2 \times 10^{30}$ kg, mostly hydrogen. It converts $\sim 4 \times 10^9$ kg of mass to energy per second to maintain its luminosity. At this rate, it has enough hydrogen for about 10 billion years of main-sequence burning. The "half-life" of solar hydrogen-burning is on a similar scale. The Sun is currently about halfway through.

**Scale shift.** That same physics, scaled to terrestrial dimensions, runs every nuclear reactor on Earth. Replace fusion (light nuclei) with fission (heavy nuclei split via neutron capture), and the binding-energy-per-nucleon curve still tells you the energy release — typically $\sim 200$ MeV per fission of $^{235}$U. From the Sun's core to a Pennsylvania power plant to a 1945 weapon test, the same physics — quantum mechanics applied to nucleon binding — controls the outcomes.

---

## Exercises

### Warm-up

**31.1** *(LO 1)* What are the components of a nucleus? Define $Z$, $N$, $A$, and *isotope*.

**31.2** *(LO 2)* Write the alpha-decay equation for $^{226}$Ra. What is the daughter nucleus?

**31.3** *(LO 2)* Write the beta-minus decay equation for $^{60}$Co. What is the daughter nucleus?

**31.4** *(LO 3)* A sample contains $1.0 \times 10^{12}$ atoms of an isotope with half-life $5.0$ years. How many atoms remain after $20$ years?

### Application

**31.5** *(LO 3)* The half-life of $^{14}$C is $5730$ years. A sample of bone has $25\%$ of the C-14 of a living organism. Estimate its age.

**31.6** *(LO 4)* Compute the binding energy and binding energy per nucleon for $^{12}$C. Use $m(^{12}\text{C}) = 12.000000$ u (definition), $m(^1\text{H}) = 1.00794$ u, $m_n = 1.00867$ u.

**31.7** *(LO 2)* Uranium-238 alpha-decays to thorium-234. Using atomic masses 238.0508 u, 234.0436 u, 4.0026 u, compute the Q-value (energy released) in MeV.

**31.8** *(LO 5)* Explain in qualitative terms why alpha-decay half-lives can vary by 17 orders of magnitude when the corresponding alpha kinetic energies vary by only a factor of 2-3.

### Synthesis

**31.9** *(LO 3)* The activity of a $1.0$ g sample of $^{226}$Ra is $1.0$ Ci ($3.7 \times 10^{10}$ decays/s). Verify this corresponds to the standard half-life $t_{1/2} = 1600$ y, given that 1 g of $^{226}$Ra contains $2.66 \times 10^{21}$ atoms.

**31.10** *(LO 4)* Compute the energy released per fission of $^{235}$U if the daughter nuclei are $^{144}$Ba and $^{89}$Kr plus 3 free neutrons, with the following atomic masses: 235.04393 u, 143.92295 u, 88.91764 u, 1.00867 u (neutron). Express in MeV.

**31.11** *(LO 4)* The Sun's luminosity is $3.86 \times 10^{26}$ W. The proton-proton chain releases $\sim 26.7$ MeV per cycle (4 H → He). Estimate (a) the rate at which the Sun consumes hydrogen, (b) the total mass-to-energy conversion rate per second, (c) the Sun's expected main-sequence lifetime if it can use $\sim 10\%$ of its hydrogen.

### Challenge

**31.12** *(beyond chapter)* The carbon-14 dating of the Shroud of Turin (1988) gave a date of 1260-1390 AD with 95% confidence. (a) Compute the C-14/C-12 ratio that would correspond to a 1300-AD origin (vs. modern atmospheric ratio). (b) What percentage of the C-14 originally present has decayed? (c) If a competing claim were that the cloth dates to 33 AD (the supposed crucifixion date), what fraction of C-14 should remain? Compare to the measured value.

**31.13** *(beyond chapter)* The neutron has half-life $t_{1/2} \approx 10.2$ minutes when free, but neutrons in stable nuclei (like $^4$He, $^{16}$O) don't decay. Why? (Hint: think about the binding energy of the nucleus and what would happen if a neutron tried to convert to a proton — would the resulting daughter nucleus be more or less tightly bound?)

---

## LLM Exercise — Chapter 31: Radioactivity in Your Anchor Phenomenon

**Project:** Physics Reality Check Logbook
**What you're building this chapter:** A Logbook entry for nuclear physics. Most everyday phenomena involve no obvious radioactivity, but background radiation, GPS clock physics (Cs-137 and other isotopes), smoke detectors (Am-241), bananas (K-40), all touch nuclear physics. You can compute one quantitative property or write an "exception entry" identifying the nearest radioactive connection.
**Tool:** Claude Project.

### The Prompt

```
I'm continuing my Physics Reality Check Logbook for College Physics with LLMs. My anchor phenomenon is [paste your 1-sentence description].

For Chapter 31, I want to think about radioactivity and nuclear physics. Most everyday phenomena are not directly nuclear, but background radiation is everywhere (cosmic rays, K-40 in bananas, radon from soil, terrestrial gamma background).

Please:

1. Identify ONE nuclear or radioactivity aspect connected to my phenomenon. Examples: for a bike commute — cosmic-ray muons hitting me (Chapter 28!), terrestrial gamma background from soil, possible radon exposure in poorly ventilated areas, Am-241 in any smoke detectors I pass. For a coffee maker — K-40 in any banana I eat with my coffee (about 15 Bq per medium banana), trace radium in some heating elements, cosmic-ray background. For a basketball shot — K-40 in my own muscle tissue (~50 Bq/kg), cosmic-ray background. For a marathon — additional cosmic-ray exposure from longer outdoor time, possible commercial-flight exposure if I'm running a destination race.

2. Apply ONE chapter equation. Compute total radiation dose (multiply activity × time × energy per decay × biological factor), or estimate decay rate of a specific isotope at known concentration, or estimate half-life-derived activity.

3. Specify input numbers (look up the isotope's half-life, decay energy, and natural abundance).

4. Run the calculation. Report value with units.

5. One sanity check: does your computed dose agree with the typical natural-background dose of ~$0.1$ μSv/hour at sea level?

6. One sentence connecting this to Chapter 32 (medical applications of nuclear physics) — radiotherapy and medical imaging are next.

Save the output as logbook/chapter-31-radioactivity.md.
```

### What this produces

A Logbook entry connecting your phenomenon to natural radioactivity (which is everywhere) or to specific isotopes used in nearby technology.

### How to adapt this prompt

- *For phenomena indoors:* Radon is often the dominant exposure (especially in basements). Look up your local radon levels.
- *For phenomena involving travel:* Aircraft flight at $10$ km altitude increases cosmic-ray dose by ~$50\times$.
- *For ChatGPT/Gemini:* Identical with interface substitutions.

### Connection to previous chapters

Builds on Chapter 28 ($E = mc^2$ for binding energies) and Chapter 29 (quantum tunneling for alpha decay; photons for gamma rays).

### Preview of next chapter

Chapter 32 (medical applications of nuclear physics) shows how the principles of this chapter — specific isotopes, half-lives, decay modes — power X-ray imaging, CT scans, PET scans, MRI, radiotherapy, and radioisotope-based diagnostics.

---

## Chapter summary

A nucleus contains $Z$ protons and $N$ neutrons (total $A = Z + N$). Unstable nuclei decay by emitting alpha particles ($^4$He), beta particles (electrons or positrons via neutron-proton interconversion), or gamma rays (from nuclear de-excitation). Each decay conserves charge and mass number. The decay law $N(t) = N_0 e^{-\lambda t}$ with half-life $t_{1/2} = \ln 2 / \lambda$ describes the population of any radioactive sample, with half-lives ranging from $10^{-23}$ s to $10^{16}$ years. Nuclear binding energy comes from a mass defect: $\text{BE} = \Delta m \cdot c^2 \sim 8$ MeV per nucleon, peaking at iron-region nuclei. Quantum tunneling explains alpha decay despite the classical Coulomb-barrier impossibility.

The one idea that matters most: **nuclear energies are MeV, atomic energies are eV — a factor of a million.** This single energy-scale difference explains why the Sun shines, why nuclear weapons are so devastating, why a gram of nuclear fuel contains as much energy as a tonne of coal, and why nuclear waste remains hazardous for thousands of years.

The common mistake to watch for: **confusing different decay types or applying the wrong conservation law.** Always check that mass number $A$ and charge $Z$ balance on both sides of any decay equation.

What you should now be able to teach someone else: how the three modes of nuclear decay differ, how the radioactive decay law gives you the half-life, how mass-energy equivalence ($E = mc^2$) accounts for the millions-of-eV nuclear energy releases, and how the binding-energy-per-nucleon curve explains both nuclear fission and stellar fusion. If you can also explain how carbon-14 dating works, you've understood the practical core of this chapter.

---

## What would change my mind

The chapter argues that nuclear physics is essentially complete at the level of nucleon (proton + neutron) bound states governed by the strong nuclear force, with quantum mechanics determining decay rates and binding energies. The argument would need revision if (a) a precision experiment found nuclear binding energies deviating significantly from the standard mass-defect formula, or (b) decay rates were observed to depend on chemical environment, temperature, or pressure (they don't, to high precision; this was checked exhaustively). Nuclear physics is one of the most experimentally constrained areas of physics.

## Still puzzling

The deepest unresolved question this chapter touches on: **why do the proton and neutron masses have the values they do?** They differ by only $0.14\%$ (the neutron is heavier), yet that small difference is what makes free neutrons unstable while free protons are not. The proton's mass and the small p-n mass difference both depend on quark masses (Chapter 33) and the strong-force coupling constant — but why those have the values they do remains unexplained. If the mass difference were the other way, neutrons would be stable and protons would decay, and the universe would look completely different (no atoms beyond hydrogen).

---

## Connections forward

Chapter 32 (medical applications of nuclear physics) uses the principles of this chapter for diagnostic imaging (X-ray, CT, PET, SPECT) and therapy (gamma knife, brachytherapy, proton therapy). Chapter 33 (particle physics) breaks the proton and neutron into quarks bound by the strong force, and shows the standard model of fundamental interactions. Chapter 34 (frontiers) considers open questions — dark matter, the matter-antimatter asymmetry, the search for grand unification, and quantum gravity.

---

**Tags:** nuclear-physics, radioactivity, half-life, binding-energy, quantum-tunneling

---

## AI Wayback Machine

**Chien-Shiung Wu** disproved parity conservation in 1956 — designing the experiment that showed nature distinguishes left from right at the nuclear level. The Nobel went to her theorist colleagues Lee and Yang; she was passed over.

**Run this:**

```
Who was Chien-Shiung Wu, and how does her parity-violation experiment connect to the nuclear physics we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about her career or ideas.
```

→ Search **"Chien-Shiung Wu"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to walk through Wu's 1956 cobalt-60 experiment and what specifically violated parity.
- Ask it about Wu's role in the Manhattan Project and her later career at Columbia.

What changes? What gets better? What gets worse?
