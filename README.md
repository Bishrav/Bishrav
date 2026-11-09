<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:312e81,100:06b6d4&height=190&section=header&text=BISHRAV%20SHIWAKOTI&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Information%20Retrieval%20%7C%20Trustworthy%20AI%20%7C%20Distributed%20Systems&descAlignY=62&descSize=16" width="100%" alt="Animated Bishrav Shiwakoti header" />

# Bishrav Shiwakoti

### Research-oriented software engineer

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1400&color=06B6D4&center=true&vCenter=true&width=760&lines=Building+systems+that+can+be+inspected+and+reproduced;Information+retrieval+%E2%80%A2+Trustworthy+AI+%E2%80%A2+Search+evaluation;Java+%E2%80%A2+Python+%E2%80%A2+C%2B%2B20+%E2%80%A2+Distributed+systems;Research+engineering+from+Kathmandu%2C+Nepal" alt="Animated research focus" />

<p>
  <a href="https://github.com/Bishrav/NEBULA">NEBULA</a> ·
  <a href="https://portfolio-self-phi-65.vercel.app/">Portfolio</a> ·
  <a href="mailto:bishravs@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/bishrav-shiwakoti-603201345/">LinkedIn</a>
</p>

[![XERJ Corpus Hub contributor](https://hub.xerj.org/contributors/Bishrav/badge.svg)](https://hub.xerj.org/contributors/Bishrav)
[![GitHub](https://img.shields.io/badge/GitHub-Bishrav-181717?logo=github)](https://github.com/Bishrav)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0f172a?logo=vercel)](https://portfolio-self-phi-65.vercel.app/)
[![Research status](https://img.shields.io/badge/research-prototype%20%7C%20preliminary-2563eb)](https://github.com/Bishrav/NEBULA)

</div>

---

## Research identity

I am Bishrav Shiwakoti, a BSc (Hons) Computing student at Softwarica College, affiliated with Coventry University, and a research-oriented software engineer based in Kathmandu, Nepal.

I build inspectable systems that connect algorithms with measurable evidence.

> Build systems people can inspect, reproduce, evaluate, and improve.

My current interests are:

- information retrieval and search evaluation;
- trustworthy and explainable AI systems;
- hybrid lexical–semantic retrieval;
- graph-based ranking and evidence provenance;
- distributed systems and failure-aware design;
- reproducible experiments and responsible research engineering.

I am interested in research supervision, research collaborations, internships, and engineering opportunities in information retrieval, AI/ML systems, backend engineering, and dependable software.

## Research snapshot

| Area | Current focus |
| --- | --- |
| Main research project | NEBULA: trust-oriented hybrid retrieval for engineering knowledge |
| Core question | How observable ranking signals affect retrieval effectiveness |
| Methods | BM25, dense retrieval, hybrid fusion, BGE, HNSW, PageRank |
| Systems work | Sharding, replication, retries, circuit breaking, partial results |
| Research practice | Provenance, blinded annotation, qrels, checksums, uncertainty |
| Current status | Research prototype with preliminary protected evidence |

## Featured research

### NEBULA — Trust-oriented hybrid retrieval

[![NEBULA CI](https://github.com/Bishrav/NEBULA/actions/workflows/validation.yml/badge.svg)](https://github.com/Bishrav/NEBULA/actions/workflows/validation.yml)
[![Java 17](https://img.shields.io/badge/Java-17-orange?logo=openjdk)](https://openjdk.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/Bishrav/NEBULA/blob/main/LICENSE)

[NEBULA](https://github.com/Bishrav/NEBULA) is an open-source Java research prototype for engineering-knowledge retrieval. It studies how observable signals affect search effectiveness and how retrieval systems can expose evidence rather than return unexplained scores.

The system combines:

- BM25 and phrase-based lexical retrieval;
- dense and BGE-backed semantic retrieval;
- hybrid ranking and Reciprocal Rank Fusion;
- freshness, source-authority, graph, and evidence signals;
- PageRank-style graph analysis and custom HNSW search;
- sharding, replication, retries, circuit breaking, and partial-result reporting;
- reproducible manifests, checksums, fixed timestamps, annotation validation, and claim controls.

The status is intentionally conservative: NEBULA is a research prototype with preliminary protected evaluation evidence. It does not claim statistical superiority, general search quality, user benefit, or production readiness. A fresh sealed held-out evaluation is being prepared before stronger academic claims are made.

Useful entry points:

- [Research summary](https://github.com/Bishrav/NEBULA/blob/main/docs/research/submission/tu-darmstadt-research-summary.md)
- [Research-readiness dashboard](https://github.com/Bishrav/NEBULA/blob/main/docs/research/research-readiness.md)
- [Publication claim ledger](https://github.com/Bishrav/NEBULA/blob/main/docs/research/claim-ledger.md)
- [Fresh held-out evaluation plan](https://github.com/Bishrav/NEBULA/blob/main/docs/research/fresh-heldout-evaluation-plan.md)
- [Architecture](https://github.com/Bishrav/NEBULA/blob/main/docs/architecture/overview.md)

## Selected systems projects

| Project | Focus |
| --- | --- |
| [AEGIS](https://github.com/Bishrav/AEGIS) | Flood-risk intelligence using Kafka, Neo4j, machine-learning ensembles, RAG, and LLM reasoning |
| [ATLAS](https://github.com/Bishrav/ATLAS) | C++20 routing engine using Dijkstra, A*, ALT landmarks, and vehicle-routing algorithms |
| [Sentinel](https://github.com/Bishrav/Sentinel) | Cybersecurity threat analysis with finite-state modelling, Isolation Forest, and attack-path graphs |
| [Nexus](https://github.com/Bishrav/Nexus) | Repository intelligence using Python AST analysis and incremental indexing |
| [LiveBoard](https://github.com/Bishrav/LiveBoard) | Real-time task management with Socket.IO, Redis, and PostgreSQL |
| [DevLens](https://github.com/Bishrav/DevLens) | AI-assisted code review with structured outputs and review history |

## Technical areas

**Languages:** Java, Python, C++20, TypeScript, JavaScript, Kotlin

**Search and AI:** BM25, TF–IDF, vector search, BGE embeddings, HNSW, RRF, PageRank, graph retrieval, RAG, evaluation methodology

**Systems:** Distributed search, sharding, replication, retries, circuit breakers, Docker, Docker Compose, Kafka, Redis, PostgreSQL, REST APIs

**Research engineering:** Dataset provenance, licensing review, blinded annotation, agreement analysis, qrels, held-out evaluation, uncertainty analysis, SHA-256 manifests, CI quality gates

## Research and engineering principles

- Separate measured evidence from hypotheses and future work.
- Keep baselines, configurations, data provenance, and checksums explicit.
- Treat explanations as evidence interfaces, not proof of correctness.
- Test failure modes, recovery paths, and degraded behaviour.
- Use human evaluation and institutional review where research claims require them.
- Make claims narrower than the evidence supporting them.

## Verified recognition

- **XERJ Corpus Hub contributor:** work from [Bishrav/NEBULA](https://github.com/Bishrav/NEBULA) was accepted into the [XERJ Corpus Hub](https://hub.xerj.org/contributors/Bishrav).
- **Open-source research publication:** NEBULA is publicly available under the MIT License with reproducible documentation and CI checks.
- **Research communication:** an academic review summary and evidence-status documentation are maintained in the repository.

> GitHub profile achievements and contribution milestones are shown directly by GitHub when available. I have not added unverified awards or badges here.

## Current direction

I am developing NEBULA from a broad systems prototype into a more defensible empirical study by focusing on:

1. a fresh sealed held-out evaluation;
2. stronger depth-10 pooled judgments;
3. per-query and category-level failure analysis;
4. uncertainty, robustness, and bias analysis;
5. reproducible academic artefacts and documentation.

## Contact

If you work on information retrieval, trustworthy AI, search evaluation, knowledge systems, or dependable software, I would be glad to hear from you.

- Email: [bishravs@gmail.com](mailto:bishravs@gmail.com)
- LinkedIn: [linkedin.com/in/bishrav-shiwakoti-603201345](https://www.linkedin.com/in/bishrav-shiwakoti-603201345/)
- Portfolio: [portfolio-self-phi-65.vercel.app](https://portfolio-self-phi-65.vercel.app/)
- GitHub: [github.com/Bishrav](https://github.com/Bishrav)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:312e81,100:0f172a&height=90&section=footer" width="100%" alt="Animated footer decoration" />

*Inspectability, reproducibility, and honest evaluation before impressive claims.*

</div>
