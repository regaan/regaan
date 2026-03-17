# ~/regaan_

**Independent Security Researcher · Offensive Security Engineer · Tool Builder**  
ROT Independent Security Research Lab · Chennai, India

[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--3683--7824-brightgreen?style=flat-square&logo=orcid)](https://orcid.org/0009-0006-3683-7824)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18909538.svg)](https://doi.org/10.5281/zenodo.18909538)
[![Figshare](https://img.shields.io/badge/Figshare-DOI-blue?style=flat-square)](https://doi.org/10.6084/m9.figshare.31566853)
[![OSF](https://img.shields.io/badge/OSF-10.17605%2FOSF.IO%2FH7BVR-blue?style=flat-square)](https://doi.org/10.17605/OSF.IO/H7BVR)
[![Website](https://img.shields.io/badge/rothackers.com-000000?style=flat-square&logo=firefox&logoColor=white)](https://rothackers.com)
[![Portfolio](https://img.shields.io/badge/regaan.rothackers.com-000000?style=flat-square&logo=firefox&logoColor=white)](https://regaan.rothackers.com)
[![X](https://img.shields.io/badge/@regaan__sec-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/regaan_sec)
[![Mastodon](https://img.shields.io/badge/@regaan-6364FF?style=flat-square&logo=mastodon&logoColor=white)](https://mastodon.social/@regaan)
[![Medium](https://img.shields.io/badge/@regaan-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@regaan)

---

## Research Interests

- **LLM Security & AI Red Teaming** — adversarial prompt evolution, guardrail bypass, differential testing across LLM providers
- **Protocol Fuzzing** — coverage-guided and mutation-based fuzzing of network protocol implementations
- **Offensive Security Automation** — high-performance exploit research infrastructure, adversary simulation systems
- **Language Engineering** — compiler design, bytecode VMs, security-oriented programming languages
- **WebSocket Security** — protocol-level vulnerability discovery, payload mutation, headless DOM verification

---

## Published Research

**Basilisk: An Evolutionary AI Red-Teaming Framework for Systematic Security Evaluation of Large Language Models**  
Regaan · ROT Independent Security Research Lab · March 2026  
📄 DOI: [10.5281/zenodo.18909538](https://doi.org/10.5281/zenodo.18909538) · Indexed: OpenAIRE · License: CC BY 4.0

> Introduces Smart Prompt Evolution (SPE-NL) — a genetic algorithm treating adversarial prompts as organisms under selection pressure. 29 attack modules across 8 OWASP LLM Top 10 categories. 92% improvement in attack success rate over static payload libraries at generation 5.

---

## Flagship Projects

### [Basilisk](https://github.com/regaan/basilisk) — AI/LLM Red Teaming Framework
[![PyPI](https://img.shields.io/pypi/v/basilisk-ai?style=flat-square)](https://pypi.org/project/basilisk-ai/)
[![License](https://img.shields.io/badge/license-AGPL--3.0-blue?style=flat-square)](https://github.com/regaan/basilisk/blob/main/LICENSE)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18909538.svg)](https://doi.org/10.5281/zenodo.18909538)
[![Figshare](https://img.shields.io/badge/Figshare-DOI-blue?style=flat-square)](https://doi.org/10.6084/m9.figshare.31566853)
[![OSF](https://img.shields.io/badge/OSF-10.17605%2FOSF.IO%2FH7BVR-blue?style=flat-square)](https://doi.org/10.17605/OSF.IO/H7BVR)
[![Downloads](https://pepy.tech/badge/basilisk-ai)](https://pepy.tech/project/basilisk-ai)

Open-source framework for systematic adversarial security evaluation of Large Language Models using evolutionary computation.

- **SPE-NL engine** — genetic algorithm with 10 mutation operators, 5 crossover strategies, multi-signal fitness function
- **29 attack modules** — prompt injection, system prompt extraction, data exfiltration, tool abuse, guardrail bypass, DoS, multi-turn manipulation, RAG attacks
- **100+ LLM providers** via LiteLLM abstraction layer
- **Differential testing** — simultaneous cross-provider behavioral divergence analysis  
- **Non-destructive posture assessment** — production-safe guardrail grading (A+ to F)
- **SARIF 2.1.0** output for GitHub Code Scanning integration
- **Cryptographic audit trail** — SHA-256 chain integrity, auto secret redaction

```bash
pip install basilisk-ai
basilisk scan --target https://your-llm-endpoint.com --mode standard
```

---

### [WSHawk](https://github.com/regaan/wshawk) — WebSocket Security Scanner
[![Stars](https://img.shields.io/github/stars/regaan/wshawk?style=flat-square)](https://github.com/regaan/wshawk/stargazers)

Enterprise-grade distributed WebSocket security testing framework. 900+ repository clones · 120+ active developers.

- Genetic payload mutation engine with 22k+ corpus
- Headless DOM verification via Playwright
- 22 integrated web pentesting modules (XSS, SQLi, SSRF, OAST)
- Real-time MitM interceptor
- Distributed fuzzing architecture in Go

---

### [ProtoCrash](https://github.com/regaan/ProtoCrash) — Protocol Fuzzer
Coverage-guided mutation fuzzer for network protocol implementations. 350k+ executions/sec in distributed environments.

### [PoCSmith](https://github.com/regaan/PoCSmith) — AI Exploit Assistant  
LLM fine-tuned on 1,400+ exploit samples and CVE data for automated proof-of-concept generation and shellcode research.

### [sqlmap-tamper-collection](https://github.com/regaan/sqlmap-tamper-collection) — WAF Bypass  
Modern WAF bypass tamper scripts targeting Cloudflare, AWS WAF, and Azure WAF using 2025 evasion techniques.

### [RedLang](https://github.com/regaan/redlang-poc) — Security Research Language  
LLVM-based statically typed systems language engineered for offensive security research and high-performance exploit primitives.

### [Keikaku](https://github.com/regaan/keikaku-programming-language) — Interpreted Language  
Interpreted language with native async/await, advanced generators, and deterministic control flow.

---

## Technical Stack

| Domain | Technologies |
|--------|-------------|
| **Languages** | Go · C · C++ · Python · TypeScript |
| **Offensive Security** | Protocol Fuzzing · LLM Red Teaming · WAF Bypass · WebSocket Security · Adversary Simulation |
| **Systems** | Linux Internals · Syscalls · TCP/IP · LLVM · Bytecode VMs · Windows Internals |
| **Infrastructure** | Docker · Redis · PostgreSQL · GitHub Actions · PyPI · Electron |
| **AI/ML Security** | Genetic Algorithms · Prompt Evolution · LLM Quantization · Adversarial ML |

---

## Achievements

- 📜 **Published Researcher** — Basilisk paper, Zenodo DOI: 10.5281/zenodo.18909538 (2026)
- 🎓 **CEH** — Certified Ethical Hacker, EC-Council (2025–2026)
- 🏆 **OffSec Echo** — Completed 9 weeks: Forensics, Cloud, Malware Analysis
- 🎤 **Guest Lecturer** — MIT App Development, DDGDVC Chennai (2026)
- 🎤 **Guest Speaker** — Offensive R&D Workshop, Mohamed Sathak Polytechnic College (2026)
- 🎤 **Workshop Instructor** — Modern Cyber Attack Engineering, eHackify (2025)

---

## Connect

| Platform | Link |
|----------|------|
| 🌐 Website | [rothackers.com](https://rothackers.com) |
| 🐦 X / Twitter | [@regaan_sec](https://x.com/regaan_sec) |
| 💼 LinkedIn | [linkedin.com/in/regaan](https://linkedin.com/in/regaan) |
| 🔬 ORCID | [0009-0006-3683-7824](https://orcid.org/0009-0006-3683-7824) |
| 📄 Research | [DOI: 10.5281/zenodo.18909538](https://doi.org/10.5281/zenodo.18909538) |

---

> All security research and tooling is conducted in authorized environments only.  
> ROT Independent Security Research Lab · © 2026 Regaan
