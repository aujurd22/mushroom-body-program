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
| [aujurd22/flymemory](https://github.com/aujurd22/flymemory) | **Memory substrate / experimental infrastructure** (fixed role) — long-term memory layer for AI agents: hybrid retrieval (dense+lexical→RRF, optional cross-encoder) + memory state machine + model-driven judgment; also hosts the program's law ledger (research/RESEARCH.md) | Anchoring law L6: anchored semantic discretion is near-mechanical (97.9%, pre-registered paired experiment). Collection line closed with a three-way negative (bare width beats every smart collector); the answer layer is repairable — **map-reduce answering 16% vs 6% baseline** on the hardest multi-session set |
| [aujurd22/flypoet](https://github.com/aujurd22/flypoet) | Selection testbed — fly mushroom-body mechanisms transplanted into a from-scratch char-level LLM (k-WTA, compartments, write gating, active forgetting), each with the control group it deserves | The U-shaped sparsity sweet spot survives seeds and most scales (the one inversion is configuration-bound; the advantage grows with scale when data-limited), but mechanism dissection shows the active ingredients are *stable subsets* and *update throttling* — not winner-take-all competition, not surprise selectivity. k25 generates a distinct self-consistent distribution (more confident AND more diverse than dense), not a degraded dense; a unified stable-binding synthesis (5 verified + 1 pending predictions) ties the sweep, scale-ladder, freezing and divergence results together, positioned beside MoE routing stability and Hopfield/Transformer equivalence |
| [aujurd22/intuition-mechanism](https://github.com/aujurd22/intuition-mechanism) | Structure-recombination testbed — can Ramanujan-style formula discovery be reduced to a mechanical pipeline? (pre-registered registry P1–P151; see also docs/MEMORY_GEOMETRY.md, the six-law geometry synthesis with production anchors measured on the live FlyMemory store) | Recognition is governed by extraction quality (C1) and solved by supplying objective sufficient statistics; novelty additionally requires hull-visible class boundaries (C2) — the two-condition law holds across four families without exception. Math line: the six-row rationality theorem closed (census to d∈[1,1000], zero errors), with d=978=6×163 found as a Ramanujan near-integer row. Generalization arc P144–P151: intuition-pack pays +41–50pp on compression domains and nothing on distributional ones (domain boundary); the 10-domain probe matrix is complete — every elementary code domain is saturated zero-shot (shrinking law ×6); verifier templates collapsed new-domain cost to configuration; a self-driving daily scan loop builds packs only in residual windows |
| [aujurd22/flyloop](https://github.com/aujurd22/flyloop) | Closed-loop sandbox wiring the three above into one learning cycle: experience → memory → prediction → error → update → insight (no LLM in the loop; mechanical world; recoverable ground truth). Runs **RSI-0**, a mechanical self-improvement lineage over its own memory policy: objective fixed a priori, deterministic selector, mutation menu (storage AND read-policy axes), preflight-gated runs | RSI-0 lineage: g0 (2.347) → G1 ✗ → G2 ✗ → G3 accepted (adaptive read policy, 2.000) → **G4 retracted** (its rerun was a bit-identical duplicate of G3 — the retraction bought a seed split, a preflight guard and an independence checker) → **G4′ true replication: the adaptive-policy gain does NOT replicate** (within realization noise); what replicates strongly is the structured-memory advantage (2.581 vs 5.186 vs 5.372). Marathon (12.5h × 12 eras): the rule registry absorbs world change with zero forgetting. ε dose-response is non-monotonic (ε=0.15 → 1.102 beats no noise). V8-LLM transfer arc: **parametric storage is not episodic** — the loop's laws bind to instance-addressable memory, and the LM already sits on the abstraction side of the program's law. V9: the **abstraction cliff** — a tolerance wide enough to forgive the world's residual destroys identification (1.14 → ~10.5 the moment W > 0). V10 composite world (SDB-aligned) launched |

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
- **Dynamics-oriented (closed loops)**: flyloop README → its V1–V9
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
- 2026-09-30 late: **P-ANSWER SUPPORTED — the answer layer is
  repairable.** With the collector fixed to FLAT-30, per-entry atomic-fact
  extraction + reduce answers the hardest multi-session set at 16.0% vs
  6.0% baseline (HIGHLIGHT backfired into 48/50 abstain; STRUCT +2pp
  reconfirms L2 from the answer side). Adopted as a caller-side protocol
  (map-reduce for aggregation-class questions); unsupported-claims audit
  registered as the open gate before production wiring. intuition-
  mechanism added P135 (field→orbit→unit→rationality chain written
  per-layer with failure modes; census-conditional "exactly" discipline).
  flyloop's epsilon dose-response hardened into a J-shaped curve with an
  optimal noise zone at ε=0.05-0.15 (0.543-1.102, 4x better than no
  noise).
- 2026-10-01: **flyloop's integrity loop and the abstraction cliff;
  intuition-mechanism's generalization arc completes itself.** The G4
  "replication" was retracted when the rerun proved a bit-identical
  duplicate of G3 — the retraction bought a seed split
  (`FLYLOOP_RUNSEED`), a preflight guard and a mechanical independence
  check; G4′ with fresh realizations then downgraded the adaptive-policy
  gain to single-realization evidence while the structured-memory
  advantage replicated strongly (2.581 vs 5.186 vs 5.372). A 12.5h
  marathon over a 12-era world showed the rule registry absorbs world
  change with zero forgetting. The V8-LLM arc bounded transfer:
  **parametric storage is not episodic** — under memorization pressure
  the model emits the true answer ~35pp more often than it replays the
  corrupted stored value. V9 W9A found the **abstraction cliff** (FULL
  1.14 → ~10.5 the moment the world carries an incompressible residual;
  registered law: a tolerance wide enough to forgive the world's
  residual destroys identification), W9B located the plateau at the
  prediction layer, and V10 (composite world, SDB-aligned) launched
  alongside the W9C residual-registry arm — both running. intuition-
  mechanism advanced P135 → P151: the math line closed its census at
  d∈[1,1000] with zero errors and found d=978=6×163 as a Ramanujan
  near-integer row (P143); the intuition-pack arc hit its domain
  boundary (+41–50pp on compression domains, nothing on distributional
  ones, P144), completed the 10-domain probe matrix (3 compression /
  6 saturated / 1 distributional — shrinking law ×6, P146/P151),
  established the single-turn rule (batch probes understate gains 5×;
  batch = lower bound, P150), and put a self-driving scan loop on a
  daily schedule whose first cycle ran clean with correct refusals
  (P151) — elementary code domains are now exhausted as pack candidates,
  making the verifier-construction bottleneck the binding constraint.
  flypoet shipped the stable-binding synthesis preview (5 verified + 1
  pending predictions) and lit-note positioning against MoE routing
  stability and Hopfield/Transformer equivalence. flymemory stayed
  quiet as the substrate (P-ANSWER remains its head).
- Next program-level milestones: W9C (residual registry) and V10
  composite-world verdicts (both running in flyloop); unsupported-claims
  audit for the map-reduce protocol, then wiring it into classify_query
  aggregation-class routing (flymemory caller side); L6 cross-model
  replication; intuition's self-driving loop hunting genuinely hard
  domains (the verifier-construction bottleneck); P35/P36
  second-math-family replication.
