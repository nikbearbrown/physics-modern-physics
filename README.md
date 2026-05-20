# Physics +1: Modern Physics

**Author:** Nik Bear Brown
**Series:** Physics +1 (Volume 6)
**Publisher:** Bear Brown, LLC
**Status:** Draft

---

## About this book

*The 20th century broke classical physics in two places — large velocities and small scales — and never put it back together.* This volume traces both breaks: special relativity (where time becomes a coordinate that observers disagree on) and quantum mechanics (where particles are spread out until they aren't), and then carries the consequences outward through stellar nuclear physics, particle physics, and Big Bang cosmology.

There is no lived-experience anchor for any of this — you cannot watch time dilate by walking across a room, and you cannot see an electron orbital. So the +1 layer is doing the heaviest lifting in this volume: D3 simulations of Lorentz transformations, photoelectric thresholds, spectral lines, stellar interiors, decay chains, and the Hubble diagram supply the visceral intuition the prose alone cannot. The book uses astronomical settings (the Sun, a dying star, a black hole, the CMB) as cold opens because the physics is the same machinery in places the student can imagine.

Audience: students who have completed classical mechanics and electromagnetism, comfortable with calculus and basic differential equations. The 16 chapter drafts in `chapters/` are a mixed corpus — OpenStax College Physics, University Physics, and Astronomy. `outline.md` proposes an 11-chapter curation for the published volume.

## How this directory is organized

```
book.md              ← one-sentence pitch, argument, gap, reader, high-level outline (planning)
outline.md           ← working TOC with D3 simulation notes per chapter
vision.md            ← Tic TOC Phase 1: vision and positioning
architecture.md      ← Tic TOC Phase 2: learning architecture
chapters-spec.md     ← Tic TOC Phase 3: per-chapter specifications
risks.md             ← Tic TOC Phase 4: scope, comparables, adoption risks
pantry/              ← scratch storage for fragments and snippets
chapters/            ← drafts (this is where the book lives)
images/              ← figures and hero images per chapter
styles/              ← Kindle-bound CSS (shared base + book-specific overrides)
build.sh             ← compile the EPUB
graphs.sh            ← process figure-placeholder comments into images/tables
```

## Detailed Table of Contents

### Front Matter

| File | Section |
|------|---------|
| `chapters/00-frontmatter.md` | Title page, copyright, dedication, preface |
| `chapters/00b-introduction.md` | Book-level introduction (template placeholder) |

### Chapters

| # | File | Title |
|---|------|-------|
| 1 | `chapters/01-special-relativity.md` | The Speed Limit: What Einstein's Postulates Reveal About Space, Time, and Energy |
| 2 | `chapters/02-the-sun-a-garden-variety-star.md` | The Sun: A Garden-Variety Star |
| 3 | `chapters/03-the-sun-a-nuclear-powerhouse.md` | The Sun Burning: Why Four Billion Years of Light Comes from Turning Mass into Energy |
| 4 | `chapters/04-the-quantum-nature-of-light.md` | The Quantum Nature of Light |
| 5 | `chapters/05-the-atom.md` | The Atom: Structure, Energy, and Uncertainty |
| 6 | `chapters/06-particle-physics.md` | Particle Physics: Reading the Deepest Structure of Matter |
| 7 | `chapters/07-the-death-of-stars.md` | The Death of Stars |
| 8 | `chapters/08-black-holes-and-curved-spacetime.md` | Black Holes and Curved Spacetime |
| 9 | `chapters/09-special-relativity.md` | Special Relativity |
| 10 | `chapters/10-quantum-physics.md` | Quantum Physics |
| 11 | `chapters/11-the-big-bang.md` | The Universe's First Three Minutes: Evidence for the Beginning |
| 12 | `chapters/12-atomic-physics.md` | Atomic Physics |
| 13 | `chapters/13-radioactivity-and-nuclear-physics.md` | Radioactivity and Nuclear Physics |
| 14 | `chapters/14-medical-applications-of-nuclear-physics.md` | Medical Applications of Nuclear Physics |
| 15 | `chapters/15-particle-physics.md` | Particle Physics |
| 16 | `chapters/16-frontiers-of-physics.md` | Frontiers of Physics |

### Back Matter

| File | Section |
|------|---------|
| `chapters/99-back-matter.md` | Acknowledgments, About the Author, References, Index |

## Notes on the chapter set

Several pairs are parallel drafts of the same topic from different source textbooks: ch. 1 & 9 (*Special Relativity*), ch. 5 & 12 (*The Atom* / *Atomic Physics*), ch. 6 & 15 (*Particle Physics*), ch. 2 & 3 (the Sun, two angles). They are kept side-by-side for now — the curated published outline (see `outline.md`) collapses each cluster.

## Build

```bash
./build.sh
```

Output lands in `output/` (gitignored).

## Figures

```bash
./graphs.sh
```

Processes `<!-- → [TYPE: description] -->` comments throughout the chapters:
tabular figures become classed markdown tables; non-tabular figures become
placeholder images in `images/`, ready to replace; CSS log appends to
`styles/kindle-book.css` on each run.

## Publish

Upload `output/physics-plus-one-modern-physics.epub` to [KDP](https://kdp.amazon.com).

---

## What This Book Is

<!-- TODO: populate from chapter content -->

---

## Who This Book Is For

<!-- TODO: populate from chapter content -->

---

## How to Read It

<!-- TODO: populate from chapter content -->

---

## Table of Contents

| Chapter | Title | File |
|---------|-------|------|
| Intro | Introduction | [chapters/00b-introduction.md](chapters/00b-introduction.md) |
| 1 | Chapter 1 — The Speed Limit: What Einstein's Postulates Reveal About Space, Time, and Energy | [chapters/01-special-relativity.md](chapters/01-special-relativity.md) |
| 2 | Chapter 2 — The Sun: A Garden-Variety Star | [chapters/02-the-sun-a-garden-variety-star.md](chapters/02-the-sun-a-garden-variety-star.md) |
| 3 | Chapter 3 — The Sun Burning: Why Four Billion Years of Light Comes from Turning Mass into Energy | [chapters/03-the-sun-a-nuclear-powerhouse.md](chapters/03-the-sun-a-nuclear-powerhouse.md) |
| 4 | Chapter 4 — The Quantum Nature of Light | [chapters/04-the-quantum-nature-of-light.md](chapters/04-the-quantum-nature-of-light.md) |
| 5 | Chapter 5 — The Atom: Structure, Energy, and Uncertainty | [chapters/05-the-atom.md](chapters/05-the-atom.md) |
| 6 | Chapter 6 — Particle Physics: Reading the Deepest Structure of Matter | [chapters/06-particle-physics.md](chapters/06-particle-physics.md) |
| 7 | Chapter 7 — The Death of Stars | [chapters/07-the-death-of-stars.md](chapters/07-the-death-of-stars.md) |
| 8 | Chapter 8 — Black Holes and Curved Spacetime | [chapters/08-black-holes-and-curved-spacetime.md](chapters/08-black-holes-and-curved-spacetime.md) |
| 9 | Chapter 9 — Special Relativity | [chapters/09-special-relativity.md](chapters/09-special-relativity.md) |
| 10 | Chapter 10 — Quantum Physics | [chapters/10-quantum-physics.md](chapters/10-quantum-physics.md) |
| 11 | Chapter 11 — The Universe's First Three Minutes: Evidence for the Beginning | [chapters/11-the-big-bang.md](chapters/11-the-big-bang.md) |
| 12 | Chapter 12 — Atomic Physics | [chapters/12-atomic-physics.md](chapters/12-atomic-physics.md) |
| 13 | Chapter 13 — Radioactivity and Nuclear Physics | [chapters/13-radioactivity-and-nuclear-physics.md](chapters/13-radioactivity-and-nuclear-physics.md) |
| 14 | Chapter 14 — Medical Applications of Nuclear Physics | [chapters/14-medical-applications-of-nuclear-physics.md](chapters/14-medical-applications-of-nuclear-physics.md) |
| 15 | Chapter 15 — Particle Physics | [chapters/15-particle-physics.md](chapters/15-particle-physics.md) |
| 16 | Chapter 16 — Frontiers of Physics | [chapters/16-frontiers-of-physics.md](chapters/16-frontiers-of-physics.md) |

---

## Signature Simulations

<!-- TODO: populate from chapter content -->

---

## Copyright

Copyright © 2026 Nik Bear Brown. All rights reserved.

Published by Bear Brown, LLC.

No part of this publication may be reproduced, distributed, or transmitted
in any form or by any means without the prior written permission of the
publisher, except in the case of brief quotations in critical reviews and
certain other noncommercial uses permitted by copyright law.

ISBN: [INSERT ISBN]

