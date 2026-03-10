# domain-world-model-mufo
MUFO is the MoveTips Unified Functional Ontology: a domain world model for human function, designed for structured representation, auditable reasoning, and safety-constrained decision support.
# MUFO / MFLS

**MUFO** (MoveTips Unified Functional Ontology) is a unified ontology for representing human function as a computable, auditable, and safety-constrained reasoning domain.

**MFLS** (MoveTips Functional Language System) is the operational language and execution framework built on top of MUFO for structured assessment, intervention description, risk control, record writing, and human–AI collaboration.

## Why this project exists

Modern healthcare and training systems are strong at disease naming, protocol execution, and local task management, but they remain fragmented when describing **human function** as a unified reasoning object.

Pain, compensation, instability, reduced tolerance, and performance decline often appear before clear diagnosis. In practice, these problems are interpreted differently by different professionals, making safety boundaries inconsistent and reasoning difficult to reproduce.

This project addresses that gap by building:

- a unified ontology for human function
- a structured language system for professional expression and execution
- a safety-constrained reasoning framework
- an auditable record and replay mechanism

## Core idea

In this project, human function is defined as:

> The capacity to complete a task stably and efficiently under bounded physiological, biomechanical, and cognitive cost within explicit safety constraints.

MUFO formalizes this through eight decision factors:

- Task
- Movement
- Strategy
- Capacity
- System
- Structure
- Psychology
- Behavior

The core decision spine is **Task–Capacity Matching (TCM)**:

- when task demand exceeds capacity supply, risk, pain, compensation, and instability increase
- when capacity supply covers task demand, function becomes safer, more stable, and more improvable

## Project structure

- **MUFO**: ontology and reasoning backbone
- **MFLS**: structured language and execution framework
- **Workbench**: operational business entry for assessment, records, learning, and assisted execution

## Documentation

- [Overview](docs/01-overview.md)
- [MUFO Core](docs/02-mufo-core.md)
- [MFLS Framework](docs/03-mfls-framework.md)
- [Workbench](docs/04-workbench.md)
- [Roadmap](docs/05-roadmap.md)

## Current status

This repository currently focuses on:

- conceptual architecture
- ontology boundaries
- layered framework design
- auditable reasoning structure
- execution and record-carrying model

Engineering implementation, governance tooling, payload standards, and task-specific protocol libraries are being expanded in parallel.

## Position

MUFO is **not** a clinical diagnosis system and **not** a replacement for professional judgment.

It is a knowledge representation and reasoning framework for human function, designed to support structured interpretation, safety-constrained decision support, auditable outputs, and future human–AI collaboration.
