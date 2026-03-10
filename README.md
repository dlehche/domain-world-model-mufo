# Domain World Model: MUFO  
## MoveTips Unified Functional Ontology

MUFO is a domain world model for **human function**. It is designed to represent functional structure, state, risk boundaries, and action-conditioned evolution in a form that is computable, auditable, and safe for high-stakes decision support.

## Why this repository exists

Most existing health and movement systems are strong at disease naming, protocol execution, and local task management, but weak at representing **human function** as a unified reasoning object.

Pain, compensation, reduced tolerance, unstable control, and declining performance often appear before a clear diagnosis. In practice, these states are interpreted differently across rehabilitation, movement training, and health management, which makes reasoning difficult to standardize, reproduce, and govern.

MUFO addresses that gap by building a structured world model for human function.

## Core position

MUFO is not a diagnosis engine.  
MUFO is not a treatment guideline.  
MUFO is not a black-box model that replaces professional judgment.

MUFO is a **knowledge-and-rules substrate** for the human functional world.

Its purpose is to support:

- structured representation of human function
- interpretable state inference
- explicit safety boundaries
- traceable reasoning artifacts
- longitudinal writeback and replay
- future human–AI collaboration under governance

## Operational definition of human function

In MUFO, human function is defined as:

> The capacity to complete a task stably and efficiently under bounded physiological, biomechanical, and cognitive cost within explicit safety constraints.

This definition is task-based rather than disease-first, and bounded rather than idealized.

## Core reasoning spine

MUFO uses **Task–Capacity Matching (TCM)** as its central decision logic.

- When task demand exceeds available capacity, risk, compensation, pain, and instability tend to rise.
- When capacity covers task demand under explicit constraints, function becomes safer, more stable, and more improvable.

This creates one shared reasoning frame across rehabilitation, training, and functional health management.

## Three-layer architecture

### 1. Functional Cooperation Layer
Defines the constraint topology of human function.

This layer captures how functional units support, constrain, or compensate for one another. It freezes structure; it does not yet compute state.

### 2. Human State Parsing Engine
Maps observations into a functional state distribution.

This layer turns structured observations into state, margin, bottleneck, and risk-window outputs with evidence trace and guardrail enforcement.

### 3. Human Functional World Model
Introduces time, action, and memory.

This layer models how functional state evolves under intervention, load, and strategy changes, and writes outcomes back into persistent memory for recalibration.

## Strategic position in the world-model stack

MUFO is not aimed at molecular structure, physics simulation, or generic language modeling.

Its strategic center is **L4: Human Functional Dynamics** — the layer that links biological constraints below with task performance above and decision support beyond.

This is where human function becomes computable, governable, and clinically usable.

## Relation to MFLS

MUFO is the ontology and reasoning substrate.  
MFLS (MoveTips Functional Language System) is the execution language built on top of MUFO for assessment, intervention description, safety labeling, records, and audit-ready workflow.

Together, they support a function-first and governance-oriented system for human decision support.

## Repository structure

- `README.md` — English overview
- `README.zh-CN.md` — Chinese overview
- `docs/world-model-en.md` — main English article
- `docs/world-model-zh.md` — main Chinese article
- `docs/figures.md` — figures and diagram notes

## Scope clarification

MUFO is intended as a knowledge representation and decision-support framework.

It does not constitute:
- diagnostic automation
- autonomous treatment
- unrestricted recommendation generation

All downstream outputs are expected to operate under explicit safety guardrails, evidence trace, and human review.
