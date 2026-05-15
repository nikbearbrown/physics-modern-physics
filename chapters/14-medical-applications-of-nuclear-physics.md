# Chapter 14 — Medical Applications of Nuclear Physics

**Suggested titles**

1. Medical Applications of Nuclear Physics
2. From Bone Scan to Gamma Knife: When Nuclear Physics Saves Lives
3. Hevesy's Hot Lunch and the Birth of Nuclear Medicine

**TL;DR.** Nuclear physics underwrites a substantial fraction of modern medicine: gamma-emitting tracers reveal organ function (SPECT and PET imaging); X-rays and CT scans map structure; targeted radiation kills cancers; even MRI is an applied quantum-mechanical effect on hydrogen nuclei. The chapter unpacks the radiation units (becquerel, gray, sievert), the relative biological effectiveness of different particle types, and the way each technique trades off resolution, dose, and biological insight.

---

## Budapest, 1913: a graduate student tags his lunch

George de Hevesy is twenty-eight, a Hungarian chemist working on his postdoctoral research in Vienna. He suspects his landlady is recycling the previous week's leftover meat into the hash she serves him. He has no proof. He has, however, just been working with radium-D — what we now call lead-210, a beta emitter with a long half-life. He acquires a small quantity, sprinkles it onto his hash one Sunday evening, leaves the rest of his portion on the plate, and asks his landlady to take it back.

The following Wednesday, she serves him hash. He brings out an electroscope (the only radiation detector readily available in 1913). The electroscope discharges. The radium-D is in the new dish.

The landlady is caught. The episode would be a footnote — except that de Hevesy realizes, sitting at his table in 1913, that he has demonstrated something profound: a radioactive isotope behaves chemically like its non-radioactive partners and follows the same biological pathways, but its presence and concentration can be detected anywhere with a radiation counter. *Tag a substance with a radioactive isotope, and you can track that substance through any chemical or biological process you like.*

Hevesy spent the rest of his career working out the implications. He won the 1943 Nobel Prize in Chemistry for "his work on the use of isotopes as tracers in the study of chemical processes." That same idea — radioactive tracers in living systems — became the foundation of nuclear medicine. By the 1960s, doctors could image organs in the body by injecting tagged compounds and detecting the emitted gamma rays. By the 1980s, positron emission tomography (PET) could map metabolic activity at submillimeter resolution. By the 2010s, targeted radioisotope therapies were curing cancers that surgery and chemotherapy could not.

This chapter is about how nuclear physics — alpha, beta, gamma, half-life, binding energy from Chapter 31 — gets put to work in medical diagnosis and therapy. It's also about the quantitative units used to measure radiation dose, since the difference between a healing dose and a fatal one can be a factor of a few.

**Learning objectives.** By the end of this chapter you should be able to:

