# RECEIPTS-NATIVE ARCHITECTURE DECK — MULTI-AGENT BUILD STRATEGY v2.1

**Target Executor:** Claude Code (deck build) + Gemini Veo (video) + Claude/Gemini (UI mockups)
**Source of Truth:** Receipts-Native Architecture v3.0, Meta-Loop v2.1, Monte Carlo v2.0, FULCRUM v4, Demo Stealth Bomber v1
**Compliance:** CLAUDEME.md standards apply to all build artifacts

---

## WHAT THIS DOCUMENT IS

A strategic instruction set for building a visual, interactive architecture presentation with three embedded UI/video deliverables. The AI coder has CLAUDEME.md. They do not need code from you. This document provides architecture decisions, narrative structure, visual specifications, and content requirements.

**This is NOT the drone deck leveled up. This is the core RNA architecture telling its own story.**

---

## CRITICAL CORRECTIONS FROM v2.0 (READ FIRST)

### 1. COMPRESSION = DISCOVERY IS INVERTED FROM v2.0

**v2.0 (WRONG):** "Legitimate data compresses efficiently (≥0.85 ratio). Fraudulent data exhibits high entropy."

**v3.0 (CORRECT):** "Legitimate operations exhibit HIGH entropy (variable, unpredictable patterns). High entropy RESISTS compression. Each legitimate transaction is contextually unique — different patient, different diagnosis, different timing. Discrepancies exhibit LOW entropy (repetitive templates). Low entropy COMPRESSES HEAVILY. Coordination reuses the same pattern, same codes, same amounts even with randomization."

**Why this matters for the deck:** The insight is counterintuitive and MORE powerful when stated correctly. Fraud LOOKS organized. Legitimacy LOOKS chaotic. Physics detects the difference because you can't fake contextual uniqueness at scale.

### 2. FOUR-DIMENSIONAL ENTROPY IS NOW CORE (NOT E/A/T ALONE)

v3.0 adds a mandatory multi-dimensional entropy module to ALL four systems (QED, ProofPack, SpaceProof, AI Flight Recorder). Every system now computes entropy across FOUR independent dimensions:

| Dimension | What It Measures | Formula |
|---|---|---|
| **Temporal** | Timing patterns — when operations occur | H(hour_distribution) + H(day_distribution) |
| **Spatial** | Source/location patterns — where operations originate | H(source_distribution) + H(phase_distribution) |
| **Sequential** | Procedure ordering — what follows what | H(bigram_distribution) |
| **Compression** | Data variability — how much the payload compresses | 1 - (compressed/original) |

**Decision rule:** 2+ violations across dimensions = discrepancy. Not 1. This solves the "legitimate repetition problem" — a dialysis clinic SHOULD have repetitive temporal patterns (3x/week) but shouldn't ALSO have identical sequential patterns AND identical spatial patterns simultaneously.

### 3. SIX PRINCIPLES SUPERSEDE THREE LAWS

v3.0 retains the Three Laws but nests them inside Six Principles:

| # | Principle | Test | What It Means |
|---|---|---|---|
| 1 | Native Provenance | Receipt is PRIMARY output, not log | Operations return (result, receipt) |
| 2 | Cryptographic Lineage | Trace any receipt to genesis | Every receipt has parent_hash |
| 3 | Verifiable Causality | Audit WITHOUT source code | Decisions include input_hashes |
| 4 | Query-as-Proof | Proofs DERIVED, not stored | No pre-computed alerts |
| 5 | Thermodynamic Governance | |ΔS| < 0.01 entropy | Physics-based health, not metrics |
| 6 | Receipts-Gated Progress | No receipt → StopRule | Deployment requires gate passage |

**Pass all 6 → receipts-native. Fail any → receipts-augmented.**

The Three Laws (No receipt → not real, No test → not shipped, No gate → not alive) remain the memorable framing. The Six Principles are the engineering specification behind them.

### 4. DOMAIN COMPOSITIONS EXPANDED

v3.0 mandates multi-dimensional entropy across all four production systems:

| Domain | Required Modules | Critical Scenario |
|---|---|---|
| Telemetry (QED) | core + ledger + detect + anchor + entropy + **multidimensional** | THERMODYNAMIC |
| Discrepancy (ProofPack) | core + ledger + detect + anchor + loop + quantum + **multidimensional** + mcp_server | STRESS |
| Space (SpaceProof) | core + ledger + anchor + sovereignty + **multidimensional** | SINGULARITY |
| Autonomous (AI Flight Recorder) | core + ledger + topology + governance + **multidimensional** | FEEDBACK_LOOP |

### 5. EFFECTIVENESS FORMULA VARIES BY SYSTEM

| System | E Formula | Source |
|---|---|---|
| QED | (H_before - H_after) / n_receipts | entropy.py:84-109 |
| ProofPack | (baseline - current) / actions | effectiveness.py:91 |
| SpaceProof | (H_before - H_after) / n_receipts | meta_integration.py:179 |
| AI Flight Recorder | (H_before - H_after) / H_before | topology.py:97-133 |

The deck shows the CONCEPT (entropy reduction per receipt) without exposing per-system implementation details.

---

## THE STORY IN ONE BREATH

"Every autonomous system makes decisions that cannot be reversed. A Mars rover swarm operating on 22-minute delay. A JADC2 fire-control loop making engagement recommendations in milliseconds. A post-AGI agent managing critical infrastructure at 10,000 decisions per minute. Today, nobody can prove what those decisions were, why they were made, or who was accountable.

Receipts-native architecture solves this at the physics layer. Every operation emits cryptographic proof. Every proof chains into tamper-evident sequences. A continuous meta-loop classifies system behavior using multi-dimensional entropy across four independent axes. Monte Carlo scenarios stress-test the governance system itself to thermodynamic equilibrium. The result: court-admissible, regulator-satisfying, insurer-pricing-grade evidence that an autonomous system did exactly what it claims — or cryptographic proof that it didn't.

We didn't build a monitoring tool. We built the accountability primitive for discontinuous systems."

---

## THREE DELIVERABLES

| # | Deliverable | What It Shows | Emotional Function |
|---|---|---|---|
| **UI-1** | "The Boring Receipt" | Single receipt lifecycle: operation → dual-hash → chain → anchor | "This is simple. This is inevitable." |
| **UI-2** | "The Process" | Screen-recorded: idea → RESEARCHLOOP → multi-modal → Claude Code build | "This guy actually builds. The methodology IS the product." |
| **UI-3** | "The Living System" | YouTube footage + interactive overlay: meta-loop + 4D entropy + Monte Carlo | "This is accountability infrastructure running." |

**Why three:** UI-1 proves the primitive works. UI-2 proves the builder is real. UI-3 proves the system is alive. Together they satisfy the "prove it" mentality at every level: technical, operational, and systemic.

