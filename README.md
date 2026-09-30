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
| [aujurd22/flymemory](https://github.com/aujurd22/flymemory) | **Memory substrate / experimental infrastructure** (fixed role) — long-term memory layer for AI agents: hybrid retrieval (dense+lexical→RRF, optional cross-encoder) + memory state machine + model-driven judgment; also hosts the program's law ledger (research/RESEARCH.md) | Anchoring law L6: anchored semantic discretion is near-mechanical (97.9%, pre-registered paired experiment, discordant 13:0); unanchored judgment is where discretion lives (70.8%) |
| [aujurd22/flypoet](https://github.com/aujurd22/flypoet) | Selection testbed — fly mushroom-body mechanisms transplanted into a from-scratch char-level LLM (k-WTA, compartments, write gating, active forgetting), each with the control group it deserves | The U-shaped sparsity sweet spot survives seeds and scales, but mechanism dissection shows the active ingredients are *stable subsets* and *update throttling* — not winner-take-all competition, not surprise selectivity. k25 generates a distinct self-consistent distribution (more confident AND more diverse than dense), not a degraded dense |
| [aujurd22/intuition-mechanism](https://github.com/aujurd22/intuition-mechanism) | Structure-recombination testbed — can Ramanujan-style formula discovery be reduced to a mechanical pipeline? (pre-registered registry P1–P73; see also docs/MEMORY_GEOMETRY.md, the six-law geometry synthesis with production anchors measured on the live FlyMemory store) | Recognition is governed by extraction quality (C1) and solved by supplying objective sufficient statistics; novelty additionally requires hull-visible class boundaries (C2) — the two-condition law holds across four families without exception |
| [aujurd22/flyloop](https://github.com/aujurd22/flyloop) | Closed-loop sandbox wiring the three above into one learning cycle: experience → memory → prediction → error → update → insight (no LLM in the loop; mechanical world; recoverable ground truth). Runs **RSI-0**, a mechanical self-improvement lineage over its own memory policy: objective fixed a priori, deterministic selector, mutation menu (storage AND read-policy axes), preflight-gated runs | Four generations done: g0 (2.347) → G1 ✗ → G2 ✗ → **G3 ✓ adaptive read policy (2.000)** → **G4 ✓ replication (1.917)** — both selection polarities exercised. V8 found the ε dose-response NON-MONOTONIC: moderate observation noise (ε=0.15, FULL E20 1.102) improves rule-based memory by forcing cleaner registrations — better than no noise at all (2.347) |

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
- 2026-09-29/30 sprint (all four repos): flymemory's L6 anchoring law
  established by pre-registered paired experiment (P-ANCH-1, 47/48 vs
  34/48) and bounded by P-PHASE-1; index+query collection lines closed
  with a three-way negative whose headline is **FLAT-30 (bare width,
  0.683 turn-recall) beating every smart collector** while the answer
  layer ate the entire gain — residual bottleneck relocated to
  answer-side aggregation. intuition-mechanism formalized the two-axis
  interestingness theory (P133, INTERESTINGNESS_FORMAL.md), answered the
  square-unit structure questions (P134), and shipped a detailed
  chart-backed README. flyloop's RSI-0 completed four generations with
  both selection polarities (G3/G4 accepted: adaptive read policy,
  2.347 → 1.917) and found the non-monotonic ε dose-response (V8d15).
  flypoet renamed the faithfulness claim to distributional divergence
  (round-8 review discipline) and shipped README v4 with six data
  charts. P-CLEANUP ran as a pre-study + registered experiment:
  production store is heavy-tail redundant (NOT two-scale), eviction
  shows a benefit-cost mirror, upstream dedup already collected the
  redundancy dividend — LRU stays.
- Next program-level milestones: answer-side aggregation experiment
  (map-reduce answering on the multi-session set — the relocated
  bottleneck); RSI-0 G5 (mutation menu now includes the READ_POLICY
  axis); L6 cross-model replication; P35/P36 second-math-family
  replication (intuition side).
