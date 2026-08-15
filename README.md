# Aleksandr Petrov

**Backend engineer — Go, distributed systems, high-load payment and data infrastructure.**

Belgrade, Serbia (CET) ·
[email](mailto:aleksandr.petrov.work@outlook.com) ·
[telegram](https://t.me/zxc00zxc00zxc) ·
[hugging face](https://huggingface.co/zxc0zxc0zxc)

---

Five years in payments and crypto infrastructure, mostly Go. I build systems where
correctness and uptime *are* the product: analytical pipelines over billions of blockchain
events, sub-second search and graph exploration over transaction data, and ledgers that
cannot lose or duplicate a cent.

Comfortable owning a service end to end — design, Go implementation, Kubernetes on AWS,
metrics, alerting, on-call. Currently leading a PHP-monolith-to-Go decomposition as the
senior-most backend engineer on the team.

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

**Beyond the logos** — microservices and event-driven architecture, saga orchestration,
idempotent APIs, at-least-once delivery with deduplication, double-entry ledgers,
reconciliation, OLAP pipelines and ETL, CI/CD, mTLS, monitoring and on-call.

**Domains** — fintech, payment processing, card issuing, acquiring, blockchain, fraud
detection, AML monitoring.

**AI systems** — RAG, vector search, MCP servers, LLM agent orchestration, LoRA fine-tuning
and evaluation.

### Experience

**PPM** — Staff Backend Engineer · *May 2026 — present*
Cross-border consumer payments; virtual card issuing, top-ups and FX. Leading the
decomposition of a PHP monolith into Go services, and owning the correctness-critical core:
double-entry ledger, reconciliation engine, acquiring integration.

**SPND** — Senior Backend Engineer · *Jul 2025 — May 2026*
Virtual card issuing for online payments and ad spend. Owned the ledger service — the
posting model and the asynchronous money-movement flows, orchestrated so that partial
failures resume instead of leaving split state.

**Innovative Systems LLC** — Backend Engineer · *May 2021 — Jul 2025*
Crypto payment processing and exchange; multi-chain wallet infrastructure at high volume.
Built the transaction-monitoring platform on ClickHouse — ingestion from every supported
chain, automated scoring of suspicious transactions, wallet clustering, and the analytics
surface the risk team worked from.

### Selected work

| | |
|---|---|
| [**reconciliation**](https://github.com/zxc0zxc0zxc/reconciliation) | A source-agnostic reconciliation engine in Go. Sources plug in behind a single gRPC method, rules live in YAML, and the matching core is a pure function with no I/O. |
| [**TinyLlama-1B-Sonar-formatting**](https://huggingface.co/zxc0zxc0zxc/TinyLlama-1B-Sonar-formatting) | LoRA/QLoRA adapter tuned for answer formatting and structural consistency, trained on a [dataset](https://huggingface.co/datasets/zxc0zxc0zxc/sonar-formatting) grown from ~20 curated references to 457 pairs by few-shot synthesis. Published with the full training config and a model card on the limits of the approach. |
| [**Nanai tokenizer adaptation**](https://huggingface.co/zxc0zxc0zxc/gigachat-nanai-extended-tokenizer) | Tokenizer work for Nanai, a low-resource Indigenous language of the Russian Far East. A Russian–Nanai [corpus](https://huggingface.co/datasets/zxc0zxc0zxc/nanai-language), two variants — [vocabulary-extended](https://huggingface.co/zxc0zxc0zxc/gigachat-nanai-extended-tokenizer) and [fully retrained](https://huggingface.co/zxc0zxc0zxc/gigachat-nanai-retrained-tokenizer) — benchmarked on segmentation quality and single-token rate. |

---

Russian — native · English — C1 · Serbian — conversational
