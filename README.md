# The Mushroom-Body Program

**Selection, Compression, and Emergent Structure**

> The big question: **when does compression induce structure?** — when a
> system replaces a keep-everything baseline with lossy compression (memory
> consolidation) or sparse competition (k-WTA), when do downstream
> capabilities rise, when do they collapse, and in what form?

This repository is the **hub and index** for a four-repository independent
research program. The insect mushroom body — sparse high-dimensional coding
plus selective compression yielding generalized memory — is treated as the
abstract prototype of a class of engineering problems: *trading simple local
selection and compression mechanisms for global capability*. Each repo owns
one experimental axis; the laws are cross-validated between them.

**Program-level question (est. 2026-09-28):** *which cognitive tasks can be
compressed into an objective sufficient statistic, and which must retain
semantic discretion?*

---

## The four repositories

| Repo | Role | One-line result |
|---|---|---|
| [aujurd22/flymemory](https://github.com/aujurd22/flymemory) | Memory testbed — long-term memory layer for AI agents: hybrid retrieval (dense+lexical→RRF, optional cross-encoder) + memory state machine (supersede lineage, evidence-linked consolidation, decay, directed forgetting) + model-driven judgment | Anchoring law L6: anchored semantic discretion is near-mechanical (97.9%, pre-registered paired experiment, discordant 13:0); unanchored judgment is where discretion lives (70.8%) |
| [aujurd22/flypoet](https://github.com/aujurd22/flypoet) | Selection testbed — fly mushroom-body mechanisms transplanted into a from-scratch char-level LLM (k-WTA, compartments, write gating, active forgetting), each with the control group it deserves | The U-shaped sparsity sweet spot survives seeds and scales, but mechanism dissection shows the active ingredients are *stable subsets* and *update throttling* — not winner-take-all competition, not surprise selectivity |
| [aujurd22/intuition-mechanism](https://github.com/aujurd22/intuition-mechanism) | Structure-recombination testbed — can Ramanujan-style formula discovery be reduced to a mechanical pipeline? (pre-registered registry P1–P50) | Recognition is governed by extraction quality (C1) and solved by supplying objective sufficient statistics; novelty additionally requires hull-visible class boundaries (C2) — the two-condition law holds across four families without exception |
| [aujurd22/flyloop](https://github.com/aujurd22/flyloop) | Closed-loop sandbox wiring the three above into one learning cycle: experience → memory → prediction → error → update → insight (no LLM in the loop; mechanical world; recoverable ground truth) | V3/V4 paired-memory arms: structured memory cuts recurrence relearn cost (dE20 = +0.64, CI [0.51, 0.77]) with zero advantage on novel variants — a pure reuse signature |

**Canonical research-state document:** [`research/RESEARCH.md`](https://github.com/aujurd22/flymemory/blob/main/research/RESEARCH.md)
in the flymemory repo (laws L1–L6, registered predictions with git-timestamp
proof, cross-testbed evidence chain). The intuition-mechanism registry is
`docs/RESEARCH_PLAN.md` in its repo.

---

## The law system (compressed; full versions with repro commands in RESEARCH.md)

- **L1 · Overlay law** — abstraction must overlay, never replace
  (replace-style consolidation −10pp; overlay +5.8pp, n=500).
- **L2 · Second-order law** — presentation form of consolidation is
  second-order; overlaying at all is the first-order variable.
- **L3 · Phase-transition law** — the sparse-competition sweet spot exists
  but is phase-transition-like and non-monotonic in scale.
- **L4 · Small-edit failure law** — selection mechanisms silently swallow
  small-edit state updates (5/20 digit/date pairs dropped by dedup);
  lineage (tombstone/supersede) must backstop them. **Engine-layer:
  P-PHASE-1 shows the judgment layer does NOT inherit this fragility.**
- **L5 · Aggregation law** — retrieval form must match question type
  (lookup → top-k; aggregation → toolized multi-round).
- **L6 · Anchoring law** — anchored discretion (concrete reference value vs
  assertion) is near-mechanical; unanchored linguistic-behavior
  classification is where discretion truly lives. Established by
  pre-registered paired experiment P-ANCH-1 (47/48 vs 34/48, McNemar
  p≈2e-4); P-PHASE-1 shows the anchored verdict stays perfect down to
  digit-swap updates (Δ_emb ≈ 0.2).
- **Two-condition law (intuition-mechanism P50, four families)** —
  recognition is governed by extraction quality (C1); novelty requires C1
  AND hull-visible class boundaries (C2). Cross-validated against
  flymemory: anchored state-change judgment is the empirical C2-N/A cell;
  unanchored assertion typing is a C1 failure.
- **Program synthesis** — task difficulty = f(C1 supplyable, C2 required);
  **anchoring rewrites a C2-dependent judgment into a C1-decidable
  comparison**, which is the mechanistic explanation of why anchors work.

---

## Method culture (what makes this a program, not four projects)

1. **Pre-registration** — criteria are committed (git timestamps) before
   results exist; verdict fields carry a `PENDING` marker until the result
   artifact has been read (adopted 2026-09-28 after a self-caught integrity
   incident in the P47 write-up).
2. **Negative results are first-class** — the scaffold-transplant negative
   (3f87703), the state-aware-reranking harmful result, the surprise-gating
   = update-throttling dissection, the P33 hull-axis null: all retained,
   all load-bearing in the current theory.
3. **Retractions with root cause** — when a conclusion falls (fixed val
   window, implementation bug, identifiability repair), the README/PAPER
   record the retraction and the lesson, not a silent edit.
4. **Mechanical-first** — the server/engine never runs an LLM; judgment
   lives in the caller; every claimed law has a one-command repro.
5. **Cross-testbed validation** — no law enters the L-series from a single
   repo; the scaffold question (P32-i) was deliberately transplanted into
   flymemory to test its boundary (and the negative result became L6's
   foundation).

---

## Reading order suggestions

- **Engineering-oriented (agent memory)**: flymemory README → its
  Benchmarks section → RESEARCH.md L4–L6.
- **Mechanism-oriented (bio-inspired training)**: flypoet README (Chinese)
  → PAPER.md §10–§14 (six-bet scoreboard, mechanism dissection).
- **Math/discovery-oriented**: intuition-mechanism README →
  docs/RESEARCH_PLAN.md (P35–P50 rows).
- **Dynamics-oriented (closed loops)**: flyloop README → its V1–V4
  research-history section.

## Status

- Hub established: 2026-09-28.
- Law ledger lives in flymemory (`research/RESEARCH.md`); registries live
  per-repo; this hub mirrors the compressed state and links out.
- Next program-level milestones: replicate the sufficient-statistic →
  capability chain on a second, structurally different math family;
  mechanical sufficient statistic for memory judgment (anchoring result is
  the first candidate); flyloop V5 design.