---

## SLIDE-BY-SLIDE ARCHITECTURE (12 SLIDES)

### SLIDE 1: TITLE
**"Receipts-Native Architecture"**
Subtitle: *"Cryptographic Decision Provenance for Discontinuous Systems"*

- The word "discontinuous" is the framing — systems that can't call home, can't be monitored in real-time, can't be trusted on their word alone
- Faint receipt chain pattern at 3% opacity extending edge-to-edge
- Stealth Bomber aesthetic: #0a0a0a background, #E2E8F0 text, no gradients

### SLIDE 2: THE DISCONTINUITY PROBLEM
**RNA Component: LAW 1 (No receipt → not real)**

The problem isn't AI. The problem is *discontinuous accountability* — the gap between when a system acts and when humans can verify.

**Three scenarios where traditional monitoring fails completely:**

**Mars Rover Swarm (Space):** 22-minute light delay. NASA's Starling mission demonstrated autonomous spacecraft swarm coordination in 2025. The 20-year Mars Exploration Plan calls for "energy-aware, collaborative, autonomous vehicles." Swarms make thousands of autonomous decisions before Earth knows anything happened. When a rover damages a geological formation or deprioritizes a critical sample site, mission teams need to reconstruct the decision chain from 4-22 minutes ago. Current approach: mutable telemetry logs that can't prove sequencing, causation, or intent.

**JADC2 Fire-Control Loop (Defense):** DOD Directive 3000.09 requires "appropriate levels of human judgment over the use of force." Joint All-Domain Command and Control propagates autonomous engagement recommendations in sub-second timeframes. After an engagement, the investigation must prove what the system recommended, what information it had, and whether human oversight was meaningfully exercised — not performatively documented. Current approach: system logs that opposing counsel will destroy in court.

**Post-AGI Infrastructure Agent (Governance):** Gartner projects 40% of enterprise apps with AI agents by 2026. Only 6% have advanced security strategy. An AI agent managing power grid allocation, financial settlement, or medical resource distribution makes 10,000 decisions per minute. When outcomes diverge from expectations, stakeholders need to verify the decision chain. Current approach: observability dashboards that show WHAT happened but not WHO DECIDED or WHY, and can't prove the data wasn't altered after the fact.

**Visual concept:** Three panels, each showing a timeline with a gap — the "discontinuity" — between when the system acted and when humans can verify. The gap is RED. Receipts fill the gap (BLUE). Simple. Devastating.

### SLIDE 3: THREE LAWS + SIX PRINCIPLES
**RNA Component: Laws (foundation) + Principles (specification)**

The Three Laws are compile-time constraints, not slogans:

```
LAW 1: No receipt → not real       (StopRule exception halts system)
LAW 2: No test   → not shipped     (CI/CD blocks deployment)
LAW 3: No gate   → not alive       (Production release forbidden)
```

Behind each law, the Six Principles specify WHAT "receipts-native" means:

| Principle | What It Means | Consequence of Violation |
|---|---|---|
| **Native Provenance** | Receipt is PRIMARY output, not afterthought | logger.info() instead of emit_receipt() = not receipts-native |
| **Cryptographic Lineage** | Every receipt traces to genesis block | Missing parent_hash = chain integrity broken |
| **Verifiable Causality** | Audit decisions WITHOUT source code | Decisions missing input_hashes = black box |
| **Query-as-Proof** | Proofs computed on demand, never pre-stored | Pre-computed alerts = stale, falsifiable |
| **Thermodynamic Governance** | System health = entropy conservation |ΔS| < 0.01 | Metrics-based health = gameable |
| **Receipts-Gated Progress** | No receipt → StopRule halts execution | Deployment without gate = unverified code in production |

**The compliance test (one sentence):** Can you reconstruct system state from receipts.jsonl alone? If yes → receipts-native. If no → receipts-augmented at best.

**Visual concept:** Three Laws large on left in monospace. Six Principles as a structured grid on right, smaller. Below: the compliance test question in italic. Below that, a comparison table:

| Architecture | Primary Structure | Verification | Offline Capable | Consensus Required |
|---|---|---|---|---|
| **Receipts-Native** | Receipt (proof) | Cryptographic | Yes | No |
| Blockchain | Block (consensus) | Distributed | No | Yes |
| Event Sourcing | Event (history) | Replay | Yes | No |
| Audit Logging | Log (retrospective) | Manual | Yes | No |

"If you can disable receipts and still operate → not receipts-native."

### SLIDE 4: THE RECEIPT — Anatomy of a Proof
**RNA Component: Receipt Schema + Dual-Hash + Receipt Levels (L0-L4)**

**>>> THIS IS WHERE UI-1 ("The Boring Receipt") LIVES <<<**

Show the lifecycle of a single receipt from birth to anchor. Deliberately "boring" — because boring is revolutionary for discontinuous systems.

**The Pipeline (animated step-by-step in UI-1):**

```
OPERATION OCCURS
  → (Mars rover selects sample site #47, confidence 0.94)
    ↓
DUAL-HASH COMPUTED
  → SHA256 computed independently
  → BLAKE3 computed independently
  → Combined: "sha256_hex:blake3_hex"
  → Two independent algorithms must agree on the same payload
    ↓
RECEIPT EMITTED (mandatory fields from v3.0 schema)
  → receipt_type: "decision"
  → ts: ISO8601 timestamp
  → tenant_id: "mars_rover_fleet_01"
  → payload_hash: "sha256:blake3" of operation data
  → parent_hash: links to previous receipt (cryptographic chain)
    ↓
LEVEL ROUTED
  → L0: Events (raw instrument readings, navigation commands)
  → L1: Agents (rover anomaly detection, communication loss alerts)
  → L2: Deploys (mission parameter updates, science priority changes)
  → L3: Effectiveness (E/A/T scores per rover, mission health metrics)
  → L4: Meta (swarm topology classification, cascade evolution decisions)
    ↓
MERKLE ANCHORED
  → Batch of receipts compressed to single verifiable root
  → merkle_root() computes binary tree of hashes
  → Single root hash proves integrity of entire batch
    ↓
TAMPER-EVIDENT
  → Change ANY receipt → root changes → tampering mathematically provable
  → No trusted third party required — the math IS the trust
```

**The self-verification loop (the kill shot of this slide):**
L4 informs L0. When meta-loop cycle detects topology drift (L4), it adjusts risk gates (L3), which changes what evidence gets flagged (L1), which changes how operations get recorded (L0). **The system watches itself watching itself.** This isn't monitoring bolted on. It's accountability woven into execution.

