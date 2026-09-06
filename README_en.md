# cnt34 Code Name Type ３４ / Sanshi-shiki (三四式)

〜 An open-source research initiative weaving position (3) and orientation (4) toward a better world 〜

[![Code License: MIT](https://img.shields.io/badge/Code_License-MIT-green.svg)](./LICENSE)
[![Content License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Content_License-CC_BY--NC--SA_4.0-lightgrey.svg)](./LICENSE-CONTENT.md)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19704117.svg)](https://doi.org/10.5281/zenodo.19704117)

[![Author](https://img.shields.io/badge/Author-Naoyuki_Kawakami-f39c12?style=for-the-badge)](https://orcid.org/0009-0009-2972-6511)

📖 [Definitions of symbols and terms](01_FOUNDATION/definitions.md) ・ 🤝 [How to contribute](CONTRIBUTING.md) ・ 🌐 [日本語](./README.md)

---

# Sanshi-shiki (三四式) — TTT Theory / Triple-Tetra Theory

> **〜 An open-source research initiative weaving position (3) and orientation (4) toward a better world 〜**

## 📛 Where the name comes from

From the Meiji era into the early Shōwa period, the Japanese military named its weapons by prefixing the adoption year to *shiki* ("type") — the Type 38 rifle, the Type 0 carrier fighter.

"Sanshi-shiki" (三四式, "Type 3-4") borrows that naming convention and inverts its meaning. It compresses the initials of Tri-Tetra Theory (TTT) together with the core of the theory: position 3 + orientation 4.

Where those weapons were symbols of conflict and killing, Sanshi-shiki aims to be a symbol of connection and harmony — a peace argument written in the language of geometry, and a model of "harmony without a center" rooted in Japanese culture. See [`four-gods-and-tensegrity.md`](06_GOVERNANCE/four-gods-and-tensegrity.md) (Japanese).

## 🌟 Project Vision

TTT Theory (Triple-Tetra Theory, 三四式) proposes a new framework of thought for reading the geometric harmony woven through nature, life, and the cosmos.

When different elements and dimensions combine, a new "autonomous system (10 · cell · solid)" is born, and spreads out into the world——

This repository is not simply a place to store mathematical or physical formulas. It is an open canvas for drawing, together with people around the world, a world in which science, medicine, information, art, and human society exist in greater harmony.

---

## 💡 What Is TTT Theory (Sanshi-shiki)?

TTT is a state-space model integrating position vectors and orientation vectors, built around the interaction between "3 (spatial position)" and "4 (orientation / rotation)."

$$P = xX + yY + zZ + uU + vV + wW$$

* **3 dimensions of position** ($xX, yY, zZ$): where matter is
* **3 dimensions of orientation** ($uU, vV, wW$): which way it faces (polarity, rotation, the tilt of the field)

When the interaction of "orientation" is added to "position," the system autonomously forms stable tensegrity structures and membranes, giving rise to spontaneous symmetry breaking — much like life itself.

### How the "three" and the "four" are counted

The "4" in the name is *not* a component count of the equation above. It is the three orientation axes ($U, V, W$) **plus the rotation axis $\pi$ that binds and closes them**.

$$XYZ\pi = 1 \qquad OOO\pi = 1$$

So: **3 position axes + 3 orientation axes = 6 components**, and counting the closing rotation axis $\pi$ in each system gives the "three and four." See [`XYZ-pi.md`](02_MATHEMATICS/XYZ-pi.md) (space side) and [`OOO-pi.md`](02_MATHEMATICS/OOO-pi.md) (energy side).

### On the notations $U,V,W$ and $R,I,J$

Two notations for the orientation components appear across this repository. They denote **the same three components**, not different quantities.

| Notation | Used in | Source |
| :--- | :--- | :--- |
| $uU + vV + wW$ | the geometric introduction (how axes are born from the dual pole) | [`00-dual-pole.md`](01_FOUNDATION/00-dual-pole.md) |
| $rR + iI + jJ$ | the formulation that assigns concrete meaning to each component | [`01-basic-equation.md`](01_FOUNDATION/01-basic-equation.md) |

A rigorous derivation of the correspondence between them is **open** — see item O-1 in [`definitions.md`](01_FOUNDATION/definitions.md).

---

## 🚀 Prospective Application Fields

* 🧬 **Artificial Life & Biotechnology**: simulating the autonomous division and self-organization of synthetic cells
* 🤖 **Autonomous Distributed Robotics**: swarm control and swarm intelligence
* 🌌 **Advanced Materials & Architectural Topology**: tensegrity structures and metamaterials
* 💻 **Next-Generation AI & Vector Representation**: high-dimensional embeddings

All of these are **at the concept stage**. Nothing here has been implemented or validated yet. This is a list of what we would like to try, not of what has been done.

---

## 🤝 Let's Dream a Good Dream Together (Contribution)

We don't consider this theory finished. If anything, this is only the starting point.

**Agreeing with TTT is not a condition for taking part.** What is being invited is interest in the questions, not assent to the answers. Refutations, alternative readings, and "this part is wrong" are as welcome as agreement — often more so.

* **If you love math or physics:** rigorous formalization, including approaches via quaternions
* **If you're a programmer:** Python and 3D visualization / simulation code
* **If you're a thinker, artist, or poet:** discussion and documentation of the new worldview this model opens up

New here? Start with [**CONTRIBUTING.md**](CONTRIBUTING.md). It lists the questions that are currently open, and explains the confidence labels attached to every claim in this repository.

> **"A dream one person tries to see alone is just a dream. A dream many people try to see together becomes reality."**

---

## 📍 Where we actually are

This project makes a point of printing **what is written and what is still missing in the same size type.**

| Status | Meaning |
| :--- | :--- |
| ✅ Written | readable end to end: 00-dual-pole, 01-basic-equation, 02-dynamic-model, 03-cosmic-sphere-model, 04-genesis-and-time, 05-lattice-and-existence, XYZ-pi, OOO-pi, euler-connection, the Four Pillars, governance |
| 🚧 Stub | heading only, content to come: [`2-to-5.md`](01_FOUNDATION/2-to-5.md), [`cell-division.md`](04_LIFE/cell-division.md) |
| ❓ Open | unanswered questions inside the theory: the "Open items" section of [`definitions.md`](01_FOUNDATION/definitions.md) (O-1 … O-5) |

[`cell-division.md`](04_LIFE/cell-division.md) is the **largest single gap**: nine other documents cite it as if it existed. We are looking for someone who can write it.

Note: most theory documents are currently Japanese-only. Translation is itself a welcome contribution — see CONTRIBUTING.md.

---

## 🏛️ TTT Governance Model

> Think of three things as four, and a fifth is born. When it becomes five, it divides.

A chapter applying TTT Theory to social institutions.

- **Core idea**: [`Governance-En.md`](06_GOVERNANCE/Governance-En.md) — 3 branches of government + popular sovereignty + AI = a 5th autonomous body, the "verifiable consensus cell"
- **Implementation blueprint**: [`5W1H-En.md`](06_GOVERNANCE/5W1H-En.md) — the consensus cell's design, unfolded across the 5W1H
- **Interactive demo**: [Governance-5w1h.html](https://kiki054-n.github.io/cnt34/06_GOVERNANCE/Governance-5w1h.html) — visualizing the birth and division of the membrane
- JA: [`governance.md`](06_GOVERNANCE/governance.md) / [`5W1H.md`](06_GOVERNANCE/5W1H.md)

[![Open in Browser](https://img.shields.io/badge/Demo-Governance%20Cell-blue?style=for-the-badge)](https://kiki054-n.github.io/cnt34/06_GOVERNANCE/Governance-5w1h.html)

### 5W1H mapping

| 5W1H | TTT | Role |
| :--- | :--- | :--- |
| Where, What, When | xX, yY, zZ | Position — the coordinates of fact |
| Why, How | uU, vV, wW | Orientation — popular sovereignty and the field of AI knowledge |
| Who | P5 | Autonomous body — the verifiable consensus cell |

---

## 📚 Theory Documents

The sequence: dual pole (2) → position (3) → orientation (4) → a manifested autonomous unit (5).

**01_FOUNDATION**
- [`00-dual-pole.md`](01_FOUNDATION/00-dual-pole.md) — the Principle of Dual Poles: why everything starts from "2," not "1"
- [`01-basic-equation.md`](01_FOUNDATION/01-basic-equation.md) — the fundamental equation, and how it differs from quaternions
- [`definitions.md`](01_FOUNDATION/definitions.md) — symbols, terms, and the list of open items
- [`2-to-5.md`](01_FOUNDATION/2-to-5.md) 🚧 — the unfolding from "2" to "5"

**02_MATHEMATICS**
- [`XYZ-pi.md`](02_MATHEMATICS/XYZ-pi.md) — the spatial unit system, $XYZ\pi=1$
- [`OOO-pi.md`](02_MATHEMATICS/OOO-pi.md) — the energy unit system, $OOO\pi=1$
- [`euler-connection.md`](02_MATHEMATICS/euler-connection.md) — reading $e^{i\pi}=-1$ as the birth of the dual pole
- [`02-dynamic-model.md`](02_MATHEMATICS/02-dynamic-model.md) — time evolution via a tensor product
- [Simulation (EN)](https://kiki054-n.github.io/cnt34/02_MATHEMATICS/TTT_theory_simulation_en.html)

**03_PHYSICS**
- [`03-cosmic-sphere-model.md`](03_PHYSICS/03-cosmic-sphere-model.md) — the bounded sphere and the zero-convergence axiom

**04_LIFE**
- [`04-genesis-and-time.md`](04_LIFE/04-genesis-and-time.md) — time as a derived quantity, defined after the motion of the dual pole
- [`four-gods-and-tensegrity.md`](04_LIFE/four-gods-and-tensegrity.md) — harmony without a center
- [`cell-division.md`](04_LIFE/cell-division.md) 🚧 — the geometry of cell division

**05_AI**
- [`05-lattice-and-existence.md`](05_AI/05-lattice-and-existence.md) — $\pi$ as the basis of the lattice

**06_GOVERNANCE / 07_WCCC**
- [`governance.md`](06_GOVERNANCE/governance.md) ・ [`gratitude.md`](07_WCCC/gratitude.md) — the Gratitude Circulation Protocol

---

## 🏛️ The Four Pillars & the Circulation of Gratitude

TTT applied to human roles and labor. Illustrated version: [TTT_4pillars_repository.html](https://kiki054-n.github.io/cnt34/06_GOVERNANCE/pillars/TTT_4pillars_repository.html)

- [`pillar-01-create.md`](06_GOVERNANCE/pillars/pillar-01-create.md) — Pillar 1: Creative Labor (spin on the $u$ axis)
- [`pillar-02-support.md`](06_GOVERNANCE/pillars/pillar-02-support.md) — Pillar 2: Support Labor (spin on the $v$ axis)
- [`pillar-03-govern.md`](06_GOVERNANCE/pillars/pillar-03-govern.md) — Pillar 3: Governance Labor (spin on the $w$ axis)
- [`pillar-04-invent.md`](06_GOVERNANCE/pillars/pillar-04-invent.md) — Pillar 4: Invention Labor (the rotation axis $\pi$ itself)
- [`gratitude.md`](07_WCCC/gratitude.md) — the Gratitude Circulation Protocol

---

## 📜 License

This project uses different licenses for code and for written content.

* **Code** (simulation HTML/JS, verification scripts, etc.): [MIT License](./LICENSE) — free to use, modify, and build into your own tools or verification work. Getting TTT actually used, tested, and (dis)proven is the priority here.
* **Theory write-ups & papers** (this README's body text, papers published on Zenodo, etc.): [CC BY-NC-SA 4.0](./LICENSE-CONTENT.md) — attributed quotation, discussion, and non-commercial use are welcome. Please don't use it commercially or redistribute it under different terms.

Note that the underlying theory itself — the equations and ideas — isn't something copyright (or any license) can cover. Both licenses govern copying/redistributing this specific text and code, not ownership of the idea of TTT itself.
