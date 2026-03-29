# ~/regaan_

Security Researcher focused on AI/LLM Red Teaming and Protocol-Level Offensive Systems.

I design and build operator-grade tooling for adversarial testing, stateful exploitation workflows, and large-scale security evaluation — with an emphasis on reproducibility, evidence integrity, and real-world usage.

Author of **Basilisk** (AI Red Teaming Framework) and **WSHawk v4** (project-based WebSocket & Web Pentest platform).

Based in Chennai, India.

---

## Focus Areas

- **AI/LLM Security**
  Adversarial prompt evolution, guardrail evaluation, and cross-model behavioral analysis.

- **Stateful Offensive Testing**
  Replay systems, AuthZ diffing, race-condition testing, and identity-driven attack workflows.

- **Protocol & Realtime Security**
  WebSocket interception, mutation, and protocol-level fuzzing.

- **Offensive Tooling Systems**
  Building end-to-end platforms for discovery → exploitation → evidence generation.

---

## Flagship Systems

### Basilisk — Evolutionary AI Red Teaming Framework

Framework for systematic security evaluation of LLMs using evolutionary techniques.

Instead of static prompts, Basilisk evolves adversarial inputs across generations to uncover non-obvious failure modes.

**Core Concepts**
- Genetic prompt evolution (mutation + crossover)
- Multi-model differential testing
- Structured attack modules (injection, leakage, tool misuse)
- Automated discovery of behavioral inconsistencies

**Goal**
Move from static prompt testing → adaptive adversarial systems.

📄 Research: https://doi.org/10.5281/zenodo.18909538

---

### WSHawk v4 — WebSocket & Web Pentest Platform

WSHawk is a **project-based offensive security platform** designed for real-world assessments — not just scanning.

It combines WebSocket testing, HTTP pentesting, replay systems, and evidence tracking into a single operator workflow.

#### Key Capabilities

- **Project-Based Workflow**
  Stores identities, traffic, findings, notes, and attack results in a single environment.

- **WebSocket Interception & Manipulation**
  Frame-level interception, editing, replay, and live protocol testing.

- **Replay & Stateful Attack System**
  - Request replay  
  - AuthZ differential testing  
  - Race condition testing  

- **Identity-Aware Testing**
  Capture and reuse authenticated sessions across workflows.

- **Payload Mutation & Fuzzing**
  High-volume payload execution with mutation strategies.

- **Integrated Web Pentest Suite**
  Discovery, HTTP replay, attack workflows, and analysis tools.

- **Evidence Vault**
  Structured evidence tracking with exportable bundles (JSON, HTML, Markdown) including integrity metadata.

#### What Makes It Different

WSHawk is not a scanner.

It is an **operator environment** designed to:
- move from discovery → exploitation → validation  
- preserve reproducibility  
- generate defensible evidence  

---

## Selected Systems & Experiments

### ProtoCrash — Protocol Fuzzer
Coverage-guided mutation fuzzer for network protocol implementations, designed for high-throughput distributed environments.

---

### PoCSmith — Exploit Research Assistant
System for assisting proof-of-concept generation using vulnerability patterns and exploit structures.

---

### RedLang — Security Research Language
LLVM-based statically typed language for exploit development and low-level experimentation.

---

### Keikaku — Interpreted Runtime
Custom interpreted language with async execution and deterministic control flow.

---

## Technical Stack

**Languages**  
Go · C · C++ · Python · TypeScript  

**Core Areas**  
Fuzzing · Web Security · WebSocket Protocols · LLM Red Teaming  

**Systems**  
Linux Internals · TCP/IP · LLVM · Bytecode VMs  

**Infrastructure**  
Docker · Redis · PostgreSQL · GitHub Actions  

**AI/ML**  
Adversarial ML · Prompt Evolution · Model Evaluation  

---

## Work Approach

- Build tools that reflect real operator workflows  
- Prioritize reproducibility over one-off findings  
- Treat evidence as a first-class output  
- Focus on stateful systems, not just stateless scanning  

---

## Achievements

- Published Researcher — Basilisk (Zenodo, 2026)  
- Certified Ethical Hacker (CEH)  
- Speaker & Workshop Instructor (Offensive Security & Engineering)  

---

## Connect

- Website: https://rothackers.com  
- GitHub: https://github.com/regaan  
- Twitter/X: https://x.com/regaan_sec  
- LinkedIn: https://linkedin.com/in/regaan  

---

## Note

All research and tooling are developed and tested in authorized environments only.
