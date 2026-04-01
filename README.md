# ~/regaan_

Security Researcher focused on AI/LLM systems, protocol-level testing, and stateful offensive workflows.

I design and build offensive tooling used for adversarial evaluation, exploit development, and reproducible security research. My work focuses on breaking complex, stateful systems where traditional scanning fails.

Based in Chennai, India.

---

## Focus Areas

AI/LLM Security  
Adversarial prompt generation, guardrail bypass testing, and cross-model behavior analysis with measurable outcomes.

Stateful Offensive Testing  
Replay systems, authorization testing, race condition discovery, and identity-driven attack workflows.

Protocol and Realtime Security  
WebSocket interception, protocol manipulation, and structured fuzzing of realtime systems.

Offensive Tooling  
End-to-end systems for discovery, exploitation, and evidence generation designed for actual operator workflows.

---

## Flagship Systems

### Basilisk - Evolutionary AI Red Teaming Framework

Basilisk is a framework for adversarial testing of LLMs using evolutionary techniques.

It generates and evolves attack prompts across iterations to uncover failure modes that static testing does not reach.

Key capabilities:
- Prompt mutation and crossover strategies
- Differential testing across multiple models
- Structured attack modules for injection, leakage, and tool misuse
- Automated discovery of inconsistent and unsafe behaviors

Outcome:
Finds non-obvious jailbreak paths and behavioral gaps across models under realistic conditions.

Research:
https://doi.org/10.5281/zenodo.18909538

---

### WSHawk v4 - WebSocket and Web Pentest Platform

WSHawk is a project-based offensive platform built for real assessments, not one-off testing.

It allows testers to move from traffic capture to exploitation and evidence generation inside a single workflow.

Key capabilities:
- Centralized project environment for identities, traffic, and findings
- WebSocket frame interception, editing, and replay
- Stateful replay system for authorization testing and race conditions
- Identity-aware testing with reusable authenticated sessions
- Payload mutation and high-volume execution
- Integrated HTTP testing and attack workflows
- Evidence vault with structured export and integrity tracking

Why it matters:
Removes fragmented tooling and enables repeatable, stateful attack workflows with defensible outputs.

---

## Selected Systems

ProtoCrash  
Coverage-guided protocol fuzzer designed for high-throughput distributed environments.

PoCSmith  
System for generating proof-of-concept exploits based on vulnerability patterns.

RedLang  
Statically typed language built on LLVM for exploit development and low-level experimentation.

Keikaku  
Custom interpreted runtime with async execution and deterministic control flow.

---

## Technical Stack

Languages  
Go, C, C++, Python, TypeScript

Core Areas  
Fuzzing, Web Security, WebSocket Protocols, LLM Red Teaming

Systems  
Linux Internals, TCP/IP, LLVM, Bytecode Virtual Machines

Infrastructure  
Docker, Redis, PostgreSQL, GitHub Actions

AI and ML  
Adversarial machine learning, prompt evolution, model evaluation

---

## Work Approach

Build systems that reflect real offensive workflows  
Prioritize reproducibility over one-off findings  
Treat evidence as a core output  
Focus on stateful systems and complex attack surfaces

---

## Achievements

Published Researcher  
Basilisk, Zenodo, 2026

Certified Ethical Hacker

Speaker and Workshop Instructor in offensive security and engineering

---

## Connect

Website  
https://rothackers.com

GitHub  
https://github.com/regaan

Twitter  
https://x.com/regaan_sec

LinkedIn  
https://linkedin.com/in/regaan

---

## Note

All work is conducted in authorized environments only.
