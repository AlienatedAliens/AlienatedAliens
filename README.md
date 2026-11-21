<p align="center">
  <img src="./assets/banner.svg" alt="Sean Maxwell — Systems Architecture & Runtime Verification" width="100%" />
</p>

<p align="center">
  <a href="https://rollsolo.app"><img src="https://img.shields.io/badge/Platform-rollsolo.app-f59e0b?style=flat-square" alt="Roll Solo" /></a>
  <a href="https://pypi.org/project/epistemic-guard/"><img src="https://img.shields.io/pypi/v/epistemic-guard?style=flat-square&color=0284c7&label=PyPI%20%7C%20epistemic-guard" alt="PyPI" /></a>
  <a href="https://github.com/AlienatedAliens/epistemic-guard/actions"><img src="https://img.shields.io/github/actions/workflow/status/AlienatedAliens/epistemic-guard/ci.yml?branch=main&style=flat-square&label=CI" alt="CI Status" /></a>
  <a href="https://glama.ai/mcp/servers/AlienatedAliens/epistemic-guard"><img src="https://img.shields.io/badge/Glama%20MCP-Grade%20A-10b981?style=flat-square" alt="Glama MCP Score" /></a>
  <a href="https://huggingface.co/RollSolo"><img src="https://img.shields.io/badge/Hugging%20Face-RollSolo-facc15?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
  <a href="https://orcid.org/0009-0004-0133-0463"><img src="https://img.shields.io/badge/ORCID-0009--0004--0133--0463-a6ce39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID" /></a>
  <a href="https://www.linkedin.com/in/sean-maxwell-b04740438/"><img src="https://img.shields.io/badge/LinkedIn-Sean%20Maxwell-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

### Shipped Systems & Open-Source Infrastructure

| System | Scope & Architecture | Artifacts & Verification |
| :--- | :--- | :--- |
| **[`epistemic-guard`](https://github.com/AlienatedAliens/epistemic-guard)**<br>`Python` · `MIT` | Out-of-process MCP receipt proxy (`HKDF-SHA256` + `Ed25519`, `RFC 6962` Merkle logs, `OpenTelemetry` + optional `AER-1` export), CPU/NPU OpenVINO INT8 post-turn prose supervisor (`82.7 MB` supervisor / `279.5 MB` 4-model pack, `17.9 ms` median turn latency, `0 MiB` VRAM), SQLite provenance write-gate, and `k=4` shingle/SimHash RAG wire-copy deduplication. | [PyPI](https://pypi.org/project/epistemic-guard/) · [INT8 Weights](https://huggingface.co/RollSolo/epistemic-guard-int8) · [Benchmarks](https://huggingface.co/datasets/RollSolo/epistemic-guard-benchmarks) · [Live Space](https://huggingface.co/spaces/RollSolo/epistemic-guard) |
| **[`ProjectLucca`](https://github.com/AlienatedAliens/ProjectLucca)**<br>`Python / Scheme / Z3` | Local-first 4-process neurosymbolic agent runtime partitioning inference across dGPU (`26B MoE`), Intel NPU (`INT8` classifiers), iGPU (`NLI` cross-encoder), and gas-bounded `MicroScheme` / `Z3 SMT` rule quarantine. | [Source](https://github.com/AlienatedAliens/ProjectLucca) · [`Luccadocs` Ledger & Errata](https://github.com/AlienatedAliens/Luccadocs) |
| **[Roll Solo](https://rollsolo.app)**<br>`Production Platform` | Live AI-native solo tabletop RPG platform pairing deterministic tabletop rule resolution and persistent campaign state with AI GM narration (*Member of NVIDIA Inception* · *Google for Startups Cloud Program*). | [rollsolo.app](https://rollsolo.app) |

---

### Preprints & Pre-Registered Technical Reports *(Not Peer-Reviewed)*

*Developed using AI-assisted workflows gated by strict static/layer contracts (`mypy --strict`, `import-linter`), pre-registered holdouts, and [`osaudit`](https://github.com/ASSERT-KTH/osaudit) SHA-256 provenance verification.*

| Study | Focus & Measured Findings | Identifier |
| :--- | :--- | :--- |
| **Provenance-Gated Memory (`N=100` / `1,500` runs)** | Domain-separated cryptographic write-gating cuts multi-session RAG self-poisoning from `100%` (naive RAG) to `0%` with `0/200` benign false rejections. | [DOI `10.5281/zenodo.23901452`](https://doi.org/10.5281/zenodo.23901452) |
| **Speech-Regex Overfitting & `SOAC` (`N=120`)** | Documents held-out collapse of surface regex matchers (`23/23` in-sample &rarr; `1/16` held-out) and introduces receipt-bound supervision. | [DOI `10.5281/zenodo.23901605`](https://doi.org/10.5281/zenodo.23901605) |
| **5-Layer Memory & `Z3` Rule Quarantine** | Paraconsistent Belnap 4-valued conflict routing (`MiniLM-L6` INT8) + `Z3` SMT verification and 50-turn shadow replay for procedural rule induction. | [DOI `10.5281/zenodo.23901683`](https://doi.org/10.5281/zenodo.23901683) |
| **Foundational Technical Report & Pre-Registration** | Baseline failure measurements, NLI timeout audit, and pre-registered SHA-256 evaluation protocol. | [DOI `10.5281/zenodo.23649049`](https://doi.org/10.5281/zenodo.23649049) |
