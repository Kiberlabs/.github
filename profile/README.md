<p align="center">
  <img src="https://raw.githubusercontent.com/Kiberlabs/kiberlabs.github.io/main/assets/kiberlabs_logo_oficial.jpg" alt="KiberLabs Official Logo" width="140" />
</p>

<h1 align="center">KiberLabs — AI & Python B2B Automation Studio</h1>

<p align="center">
  <strong>Deterministic Python 3.11+ Systems · Zero-Token Sieves · 24/7 Omnichannel Bots · Grounded RAG · Invoice Reconciliation · FastAPI + Docker</strong><br/>
  Senior-reviewed fixed-price engineering delivered in 2–7 days.<br/><br/>
  <a href="https://kiberlabs.github.io"><strong>🌐 Live Sandbox</strong></a> ·
  <a href="https://kiberlabs.github.io/benchmarks.html"><strong>⚡ Benchmarks & Red-Team</strong></a> ·
  <a href="https://kiberlabs.github.io/trust.html"><strong>🛡️ Trust Center & ADRs</strong></a> ·
  <a href="https://kiberlabs.github.io/sow.html"><strong>📄 SOW PDF Generator</strong></a>
</p>

---

## Core Open-Source Reference Engines & Verification Harness

| # | Repository | Domain & Capabilities | CI Status |
| :-: | :--- | :--- | :-: |
| **01** | **[`ecommerce-price-monitor-sieve`](https://github.com/Kiberlabs/ecommerce-price-monitor-sieve)** | Deterministic 3-stage net-margin sieve, SSRF guard, price-drop alerts & SQLite WAL | [![CI](https://github.com/Kiberlabs/ecommerce-price-monitor-sieve/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/ecommerce-price-monitor-sieve/actions/workflows/ci.yml) |
| **02** | **[`omnichannel-lead-bot`](https://github.com/Kiberlabs/omnichannel-lead-bot)** | 24/7 WhatsApp/Telegram/Web lead qualification state machine, ES/EN zero-token NLU & atomic webhook deduplication | [![CI](https://github.com/Kiberlabs/omnichannel-lead-bot/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/omnichannel-lead-bot/actions/workflows/ci.yml) |
| **03** | **[`ai-shortform-video-pipeline`](https://github.com/Kiberlabs/ai-shortform-video-pipeline)** | 9:16 mobile safe-zone validator, dynamic `.ass` subtitle engine & EBU R128 (`loudnorm`) FFmpeg filtergraph builder | [![CI](https://github.com/Kiberlabs/ai-shortform-video-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/ai-shortform-video-pipeline/actions/workflows/ci.yml) |
| **04** | **[`b2b-rag-citation-engine`](https://github.com/Kiberlabs/b2b-rag-citation-engine)** | Article-aware legal/policy chunker, SQLite FTS5 BM25 bilingual search & zero-hallucination citation verifier | [![CI](https://github.com/Kiberlabs/b2b-rag-citation-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/b2b-rag-citation-engine/actions/workflows/ci.yml) |
| **05** | **[`kiberlabs-automation-api`](https://github.com/Kiberlabs/kiberlabs-automation-api)** | Production FastAPI + multi-stage non-root Docker gateway with HMAC `X-API-Key` auth, rate limiting & SQLite WAL audit | [![CI](https://github.com/Kiberlabs/kiberlabs-automation-api/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/kiberlabs-automation-api/actions/workflows/ci.yml) |
| **06** | **[`b2b-invoice-reconciliation-engine`](https://github.com/Kiberlabs/b2b-invoice-reconciliation-engine)** | Multi-format invoice parser (JSON, UBL/Facturae XML, OCR), 3-way PO/GRN reconciliation with 0-100 risk score, IBAN MOD-97 & SHA-256 hash-chained SQLite ledger with dark-mode dashboard | [![CI](https://github.com/Kiberlabs/b2b-invoice-reconciliation-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/b2b-invoice-reconciliation-engine/actions/workflows/ci.yml) |
| **07** | **[`kiberlabs-benchmarks`](https://github.com/Kiberlabs/kiberlabs-benchmarks)** | Reproducible throughput & p50/p95/p99 latency harness, 50-thread SQLite WAL 0-lock stress test & 112-payload Adversarial Red-Team security suite (0 runtime deps, weekly CI) | [![CI](https://github.com/Kiberlabs/kiberlabs-benchmarks/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/kiberlabs-benchmarks/actions/workflows/ci.yml) |

---

## Engineering Standards Included in Every Delivery

- **Typed Python 3.11+ & Pydantic v2:** Strict boundary validation (SSRF, path traversal, FTS5/SQL injection, and webhook replay prevention).
- **Concurrent Persistence (`SQLite WAL` / PostgreSQL):** Configured with `PRAGMA journal_mode=WAL` and `busy_timeout=5000` — empirically verified at 50 concurrent threads with `0` lock errors.
- **Automated Verification (`pytest` + GitHub Actions CI):** Every deliverable ships with reproducible tests across Python 3.11 and 3.12.
- **100% Client IP Ownership & GDPR-Ready Isolation:** Zero-AI-training commitment, Senior Tech Lead QA sign-off, and clean operator handoff ([Read Trust Center & Public ADRs](https://kiberlabs.github.io/trust.html)).

---

<p align="center">
  <a href="https://kiberlabs.github.io">Live Sandbox</a> ·
  <a href="https://kiberlabs.github.io/benchmarks.html">Verified Benchmarks</a> ·
  <a href="https://kiberlabs.github.io/trust.html">Trust &amp; Security</a> ·
  <a href="https://kiberlabs.github.io/sow.html">Generate Fixed-Price SOW PDF</a>
</p>
