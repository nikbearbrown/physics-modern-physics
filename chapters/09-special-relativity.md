# Chapter 9 — Special Relativity

**Suggested titles**

1. Special Relativity
2. Two Postulates and the End of Absolute Time
3. Cleveland, 1887: A Failed Experiment That Changed Everything

**TL;DR.** In 1905 Einstein proposed two postulates: (1) the laws of physics are the same in every inertial frame, and (2) the speed of light in vacuum is the same for every observer regardless of how the observer or the source is moving. These two innocent-looking statements logically force time dilation, length contraction, and the famous $E = mc^2$ — replacing Newton's mechanics, in the regime of high speeds, with a more fundamental theory in which space and time are interwoven. Classical mechanics survives as the low-velocity limit and remains essentially exact for everything you do under about 1% of the speed of light.

---

## A failed experiment in a basement, Cleveland, 1887

Albert Michelson and Edward Morley have spent two years setting up an interferometer in the basement of a dormitory at the Case School of Applied Science in Cleveland. The instrument floats on a slab of sandstone in a pool of mercury, isolated from vibration. Light from a sodium lamp is split into two perpendicular beams; each beam travels several meters down a long arm, bounces off a mirror, and returns. The two beams recombine and produce an interference pattern.

The experiment is designed to detect the speed of the Earth through the *luminiferous aether* — the invisible medium 19th-century physicists were certain must permeate space and carry light waves the way air carries sound. As Earth orbits the Sun at $30 \text{ km/s}$, it should be moving through the aether at varying speeds depending on the season. Light traveling parallel to Earth's motion through the aether should take a different amount of time than light traveling perpendicular. The interference pattern between the two beams should *shift* as Michelson and Morley rotate the apparatus through different orientations.

It doesn't shift. Not by anything detectable.

They expected a shift of about $0.4$ fringes. They detect, at best, $0.01$. They publish the null result in the *American Journal of Science* and conclude, cautiously, that they have not been able to detect Earth's motion through the aether. The next two decades produce a parade of attempted explanations — the Earth drags the local aether with it; the aether contracts moving objects to compensate; the apparatus is somehow defective. None of them survive scrutiny.

In June 1905, a 26-year-old patent clerk in Bern, Switzerland, named Albert Einstein submits a paper titled "*Zur Elektrodynamik bewegter Körper*" — "On the Electrodynamics of Moving Bodies." He cites essentially no experiments. He starts from two postulates. The first is unobjectionable: the laws of physics are the same in every inertial frame. The second is shocking: the speed of light in vacuum is the same for every observer, regardless of how the observer or the light's source is moving.

If you accept the second postulate, the Michelson-Morley null result is *automatic*. There is no aether to detect a motion against. The two beams take the same time around the apparatus regardless of orientation, because $c$ is the same for both. The experiment isn't failed — it's confirmation of a postulate Einstein took as foundational.

But the second postulate has consequences far beyond that one experiment. From it, Einstein derived that moving clocks run slow, that moving rulers shrink, that simultaneity is not absolute, that energy and mass are interconvertible — $E = mc^2$. None of this is intuitive. All of it has been confirmed to extraordinary precision in over a century of experiments, from cosmic-ray muons that survive longer than they should, to GPS satellites whose clocks must be corrected for relativistic effects, to the routine operation of every particle accelerator in the world.

This chapter is about what Einstein's two postulates force you to conclude. Classical mechanics is still right when speeds are slow compared to $c$ — that's why bridges stand and airplanes fly using Newton's laws. But at high speeds, Newton is wrong, and Einstein is right.

**Learning objectives.** By the end of this chapter you should be able to:

1. State Einstein's two postulates of special relativity and explain what an *inertial reference frame* is.
2. Apply time dilation $\Delta t = \gamma \Delta t_0$ and length contraction $L = L_0 / \gamma$ to compute observed times and lengths for fast-moving systems, where $\gamma = 1/\sqrt{1 - v^2/c^2}$.
3. Use the relativistic velocity addition formula $u = (v + u')/(1 + vu'/c^2)$ to combine velocities and verify that no combination of sub-light velocities exceeds $c$.
4. Compute relativistic momentum $p = \gamma m u$ and total energy $E = \gamma m c^2$, and recognize $E_0 = mc^2$ as the rest energy.
5. Identify the *correspondence principle* — that relativistic equations reduce to classical ones when $v \ll c$ — and use it to sanity-check any relativistic calculation.

