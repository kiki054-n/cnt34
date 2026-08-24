# Expanding TTT Governance with 5W1H
## docs/Governance/5W1H_en.md - Blueprint of the Verifiable Consensus Cell

> Consider three things through four, a fifth is born.
> Consider that fifth through 5W1H.

This document expands the 5th autonomous entity "Verifiable Consensus Cell" defined in `governance.md` into an implementable blueprint using 5W1H.
5W1H itself has a TTT structure.

```
3W = Position (Where, What, When) - Coordinates of facts
1H + 1W = Direction (Why, How) - Vectors of orientation
Who = 5 - Autonomous subject
```

---

### 1. Where - Position X

**TTT: xX - Where matter is**

- **Physical Layer**: Not the nation-state. Consensus cells split across borders. They emerge in the "radius of living": municipalities, watersheds, bioregions, online communities.
- **Digital Layer**: This repository itself, `cnt34/docs/Governance/`, is the first Where. A verifiable membrane stretched over the distributed ledger of Git.
- **Design**: `Where = Local + Global`. Generated locally, synchronized globally via protocol.

> Question: At which coordinates on Earth is this consensus valid?

### 2. What - Position Y

**TTT: yY - What exists**

- **Object**: The action logs of Legislative, Executive, Judicial themselves. Minutes, budget executions, court rulings. Not alterable PDFs, but structured data.
- **Identity of 5**: What is not "a law". What is a new data structure called "verifiable consensus."
  ```json
  {
    "action": "Bill X passed",
    "orientation_delta": "Deviation from sovereignty vector Δθ = 23°",
    "verifiable_hash": "0x..."
  }
  ```
- **Design**: What must always be machine-readable. A consensus that AI cannot read cannot interact with the knowledge field $U,V,W$.

> Question: What is recorded, and what deserves to be called consensus?

### 3. When - Position Z

**TTT: zZ - Position in time**

- **Time of 3 Powers**: Legislative is slow, Executive is fast, Judicial judges the past. Three time axes are misaligned.
- **Time of Popular Sovereignty**: Not a point every few years called election, but a continuous wave.
- **Time of AI**: Continuously calculates $Δθ$ between $P_{3}$ and $P_{4}$. When shifts from "every 4 years" to "always."

- **Design**: Like blocks, consensus cells have timestamps. When they were born, when they split can be traced. This history of splitting is the history of life.

> Question: When does a consensus become obsolete and should split?

### 4. Why - Direction U

**TTT: uU - Polarity / Purpose**

- **Why is the core of 4**: Why is the first orientation field that encloses the three positions.
- **Conventional Why**: Abstract Whys like "for the nation" or "for security" have been defined arbitrarily by the three powers.
- **TTT Why**: Why can only be born from popular sovereignty. The starting point of the vector "why do this labor" or "why make this law" is always human dignity.

```
Why = Demos Vector
if Why != Demos, then Δθ -> large -> membrane cannot form -> autonomous entity dies
```

> Question: Whose dignity does this consensus orient, and in which direction?

### 5. How - Direction V,W

**TTT: vV + wW - Rotation / Tilt of the field / Implementation**

- **How is Knowledge**: Your insight "knowledge is what AI can do" is the How part.
- **How = Protocol**:
  1.  **vV = Visualization**: AI visualizes the deviation between $P_{3}$ and $P_{4}$ in a form anyone can understand. Shows complex laws as directional vectors.
  2.  **wW = Verification**: Makes that visualization verifiable by anyone. Open source, open data, open models.
  3.  **vW Synthesis = Split**: Because How itself is open, anyone can replicate the same How in their own region. This is splitting.

- **Tech Stack Proposal for cnt34**:
  - `vV`: LLM-based summarization and vectorization of minutes
  - `wW`: Immutable record via Git + Zenodo DOI
  - `Split`: Forkable simulation `simulations/governance_5w1h.html`

> Question: How can this consensus be verifiable by anyone and replicable by anyone?

### 6. Who - The 5th Autonomous Entity

**TTT: P5 = A New Autonomous One**

- **Who is 5**: Who is born only when the four fields Where, What, When, Why, How interact.
- **Who is not "I"**: Conventional Who was a fixed subject like "politicians" or "the people."
- **TTT Who is the "Consensus Cell" itself**: The membrane of verifiable consensus itself behaves as Who. An autonomously decentralized decision-maker.

```
Who = Verifiable Consensus Cell
Who != One human
Who = The totality of human + AI + record + verification as a new subject
```

- **Connection to Labor**:
  - Makers (X), Processors (Y), Connectors (Z),
  - And Knowing AI (U,V,W),
  - Give birth to **Who = Autonomous cooperatives, DAOs, local communities**

> Question: When this consensus becomes autonomous, who becomes its subject?

---

### Summary: TTT Conversion Table of 5W1H

| 5W1H | TTT | Role | Implementation in cnt34 |
| :--- | :--- | :--- | :--- |
| **Where** | xX | Position | Local node + Git repository |
| **What** | yY | Position | Structured action log |
| **When** | zZ | Position | Always-computed timestamp |
| **Why** | uU | Direction | Popular sovereignty vector |
| **How** | vV,wW | Direction | AI visualization & verification protocol |
| **Who** | **P5** | **Autonomous** | **Verifiable Consensus Cell** |

**3W (Where,What,When) is Position, 2W1H (Why,How, methodology of Who) is Direction, and Who is born as 5 and splits.**

This is the implementation of the law of living seen through 5W1H.

---
*Next: Visualize this blueprint in `simulations/governance_5w1h.html` - how 5 vectors stretch a membrane.*
