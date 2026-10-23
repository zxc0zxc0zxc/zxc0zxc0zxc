# Aleksandr Petrov

### i do agentic stuff & money

Backend engineer & technical lead in Belgrade, Serbia.  
5+ years building payment systems, crypto infrastructure and things that have to survive retries.

Mostly Go and PHP. These days I also build agents that write, review and test code,
tools that help them keep context, and small ML experiments with results you can inspect.

[email](mailto:aleksandr.petrov.work@outlook.com) ·
[telegram](https://t.me/zxc00zxc00zxc) ·
[hugging face](https://huggingface.co/zxc0zxc0zxc)

### What I build

- **Money flows:** double-entry ledgers, idempotent APIs, transactional outboxes and reconciliation.
- **Agentic workflows:** spec → implementation → independent reviews → tests → human review.
  MCP tools, persistent context, budget limits and approval gates for mutations.
- **Data & ML:** on-chain analytics, RAG, inference experiments, fine-tuning and evaluation.

A few things I'm happy with:

- Built a production support RAG system: average user-submitted ratings went **3.1 → 4.2/5**,
  operator-escalation requests **65% → 20%** month over month.
- Cut feature-test median runtime **408 → 104 seconds** by replacing 302 replayed migrations
  with a schema baseline.
- Reworked queue-worker allocation: **94–102 → 2 workers per test environment**,
  reclaiming about **26.6 GiB across four test environments**.

### Selected work

| Project | What's inside |
|---|---|
| [**Jev Inference**](https://github.com/zxc0zxc0zxc/jev-inference) | A choice API for causal LMs, plus five decision strategies compared on 231 public tasks and two Qwen sizes. Restricted logits took **36.0 ms vs 69.9 ms** median for label generation with the same prompt on a T4. Published [the experiment](https://huggingface.co/blog/zxc0zxc0zxc/qwen-decisions), raw results and the order-sensitivity trade-offs. |
| [**vivoficator-img**](https://huggingface.co/zxc0zxc0zxc/vivoficator-img) | An **852K-parameter** photo-restoration CNN adapted from FFDNet toward Vivo-style processing. Weights, inference code, training recipe and baseline comparisons. Still an experiment: sharper edges can come with lost texture. |
| [**reconciliation**](https://github.com/zxc0zxc0zxc/reconciliation) | A source-agnostic Go engine for finding where two systems disagree. One gRPC source interface, YAML rules, a pure matching core and a CLI that reports discrepancies. |
| [**Nanai tokenizer adaptation**](https://huggingface.co/zxc0zxc0zxc/gigachat-nanai-extended-tokenizer) | Vocabulary-extension experiments for a low-resource language, with a Russian–Nanai corpus and published segmentation comparisons. |

Jev numbers are single-request benchmark timings, excluding loading, queueing and HTTP.

### On my workbench

**Agent engineering toolkit** — reusable skills and a Python orchestrator for scoped tasks,
durable state, independent verification, recovery and token/USD accounting.
Spans product research, software delivery and bounded ML experiments. Private for now.

**Native Rust/macOS experiments** — an encrypted communicator with text and video circles.
Calling and real two-device acceptance are still in progress.

### Experience

- **Some Eastern European Card Issuing Company** · Lead Software Engineer / Technical Lead · May 2026 — present
- **Another EEA Card Issuing Company** · Senior Backend Engineer · Jul 2025 — May 2026
- **Eastern European Crypto Startup** · Backend Engineer · May 2021 — Jul 2025

### Tools I reach for

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

Russian — native · English — C1 · Serbian — conversational