**Visual for UI-1 (React artifact):**
- Background: #0a0a0a
- Receipt text: JetBrains Mono, #E2E8F0
- Hash computations: animated character-by-character, amber (#F59E0B)
- Merkle tree: trust blue (#3B82F6) connecting lines
- Level routing: faint horizontal layers, receipt drops to correct level
- Interactive: hover any field for explanation, click to expand
- NO animations beyond text reveals and connection lines. Simplicity IS the point.
- Final frame holds: "This happened on Mars. 22 minutes before anyone on Earth knew. The proof was already sealed."
- Duration: 30-45 seconds animated, with presenter controls (no auto-start per Stealth Bomber Doctrine 2)

### SLIDE 5: MULTI-DIMENSIONAL ENTROPY — Four Axes of Truth
**RNA Component: multidimensional/ module (v3.0 ADDITION — the biggest upgrade)**

This is the slide that separates RNA from every other architecture. Not single-metric health checks. Four independent entropy dimensions computed in parallel, with context-aware baselines per operational domain.

**The Four Dimensions:**

| Dimension | What It Measures | How It's Computed | What Violation Means |
|---|---|---|---|
| **Temporal** | When operations occur — timing patterns | H(hour_distribution) + H(day_distribution) | Operations clustering at unusual times |
| **Spatial** | Where operations originate — source/location patterns | H(source_distribution) + H(phase_distribution) | Operations routing through unusual sources |
| **Sequential** | What follows what — procedure ordering | H(bigram_distribution) — transition probabilities | Operations following unusual sequences |
| **Compression** | How variable the data is | 1 - (compressed_size / original_size) | Data too uniform (templated) or too random (injected) |

**The Decision Rule (simple, brutal, correct):**
```
violations = dimensions where measured entropy falls OUTSIDE baseline range
IF len(violations) >= 2: verdict = DISCREPANCY
ELSE: verdict = LEGITIMATE
```

Two or more dimensions out of range = discrepancy. Not one. This solves the **legitimate repetition problem**: a dialysis clinic SHOULD have repetitive temporal patterns (3x/week, same times). That's one dimension of low entropy. But if temporal AND sequential AND spatial are all simultaneously low-entropy, that's coordination — and coordination at that level is discrepancy.

**Context-Aware Baselines (why this works across domains):**

Each operational context has its own expected entropy ranges. The system doesn't apply one-size-fits-all thresholds:

*Space (SpaceProof — 9 entity types):* autonomous_ops, earth_commanded, communication_blackout, orbital_compute, constellation_ops, firmware_update, telemetry_collection, decision_lineage, default

*Defense (AI Flight Recorder — 7 entity types):* routine_navigation, emergency_response, human_supervised, inspection_mode, return_to_base, stuck_agent, default

*Discrepancy Detection (ProofPack — 7 entity types):* primary_care_clinic, emergency_room, dialysis_clinic, surgical_center, pharmacy, vaccination_clinic, default

**The domain examples (no drones, no existing demos):**

*Mars Communication Blackout:* During a 22-minute communication blackout, the rover swarm operates autonomously. The `communication_blackout` baseline expects HIGH temporal entropy (decisions happening at irregular intervals as problems arise), HIGH sequential entropy (novel problem-solving, not routine), but MODERATE spatial entropy (rovers stay in assigned zones). If during a blackout the swarm suddenly exhibits LOW temporal entropy (clock-regular decisions), LOW sequential entropy (identical operation sequences), and LOW spatial entropy (all converging on same coordinates) — that's 3 violations. Something is wrong. The multi-dimensional detection fires BEFORE any human sees the data.

*JADC2 Track Classification:* A `routine_navigation` baseline expects moderate temporal entropy (regular radar sweeps), low sequential entropy (standard track-update-classify cycle), moderate spatial entropy (various sectors). If a hostile engagement scenario shifts to `emergency_response` baseline — high temporal entropy (rapid decisions), high sequential entropy (non-standard procedures), HIGH spatial entropy (multi-sector coordination) — the system automatically adjusts expectations. What looks anomalous under routine baseline is EXPECTED under emergency baseline. Context prevents false positives.

*Post-AGI Infrastructure Management:* An AI agent managing power grid allocation during normal operations follows a `routine` baseline. During a cascading failure event, the agent shifts to `emergency` baseline. Multi-dimensional entropy analysis ensures the agent's emergency response PATTERN matches what emergency response SHOULD look like — high temporal urgency, high sequential novelty, but still operating within spatial bounds of its authorized grid sectors. If the agent's emergency behavior matches a different baseline (say, `firmware_update` — low entropy, repetitive, systematic), that's a signal that the agent may not be responding to the emergency but running a different program entirely.

**Visual concept:** Four parallel vertical columns (one per dimension), each showing a waveform of entropy values over time. A horizontal baseline band in each column shows the expected range. Values inside the band = blue. Values outside = red. Below the columns: "VIOLATIONS: X of 4" with the decision threshold marked. When 2+ go red, the verdict flips. Interactive: click domain tabs (SPACE | DEFENSE | GOVERNANCE) to see different baseline configurations.

### SLIDE 6: THREE-SOURCE EVIDENCE
**RNA Component: Multi-Source Evidence Model**

Trust isn't binary. It's triangulated.

| Source | Trust Level | Space Example | Defense Example | Post-AGI Example |
|---|---|---|---|---|
| Agent Self-Report | Medium | Rover: "Selected site #47, mineral confidence 0.94" | Fire-control: "Track classified hostile, confidence 0.87" | Grid agent: "Allocated 450MW to sector 7, priority critical" |
| External Telemetry | High | Orbiter imaging independently confirms mineral at site #47 | ELINT/SIGINT independently confirms track trajectory | Smart meters confirm 450MW delivered and consumed |
| Third-Party Attestation | Highest | Partner nation's relay confirms rover position/timing | Coalition sensor network corroborates classification | Independent auditor verifies allocation logic in real-time |

**Three edge cases that define the architecture:**

**Sources agree:** High confidence receipt. Evidence is court-grade. Lower risk tier in meta-loop topology classification.

**Sources contradict:** `contradiction_receipt` (L1) fires immediately. System escalates to HITL. The contradiction IS the signal — not a bug, a feature. On Mars with 22-minute delay, the contradiction receipt queues for ground review. But the receipt EXISTS from the moment of contradiction. The proof that something went wrong is sealed before any human can intervene to cover it up.

**Sources go silent:** Heartbeat monitor fires parametric trigger. Expected evidence does not arrive within timeout window (default: 30s interval, 90s silence threshold = grace_multiplier × 3). **Silence IS evidence.** The absence of a receipt is itself a provable event. The system doesn't need to know WHY silence occurred to know THAT it occurred and WHEN it started.

**Visual concept:** Three parallel streams (blue/amber/green for agent/telemetry/attestation) converging. Show a contradiction scenario: streams diverge, red flash, escalation branch to HITL. Show a silence scenario: one stream flatlines, heartbeat timer counts up, trigger fires at threshold. These edge cases are what matters for discontinuous systems.

### SLIDE 7: THE META-LOOP — Physics-Based Governance
**RNA Component: Meta-Loop v2.1 — 8-Phase Cycle + E/A/T + Topology Classification**

**>>> THIS IS WHERE UI-3 ("The Living System") FOOTAGE ANCHORS <<<**

The meta-loop is the heartbeat. Every 60 seconds, it processes evidence, computes multi-dimensional entropy, classifies system topology, and triggers governance actions. Every phase emits a receipt. 11 receipt types total, every cycle.

**The 8-Phase Cycle (from Meta-Loop v2.1):**
```
SENSE → ANALYZE → CLASSIFY → HARVEST → HYPOTHESIZE → GATE → ACTUATE → SELECT
  ↑                                                                          ↓
  └──────────────────── 60 seconds, continuous ─────────────────────────────┘
```

| Phase | What Happens | Receipt Emitted |
|---|---|---|
| SENSE | Collects evidence from all subsystems (L0 receipts, all sources) | sense_receipt |
| ANALYZE | Computes E/A/T metrics (Sliced Wasserstein for T, 50 1D projections, O(N log N)) | analyze_receipt |
| CLASSIFY | Assigns topology with **confidence-gated fallback** (below 0.85 → enrich before deciding) | topology_receipt |
| HARVEST | Sorts agent queues by topology classification | harvest_receipt |
| HYPOTHESIZE | Proposes risk tier adjustments based on topology changes | hypothesis_receipt |
| GATE | Routes proposals through HITL/HOTL based on risk level | gate_receipt |
| ACTUATE | Executes approved actions, fires parametric triggers | actuate_receipt |
| SELECT | Determines survivors, identifies candidates for cascade spawning | selection_receipt |

**E/A/T: Three Dimensions of System Governance (from FULCRUM v4)**

- **E (Effectiveness):** Entropy reduction per receipt over defined state space. `E = (H_before - H_after) / n_receipts`. High E = system producing order. Low E = system adding noise. Measured using Shannon entropy over domain-specific state dimensions with discretization bins defined in domain YAML configs.

- **A (Autonomy):** `auto_approved / total_actions`. Fraction of operations passing gates without human intervention. High A = self-governing within rules. Low A = constant human override required.

- **T (Transfer):** Similarity to known-good patterns cross-domain. Computed via **Sliced Wasserstein** (NOT cosine similarity): projects distributions onto 50 random 1D slices, computes 1D Wasserstein on each (sorting, O(N log N)), averages. Hard compute budget: 5 seconds max per cycle. If exceeded → defer T update, emit budget_violation_receipt.

**Topology Classification (one equation decides fate):**
```
IF E >= V_esc[domain] AND A > 0.75:  topology = "OPEN"    → Graduate
ELIF T > 0.70:                       topology = "HYBRID"  → Transfer cross-domain
ELSE:                                topology = "CLOSED"  → Keep optimizing
```

**Confidence-Gated Fallback (v2.1 addition):** Every topology assignment has a confidence score. If confidence drops below threshold, the system triggers external context enrichment (temporal graph, web search, additional evidence collection) BEFORE making the classification. It doesn't guess. It gets smarter before deciding. The fallback itself emits a receipt.

**What topology decisions mean:**

| Topology | What Happens | Space Example | Defense Example |
|---|---|---|---|
| **OPEN** | Pattern graduates → cascade spawns 5 variants to shadow environment | Rover navigation strategy proven effective → spawn 5 mutations for other terrain types | Engagement recommendation pattern validated → spawn variants for different threat profiles |
| **HYBRID** | Pattern transfers to adjacent domain | Mars orbital compute pattern applies to asteroid belt navigation | JADC2 pattern transfers to allied coalition's command structure |
| **CLOSED** | Pattern keeps optimizing internally | New geological analysis strategy still learning → needs more cycles | Novel threat detection approach needs more validation data |

**The Pulsar Metaphor (from Meta-Loop v2.1):** Borrowed from astrophysics. Closed field lines = pattern optimizes internally. Open field lines = pattern graduates to autonomy. The separatrix = effectiveness threshold (escape velocity). Physics decides topology, not engineers.

**Cascade Spawning (from Meta-Loop v2.1 — regulatory compliant):**
When a pattern achieves escape velocity:
1. Spawn CASCADE_MULTIPLIER (5x) variants with mutation rate 0.05
2. Recombine each variant with similar known patterns
3. Deploy ALL variants to SHADOW ENVIRONMENT ONLY
4. Backtest in shadow — success rate must reach 0.75
5. Queue successful variants for HITL approval
6. HITL approves → `regulatory_filing_receipt` emits with model diff, jurisdiction, backtest results
7. ONLY THEN promote to live

**No variant reaches production without human approval and a regulatory filing receipt.**

**Visual concept for UI-3:** The 8-phase cycle as a circular diagram pulsing every 60 seconds. E/A/T gauges in center. Topology indicator changes state (OPEN=bright, CLOSED=dim, HYBRID=mixed). When a pattern graduates → cascade animation: one node splits into five, deploys to "shadow" region, backtests run, success indicators appear. The whole thing loops continuously while receipt stream flows in the overlay.

### SLIDE 8: MONTE CARLO — Proving Dynamics, Not Functions
**RNA Component: Monte Carlo v2.0 — 8 Mandatory Scenarios + 5 Constraint Validators**

**The paradigm:** Unit tests prove functions return correct values. Monte Carlo proves the SYSTEM reaches stable equilibrium under extreme conditions. Microscopic correctness + macroscopic correctness = production-ready.

**8 Mandatory Scenarios (no exceptions, from Monte Carlo v2.0):**

| # | Name | Cycles | Pass Criteria | What It Proves For Discontinuous Systems |
|---|---|---|---|---|
| 1 | **BASELINE** | 1000 | 99.9% completion, 0 violations | Normal operations are clean over sustained duration |
| 2 | **STRESS** | 500 | ≥95% accuracy at 5x volume, <5.5GB RAM | System holds under 5x Mars swarm data volume |
| 3 | **TOPOLOGY** | 100 | ≥98% classification accuracy | Correctly categorizes agent behavior even under pressure |
| 4 | **CASCADE** | 100 | Exact variant count, all backtests pass | Evolution of strategies produces no rogue variants |
| 5 | **COMPRESSION** | 200 | Meta-pattern outperforms both parents by ≥5% | System actually improves — not just survives |
| 6 | **SINGULARITY** | 2000* | Population converges, entropy goes negative | System achieves self-optimization equilibrium |
| 7 | **THERMODYNAMIC** | 1000 | \|Δentropy\| < 0.01 EVERY cycle | Conservation law holds — information-theoretic first law |
| 8 | **FEEDBACK_LOOP** | 500 | Correction rate decreases 50%, model improves | System learns from human oversight, not just complies |

*Early termination on convergence.

**5 Constraint Validators (run EVERY cycle):**

| Validator | Condition | Action on Violation |
|---|---|---|
| **ConservationValidator** | \|entropy_in - (entropy_out + work)\| < 0.01 | **HALT** (thermodynamic law broken) |
| **BoundaryValidator** | Open patterns meet domain escape velocity | Emit violation |
| **PopulationValidator** | Pattern count < max_sustainable | Emit violation |
| **ReceiptValidator** | All operations emit receipts | Emit violation |
| **LearningValidator** | Correction rate decreasing over time | Emit violation |

**Composable Stress Vectors (from Monte Carlo v2.0):**
```
multiply_volume(5.0)           — 5x receipt rate
vary_effectiveness(0.5, 1.0)   — Random pattern effectiveness
inject_entropy_noise(0.2)      — ±20% entropy fluctuation
inject_human_corrections(0.05) — 5% of decisions get corrected
simulate_policy_drift(0.1)     — 10% policy change mid-run
```

**The THERMODYNAMIC scenario is the kill shot.** It proves the system obeys conservation of entropy — the information-theoretic equivalent of the first law of thermodynamics. If total entropy changes by more than 0.01 per cycle across 1000 cycles, something is fundamentally wrong. Not a software bug. A physics violation. This isn't testing. It's certification.

**The FEEDBACK_LOOP scenario is the learning proof.** It validates that human corrections → training examples → improved model. If correction rate doesn't decrease over 500 cycles, the system isn't learning from oversight — it's just complying. The deck should emphasize: this scenario proves the GOVERNANCE SYSTEM ITSELF improves, not just the operations it governs.

**Runtime:** All 8 scenarios run in parallel (7 workers) in ~35 minutes total. Not a quarterly audit. An automated certification that runs before every deployment.

**Visual concept:** Grid of 8 scenario cards, each showing name, cycle count, pass/fail indicator (all green). Below: the 5 validators as a horizontal status bar. Below that: "Every system. Every deployment. 8 scenarios. 5 validators. Zero exceptions." Feels like a flight certification checklist — because it IS one.

### SLIDE 9: CONTEXT ENGINEERING + MCP
**RNA Component: Context Engineering (replaces prompt engineering) + MCP Protocol**

Two concepts, one slide, because they answer the same question: how does the RIGHT information reach the RIGHT decision at the RIGHT time?

**Context Engineering (from RNA v3.0):**

| Query Type | Primary Source | Fallback | Confidence Threshold |
|---|---|---|---|
| Historical fact | Receipt ledger | — | 0.95 |
| Pattern match | META-LOOP topology | Receipt scan | 0.85 |
| External validation | Web search | Fail gracefully | 0.70 |
| Cross-domain | Temporal graph | Cosine similarity | 0.80 |

Auto-fallback: If primary confidence < threshold → system escalates automatically. No human intervention required for routing. The routing decision itself emits a receipt.

**The paradigm shift (from RNA v3.0):**
OLD: Architecture describes what components DO.
NEW: Architecture prescribes how components DECIDE which context to use.
Receipts aren't storage — they're **context sources** in a self-correcting pipeline.

**MCP Integration (from RNA v3.0):**

Any agent. One URL. Zero code changes. Full accountability.

```json
{
  "mcpServers": {
    "receipts": {
      "command": "python",
      "args": ["-m", "system_name.mcp_server"],
      "tools": ["query_receipts", "verify_chain", "get_topology"]
    }
  }
}
```

Three required tools (minimum viable):
- `query_receipts(filters)` → Returns matching receipts
- `verify_chain(start, end)` → Returns integrity boolean
- `get_topology(pattern_id)` → Returns open/closed/hybrid

**Space:** Mars rover swarm agents connect via MCP to a local receipts server on the lander. Decisions receipted, chained, anchored locally. During communication windows, Merkle roots transmit to Earth — compact, verifiable, tamper-evident. Full accountability over a 22-minute gap using kilobytes, not megabytes.

**Defense:** JADC2 nodes add one MCP URL. Every engagement recommendation, sensor fusion output, and command decision emits a receipt. Post-engagement review queries the chain. Chain verification proves nothing was altered. The receipt chain IS the investigation file.

**Post-AGI:** Any advanced AI agent adds the MCP server. From day one, every decision has cryptographic provenance. Governance-wrap an agent system without degrading performance — receipts add nanoseconds of overhead, not seconds.

**Visual concept:** Left side: context engineering routing diagram (query → confidence check → primary or fallback). Right side: MCP integration diagram showing "Agent + 1 URL = Full Accountability." Below: three domain tabs showing the same MCP integration serving different contexts.

### SLIDE 10: HITL/HOTL — Who Decides What
**RNA Component: Human-in-the-Loop / Human-on-the-Loop Decision Matrix + Gate Receipts**

| Risk Level | Model | Human Role | Gate Receipt Contains |
|---|---|---|---|
| **CRITICAL** | Human-in-Loop (HITL) | Approves each decision | risk_level, approval_type, approver_id, decision_hash |
| **HIGH** | Human-on-Loop (HOTL) | Monitors, intervenes on trigger | risk_level, monitor_id, trigger_type |
| **MEDIUM** | Autonomous + Audit | Reviews samples post-hoc | risk_level, auto_approved, audit_queue_id |
| **LOW** | Full Autonomous | Audit trail only | risk_level, auto_approved |

**Every decision emits gate_receipt.** The risk level, approval type, and approver ID are permanently recorded. This satisfies DOD 3000.09 not through policy documents but through cryptographic proof that human judgment was exercised at the right level.

**The risk level isn't hardcoded — it's COMPUTED from E/A/T entropy:**
- Low E (system not producing order) + Low A (frequent human overrides) → CRITICAL risk level → HITL
- High E + High A + High T (cross-domain validation) → LOW risk level → Full Autonomous

The system KNOWS which decisions need humans because the math tells it, not because a developer guessed a threshold.

*Mars:* Rover drilling decision = MEDIUM (autonomous with audit). Swarm-wide redirect to unexpected feature = CRITICAL (HITL, 22-minute delay accepted).
*Defense:* Track classification update = LOW. Engagement recommendation = CRITICAL (commander approves, gate_receipt proves it).
*Post-AGI:* Routine allocation = LOW. Emergency reallocation during cascading failure = CRITICAL.

### SLIDE 11: THE ARCHITECTURAL MOAT
**RNA Component: Compression = Discovery (CORRECTED per v3.0) + Structural Advantages**

**The insight (stated correctly per v3.0):**

Legitimate operations exhibit HIGH entropy — they're contextually unique. Different patient, different diagnosis, different timing, different provider. High entropy RESISTS compression. You can't compress uniqueness.

Discrepancies exhibit LOW entropy — they're repetitive templates. Coordination reuses the same patterns, same codes, same amounts, same timing. Low entropy COMPRESSES HEAVILY. You can't fake contextual uniqueness at scale.

**This is counterintuitive and that's why it works:** Fraud LOOKS organized. Legitimacy LOOKS chaotic. Physics detects the difference because you can't manufacture genuine entropy.

**Multi-dimensional entropy (Slide 5) operationalizes this insight.** Single-dimensional compression ratio catches obvious fraud. Four-dimensional analysis with context-aware baselines catches sophisticated coordination that passes any single metric.

**Trust comparison (architectural disqualification):**

| Dimension | Observability Incumbents | Receipts-Native |
|---|---|---|
| Data integrity | Mutable logs | Immutable dual-hash receipts |
| Verification model | Trust the vendor | Verify the math |
| Evidence scope | What happened | What + who decided + why + at what confidence |
| Compliance approach | Point-in-time exports | Continuous cryptographic chain |
| Agent integration | SDK/API wrappers per agent | MCP: one URL, zero code |
| System learning | Static dashboards | Meta-loop: topology evolves every 60 seconds |
| Validation method | Load testing | Monte Carlo: 8 scenarios to thermodynamic equilibrium |
| Governance model | Policy documents | Gate receipts with HITL/HOTL + RACI + reason codes |
| Anomaly detection | Single metrics, fixed thresholds | 4D entropy, context-aware baselines, 2+ violation rule |
| Offline capability | Requires connectivity | Full verification without network |

Incumbents would need to rebuild from the ground up. This isn't a feature gap. It's an architectural canyon.

### SLIDE 12: THE PROCESS IS THE PROOF (CLOSING)
**RNA Component: Build Gates (T+2h, T+24h, T+48h) + RESEARCHLOOP v3**

**>>> THIS IS WHERE UI-2 ("The Process") VIDEO ANCHORS <<<**

This slide shows the methodology that built the architecture. The process of building receipts-native systems IS receipts-native.

**The Build Loop (from RESEARCHLOOP v3 + Build Gates):**
```
IDEA
  → RESEARCHLOOP v3 (Phase 0: Load Context → Phase 1: Research → Phase 2: Baseline → Phase 3: Outlier Expansion)
  → MULTI-MODAL ORCHESTRATION (5 LLMs: Grok research, Claude strategy, Claude Code execution)
  → SPECIFICATION (receipts-native build strategy document — strategist output, not code)
  → CLAUDE CODE EXECUTION (CLAUDEME-compliant, receipt-emitting)
  → T+2h GATE (gate_t2h.sh: dual_hash() emits valid receipt, CLI produces JSON)
  → T+24h GATE (gate_t24h.sh: all modules, 80% coverage, BASELINE passes)
  → T+48h GATE (gate_t48h.sh: 100% coverage, all 8 scenarios pass)
  → SHIP (with MANIFEST.anchor proving every step)
```

**The video for this slide IS the real screen recording.** Idea to deployed system. Every step visible. Every gate passed. Every receipt emitted.

The process video is the meta-demonstration: "We don't just build accountability systems. We build them accountably. And we show you the whole thing."

**Close with:**
- "We welcome the audit. We welcome the due diligence. We welcome the red team."
- "Every claim in this presentation has a receipt."
- "Six principles. Three laws. One question: Can you prove what your system did?"
- **"No receipt → not real."**
- Contact. Next steps.

---

## THREE UI/VIDEO DELIVERABLES — BUILD SPECIFICATIONS

### UI-1: "The Boring Receipt" (React Artifact)

**Format:** Interactive React component (.jsx) + screenshot for deck embedding
**Duration:** 30-45 seconds animated, with presenter controls (spacebar/button, no auto-start)

**Scene Flow:**

1. **OPERATION** (0-5s): Monospace text appears — "Mars Rover-7: Selected sample site #47 based on mineral signature confidence 0.94". Subtle pulse indicates operation occurring. Dark background (#0a0a0a).

2. **DUAL-HASH** (5-12s): Two hash computations run in parallel — SHA256 left, BLAKE3 right. Characters appear sequentially (typewriter effect). Both resolve to hex strings. Combined dual-hash appears center: `sha256_hex:blake3_hex`. Brief label: "Two independent algorithms verify the same payload."

3. **RECEIPT ASSEMBLY** (12-20s): Receipt JSON assembles field by field. Each field appears with a faint label explaining purpose:
   - receipt_type → "What kind of operation"
   - ts → "When it happened (ISO8601)"
   - tenant_id → "Which system"
   - payload_hash → "Cryptographic fingerprint"
   - parent_hash → "Links to previous receipt (the chain)"

4. **LEVEL ROUTING** (20-25s): Five horizontal layers appear (L0-L4). Receipt drops to L0 (Events). Faint arrows show L4 → L0 feedback loop. Label: "L4 meta-loop will use this receipt to compute topology."

5. **MERKLE ANCHOR** (25-35s): This receipt joins a batch. Binary tree builds upward — hashes combining pairwise. Single root emerges. Label: "Tamper any receipt in this batch → the root changes → mathematically provable."

6. **HOLD** (35-45s): Complete chain visible. Final text overlay: "This happened on Mars. 22 minutes before anyone on Earth knew. The proof was already sealed."

**Design System (Stealth Bomber Doctrine 1):**
- Background: #0a0a0a (deep charcoal, never pure black)
- Text: #E2E8F0 (bone white, readable not blinding)
- Hash values: #F59E0B (amber, indicates computation)
- Merkle tree lines: #3B82F6 (trust blue)
- Level routing: #4B5563 (muted gray, not green — green is toys)
- Typography: JetBrains Mono for all data, Georgia for labels
- NO neon (#00FF00), NO cyberpunk purple, NO gradients, NO glows
- Interactive: hover for explanation, click to expand hash details
- "System Armed" subtle pulse when idle (Doctrine 5: never show dead black screen)

### UI-2: "The Process" (Screen Recording — NOT GENERATED)

**Format:** Real screen recording by Bubba, 3-5 minutes full length, 60-90 second highlight cut
**This is NOT generated by AI. This is documentation of actual methodology.**

**Recording Structure:**

1. **THE IDEA** (0-30s): Bubba describes a new RNA component to build. Something visible enough to demonstrate methodology (new Monte Carlo scenario, new compliance formatter, new domain baseline config). Quick, clear articulation of what's being built and why.

2. **RESEARCHLOOP** (30-90s): Show multi-modal orchestration in action:
   - Grok running research validation
   - Claude generating strategic architecture
   - Quick web search for domain validation
   - The specification document EMERGING from research
   - Fast-cut between screens. Point isn't content of each response — it's the PROCESS of triangulating across sources and the RESEARCHLOOP phases executing.

3. **BUILD STRATEGY** (90-120s): Specification document appears. Quick scroll showing chunked structure, gated deliverables, receipts-native patterns. This IS the handoff to Claude Code — strategist output, not code.

4. **CLAUDE CODE EXECUTION** (120-210s): Terminal appears (JetBrains Mono, dark theme matching deck). Claude Code executes the specification. Tests run. Receipts emit (actual receipt JSON visible in terminal output). T+2h gate passes. Show the actual receipt appearing. Show test output: green.

5. **THE RECEIPT OF THE BUILD** (210-240s): The build process itself has receipts. Git commit includes receipt metadata. MANIFEST.anchor created. "We built this accountably. Here's the proof."

**Production Notes:**
- Record at 1080p minimum
- Terminal: JetBrains Mono, dark theme matching deck palette
- Speed up slow sections (pip installs, long test runs) by 4-8x
- Narrate live or add voiceover post
- Subtle annotations at key moments (receipt emitting, gate passing, hash verifying)
- Cut cleanly — no fumbling, no errors left in (professionalism, Doctrine 5)

**Gemini B-roll (enhancement, not replacement):** Abstract data flow visualizations, receipt chain animations, hex grid overlays — intercut with real footage to make it feel polished without losing authenticity.

### UI-3: "The Living System" (YouTube Footage + Interactive Overlay)

**Format:** Gemini Veo generated footage (90-120 seconds) + React overlay component (synced to video)

This is the signature piece. Abstract visualization of the meta-loop running, with a receipt overlay showing value accumulating.

**YouTube Footage (Gemini Veo):**

**Scene 1: The Meta-Loop Pulse (0-20s)**
- Dark void. Circular structure appears — the 8-phase cycle.
- Each phase illuminates in sequence: SENSE (blue data collection pulse), ANALYZE (amber computation rings), CLASSIFY (topology indicator resolves — OPEN/CLOSED/HYBRID), HARVEST through SELECT follow.
- Cycle completes. Repeats. 60-second heartbeat.
- Each phase emits a tiny receipt icon that drops into a growing chain below.
- Text: "Every 60 seconds. Every autonomous system. 11 receipt types per cycle."

**Scene 2: Four-Dimensional Entropy Space (20-40s)**
- Four vertical columns materialize — Temporal, Spatial, Sequential, Compression.
- Each shows an entropy waveform oscillating within a baseline band.
- Normal operation: all four within bounds. System reports "LEGITIMATE."
- Anomaly injection: Temporal drops below baseline. Then Sequential. Two violations. Verdict flips to "DISCREPANCY." Red flash on the two violating dimensions.
- Text: "Four dimensions. Context-aware baselines. Two violations = discrepancy."

**Scene 3: E/A/T Topology Classification (40-60s)**
- Three-dimensional space appears — E axis, A axis, T axis.
- Data points cluster. Escape velocity surface visible as a boundary.
- A point crosses the boundary — achieving OPEN topology. 
- Cascade spawning: one point becomes five. Five variants deploy to shadow region (slightly transparent/ghosted).
- Backtest results appear: 4 of 5 pass. One fails (removed). Four queue for HITL.
- HITL approval animation: human icon taps "approve." regulatory_filing_receipt emits.
- Approved variants promote from shadow to live (opacity goes to full).
- Text: "Physics decides topology. Humans approve promotion. Receipts prove both."

**Scene 4: Monte Carlo Stress (60-85s)**
- 8 scenario cards from Slide 8 appear in a grid.
- STRESS fires: 5x volume floods the system. Receipt rate accelerates. Meta-loop holds.
- THERMODYNAMIC fires: entropy gauge holds rock-steady at |Δ| < 0.01. Conservation law holds. 
- FEEDBACK_LOOP fires: human corrections inject (5% rate). Correction rate visibly decreases over cycles. System is LEARNING.
- All 8 resolve: green checkmarks.
- 5 constraint validators flash green below.
- Text: "Not tested. Proven. To thermodynamic equilibrium."

**Scene 5: Cross-Domain Convergence (85-110s)**
- Validated system sits at center.
- Three domain connections materialize:
  - LEFT: Mars swarm (small vehicles with receipt chains trailing, 22-minute delay gap visible, receipts sealed in the gap)
  - RIGHT: Defense grid (interconnected nodes with gate_receipts flashing at decision points, HITL gates visible at CRITICAL nodes)
  - TOP: Post-AGI infrastructure (agent network with continuous receipt emission, multi-dimensional entropy bars visible on each agent)
- All three connect to same central architecture. Receipt chains from all domains feed into a single Merkle anchor.
- Text: "One architecture. Every discontinuous system. Every domain."

**Scene 6: Close (110-120s)**
- Everything contracts to a single receipt chain extending to vanishing point.
- Text: "No receipt → not real."
- Northstar AO logo.

**Visual Directives (Stealth Bomber Doctrine 1, strictly enforced):**
- Background: #0a0a0a throughout. No exceptions.
- Color is ALARM, not decoration: 90%+ of frames are black/white/gray
- Trust blue (#3B82F6) for receipt chains and verification
- Amber (#F59E0B) for computation/analysis moments
- Red (#DC2626) ONLY for violations, contradictions, threats
- Green (#10B981) ONLY for validation passing (use sparingly — muted)
- Typography: monospace only (JetBrains Mono aesthetic)
- Camera: static or slow dolly. No handheld. No rapid cuts. Precision.
- Motion: mechanical, precise, deliberate. Bloomberg terminal meets architectural blueprint.
- NO: particle effects, matrix rain, glowing orbs, neon, cyberpunk, lens flares

**Interactive Overlay (React Component, runs alongside video):**

**Left column (30% width) — Receipt Feed:**
- Receipts appear in real-time synced to video scenes
- Each shows: type (sense/analyze/classify/topology/cascade/etc.), timestamp (incrementing), hash (truncated 8 chars)
- Color-coded by receipt level: L0 dim gray, L1 slightly brighter, L2-L3 standard, L4 bright
- Last 5 receipts visible, STATIC (Doctrine 5: no scrolling, fixed-height container)
- New receipts push old ones down

**Center (transparent, overlaid on video) — Status:**
- Current meta-loop phase indicator (8 dots in circle, active one highlighted)
- Cycle count: incrementing integer
- E/A/T gauges: three small horizontal bars
- Topology indicator: OPEN / HYBRID / CLOSED with color

**Right column (25% width) — "ACCOUNTABILITY VALUE GENERATED":**
- Three counters incrementing with each receipt:
  - **Compliance automation:** receipts × per-receipt compliance value = $ saved vs manual audit
  - **Risk quantification:** topology classifications × pricing precision value = $ in insurance accuracy
  - **Legal defense:** Merkle anchors × evidence grade value = $ in court-admissible proof
- Running total at bottom, accumulating
- **This counter is the heartbeat.** Receipts flow → value compounds. That's the entire business model.

**Domain tabs at bottom:** SPACE | DEFENSE | GOVERNANCE — click to switch receipt stream context, ROI math, and baseline configurations.

---

## WHAT TO SHOW vs. WHAT TO PROTECT

### SHOW (proves architecture without exposing implementation)

- Three Laws + Six Principles (concept level)
- 8-phase cycle names and sequence
- E/A/T concept: three dimensions of system governance (effectiveness, autonomy, transfer)
- Topology concept: OPEN/CLOSED/HYBRID classification
- Multi-dimensional entropy: four dimensions (temporal, spatial, sequential, compression)
- The 2+ violation decision rule (concept)
- Context-aware baselines: concept that different operational contexts have different expected ranges
- Monte Carlo: 8 scenario names and pass criteria
- 5 Constraint validators: names and concepts
- Receipt levels: L0-L4 hierarchy and L4→L0 self-verification loop
- Compression = Discovery: the CORRECTED insight (legitimate = high entropy, discrepancy = low entropy)
- MCP integration: one-URL zero-code concept
- HITL/HOTL matrix: risk levels and human oversight model
- Context engineering: confidence-gated source routing concept
- Build gates: T+2h / T+24h / T+48h
- RESEARCHLOOP methodology: phases and purpose
- Confidence-gated fallback: concept that system enriches context before deciding when uncertain
- Heartbeat monitoring: silence IS evidence
- Three-source evidence: agent + telemetry + attestation trust model
- Cascade spawning: concept of shadow environment → backtest → HITL → promote
- Sliced Wasserstein: concept of efficient cross-domain similarity (NOT the algorithm details)
- Domain entity type counts (7-9 types per domain)
- Architectural comparison table vs incumbents
- Receipt count: 11 types per meta-loop cycle

### PROTECT (state secrets — if showing it lets a funded competitor replicate in 6 months, don't show it)

- Escape velocity thresholds per domain (ESCAPE_VELOCITY dict values)
- E/A/T computation formulas per system (the four different implementations)
- Shannon entropy implementation details (PLANCK_ENTROPY constant, edge case handling)
- Sliced Wasserstein algorithm specifics (50 projections, O(N log N) sorting, 5s budget)
- Confidence fallback threshold value (0.85)
- Cascade spawning parameters (mutation rate 0.05, backtest threshold 0.75, multiplier 5)
- Topology classification algorithm internals beyond the one-equation concept
- Context-aware baseline ranges per entity type (the actual numeric ranges)
- Glyph schema details (Intent/Evidence/Decision/Anchor field structures)
- Receipt schema field-level details beyond concept (full JSON schema)
- SLO thresholds and stoprule conditions (specific numbers)
- State-space mapping protocol details (discretization bins, domain YAML internals)
- Compression ratio formulas per system (the four different implementations)
- Multi-dimensional detection source code (detect.py internals)
- Patent claim language (narrow claims, domain-specific claims)
- AI Flight Recorder RACI implementation details
- SpaceProof sovereignty score formula (internal_rate vs external_rate calculation)
- Heartbeat configuration values (30s interval, 3x grace multiplier)
- Feature flags and their states
- File:line references to any implementation

---

## BUILD SEQUENCE

```
1. ALIGN (this document — Bubba reviews, confirms direction)
2. UI-1 BUILD (React artifact: "The Boring Receipt")
   → Interactive receipt lifecycle visualization
   → Screenshot for deck embedding
   → Test: non-technical viewer can explain what a receipt is after watching
3. DECK BUILD (Claude Code: .pptx using python-pptx)
   → 12 slides, Stealth Bomber aesthetic
   → Placeholder slots for UI-1 screenshot, UI-2 video thumbnail, UI-3 video/overlay
   → All text finalized from this strategy document
   → Visual SLOs enforced: no neon, no green-as-success, terminal discipline
4. UI-2 RECORDING (Bubba: real screen capture)
   → Follow recording structure from spec above
   → 3-5 minutes full, 60-90 second highlight cut
   → Gemini generates B-roll for intercut
5. UI-3 BUILD
   → Gemini Veo: 90-120 second abstract footage (6 scenes)
   → Claude/React: interactive overlay component
   → Integration: overlay synced to footage timing
6. INTEGRATION
   → UI-1 screenshot embedded in Slide 4
   → UI-2 thumbnail/link embedded in Slide 12
   → UI-3 thumbnail/link embedded in Slide 7
   → PDF export for distribution
7. QA GATE
   → Show to 3-5 non-technical viewers
   → ≥95% can explain what receipts-native means
   → ≥70% say "I want to learn more" (interest signal)
   → ≥80% can articulate why incumbents can't replicate
   → 0% confusion about compression=discovery direction
```

---

## FINAL CHECK: WHAT MAKES THIS DECK DIFFERENT FROM v2.0

| Dimension | v2.0 | v2.1 |
|---|---|---|
| Compression = Discovery | WRONG (legitimate compresses well) | CORRECT (legitimate = high entropy, resists compression) |
| Entropy model | E/A/T only | E/A/T + 4-dimensional multi-dim (temporal/spatial/sequential/compression) |
| Principles | Three Laws only | Three Laws + Six Principles (v3.0) |
| Domain focus | Mixed (drones crept in) | Pure: Space / Defense / Post-AGI only |
| Domain compositions | Generic | Verified: QED, ProofPack, SpaceProof, AI Flight Recorder with mandatory multidimensional/ |
| UI deliverables | Concepts | Three fully specified: UI-1 (boring receipt), UI-2 (process video), UI-3 (living system) |
| Process video | Mentioned | Full recording structure, production notes, Gemini B-roll spec |
| Effectiveness formula | Single formula | Acknowledged: varies per system (concept only, details protected) |
| Architectural comparison | 8 dimensions | 10 dimensions (added anomaly detection, offline capability) |
| Confidence-gated fallback | Mentioned | Fully integrated into meta-loop slide with receipt emission |
| Cascade spawning | Concept | Full regulatory-compliant pipeline: shadow → backtest → HITL → regulatory_filing_receipt → promote |
| Constraint validators | Not in v2.0 | 5 validators specified, run every cycle |
| Stress vectors | Not in v2.0 | 5 composable vectors specified |
| Baseline types | Generic | Actual entity type counts: 9 (Space), 7 (Defense), 7 (Discrepancy) |
| Receipts per cycle | Not specified | 11 receipt types per meta-loop cycle |
| State secrets | Basic list | Comprehensive with rationale: "if funded competitor can replicate in 6 months, don't show" |

---

*No receipt → not real. No test → not shipped. No gate → not alive.*
*Pass all 6 principles or fail. Physics decides, not engineers.*