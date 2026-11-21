<p align="center">
  <img src="https://raw.githubusercontent.com/Kiberlabs/kiberlabs.github.io/main/assets/kiberlabs_logo_oficial.jpg" alt="KiberLabs Official Logo" width="140" />
</p>

<h1 align="center">KiberLabs — AI & Python B2B Automation Studio</h1>

<p align="center">
  <strong>Deterministic Python 3.11+ Systems · Zero-Token Sieves · 24/7 Omnichannel Bots · Grounded RAG · Invoice Reconciliation · FastAPI + Docker</strong><br/>
  Senior-reviewed fixed-price engineering delivered in 2–7 days.<br/><br/>
  <a href="https://kiberlabs.github.io"><strong>🌐 Live Interactive Demo & Scope Calculator (kiberlabs.github.io)</strong></a>
</p>

---

## Core Open-Source Reference Engines

| # | Repository | Domain & Capabilities | CI Status |
| :-: | :--- | :--- | :-: |
| **01** | **[`ecommerce-price-monitor-sieve`](https://github.com/Kiberlabs/ecommerce-price-monitor-sieve)** | Deterministic 3-stage net-margin sieve, SSRF guard, price-drop alerts & SQLite WAL | [![CI](https://github.com/Kiberlabs/ecommerce-price-monitor-sieve/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/ecommerce-price-monitor-sieve/actions/workflows/ci.yml) |
| **02** | **[`omnichannel-lead-bot`](https://github.com/Kiberlabs/omnichannel-lead-bot)** | 24/7 WhatsApp/Telegram/Web lead qualification state machine, ES/EN zero-token NLU & atomic webhook deduplication | [![CI](https://github.com/Kiberlabs/omnichannel-lead-bot/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/omnichannel-lead-bot/actions/workflows/ci.yml) |
| **03** | **[`ai-shortform-video-pipeline`](https://github.com/Kiberlabs/ai-shortform-video-pipeline)** | 9:16 mobile safe-zone validator, dynamic `.ass` subtitle engine & EBU R128 (`loudnorm`) FFmpeg filtergraph builder | [![CI](https://github.com/Kiberlabs/ai-shortform-video-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/ai-shortform-video-pipeline/actions/workflows/ci.yml) |
| **04** | **[`b2b-rag-citation-engine`](https://github.com/Kiberlabs/b2b-rag-citation-engine)** | Article-aware legal/policy chunker, SQLite FTS5 BM25 bilingual search & zero-hallucination citation verifier | [![CI](https://github.com/Kiberlabs/b2b-rag-citation-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/b2b-rag-citation-engine/actions/workflows/ci.yml) |
| **05** | **[`kiberlabs-automation-api`](https://github.com/Kiberlabs/kiberlabs-automation-api)** | Production FastAPI + multi-stage non-root Docker gateway with HMAC `X-API-Key` auth, rate limiting & SQLite WAL audit | [![CI](https://github.com/Kiberlabs/kiberlabs-automation-api/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/kiberlabs-automation-api/actions/workflows/ci.yml) |
| **06** | **[`b2b-invoice-reconciliation-engine`](https://github.com/Kiberlabs/b2b-invoice-reconciliation-engine)** | Multi-format invoice parser (JSON, UBL/Facturae XML, OCR), 3-way PO/GRN reconciliation with 0-100 risk score, IBAN MOD-97 & SHA-256 hash-chained SQLite ledger with dark-mode dashboard | [![CI](https://github.com/Kiberlabs/b2b-invoice-reconciliation-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/Kiberlabs/b2b-invoice-reconciliation-engine/actions/workflows/ci.yml) |

---

## Engineering Standards Included in Every Delivery

- **Typed Python 3.11+ & Pydantic v2:** Strict boundary validation (SSRF, path traversal, FTS5/SQL injection prevention).
- **Concurrent Persistence (`SQLite WAL` / PostgreSQL):** Configured with `PRAGMA journal_mode=WAL` and `busy_timeout=5000` for zero lock contention.
- **Automated Verification (`pytest` + GitHub Actions CI):** Every deliverable ships with reproducible tests across Python 3.11 and 3.12.
- **100% Code Ownership:** Clean modular architecture, concise method docstrings, and clear README handoff.

---

<p align="center">
  <a href="https://kiberlabs.github.io">Try the Live Browser Sandbox at <strong>kiberlabs.github.io</strong></a>
</p>