**Prerequisites.** Chapter 24 (light as an EM wave at speed $c$). Chapters 2–8 (classical kinematics, Newton's laws, energy, momentum). Comfort with $\gamma$ as a function of $v/c$.

**Why this chapter matters.** This is the chapter where classical physics — the physics of cars and bridges and falling apples — meets its limit. Special relativity is not a "small correction" in any regime of physics that involves high speeds: particle accelerators (Chapter 33), GPS satellites, cosmic-ray showers, the internal physics of stars. It is also the conceptual bridge to Chapter 29 (quantum mechanics), Chapter 30 (atomic physics), and Chapter 33 (particle physics) — each of which uses relativistic kinematics routinely.

---

## Concept 1 — Two postulates, and the death of absolute time

### A train and a flash of light, 1905

Einstein loved *Gedankenexperimente* — thought experiments. Here's the classic one. Imagine a train moving at constant velocity along a straight track. Two flash lamps are mounted at the front and back of the train. An observer (call her Alice) stands on the train, exactly midway between the two lamps. Another observer (Bob) stands on the embankment beside the track. As Alice rides past Bob, both lamps flash. In Bob's frame, Bob sees the flashes as simultaneous — the lamps were equidistant from him at the moment they flashed (in his frame), and light from both reaches him at the same instant.

What about Alice? She is moving toward the front lamp's flash and away from the back lamp's flash, in Bob's frame. So in Bob's frame, the light from the front lamp reaches Alice *before* the light from the back lamp. But Alice is also at rest in *her own* frame — she is midway between the lamps in her own frame too. By Einstein's second postulate, light travels at $c$ in Alice's frame. So if light from the front lamp reaches her before light from the back, the only conclusion she can draw is that *the front lamp flashed first*. The two flashes were not simultaneous *in her frame*.

Two events that are simultaneous in one inertial frame are not simultaneous in another moving relative to the first. *Simultaneity is not absolute.*

This is the first surprise. Newton had assumed time was universal — a single river flowing at the same rate everywhere in the universe, the same for all observers. Einstein's two postulates make that assumption false. Different observers in relative motion disagree about which events are simultaneous, about how much time passes between events, and (Concept 2) about how long things are.

### The mechanism — Einstein's postulates and time dilation

**First postulate.** The laws of physics are the same in every inertial reference frame. (An *inertial* frame is one not accelerating and not rotating — a frame in which Newton's first law holds: an object at rest stays at rest unless acted on.)

**Second postulate.** The speed of light in vacuum, $c = 2.998 \times 10^8 \text{ m/s}$, is the same for every observer regardless of the relative motion of the source or the observer.

The first postulate is essentially Galilean — Galileo had already argued you cannot tell, from inside a smoothly moving ship, whether the ship is moving or at rest. The second is the radical new ingredient. From these two, all of special relativity follows.

**Time dilation.** Consider a clock built from a light pulse bouncing between two mirrors separated by distance $D$. The pulse leaves the bottom mirror, travels to the top, reflects, returns. In the clock's own rest frame, the round-trip time is

$$\Delta t_0 = \frac{2D}{c}.$$

This is the *proper time* — the time interval between two events measured by an observer at rest with respect to those events.

Now put the clock on a fast-moving spaceship and watch from outside. As the light pulse travels up and back, the ship moves sideways. The pulse traces a longer, zig-zag path in your (outside-observer) frame — a longer total distance, and since light travels at $c$ in your frame too (postulate 2), it must take *longer*. Working through the geometry of the right triangle whose legs are $D$ (vertical) and $v \Delta t / 2$ (horizontal) and whose hypotenuse is $c \Delta t / 2$:

$$\left( \frac{c \Delta t}{2} \right)^2 = D^2 + \left( \frac{v \Delta t}{2} \right)^2,$$

solving for $\Delta t$:

$$\Delta t = \frac{2D / c}{\sqrt{1 - v^2/c^2}} = \frac{\Delta t_0}{\sqrt{1 - v^2/c^2}}.$$

Define the *Lorentz factor*:

$$\boxed{\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}.}$$

Then time dilation is

$$\boxed{\Delta t = \gamma \, \Delta t_0.}$$

For $v = 0$, $\gamma = 1$ — no dilation, classical limit. For $v$ small compared to $c$, $\gamma \approx 1 + \tfrac{1}{2}(v/c)^2$ — dilation is microscopic. For $v$ approaching $c$, $\gamma$ blows up — time effectively stops for the moving clock as observed from outside.

A moving clock runs slow, by a factor of $\gamma$.

### The trade-off

The relativistic description trades **intuition about absolute time for consistency with the speed of light.** Newton's universal time is the comfortable, intuitive picture. Einstein's relative time is forced on us by the requirement that $c$ be the same in every frame. The cost is that we have to rebuild our intuition. The benefit is a theory that correctly predicts every experiment ever done with high-speed particles, satellites in motion, and matter at relativistic energies.

### Worked example — muons surviving a 10-km journey

Cosmic-ray muons are created in the upper atmosphere when high-energy cosmic rays strike air molecules — typically at altitudes of about $10 \text{ km}$. Muons are unstable particles with a *proper* lifetime (in their own rest frame) of $\tau_0 = 2.20 \text{ }\mu\text{s}$. After this time, statistically, they decay into electrons and neutrinos.

If muons traveled at the speed of light (impossible, but as an upper bound), they would cover

$$d = c \tau_0 = (3.00 \times 10^8)(2.20 \times 10^{-6}) \approx 660 \text{ m}.$$

Far less than $10 \text{ km}$. So classically, almost no muons should survive the journey from upper atmosphere to ground level. But experimentally, lots of them do. About $1 \text{ muon/cm}^2/\text{minute}$ rains down on Earth's surface.

The resolution is time dilation. Muons created in the upper atmosphere travel at speeds like $v = 0.999c$. Their Lorentz factor is

$$\gamma = \frac{1}{\sqrt{1 - 0.999^2}} \approx 22.4.$$

In Earth's frame, the muon's lifetime is

$$\tau = \gamma \tau_0 = 22.4 \times 2.20 \text{ }\mu\text{s} \approx 49.3 \text{ }\mu\text{s}.$$

In that time, the muon travels

$$d = v \tau \approx (0.999 \times 3 \times 10^8)(49.3 \times 10^{-6}) \approx 14.8 \text{ km}.$$

Now $10 \text{ km}$ is well within reach. The muon makes it to the ground because, from our perspective on the ground, its internal clock is running slow.

(In the muon's own frame, it does not live longer — its lifetime is still $2.20 \text{ }\mu\text{s}$. But in its frame, the *distance* from upper atmosphere to ground is contracted by the same factor $\gamma$, so the journey is short enough to complete before decay. Both observers agree the muon reaches the ground; they disagree about *why*. Concept 2 makes this length contraction explicit.)

**Sanity check.** Muon survival was first quantitatively measured in 1941 (Rossi and Hall on Mount Washington in New Hampshire — comparing the muon flux at altitude vs. sea level). The experiment confirmed time dilation to within a few percent, and is still done routinely in undergraduate physics labs today.

### Common misconceptions

- *"Time dilation is an illusion — clocks just appear to run slow."* No. Every physical process — radioactive decay, biological aging, atomic vibration, the ticks of a quartz watch — is subject to time dilation. The slow-running is real and measurable. (For GPS satellites in orbit, the clocks must be corrected by about $38 \text{ }\mu\text{s/day}$ to account for combined special- and general-relativistic effects. Without correction, GPS positions would drift by kilometers within hours.)
- *"Relativity says everything is relative."* No — only inertial-frame quantities like time interval, length, and simultaneity are frame-dependent. The speed of light $c$, the spacetime interval, the rest mass of a particle, and the laws of physics themselves are *invariant* — the same in every frame. The name "relativity" is misleading; "invariance theory" would be closer.

↳ **Dig Deeper — The twin paradox and what makes it not a paradox**

*The chapter mentions that moving clocks run slow. The twin paradox asks: if Alice rockets to a distant star at high speed and returns while Bob stays home, who has aged less? Both Alice (in her frame) and Bob (in his frame) saw the other's clock running slow during the journey — so they should both be younger than each other when Alice returns? The resolution is that one of them (Alice) accelerated to turn around, breaking the symmetry between the frames.*

**Prompt:**
> Walk me through the twin paradox carefully. Set up the scenario: Alice rockets to a star 4 light-years away at $0.8c$, turns around, returns. Bob stays on Earth. (a) Compute the round-trip time in Earth's frame and in Alice's frame. (b) Compute the age difference between the twins when Alice returns. (c) Resolve the apparent paradox by explaining what happens during Alice's acceleration phase — why the symmetry between the two observers is broken, and why Alice ages less even though "both saw the other's clock running slow during the constant-velocity legs." End with one sentence on whether this prediction has been verified experimentally (atomic clocks on commercial flights, Hafele-Keating 1971).

**What to do with the output:** Save it. The twin paradox is the iconic puzzle of special relativity and the cleanest test of whether you've actually understood time dilation rather than just memorized the equation.

---

## Concept 2 — Length contraction and the impossibility of $v > c$

### The same muon, in its own frame

Pick the muon up from the previous section. In Earth's frame, it travels $10 \text{ km}$ from the upper atmosphere to the ground in $49 \text{ }\mu\text{s}$. In its own frame, it lives for only $2.2 \text{ }\mu\text{s}$ — a hard biological fact about how long a muon exists before decay. How does the muon, in its own frame, complete the journey?

The answer is *length contraction*. In the muon's frame, the Earth and atmosphere are racing toward it at $0.999c$. The distance from the upper atmosphere to the ground is not $10 \text{ km}$ in the muon's frame; it is contracted by the same factor $\gamma$:

$$L = \frac{L_0}{\gamma} = \frac{10 \text{ km}}{22.4} \approx 0.45 \text{ km}.$$

In the muon's frame, the ground is only $450 \text{ m}$ away when the muon is created — and it's racing toward the muon at almost the speed of light. The muon traverses this contracted distance in

$$t = \frac{0.45 \text{ km}}{0.999 c} \approx 1.5 \text{ }\mu\text{s},$$

less than its own proper lifetime. It survives. Both observers (Earth and muon) agree the muon reaches the ground; they disagree about the explanation. Earth says the muon's clock ran slow; the muon says the distance was short.

This is the second great surprise of special relativity. Lengths along the direction of motion contract by the same factor $\gamma$ that dilates time intervals.

### The mechanism — length contraction

The *proper length* $L_0$ is the length of an object measured in its own rest frame. An observer moving at velocity $v$ relative to the object measures a length

$$\boxed{L = L_0 \sqrt{1 - v^2/c^2} = \frac{L_0}{\gamma}.}$$

For $v \ll c$, $\gamma \approx 1$ and $L \approx L_0$ — no contraction, classical. For $v$ approaching $c$, $L \to 0$ — extreme contraction.

A meter stick moving past you at $0.99c$ has $\gamma \approx 7.1$, so it appears contracted to about $14 \text{ cm}$ in your frame. (Note: I'm being careful with the word "appears" — *measured* length, not visually perceived appearance. Visual perception involves additional optical effects from finite light travel time.)

### Velocity addition

If special relativity forced length contraction and time dilation, what does it say about velocities? In Newton's mechanics, velocities add as ordinary vectors: a ball thrown forward at $5 \text{ m/s}$ from a train moving at $30 \text{ m/s}$ has a velocity of $35 \text{ m/s}$ relative to the ground. But what if the "ball" is a flash of light emitted forward from a spaceship? By postulate 2, the flash moves at $c$ in *both* the ship's frame and the ground frame — not $c + v_{\text{ship}}$.

The Newtonian addition rule must be wrong at high speeds. The correct relativistic rule, derivable from the postulates:

$$\boxed{u = \frac{v + u'}{1 + vu'/c^2},}$$

where $u'$ is the velocity of an object in one frame, $v$ is the relative velocity between two frames, and $u$ is the velocity of the object in the second frame. For $u'$ and $v$ both small compared to $c$, the denominator is essentially 1 and you recover the classical $u = v + u'$. But for $u' = c$ (light emitted forward), the formula gives $u = (v + c)/(1 + v/c) = c$ regardless of $v$. The speed of light is preserved.

It also shows that no combination of sub-$c$ velocities can produce a result above $c$. Two ships moving toward each other at $0.9c$ each (relative to a third frame) approach each other at velocity

$$u = \frac{0.9c + 0.9c}{1 + (0.9)(0.9)} = \frac{1.8c}{1.81} \approx 0.994c,$$

not $1.8c$. The speed-of-light limit is not a special boundary — it's an absolute upper limit on the relative velocity of any two material objects.

### The trade-off

Relativistic kinematics trades **intuitive Galilean addition for $c$ as universal speed limit.** The cost: velocities don't add the way you think they do; lengths and times depend on observer. The benefit: the equations are consistent with every measured behavior of fast particles, from cosmic rays to LHC collisions.

### Worked example — alpha Centauri trip with $\gamma = 30$

Alpha Centauri, the nearest star system to ours, is $4.30$ light-years from Earth (as measured by an Earth-bound observer). An astronaut travels there at a speed corresponding to $\gamma = 30.0$.

**(a) How far is Alpha Centauri in the astronaut's frame?**

The astronaut sees the Earth-Alpha-Centauri distance contracted:

$$L = \frac{L_0}{\gamma} = \frac{4.30 \text{ ly}}{30.0} = 0.143 \text{ ly}.$$

Almost negligible. From her perspective, she's not crossing 4.3 light-years — she's crossing 0.14 light-years.

**(b) What is her velocity in $c$?**

Solve $\gamma = 1/\sqrt{1 - v^2/c^2}$ for $v$:

$$1 - v^2/c^2 = 1/\gamma^2 = 1/900,$$

$$v^2/c^2 = 899/900 \approx 0.99889,$$

$$v/c = \sqrt{0.99889} \approx 0.99944.$$

The astronaut is moving at about $0.9994c$.

**Sanity check.** At $0.9994c$, the trip in Earth's frame takes $4.30 / 0.9994 \approx 4.30$ years. In the astronaut's frame, the trip takes $4.30 / 30.0 \approx 0.14$ years $\approx 53$ days. The astronaut ages 53 days; Earth ages 4.3 years.

### Common misconceptions

- *"Length contraction means the object physically shrinks."* The object's proper length in its own frame is unchanged. What changes is the *measured* length in another frame. Different observers in relative motion measure different lengths for the same object — none of which is "the real" length. There is no preferred frame.
- *"Two objects can approach each other at $1.8c$."* Their relative velocity, computed in either of their own frames, never exceeds $c$. The classical addition formula gives nonsense at high speeds.

↳ **Dig Deeper — The cosmic speed limit and tachyons**

*Special relativity forbids any massive object from reaching $c$ (it would take infinite energy). It also forbids accelerating from below $c$ to above $c$ in any continuous process. But what about hypothetical particles that always travel faster than $c$? These are called tachyons, and they have appeared in serious theoretical proposals. They have never been observed.*

**Prompt:**
> Explain why special relativity forbids massive particles from reaching the speed of light $c$, by computing the kinetic energy required as a particle's velocity approaches $c$. Then explain the concept of tachyons — hypothetical particles that always travel faster than $c$ — and why their existence would create severe causality problems (they could send signals into the past). End with one sentence on the experimental status of tachyon searches and why most physicists are skeptical they exist.

**What to do with the output:** Save it. The cosmic speed limit is one of the most testable predictions of relativity, and a constant temptation for science fiction (warp drives, hyperspace) to violate.

---

## Concept 3 — Energy, momentum, and $E = mc^2$

### The nuclear reactor at Chicago Pile-1, December 2, 1942

In a rackets court underneath the abandoned football stands at the University of Chicago, Enrico Fermi has assembled a 28-foot-high pile of uranium and graphite blocks — Chicago Pile-1, the world's first artificial nuclear reactor. At 3:36 PM on December 2, 1942, he gives the order to withdraw the control rods. For the first time in history, a controlled, self-sustaining nuclear chain reaction is established. The pile generates about half a watt of power for several minutes.

The reaction works because uranium-235, when struck by a neutron, splits into two lighter nuclei plus 2-3 free neutrons plus a release of energy. The total *mass* of the fission products is *less* than the mass of the original uranium nucleus plus its incoming neutron. The missing mass shows up as kinetic energy of the products — and it is a *lot* of kinetic energy. The relationship is Einstein's:

$$E = m c^2.$$

For a single uranium-235 fission, the mass deficit is about $0.1\%$ of the nucleus's rest mass — about $200 \text{ MeV}$ of energy released per fission. A gram of uranium-235 contains $\sim 2.6 \times 10^{21}$ atoms; if all of them fissioned, the energy released would be roughly $8 \times 10^{10} \text{ J}$, equivalent to burning about $2{,}500$ tonnes of coal. The energy density of nuclear fuel is, by mass, about ten million times greater than chemical fuel. That ratio is what made nuclear weapons possible and what makes nuclear power plants possible.

The equation $E = mc^2$ — derived by Einstein in 1907, two years after the special-relativity papers — is not just a piece of physics history. It is the operating principle behind every nuclear reactor on Earth, every star in the sky (which fuses hydrogen into helium and converts a fraction of a percent of mass to energy), and every particle accelerator (which uses electric fields to convert energy to mass, creating new particles).

### The mechanism — relativistic momentum and energy

**Relativistic momentum.** Newton's $p = mu$ doesn't work at high speeds (it would let you accelerate to $c$ with finite force). The correct definition:

$$\boxed{p = \gamma m u,}$$

where $m$ is the *rest mass* (the mass measured in the object's own frame), $u$ is the velocity, and $\gamma = 1/\sqrt{1 - u^2/c^2}$. As $u \to c$, $\gamma \to \infty$, and so does $p$ — meaning it would take infinite force/energy to accelerate any massive object to $c$.

For low velocities ($u \ll c$), $\gamma \approx 1$ and $p \approx mu$ — Newton.

(Some older textbooks call $\gamma m$ the "relativistic mass" and treat the moving object as having a velocity-dependent mass. This convention is now discouraged; mass is just rest mass, and the velocity dependence belongs in the momentum equation. The misconception alert in the OpenStax source flags this clearly.)

**Total energy.** The total energy of a particle (rest energy plus kinetic energy) is

$$\boxed{E = \gamma m c^2.}$$

When $u = 0$, $\gamma = 1$, and the particle has *rest energy*

$$\boxed{E_0 = m c^2.}$$

This is Einstein's most famous equation, and the physical content of it is staggering. A particle at rest still has energy by virtue of its mass alone. A 1-gram object has rest energy

$$E_0 = (10^{-3} \text{ kg})(3 \times 10^8 \text{ m/s})^2 = 9 \times 10^{13} \text{ J},$$

equivalent to about $20 \text{ kilotons}$ of TNT. (Hiroshima was about $15 \text{ kilotons}$.) Mass, in this picture, is just one form of energy — a remarkably concentrated one.

**Relativistic kinetic energy.** Kinetic energy is total energy minus rest energy:

$$KE = E - E_0 = (\gamma - 1) m c^2.$$

For $u \ll c$, expand $\gamma = (1 - u^2/c^2)^{-1/2} \approx 1 + \tfrac{1}{2}(u/c)^2 + \ldots$, giving $KE \approx \tfrac{1}{2} m u^2$ — the classical formula. So Newton's $\tfrac{1}{2} m v^2$ is the low-velocity limit of Einstein's $(\gamma - 1) m c^2$.

### The energy-momentum relation

A useful identity, derivable from the definitions, is

$$E^2 = (pc)^2 + (mc^2)^2.$$

For a massless particle ($m = 0$), this reduces to $E = pc$ — energy proportional to momentum. *Photons*, the quantum particles of light (Chapter 29), are massless and obey this relation: $E = pc$. They have momentum without mass. This is part of how a photon can exert pressure on a surface (radiation pressure), how solar sails could propel spacecraft, and how laser cooling works.

### The trade-off

Relativistic energy and momentum trade **simple Newtonian forms for consistency at all velocities.** The cost: more complicated formulas, the strange notion that mass equals energy, the requirement to track $\gamma$ carefully. The benefit: a description that correctly predicts every collision experiment ever done at high energy (LHC, fusion reactor cross-sections, particle decay rates, atomic mass defects, the energy output of the Sun).

### Worked example — momentum of a fast electron

An electron travels at $u = 0.985c$. The electron's rest mass is $m = 9.11 \times 10^{-31} \text{ kg}$. Find its momentum.

Compute $\gamma$:

$$\gamma = \frac{1}{\sqrt{1 - 0.985^2}} = \frac{1}{\sqrt{1 - 0.970}} = \frac{1}{\sqrt{0.030}} \approx 5.78.$$

Compute momentum:

$$p = \gamma m u = (5.78)(9.11 \times 10^{-31})(0.985 \times 3.00 \times 10^8) \approx 1.56 \times 10^{-21} \text{ kg} \cdot \text{m/s}.$$

For comparison, the *classical* momentum at this velocity would be $p_{\text{classical}} = m u = (9.11 \times 10^{-31})(0.985 \times 3 \times 10^8) = 2.69 \times 10^{-22} \text{ kg} \cdot \text{m/s}$ — about a factor of 5.8 smaller. The relativistic correction is enormous at $0.985c$.

**Sanity check.** Inside an electron accelerator (e.g., SLAC's linear accelerator), electrons can reach $\gamma$ values in the tens of thousands. Their momenta are correspondingly huge despite their tiny rest mass. The bending of high-$\gamma$ electrons in magnetic fields agrees precisely with $p = \gamma m u$ — confirmed routinely in every accelerator on Earth.

### Common misconceptions

- *"Mass increases with velocity."* No — rest mass is invariant. What grows with velocity is *momentum* and *energy*, via the factor $\gamma$. The "relativistic mass" terminology is now considered misleading.
- *"$E = mc^2$ only applies to nuclear reactions."* It applies to *every* form of mass-energy conversion. A heated cup of coffee weighs measurably more than a cold one (in principle — the effect is too tiny to measure). A spinning flywheel weighs more than a stationary one. Mass is just one form of energy, and energy of any kind contributes to mass.

↳ **Dig Deeper — Why $E^2 = (pc)^2 + (mc^2)^2$ is the most useful relativistic formula**

*The energy-momentum relation $E^2 = (pc)^2 + (mc^2)^2$ is not just an algebraic curiosity. It is invariant — the same in every inertial frame — even though $E$ and $p$ separately are not. It also reveals immediately that massless particles ($m = 0$) must always travel at $c$: setting $m = 0$ gives $E = pc$, and using $E = \gamma m c^2$ and $p = \gamma m v$ shows $v = c$.*

**Prompt:**
> Walk me through three uses of the relation $E^2 = (pc)^2 + (mc^2)^2$. (1) Derive that massless particles (like photons) travel at exactly $c$. (2) Compute the momentum of a $1 \text{ MeV}$ photon (use $E = pc$). (3) Show that $E^2 - (pc)^2$ is the same in every inertial frame, while $E$ and $p$ separately are not — meaning $m^2 c^4$ is a Lorentz invariant (a quantity all observers agree on). End with one sentence on why this invariant is crucial in particle physics for identifying particles from collision-product trajectories.

**What to do with the output:** Save it. This relation is the workhorse of all relativistic kinematics in particle physics, and one of the most beautiful invariance relationships in physics.

---

## Synthesis — the postulates and their inevitable consequences

Step back. Two postulates, taken seriously, force a rewriting of mechanics. Time isn't absolute (Concept 1). Length isn't absolute (Concept 2). Velocities don't add the simple way you thought (Concept 2). Mass and energy are interchangeable (Concept 3). The speed of light is an absolute limit on the relative velocity of any two material objects.

The chapter's three concepts braid: **Concept 1** introduced the postulates and showed how the second one (constant $c$) immediately forces time dilation. **Concept 2** showed that the same physics forces length contraction along the direction of motion and modifies velocity addition so $c$ cannot be exceeded. **Concept 3** rewrote momentum and energy to be consistent with the postulates, producing $p = \gamma m u$, $E = \gamma m c^2$, and the now-iconic $E_0 = m c^2$.

The deepest single fact: **classical mechanics is right where speeds are small compared to $c$, and wrong where they aren't.** Newton's laws are not "wrong" in the sense of being demonstrably useless — bridges built with them stand, satellites launched with them orbit. They are the low-velocity limit of a more general theory. This is the *correspondence principle*: any new theory must reproduce the predictions of the old theory in the regime where the old theory was accurate. Relativity does this; quantum mechanics will too in Chapter 29.

### A worked example using all three concepts — a particle at the LHC

A proton at the Large Hadron Collider (CERN) is accelerated to a kinetic energy of $7 \text{ TeV} = 7 \times 10^{12} \text{ eV} = 1.12 \times 10^{-6} \text{ J}$. The proton's rest energy is $E_0 = m_p c^2 = 938 \text{ MeV} \approx 1.50 \times 10^{-10} \text{ J}$.

**Concept 3 — total energy and $\gamma$.** Total energy is $E = E_0 + KE \approx 7 \text{ TeV}$ (kinetic energy dominates massively). Then

$$\gamma = E / E_0 = (7 \times 10^{12}) / (938 \times 10^6) \approx 7460.$$

The proton's Lorentz factor is about $7460$.

**Concept 2 — speed and length contraction.** Solve $\gamma = 1/\sqrt{1 - u^2/c^2}$ for $u$:

$$1 - u^2/c^2 = 1/\gamma^2 \approx 1.8 \times 10^{-8},$$

$$u/c = \sqrt{1 - 1.8 \times 10^{-8}} \approx 1 - 9 \times 10^{-9}.$$

The proton travels at approximately $c$ minus 9 parts per billion. The LHC ring is $27 \text{ km}$ in circumference; in the proton's frame, this is contracted to $27 / 7460 \text{ km} \approx 3.6 \text{ m}$.

**Concept 1 — time dilation.** A proton makes one circuit of the ring in $27 \text{ km} / c \approx 9 \times 10^{-5} \text{ s}$ in the lab frame. In the proton's frame, this same circuit takes $9 \times 10^{-5} / 7460 \approx 1.2 \times 10^{-8} \text{ s}$ — about 12 nanoseconds, the time for light to cross 3.6 m.

Both observers (proton and lab) agree the proton makes one full circuit. They disagree on how long it took and how long the ring is.

**Scale shift.** That same physics, in the regime of GPS satellites, requires clock corrections of $\sim 38 \text{ }\mu\text{s/day}$ to maintain meter-level positioning accuracy. In the regime of muons in cosmic-ray showers, it explains why $10$-km-deep mountains see a measurable muon flux. In the regime of supernovae, it produces the relativistic jets observed by gamma-ray telescopes. From microsatellites to particle accelerators to the violent end-states of stars, special relativity is operating.

---

## Exercises

### Warm-up

**28.1** *(LO 1)* State Einstein's two postulates of special relativity in one sentence each. Identify which one was the radical departure from 19th-century physics.

**28.2** *(LO 2)* A clock moves at $0.6c$ relative to you. Compute $\gamma$. Compute the elapsed time in your frame for a process the clock measures as $1.0 \text{ s}$ in its own frame.

**28.3** *(LO 2)* A meter stick moves past you at $0.8c$ along its length. What length do you measure?

**28.4** *(LO 4)* Compute the rest energy of an electron in joules and in MeV. ($m_e = 9.11 \times 10^{-31} \text{ kg}$.)

### Application

**28.5** *(LO 2)* A spaceship traveling at $0.95c$ relative to Earth makes a 4.3-light-year journey to Alpha Centauri. Find (a) the trip time in Earth's frame, (b) the trip time in the ship's frame, (c) the distance to Alpha Centauri in the ship's frame.

**28.6** *(LO 3)* Two spaceships approach each other, each moving at $0.7c$ relative to a station. Find their relative velocity using the relativistic velocity addition formula. Compare to the classical (incorrect) result.

**28.7** *(LO 4)* A proton has rest energy $938 \text{ MeV}$. If it has total energy $1500 \text{ MeV}$, find (a) its kinetic energy, (b) $\gamma$, (c) its velocity in $c$.

**28.8** *(LO 2)* A muon created in the upper atmosphere has $\gamma = 10$. (a) Find its proper lifetime if its observed lifetime in Earth's frame is $22 \text{ }\mu\text{s}$. (b) Find the distance it travels (in Earth's frame) at $\sim c$.

### Synthesis

**28.9** *(LO 2, LO 3)* In the Hafele-Keating experiment of 1971, atomic clocks were flown around the world on commercial airliners and compared to clocks left at the U.S. Naval Observatory. The observed time differences were a few hundred nanoseconds. Estimate the special-relativistic (time dilation) contribution for a $40$-hour eastbound flight at $250 \text{ m/s}$, and compare to the actual measured value of $\sim -59 \text{ ns}$. (You'll find a small discrepancy because the experiment also includes general-relativistic effects from altitude.)

**28.10** *(LO 4)* The Sun's power output is $L_\odot = 3.86 \times 10^{26} \text{ W}$. Compute the rate at which the Sun loses mass via $E = mc^2$. Express in kg/s and in solar masses per billion years (the Sun's mass is $1.989 \times 10^{30} \text{ kg}$).

**28.11** *(LO 1, LO 5)* The classical formula $KE = \tfrac{1}{2} m u^2$ is the low-velocity limit of $KE = (\gamma - 1) m c^2$. (a) Derive the limit by Taylor-expanding $\gamma$ for small $u/c$. (b) For what speed (in km/s) does the classical formula err by 1% (i.e., the relativistic correction is 1%)?

### Challenge

**28.12** *(beyond chapter)* The twin paradox in detail: Alice rockets to a star $L_0 = 8 \text{ ly}$ away at $v = 0.8c$, immediately turns around, and returns. Bob stays on Earth. (a) Compute the round-trip time in Earth's frame. (b) Compute Alice's age gain over the trip in her frame. (c) Compute Bob's age gain. (d) Explain qualitatively why Bob ages more, even though "during each constant-velocity leg, Alice and Bob each saw the other's clock running slow." (Hint: the asymmetry is in Alice's acceleration phases.)

**28.13** *(beyond chapter)* GPS satellites orbit at altitude $\sim 20{,}200 \text{ km}$ at speed $\sim 3870 \text{ m/s}$ relative to Earth's center. (a) Compute the special-relativistic time dilation effect on the satellite's clock per day (clock runs slow). (b) Look up — with sources you can verify — the general-relativistic gravitational effect (clock runs faster at altitude). (c) The net effect is about $+38 \text{ }\mu\text{s/day}$ (clock runs faster). Without this correction, GPS positions would drift by how many meters per day? (Hint: $c \times 38 \text{ }\mu\text{s}$.)

---

## LLM Exercise — Chapter 28: Special Relativity in Your Anchor Phenomenon

**Project:** Physics Reality Check Logbook
**What you're building this chapter:** A Logbook entry for special relativity. *Note:* most everyday phenomena involve speeds far below $c$, so relativistic effects are tiny. You have two options: (a) compute the (microscopic) relativistic correction to your phenomenon, or (b) write an "exception entry" explaining why this chapter doesn't apply directly and identifying the most distant connection.
**Tool:** Claude Project.

### The Prompt

```
I'm continuing my Physics Reality Check Logbook for College Physics with LLMs. My anchor phenomenon is [paste your 1-sentence description].

For Chapter 28, I want to think about special relativity. Most everyday phenomena are non-relativistic, so the direct effects are negligible. I want to choose between two options:

Option A — compute the (tiny) relativistic correction to my phenomenon. For a bike commute at ~5 m/s: time dilation is unimaginably small. For an espresso machine pumping water at a few m/s: same. I'd compute γ, find that γ - 1 ~ 10^(-16), and report that classical physics is essentially exact.

Option B — find the most distant connection. For a bike commute: my GPS uses relativistic corrections (~38 μs/day for the satellites). For a coffee maker: the precision atomic clocks underlying GPS rely on relativistic atomic-physics calculations. For a basketball shot: the lights overhead are filaments emitting EM radiation, and Einstein's photoelectric explanation (Chapter 29) was awarded the same year as his special-relativity papers. For a marathon: the GPS watch I wear depends on relativistic clock corrections in its satellites.

Please:

1. Identify which option fits better for my phenomenon, and explain why.

2. If Option A: compute the relativistic correction (γ - 1) to whatever quantity is most relevant. Report with units. This will likely be a very small number — that's the point.

3. If Option B: identify the most distant relativistic connection (likely GPS satellite clock corrections) and explain how it indirectly impacts my phenomenon.

4. Either way: write one sentence on what would happen if relativity were "off" — what specific failures would occur in technology I use.

5. One sentence connecting this to Chapter 29 (quantum mechanics) — the next chapter takes EM radiation and reveals it has discrete photon structure.

Save the output as logbook/chapter-28-relativity.md.
```

### What this produces

A Logbook entry that either quantifies the (tiny) relativistic effect on your phenomenon or honestly admits the chapter is an exception and identifies the indirect technology link.

### How to adapt this prompt

- *For phenomena with no relativistic content:* Option B almost always reveals a GPS/atomic-clock link.
- *For phenomena involving fast-moving particles:* If you happen to be analyzing cosmic rays, particle accelerators, or astrophysics, Option A is fully applicable.
- *For ChatGPT/Gemini:* Identical with interface substitutions.

### Connection to previous chapters

Builds on Chapter 24 (the speed of light $c$ as electromagnetic wave speed). Uses Chapter 1's discipline of significant figures and uncertainty.

### Preview of next chapter

Chapter 29 (quantum mechanics) introduces the photon and shows that classical wave optics (Chapter 27) cannot fully explain the photoelectric effect. The 1905 paper that won Einstein the 1921 Nobel Prize was on the photoelectric effect, not relativity.

---

## Chapter summary

Special relativity (Einstein, 1905) replaces Newton's mechanics in the regime of high speeds. Two postulates: the laws of physics are the same in every inertial frame, and the speed of light $c$ is the same for every observer. From these follow time dilation ($\Delta t = \gamma \Delta t_0$), length contraction ($L = L_0 / \gamma$), the impossibility of any massive object reaching $c$, the relativistic momentum $p = \gamma m u$, the total energy $E = \gamma m c^2$, the rest energy $E_0 = m c^2$, and the relation $E^2 = (pc)^2 + (mc^2)^2$. Classical mechanics survives as the $v \ll c$ limit and remains essentially exact for everyday phenomena.

The one idea that matters most: **simultaneity, length, and time interval are all frame-dependent. The speed of light, the laws of physics, and the rest mass of a particle are not.** What is invariant — the same in every frame — is what the new physics insists you focus on.

The common mistake to watch for: **applying relativistic equations where they don't matter, or refusing to apply them where they do.** A car at $30 \text{ m/s}$ has $\gamma \approx 1 + 5 \times 10^{-15}$ — relativistic corrections are utterly negligible. A muon at $0.99c$ has $\gamma \approx 7$ — relativity is the dominant effect. Use the correspondence principle to know which regime you're in.

What you should now be able to teach someone else: why moving clocks run slow, why moving rulers shrink, why no massive object can reach the speed of light, and what $E = mc^2$ physically means (mass is one form of energy and can be converted to other forms in nuclear processes). If you can also explain the muon-survival experiment in a single paragraph — invoking either time dilation (Earth frame) or length contraction (muon frame) and showing both observers agree the muon reaches the ground — you've understood this chapter.

---

## What would change my mind

The chapter argues that special relativity is the correct theory of mechanics for inertial frames at all speeds, and that it has been verified to extraordinary precision. The argument would need revision if a precision experiment found (a) a deviation from $\gamma$-scaling of time dilation or length contraction, (b) the existence of a preferred reference frame for the speed of light, or (c) a way to accelerate a massive object continuously to $v = c$ or beyond. None of these has been observed despite a century of high-precision tests.

## Still puzzling

The deepest unresolved question this chapter raises: **why does light have a finite, universal speed at all, and why does it have the particular value it does?** Maxwell's equations give $c = 1/\sqrt{\mu_0 \varepsilon_0}$, but the values of $\mu_0$ and $\varepsilon_0$ are themselves unexplained at a deeper level. In some sense, $c$ is built into the geometry of spacetime; general relativity (Einstein's 1915 extension to non-inertial frames and gravity) makes this explicit but still doesn't derive $c$ from a deeper principle. Some quantum-gravity programs aim to derive $c$ from more fundamental quantities; none has yet succeeded.

---

## Connections forward

Chapter 29 (quantum mechanics) introduces the photon, the photoelectric effect, and wave-particle duality — completing the modernization of physics that special relativity began. Chapter 30 (atomic physics) uses relativistic energy-mass equivalence to interpret the binding energies of atoms. Chapter 31 (radioactivity) builds entirely on $E = mc^2$ to explain how nuclear decays release the energies they do. Chapter 33 (particle physics) uses relativistic kinematics ($E^2 = (pc)^2 + (mc^2)^2$) routinely to identify particles from their tracks in detectors. Chapter 34 (frontiers) returns to general relativity — the gravity-and-acceleration extension — and to current attempts to merge it with quantum mechanics.

---

**Tags:** special-relativity, time-dilation, length-contraction, $E=mc^2$, Michelson-Morley

---

## AI Wayback Machine

**Hendrik Lorentz** developed the Lorentz transformation in 1904 — the equations relating measurements between observers in relative motion. Einstein's 1905 special relativity used Lorentz's mathematics with a different interpretation: not a real ether contraction, but a property of spacetime itself.

**Run this:**

```
Who was Hendrik Lorentz, and how does his transformation connect to special relativity we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about his career or ideas.
```

→ Search **"Hendrik Lorentz"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to compare Lorentz's 1904 interpretation of his equations with Einstein's 1905 interpretation — what changed?
- Ask it about Lorentz's role chairing the Solvay Conferences that brought together quantum-era physicists.

What changes? What gets better? What gets worse?
