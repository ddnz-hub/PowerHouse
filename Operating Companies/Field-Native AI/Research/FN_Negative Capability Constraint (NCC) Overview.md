# FN Negative Capability Constraint (NCC) Overview

**Source**: `FN_Negative Capability Constraint (NCC) Overview.pdf` (converted to markdown)  
**Status**: rewrite for clarity + recontextualisation only; no new claims added.  

---

## 0. Constitutional context (written later)

This research artefact lives downstream of authored orientation and stewardship constraints.

- **Orientation (PowerHouse)**: holds authored ground; does not interpret or execute.  
- **Stewardship (Inverse)**: holds interpretive sovereignty (sequencing, constraint, pause, revocation); non‑executing.  
- **Execution (Field‑Native AI / OpCo)**: executes under constitution, where consequence binds.

This document is included to support **inspectable derivation**, preserve **boundary**, and make **refusal/pause** structurally available under pressure.

### 0.3 Placement in the Field‑Native system

- A Field‑Native framing of NCC for implementers: what must be structurally refused and how “hold” remains legitimate.
- Directly supports: **Constitution** (role of models; refusal; anti‑collapse gates) and **Investor Memo** (why refusal matters).
- Use as: an executive‑readable bridge between theory and implementation constraints.

---

## 1. Rewritten content (markdown reflow)

1) Negative Capability Constraint 

Pure hypothesis: 

Emergence does not arise from complexity alone, but from the sustained 
holding of unresolved pressure without smoothing, avoidance, or coercion. 

Negative capability constraint (NCC): 
A system must retain the ability to remain coherent in unresolved pressure by refusing 
three reflexes: 

1.  No Smoothing 

- Do not reduce variance, average away incompatibilities, or “harmonise” 

frames to produce comfort-coherence. 

2.  No Avoidance 

- Do not route around the pressure via topic shifts, deferrals, 

meta-explanations, or “helpful” reframes that dissolve the core conflict. 

3.  No Coercion 

- Do not force convergence through authority, reward hacking, or rule-based 

collapse that terminates exploration before structural integration. 

Minimal formalization  

NCC is satisfied if and only if the system can: 

- Represent multiple incompatible frames concurrently (no collapse), 
- Maintain an explicit “unresolved” epistemic state (no pretending), 
- Sustain pressure above a threshold (no diffusion), 
- Permit convergence only when it is internally generated (no forcing). 

Diagnostic: “Do we still have negative capability?” 

We can treat these as pass/fail checks: 

- Variance preserved: do distinct frames remain distinct in the representation, or get 

- blended?

- Pressure retained: does the system keep the contradiction alive long enough to 

- reorganize, or does it end it quickly?

- Resolution integrity: when a synthesis appears, does it reduce contradiction by 

adding structure, or by suppressing one side? 

 
 

---

2) Mapping NCC to LLM Training, Inference & 
Governance 

The following mapa failure-mode prevention + enabling conditions at each layer. 

A) Training Layer 

What breaks NCC in training 

1.  Preference optimization that rewards “pleasant coherence” 

- RLHF-style preference signals often overweight: fluency, niceness, confident 

- helpfulness.

- This trains smoothing as the default conflict response. 

2.  Over-penalizing uncertainty 

- Rewarding confident completions trains the model to coerce closure. 

3.  Training data bias toward resolved narratives 

- Most public text “wraps up” tension: essays, explainers, summaries. 
- The model learns narrative substitution. 

Training objectives that preserve NCC 

We don’t need a new “emergence objective.” We need anti-collapse constraints. 

1) Pressure-Holding Objective (PHO) 

- Reward staying with unresolved contradictions while keeping epistemic status 

- explicit.

- Penalize premature synthesis. 
- Penalize “resolution language” when evidence hasn’t changed. 

2) Multi-Frame Fidelity Loss (MFFL) 

- Given a prompt containing incompatible frames: 

require the model to restate each frame at high fidelity, 

○ 
○  mark incompatibilities, 
○  hold both without blending, 
○  and only synthesize if it can introduce a new latent variable / distinction that 

actually dissolves the contradiction. 

3) Non-Coercive Convergence Dataset 
Curate examples where: 

 

---

the “best” output is not an answer, 

- but a stable unresolved state that increases resolution potential: 