1. Identify the principal medical-imaging modalities that use nuclear physics (X-ray, CT, MRI, gamma camera/SPECT, PET) and describe what physical signal each detects.
2. Define and convert between the principal radiation units: activity (Bq, Ci), absorbed dose (Gy = J/kg, rad), and equivalent dose (Sv, rem) using the relative biological effectiveness (RBE) of different particles.
3. Explain how radioactive tracers (radiopharmaceuticals) are used for diagnostic imaging — what isotopes are chosen, why, and how the localization of the tracer reveals function (e.g., $^{99m}$Tc for bone scans, $^{18}$F-FDG for PET metabolic imaging, $^{131}$I for thyroid).
4. Describe radiation therapy — external beam (X-ray, $^{60}$Co gamma, proton beam) and internal (brachytherapy seeds, radiopharmaceuticals) — and explain the *therapeutic ratio* and how it constrains dose planning.
5. Estimate biological dose for a given exposure scenario (activity, time, tissue type) and connect it to the lifetime cancer risk via the linear no-threshold model (with appropriate caveats about the model's limits).

**Prerequisites.** Chapter 30 (atomic structure, X-rays, characteristic spectra). Chapter 31 (radioactivity, alpha/beta/gamma decay, half-life, $E = mc^2$ for binding energies). Chapter 24 (electromagnetic spectrum, intensity).

**Why this chapter matters.** Nearly every modern medical workup involves at least one nuclear-physics-based imaging or treatment technique. CT scans alone account for ~$70$ million procedures per year in the US. PET-CT imaging has revolutionized cancer diagnosis and staging. Targeted radiotherapy now cures many cancers that were uniformly fatal a generation ago. Understanding both the diagnostic power and the dose risks is part of being a literate citizen in a modern medical system.

---

## Concept 1 — Imaging: structure, function, and the tools that distinguish them

### A bone scan, today

A patient swallows or is injected with a small dose of technetium-99m bound to a bone-seeking compound (typically methylene diphosphonate, MDP). The Tc-99m has a half-life of 6.0 hours and emits a 140-keV gamma ray when it decays — ideal for medical imaging because the gamma is energetic enough to escape the body but not so energetic that it deposits excessive dose. The compound concentrates in regions of active bone metabolism — places where new bone is being laid down. That happens at fracture sites, around tumors, and at sites of infection.

A few hours after injection, the patient lies under a *gamma camera* — a large flat detector that records each gamma ray's arrival position. The image, accumulated over a few minutes per body region, shows the patient's skeleton highlighted in places where the tracer has concentrated. A radiologist looking at the image can spot, with high sensitivity, fractures invisible to X-ray, metastatic cancer that has spread to bone, infections deep in the skeleton.

Compare this to a chest X-ray. The X-ray is a *transmission* image: external X-rays from a tube pass through the body and are differentially absorbed by tissues of different density. Bone (high atomic number) absorbs more than soft tissue, which absorbs more than air. The image is a 2D shadow of the 3D body. It reveals *structure* — broken ribs, lung tumors that have changed local density, foreign objects.

Now compare both to PET. The patient is injected with $^{18}$F-FDG (fluorodeoxyglucose) — a glucose analog labeled with fluorine-18 ($t_{1/2}$ = 110 min). Cells that take up glucose preferentially (most cancer cells, most active brain regions) accumulate the FDG. The fluorine-18 decays by positron emission. Each emitted positron travels a few millimeters before annihilating with an electron, producing two 511-keV gamma rays moving in exactly opposite directions. A ring of detectors around the patient records *coincident* gamma pairs and uses the line connecting them to localize each annihilation event. The reconstructed 3D image shows where glucose is being consumed — *function*, not structure.

Three completely different windows into the body, three different physical signals, three different things you can see. Choosing the right tool for the question is half the art of medical imaging.

### The mechanism — what each modality detects

**X-ray and CT.** Differential X-ray absorption ($\mu = \mu(Z, \rho, E)$, where $\mu$ is the linear attenuation coefficient that depends on atomic number, density, and X-ray energy). High-density and high-Z tissues (bone, calcified deposits, contrast agents) absorb more X-rays. CT (computed tomography) takes hundreds of X-ray images from different angles and reconstructs a 3D image computationally. Resolution is excellent (sub-millimeter). Dose is meaningful (a chest CT delivers ~7 mSv, roughly 2-3 years' worth of natural background).

**MRI.** Radio-frequency excitation of hydrogen-nucleus spin in a strong magnetic field. The signal depends on local proton density (mostly water) and the local relaxation times $T_1$ and $T_2$ (which depend on the chemical environment). MRI is excellent for soft tissue contrast, doesn't use ionizing radiation, but is slow, expensive, and excludes patients with metallic implants. The physics underlying MRI uses Chapter 22 (magnetic fields) and Chapter 30 (atomic energy levels via the spin-magnetic-field interaction).

**Gamma camera / SPECT.** Detection of gammas from injected tracers. SPECT (single-photon emission computed tomography) is the 3D version using a rotating gamma camera. Resolution is moderate (~1 cm), but reveals metabolic and functional information no structural imaging can show.

**PET.** Detection of coincident gamma pairs from positron-electron annihilations. Uses positron-emitting isotopes ($^{18}$F most commonly; also $^{11}$C, $^{15}$O, $^{13}$N). Resolution is better than SPECT (~5 mm), and the technique is highly quantitative — the reconstructed image is proportional to the local concentration of tracer.

### The trade-off

Imaging modalities trade **anatomical resolution against functional information.** CT gives you the highest-resolution structural image but no functional information. PET gives you metabolic function but at lower spatial resolution. MRI offers both modest structure and some functional information (with specialized techniques like fMRI for brain function). Modern *hybrid* imaging — PET-CT, PET-MRI — fuses structure and function in one scan, becoming the standard for cancer staging and many other diagnostic questions.

### Worked example — a brain PET scan with $^{18}$F-FDG

A patient is given $10$ mCi of $^{18}$F-FDG ($t_{1/2}$ = 110 min). The fluorine-18 emits a 0.633-MeV positron at end-point energy (average energy ~250 keV before annihilation), and each decay ultimately produces two 511-keV gammas.

**Activity.** $10$ mCi $= 10 \times 3.7 \times 10^7$ Bq $= 3.7 \times 10^8$ decays/sec.

**Time-integrated dose during the scan.** Suppose the patient is imaged for 30 minutes starting 30 minutes after injection. By 30 minutes after injection, the activity has dropped by a factor of $e^{-\lambda t}$ with $\lambda = \ln 2 / 110 = 0.0063$ min$^{-1}$, so $A(30) = A_0 \cdot e^{-0.189} \approx 0.83 A_0$. The remaining isotope continues decaying during imaging and after.

**Total decays during the patient's body retention** (effectively $\sim$ a few half-lives, after which the patient excretes the rest):

$$N_{\text{decays}} = A_0 \cdot \tau$$

where $\tau = t_{1/2} / \ln 2 \approx 159$ min is the average lifetime. So $N_{\text{decays}} \approx 3.7 \times 10^8 \times 159 \times 60 \approx 3.5 \times 10^{12}$ decays.

**Energy deposited (rough estimate).** Each decay deposits about $0.25$ MeV (positron energy) locally before annihilation. The two 511-keV gammas largely escape the body. So energy deposited:

$$E \approx 3.5 \times 10^{12} \times 0.25 \text{ MeV} \times 1.6 \times 10^{-13} \text{ J/MeV} \approx 0.14 \text{ J}.$$

For a 70-kg patient, this is

$$D = E/m = 0.14/70 = 2.0 \times 10^{-3} \text{ J/kg} = 2.0 \text{ mGy}.$$

The effective whole-body dose for a typical FDG-PET scan is about 7-10 mSv (Sv accounts for biological effectiveness, with X-rays and gammas having $w_R = 1$). Our estimate is in the ballpark.

**Sanity check.** Annual natural background radiation in the US is ~3.0 mSv. A single PET scan delivers about 2-3 years' worth of background. Justified for cancer diagnosis or treatment monitoring; not for routine screening.

### Common misconceptions

- *"Imaging modalities are interchangeable."* Each detects a different physical signal and is good for different things. Pneumonia: chest X-ray. Brain tumor with edema: MRI. Whole-body cancer staging: PET-CT. Bone metastasis: bone scan with Tc-99m. The choice matters.
- *"All imaging uses ionizing radiation."* MRI and ultrasound do not. Both have other limitations (cost, resolution, exclusions) but no radiation dose.

↳ **Dig Deeper — How MRI works at the level of nuclear spin**

*The chapter mentions that MRI works by exciting hydrogen-nucleus spin in a magnetic field. The full physics is a beautiful synthesis of quantum mechanics (nuclear spin, Larmor precession), classical electrodynamics (radio-frequency pulses), and engineering (magnetic-field gradients for spatial encoding). It's also a counterexample to the belief that all medical imaging uses radioactivity.*

**Prompt:**
> Explain how MRI works at the level of nuclear spin. (a) Describe the alignment of hydrogen-1 nuclear spins (protons in water) in a strong external magnetic field $B_0$ (typically 1.5-3 T in clinical scanners). (b) Explain the Larmor precession at frequency $f = \gamma B_0 / (2\pi)$, with $\gamma$ the gyromagnetic ratio of the proton ($\gamma/(2\pi) = 42.58$ MHz/T). (c) Describe how a transverse RF pulse at the Larmor frequency tips the spins out of alignment, then how the relaxation back ($T_1, T_2$) emits a measurable RF signal. (d) Explain how magnetic-field gradients encode spatial location into the precession frequency. End with one sentence on why MRI is so good for soft tissue contrast (different tissues have different $T_1$ and $T_2$ from different water environments).

**What to do with the output:** Save it. MRI is one of the most beautiful applications of quantum mechanics in everyday medicine, and a great example of how an arcane physical principle becomes routine clinical practice.

---

## Concept 2 — Radiation dose: counting energy, weighting biology

### A radiation worker's badge

A worker at a nuclear medicine clinic wears a small badge clipped to their lab coat. The badge contains film, thermoluminescent crystals, or a chip-based dosimeter. Once a month, the badge is collected and read; the worker's accumulated radiation dose for the period is recorded. If their cumulative annual dose exceeds 50 mSv (the U.S. occupational limit), they are pulled from radiation work for the remainder of the year. If it exceeds 100 mSv (5-year average above 20 mSv/year limit), they may be permanently restricted.

The badge is reading *equivalent dose* in millisieverts. To understand what that number actually means — to compare it to the dose from a chest X-ray, or to background, or to a chemotherapy treatment — you need to understand the chain of units that convert raw decays to biological impact.

### The mechanism — three chains of units

**Activity.** How many decays per unit time in your sample.
- 1 becquerel (Bq) = 1 decay per second.
- 1 curie (Ci) = $3.7 \times 10^{10}$ Bq (the activity of 1 g of $^{226}$Ra).

**Absorbed dose.** Energy deposited per unit mass of tissue.
- 1 gray (Gy) = 1 J/kg.
- 1 rad = 0.01 J/kg = 0.01 Gy. (Older non-SI unit, still used in clinical practice.)

A given activity over a given time deposits a dose that depends on the geometry and stopping properties of tissue — a complicated calculation that nuclear medicine physicists do for each procedure.

**Equivalent dose.** Absorbed dose weighted by the biological effectiveness of the radiation type. Different particles deposit energy in different patterns, and a 1-Gy dose of alpha particles damages tissue much more than 1 Gy of X-rays. The *relative biological effectiveness* (RBE), or the closely related *radiation weighting factor* $w_R$, quantifies this.

| Radiation type | $w_R$ |
|---|---|
| X-rays, gamma rays | 1 |
| Beta particles, electrons | 1 |
| Thermal neutrons | 5-10 |
| Fast neutrons | 10-20 |
| Alpha particles | 20 |
| Heavy nuclei | 20+ |

- 1 sievert (Sv) = 1 Gy × $w_R$.
- 1 rem = 1 rad × $w_R$ = 0.01 Sv.

Why do alphas damage so much more per Gy? Because alphas are heavy and slow at the same kinetic energy as electrons. They deposit their energy in dense, concentrated tracks that overlap many DNA strands within a single cell, creating clustered double-strand breaks that are difficult for the cell to repair. Beta and gamma radiation deposits energy in sparse, isolated ionizations that the cell can usually handle.

**Effective dose** further weights equivalent dose by tissue type — some organs (gonads, bone marrow, lung, colon) are more sensitive than others (skin, bone surface). Effective dose is in Sv too, but accounts for the specific organs hit.

### Reference dose levels

| Source | Effective dose |
|---|---|
| Cosmic-ray + terrestrial background, US average | ~3.0 mSv/year |
| Chest X-ray | ~0.1 mSv |
| Chest CT | ~7 mSv |
| Whole-body PET-CT | ~14 mSv |
| Abdominal CT with contrast | ~10 mSv |
| Mammogram | ~0.4 mSv |
| Single dental X-ray | ~0.005 mSv |
| Acute lethal dose (no medical care) | ~5 Sv (LD50 ~ 4-5 Sv at 30 days) |
| Annual occupational limit (US) | 50 mSv |

Background radiation is dominated by radon ($^{222}$Rn from soil) at ~2 mSv/year on average and by cosmic rays at ~0.3 mSv/year (more at altitude — mountain dwellers and frequent flyers get 2-3× more).

### The trade-off

Radiation dosing trades **diagnostic information against cancer risk.** A typical CT scan is estimated to increase lifetime cancer risk by ~$0.05$%. For an indication where the imaging will change clinical management (suspected stroke, suspected appendicitis), this is well worth it. For routine screening of asymptomatic patients, the risk-benefit balance is harder. There is ongoing debate in medicine about appropriate use of CT and PET, especially in pediatric patients (whose growing tissues are more sensitive).

### Worked example — equivalent dose from an alpha source

A worker is exposed to alpha particles depositing $0.50$ Gy of absorbed dose to the lung. What is the equivalent dose?

Equivalent dose = absorbed dose × $w_R$:

$$H = D \times w_R = 0.50 \text{ Gy} \times 20 = 10 \text{ Sv}.$$

This is a substantial dose — about 200× the annual occupational limit and into the range of acute radiation syndrome. Alpha particles in the lung are particularly dangerous because they're stopped by a few cells and deposit all their energy locally, with high RBE. Inhaled radon daughters (alpha-emitters) are the second-leading cause of lung cancer in the U.S. after smoking.

**Sanity check.** Compare to gamma radiation: a 0.50-Gy dose of gamma rays would give $H = 0.5$ Sv — still substantial but 20× less than the alpha case. This is why alphas (and inhaled or ingested alpha emitters) are dangerous in ways gammas are not.

### Common misconceptions

- *"All radiation is equally dangerous per unit energy."* No. Per unit absorbed dose (Gy), alphas are 20× more biologically effective than gammas. The unit Sv accounts for this.
- *"One CT scan will cause cancer."* The risk per scan is small (~$0.05\%$ lifetime) compared to the baseline cancer risk (~$40\%$). A single scan when medically indicated is a clear net benefit. Repeated unnecessary scans are not.
- *"Background radiation is everywhere; therefore radiation is harmless."* Background dose averages ~3 mSv/year; high-altitude or radon-prone areas push that to ~5-10 mSv/year. The lifetime risk from background is small but not zero. Above background, the linear no-threshold model assumes additional risk scales linearly with dose, with the assumption (debated at very low doses) that there's no safe threshold.

↳ **Dig Deeper — The linear no-threshold model and its critics**

*The chapter uses the LNT (linear no-threshold) model implicitly. Below ~100 mSv, the data are not strong enough to confirm or refute LNT. Some scientists argue for a threshold; others argue for hormesis (low doses being beneficial). The debate has real policy implications.*

**Prompt:**
> Explain the linear no-threshold (LNT) model of radiation risk and its critics. (a) State the LNT assumption: cancer risk is linearly proportional to dose, with no threshold. (b) Summarize the main evidence for LNT (Hiroshima/Nagasaki survivor data above ~50-100 mSv). (c) Summarize the main critics: hormesis (very low doses may be beneficial), threshold (no risk below some level), and arguments from cellular DNA-repair mechanisms. (d) Explain why LNT is widely used in regulation despite uncertainty (precautionary principle, lack of strong contradictory data). End with one sentence on why this matters for nuclear-medicine practice and radiation protection.

**What to do with the output:** Save it. The LNT debate is one of the few places in physics where the science directly drives public-health policy (radiation regulation, nuclear-medicine guidelines, allowable occupational exposures), and the underlying epidemiology is genuinely uncertain at low doses.

---

## Concept 3 — Therapy: killing cancer with the same physics that diagnoses it

### A gamma knife treatment, today

A patient with a brain tumor is fitted with a stereotactic frame — a metal halo bolted to the skull for sub-millimeter positioning accuracy. They are placed inside a *Leksell Gamma Knife*, a hemispherical helmet containing 192 cobalt-60 sources arranged in a precise geometric pattern. Each source emits gammas (1.17 and 1.33 MeV from $^{60}$Co decay). Each individual beam is too weak to damage tissue. But all 192 beams converge on one point — the tumor — where the combined dose is intense enough to destroy the targeted tissue.

The treatment lasts an hour or so. The patient walks out the same day. There is no incision. The targeting is exquisite — sub-millimeter accuracy. The technique is used for brain tumors, AVMs, trigeminal neuralgia, and other conditions where precision matters and the target is small.

This is *radiation therapy* — using ionizing radiation to kill cancer or other unwanted tissue. The principle is the same as in diagnostic imaging (deposit energy in tissue) but the dose is millions of times higher and the goal is destruction, not measurement. The challenge is to deposit enough dose to kill the tumor while limiting dose to surrounding healthy tissue. The ratio of tumor cell kill to normal cell kill is the *therapeutic ratio*, and every radiation-therapy technique is engineered to maximize it.

### The mechanism — targeting and dose modulation

**External beam radiation therapy (EBRT).** A beam of high-energy X-rays, gammas, or charged particles is aimed at the tumor from outside the body. To spare normal tissue, the beam is rotated through multiple angles (intensity-modulated radiation therapy, IMRT) so the cumulative dose at any normal point is small but the cumulative dose at the tumor (where the beams cross) is high. Modern linear accelerators (LINACs) produce 6-25 MV X-rays via bremsstrahlung from electrons accelerated to those energies and slammed into a tungsten target.

**Brachytherapy.** Small radioactive sources (seeds) are implanted directly inside or adjacent to the tumor, delivering high local dose. Common isotopes: $^{125}$I ($t_{1/2}$ = 60 d), $^{103}$Pd ($t_{1/2}$ = 17 d), $^{192}$Ir ($t_{1/2}$ = 74 d). Used for prostate, cervical, breast, and other cancers. The seeds either remain (low-dose-rate, LDR) or are removed after delivering their dose (high-dose-rate, HDR).

**Targeted radiopharmaceuticals.** A radioisotope is chemically attached to a molecule that selectively binds to cancer cells. Examples: $^{131}$I for thyroid cancer (the thyroid concentrates iodine), $^{223}$Ra for bone-metastatic prostate cancer (radium-223 is a calcium analog that goes to bone). Newer agents target specific tumor receptors with antibody-conjugated isotopes.

**Particle therapy.** Beams of protons or carbon ions instead of X-rays. Charged particles have a sharp *Bragg peak* — they deposit most of their energy at a specific depth determined by their initial energy, with much less dose in front of and almost none behind the peak. This produces excellent depth-dose conformity, sparing tissue beyond the tumor. Proton therapy is increasingly used for pediatric cancers, brain tumors, and tumors near critical structures. Carbon-ion therapy is even more selective but available at only a handful of centers worldwide due to cost.

### The Bragg peak

The Bragg peak — the depth at which a charged-particle beam deposits maximum energy — is the central physical advantage of particle therapy. As a fast charged particle moves through tissue, it loses energy gradually via ionizations (Bethe-Bloch formula); the rate of energy loss increases as the particle slows down (because slower particles spend more time in any given region of tissue). Just before the particle stops, it deposits a sharp peak of energy. By choosing the initial energy, the therapy planner places the Bragg peak exactly at the tumor depth.

Compare to a megavoltage X-ray beam, which deposits maximum dose near the surface and falls off exponentially with depth. To treat a deep tumor with X-rays, you have to overdose the tissue in front. With protons, you don't.

### The trade-off

Radiotherapy trades **dose to tumor against dose to normal tissue (the therapeutic ratio).** The cost: every treatment damages some normal tissue, which limits how much dose you can deliver and may cause acute or late side effects. The benefit: many cancers — Hodgkin's lymphoma, early-stage breast cancer, prostate cancer, brain tumors, head-and-neck cancers, many others — have high cure rates with radiation therapy, often without requiring surgery or chemotherapy.

### Worked example — total dose for a typical cancer treatment

A patient with prostate cancer receives external-beam radiotherapy at 200 cGy ($= 2$ Gy) per fraction, 5 days per week for 8 weeks. Total dose:

$$D_{\text{total}} = 2 \text{ Gy} \times 5 \times 8 = 80 \text{ Gy}.$$

(Modern protocols vary; some use higher dose per fraction, fewer fractions — *hypofractionation*.)

For comparison:
- Whole-body acute lethal dose: ~5 Gy.
- This treatment: 80 Gy *to the prostate*, with much smaller doses to surrounding tissue (modulated by IMRT geometry).

The reason 80 Gy is survivable is that it's *highly localized* to the prostate. Surrounding normal tissue receives much less. The therapeutic ratio is what makes this work.

**Sanity check.** Standard definitive prostate-radiation protocols use total doses of 70-80 Gy in 35-44 daily fractions, with 5-year cure rates >90% for low-risk disease. The numbers are well-established clinical practice.

### Common misconceptions

- *"Radiation therapy makes you radioactive."* No. External-beam radiation passes through and is absorbed; the patient does not become a radiation source afterward. Brachytherapy does temporarily make the patient slightly radioactive (until the implanted source decays or is removed), but external beam does not.
- *"Only cancer cells are affected."* All cells in the radiation field are damaged. Cancer cells are typically more sensitive (they reproduce more, and rapid replication is when DNA damage causes problems). Selectivity comes from geometry (focusing dose on the tumor) and from biological differences (cancer cells less able to repair).

↳ **Dig Deeper — The Bragg peak and the case for proton therapy**

*The chapter mentions proton therapy as a way to put dose precisely at the tumor depth. The full physics — the Bethe-Bloch energy-loss formula and the resulting Bragg peak — explains both the technique's promise and its current limitations (high cost, limited availability, debated cost-effectiveness for many adult cancers).*

**Prompt:**
> Explain the physics of the Bragg peak in proton therapy. (a) Describe the Bethe-Bloch formula for energy loss of a charged particle in matter: $-dE/dx \propto Z^2 / v^2$ (where Z is the particle charge and v is its velocity). Explain why slowing particles deposit more energy per unit length. (b) Compare the depth-dose curve of protons (sharp Bragg peak at a depth determined by initial energy, near-zero dose beyond) to megavoltage X-rays (maximum dose near the surface, exponential falloff with depth). (c) Briefly cover the case for proton therapy: pediatric cancers, brain tumors near critical structures, situations where sparing tissue behind the tumor matters most. (d) Briefly cover the controversy: high cost ($100M+ to build a proton facility), limited evidence of clinical benefit over advanced X-ray techniques (IMRT, VMAT) for many adult cancers. End with one sentence on the future of proton therapy in oncology.

**What to do with the output:** Save it. Proton therapy is one of the active frontiers in radiation oncology, and a good case study in how a clear physics advantage may or may not translate into proportionate clinical benefit.

---

## Synthesis — nuclear physics in service of medicine

Step back. Three concepts in this chapter, all built from Chapter 31's nuclear physics applied to specific medical problems:

**Concept 1** introduced the major imaging modalities — X-ray and CT (transmission of external radiation), MRI (radio-frequency response of nuclear spins in a magnetic field), gamma camera and SPECT (detection of gammas from internal tracers), PET (coincident gamma detection from positron-electron annihilation). Each detects a different physical signal and reveals different information.

**Concept 2** quantified radiation dose: activity (Bq), absorbed dose (Gy), equivalent dose (Sv) with biological weighting factors. Reference doses (mSv to Sv) for various procedures and exposures put medical doses in context with natural background and occupational limits.

**Concept 3** described radiation therapy: external-beam (X-ray, gamma, proton), brachytherapy (implanted seeds), and targeted radiopharmaceutical therapy. The therapeutic ratio (tumor kill vs. normal tissue kill) is the central engineering challenge, and physical techniques — IMRT, the Bragg peak of proton therapy, gamma-knife geometry — exist to maximize it.

The deepest single fact: **the same physics — ionizing radiation depositing energy in tissue — both diagnoses and treats. The dose makes the difference.** A bone scan delivers 5-10 mSv (small risk, useful diagnostic). A prostate-cancer radiotherapy course delivers 80 Gy *to the prostate* (definitive treatment, highly localized). Same fundamental interactions; six orders of magnitude difference in dose.

### A worked example using all three concepts — a thyroid-cancer treatment plan

A patient is diagnosed with differentiated thyroid cancer. Their treatment plan involves three nuclear-medicine steps:

**Concept 1 — diagnosis with a Tc-99m scan.** Initial workup includes a thyroid scan with $^{99m}$Tc-pertechnetate. The Tc concentrates in the thyroid (and salivary glands). The gamma camera shows the thyroid's activity distribution; cancerous nodules appear as "cold" (less uptake) or rarely "hot" (more uptake) regions. Activity: ~5-10 mCi. Effective dose: ~3-5 mSv.

**Concept 1 + 3 — confirmation with PET.** $^{18}$F-FDG PET-CT confirms the metabolic activity and detects any metastases. Activity ~10 mCi, effective dose ~7 mSv. The PET-CT may identify lymph nodes or other sites that need to be addressed.

**Concept 3 — surgery + radioactive iodine therapy.** After surgical removal of the thyroid, the patient receives $^{131}$I (iodine-131; $t_{1/2}$ = 8 days; emits both beta particles for therapy and gamma rays for imaging). The dose is therapeutic — typically 100-200 mCi (3.7-7.4 GBq) — orders of magnitude higher than any diagnostic dose. The beta particles have range ~1-2 mm in tissue, so they kill any remaining thyroid tissue (including residual cancer cells that take up iodine) without significantly damaging surrounding structures. The gammas allow post-treatment imaging to confirm uptake.

**Concept 2 — dose assessment.** The patient's bone marrow dose during treatment is carefully tracked (limit: ~2 Gy to bone marrow over the course of treatment). The patient is briefly hospitalized in a shielded room because they are temporarily radioactive (gamma emission from the I-131 in their thyroid bed) and could expose family members at home.

**Outcome.** Differentiated thyroid cancer has 5-year survival rates >95% with this approach. The combination of surgery + radioactive iodine is the gold standard.

**Scale shift.** That same use of $^{131}$I for diagnosis and treatment was pioneered in the late 1940s by Saul Hertz at Massachusetts General Hospital. Modern nuclear medicine uses dozens of different radioisotopes for specific cancer types, each chosen for its half-life, decay mode, and chemical pathway in the body. The principles set by Hevesy in 1913 — radioactive tracking of biological molecules — remain unchanged.

---

## Exercises

### Warm-up

**32.1** *(LO 1)* Match each imaging modality to the physical signal it detects: (a) CT scan, (b) MRI, (c) PET, (d) bone scan with $^{99m}$Tc, (e) chest X-ray. Pick from: X-ray transmission; gamma emission from injected tracer; coincident gamma pairs from positron-electron annihilation; radio-frequency response from nuclear spin precession.

**32.2** *(LO 2)* Convert: (a) 5.0 mCi to Bq, (b) 2.5 Gy to rad, (c) 10 mSv to rem, (d) 0.5 Gy of alpha radiation to Sv (use $w_R = 20$).

**32.3** *(LO 3)* List two radiopharmaceuticals used for diagnostic imaging and one used for therapy. For each, state which organ or condition it targets.

**32.4** *(LO 4)* What are the three principal external-beam radiotherapy modalities? Briefly describe one technical advantage of proton therapy over X-ray therapy.

### Application

**32.5** *(LO 1)* Why is $^{99m}$Tc the most widely used isotope for nuclear-medicine imaging? Consider its half-life (6 h), gamma energy (140 keV), production from $^{99}$Mo generators, and biological behavior of the various technetium compounds.

**32.6** *(LO 2)* A patient receives a CT abdominal scan delivering 10 mSv. Compare this to (a) annual U.S. background radiation, (b) a single chest X-ray, (c) a transatlantic flight (estimated 0.05 mSv).

**32.7** *(LO 5)* Estimate the increased lifetime cancer risk from a single 10-mSv CT scan, using the linear no-threshold model with risk coefficient ~$5 \times 10^{-5}$ per mSv. Compare to baseline U.S. lifetime cancer risk of ~40%.

**32.8** *(LO 3)* Explain why the iodine isotope used for thyroid *imaging* ($^{123}$I, t1/2 = 13 h, gamma-only) differs from the one used for thyroid *therapy* ($^{131}$I, t1/2 = 8 d, beta + gamma). What property makes each suitable for its purpose?

### Synthesis

**32.9** *(LO 2, LO 5)* A radiation worker accidentally ingests $1 \times 10^7$ Bq of an alpha emitter that lodges in her lung. Each alpha deposits 5 MeV in surrounding lung tissue (assume 50 g of lung receives the dose). Estimate (a) the absorbed dose in Gy if all alphas decay within the lung over a year, (b) the equivalent dose in Sv. Comment on the result vs. occupational limits.

**32.10** *(LO 3, LO 4)* A patient with a 2-cm brain tumor is treated with the Gamma Knife (192 sources of $^{60}$Co, each emitting 1.17 and 1.33 MeV gammas). (a) Why are 192 separate beams used rather than one strong beam? (b) Why is $^{60}$Co (rather than, say, $^{137}$Cs or $^{99m}$Tc) chosen as the isotope? Hint: consider gamma energy, half-life, and availability.

**32.11** *(LO 1, LO 3)* A breast cancer patient undergoes (i) a mammogram (X-ray), (ii) a follow-up biopsy (no radiation), (iii) PET-CT for staging ($^{18}$F-FDG), (iv) a sentinel lymph node biopsy with $^{99m}$Tc colloid (gamma probe). For each of (i), (iii), (iv), state the imaging modality, what it reveals, and approximate effective dose.

### Challenge

**32.12** *(beyond chapter)* Why are children's radiation doses from CT scans more concerning than adults', for the same scan? Consider (a) more remaining lifetime for cancer to develop, (b) tissue radiosensitivity in growing tissue, (c) anatomical scaling (a fixed scanning protocol delivers more dose per unit body mass to a smaller patient).

**32.13** *(beyond chapter)* The natural background dose averages ~3 mSv/year in the US, dominated by radon ($^{222}$Rn from soil). Find and report the typical radon level in a basement and what that translates to in mSv/year. How does this compare to the dose from one CT scan?

---

## LLM Exercise — Chapter 32: Medical Nuclear Physics in Your Anchor Phenomenon

**Project:** Physics Reality Check Logbook
**What you're building this chapter:** A Logbook entry for medical nuclear physics. Most everyday phenomena don't involve direct medical imaging, but you can compute the radiation dose from imaging procedures you've had, or from natural sources connected to your phenomenon, or from the imaging modalities used to diagnose conditions related to your phenomenon (e.g., a runner's stress-fracture scan).
**Tool:** Claude Project.

### The Prompt

```
I'm continuing my Physics Reality Check Logbook for College Physics with LLMs. My anchor phenomenon is [paste your 1-sentence description].

For Chapter 32, I want to apply medical-nuclear-physics — imaging, dose, therapy — to my phenomenon.

Please:

1. Identify ONE medical-nuclear connection to my phenomenon. Examples: for a bike commute — the X-ray that diagnoses a wrist fracture from a fall, the chiropractor's possible CT, the PET-CT a cyclist might get for cancer screening as an aging athlete. For a coffee maker — the cumulative dose from medical imaging over a typical adult lifetime, the X-rays the hospital uses to monitor an industrial coffee facility's machinery. For a basketball shot — the X-ray for any sports-related injury (knee, ankle, finger), the MRI for ligament damage. For a marathon — common runner's injuries imaged with X-ray or MRI (stress fractures, tendinitis), the dexa scan for bone density monitoring of older runners.

2. Apply ONE chapter equation. Compute total dose from a specific imaging procedure (e.g., chest X-ray ~0.1 mSv, abdominal CT ~10 mSv), or compute equivalent dose from absorbed dose × $w_R$, or estimate cancer risk using the LNT model.

3. Specify input numbers (look up the typical effective dose for the procedure).

4. Run the calculation. Report value with units.

5. One sanity check: does the dose match published reference values?

6. One sentence connecting this to Chapter 33 (particle physics) — many of the same physics ideas (relativistic kinematics, charged particles in fields) underlie particle therapy.

Save the output as logbook/chapter-32-medical-nuclear.md.
```

### What this produces

A Logbook entry connecting your phenomenon to medical imaging or therapy via radiation dose.

### How to adapt this prompt

- *If you've had medical imaging procedures yourself:* The exercise becomes about computing your own cumulative dose, in millisieverts, with appropriate uncertainty.
- *For ChatGPT/Gemini:* Identical with interface substitutions.

### Connection to previous chapters

Builds on Chapter 31 (radioactivity, half-life, decay modes, $E = mc^2$) and Chapter 30 (X-ray production from atomic transitions).

### Preview of next chapter

Chapter 33 (particle physics) descends below the nucleon level — to quarks and the Standard Model. Many of the same physics ideas (relativistic energy-momentum, decay rates, conservation laws) reappear at the smaller scale.

---

## Chapter summary

Medical nuclear physics applies the principles of Chapter 31 (radioactivity) and Chapter 30 (atomic structure, X-rays) to diagnosis and therapy. Imaging modalities — X-ray, CT, MRI, gamma camera, SPECT, PET — each detect different physical signals and reveal different aspects of structure or function. Radiation dose is measured in becquerels (activity), grays (absorbed dose, J/kg), and sieverts (equivalent dose, weighted by $w_R$ for biological effectiveness). Radiation therapy delivers ~100× higher doses than diagnosis but is geometrically targeted to spare normal tissue, using techniques like IMRT, gamma-knife stereotactic radiosurgery, brachytherapy, and proton/charged-particle therapy.

The one idea that matters most: **radiation can both diagnose disease (low dose, high information) and cure it (high dose, focused delivery). The same physics underlies both.** Nuclear medicine is a clear case of physics-as-enabling-science.

The common mistake to watch for: **confusing the units.** Activity (Bq) is decay rate. Absorbed dose (Gy) is energy per mass. Equivalent dose (Sv) is dose × $w_R$. Always check what unit a quoted radiation level uses; the conversions are not all simple factors of 100.

What you should now be able to teach someone else: how the major imaging modalities differ, how radiation dose is quantified, how the therapeutic ratio guides radiation therapy, and why proton therapy has a physical (Bragg-peak) advantage over X-ray therapy. If you can also explain why a single CT scan delivers about 2-3 years of background radiation, you've understood the practical core.

---

## What would change my mind

The chapter argues that nuclear-medicine techniques are well-validated and that their benefits, in appropriately selected clinical situations, outweigh their radiation risks. The argument would need revision if (a) large-scale epidemiological studies found cancer risks from low-dose imaging (~10 mSv) substantially higher than the LNT extrapolation predicts, or (b) a non-ionizing imaging modality (e.g., advanced MRI or ultrasound) achieved equivalent or better diagnostic performance for current PET/CT applications. Both are active research areas.

## Still puzzling

The deepest unresolved question this chapter touches: **what is the actual cancer risk of diagnostic-level radiation doses (1-50 mSv)?** Above ~100 mSv, the data from atomic-bomb survivors and other cohorts are clear; below that, the data are too sparse to definitively confirm or refute the linear no-threshold model. This is one of the few areas in medicine where physics-derived doses interact with imperfectly known biological response, and where regulatory practice (assuming LNT) outpaces scientific certainty. The answer matters for whether routine pediatric CT screening is wise, whether the wider use of PET-CT for cancer monitoring increases population cancer rates, and how strict occupational limits should be.

---

## Connections forward

Chapter 33 (particle physics) goes below the nucleon, examining the quark structure of protons and neutrons and the Standard Model of fundamental interactions. Some particle-physics techniques (relativistic charged-particle beams, particle accelerators) directly enable proton-beam radiotherapy. Chapter 34 (frontiers) considers open questions in physics including dark matter and gravitational waves; many of the detection techniques used in particle physics also originated in or feed back into medical and other nuclear technologies.

---

**Tags:** medical-nuclear-physics, radiation-dose, PET-imaging, radiotherapy, dosimetry

---

## AI Wayback Machine

**Irène Joliot-Curie** discovered artificial radioactivity in 1934 with her husband Frédéric — and the Nobel Prize they shared the next year made possible the medical isotopes used in modern PET and SPECT imaging.

**Run this:**

```
Who was Irène Joliot-Curie, and how does her work on artificial radioactivity connect to the medical applications of nuclear physics we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about her career or ideas.
```

→ Search **"Irène Joliot-Curie"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to walk through how Joliot-Curie's bombardment of aluminum with alpha particles produced the first artificial radioisotope.
- Ask it about her parallel work as a French government minister for scientific research.

What changes? What gets better? What gets worse?