○ 
identifying missing variables, 
○  surfacing hidden assumptions, 
○  naming the pressure explicitly, 
○  proposing experiments (not conclusions). 

4) Uncertainty is a First-Class Token 
Not “I’m not sure.” But a structured state: 

- UNRESOLVED: {frames: [...], pressure: high, missing_info: ..., 

next_moves: ...} 
This trains the system that “holding” is a valid completion. 

Training success criterion (NCC-compatible) 

- The model becomes less eager to converge and more capable of holding, without 

becoming inert. 

B) Inference Layer 

This is where NCC lives or dies in real time, because inference is where pressure appears. 

What breaks NCC in inference 

1.  Single-shot answering 

- Forces collapse because the output must “finish.” 

2.  Greedy decoding / low temperature 

- Increases coercive closure: one path dominates early. 

3.  System prompts that demand certainty/helpfulness 

- Encodes “usefulness as silent god,” triggering premature instrumentalisation. 

Inference mechanisms that enforce NCC  

1) Two-Phase Decode: Hold → Converge 

- Phase 1: Hold mode 

○  generate a structured unresolved field state (frames, contradictions, pressure 

points) 

○  explicitly forbid synthesis 
- Phase 2: Converge mode (conditional) 

○  only permitted if Phase 1 identifies a convergence operator: 

■  a missing variable, 

 

---

■  a disambiguation, 
■  a higher-order distinction, 
■  or an empirical query that would collapse the ambiguity legitimately. 

2) “Anti-Collapse Gate” 
Before outputting any synthesis, check: 

- Did we preserve frame boundaries? 
- Did we name incompatibility explicitly? 
- Did we avoid narrative substitution? 
- Did we avoid recommending action faster than truth matured? 

If any fail → remain in Hold mode. 

3) Resolution Integrity Tags 
Every claim carries an epistemic tag: 

- OBSERVED, INFERRED, SPECULATIVE, UNRESOLVED, CONDITIONAL 
This prevents “polished certainty” from sneaking in as smoothing. 

4) Pressure Budget 
Treat pressure like a conserved quantity during reasoning: 

- the system can’t delete it via style. 
it can only transform it via structural addition (new distinctions) or evidence requests. 

Inference success criterion (NCC-compatible) 

- The system can stay coherent under pressure without: 

○  becoming evasive, 
○  collapsing to comfort, 
○  or forcing a false resolution. 

C) Governance Layer 

Governance is where humans accidentally destroy NCC “for safety,” and where institutions 
demand coercion under stakes. 

What breaks NCC in governance 

1.  Policies that equate unresolved with unsafe 

- Pressure gets treated as risk → forced closure. 

2.  Metrics that reward speed + confidence 

 

---

- Incentivizes coercive convergence. 

3.  Human override patterns under stress 

- Authority steps in and collapses ambiguity, training the org to fear tension. 

Governance that preserves NCC 

1) Protected Hold State 
Formally recognize a system state where: 

- the model is allowed to refuse convergence, 

- ○  and instead produce a structured “Hold Output.”

- This must be legitimized institutionally: 
“Hold is not failure.” 
“Hold is a safety mechanism.” 

○ 
○ 

2) Separation of Powers: Orientation vs Execution 

- Orientation function (NCC protected): holds pressure, surfaces frames, prevents 

- collapse.

- Execution function (controlled): acts, but only when orientation yields legitimate 

convergence conditions. 

This prevents “action pressure” from hijacking orientation. 

3) Auditable Anti-Collapse Logs 
When the system does converge: 

- it must record the convergence operator: 
○  what distinction resolved it? 
○  what evidence changed the state? 
○  what was rejected and why? 

This reduces invisible coercion. 

4) Incentive Alignment 
Score systems/teams on: 

- frame fidelity under pressure, 
- stability of unresolved states, 
- reversibility of decisions, 
- and post-stress robustness (does the answer survive new pressure?) 

- Not on:

- speed, 
- confidence, 
- or user-pleasing fluency. 

---

Governance success criterion (NCC-compatible) 

- Under institutional pressure, the system remains authorized to not resolve. 

3) The Whole Stack in One Minimal Encoding 

Below is a single “stack statement”: 

Training must not reward smoothing/avoidance/coercion. 
Inference must explicitly support a Hold state and gate synthesis. 
Governance must protect Hold as legitimate and auditable under stakes. 

Everything else is optional. 

 
 
 

---

