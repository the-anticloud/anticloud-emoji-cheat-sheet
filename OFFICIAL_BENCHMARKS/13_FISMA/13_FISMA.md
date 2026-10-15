# FISMA / FIPS 199-200

**Project:** EMOJI_CHEAT_SHEET · **Category:** REAL_ESTATE · **Vendor:** Anticloud FZ LLE

## Model component (PAX L5 Narrow L2 General 27B — quoted with provenance)

| Module | Key Metric | Value |
|--------|-----------|-------|
| CRDT | lww_set_us | 0.51 |
| CRDT | merge_10k_ms | 0.07 |
| CRDT | convergence | GUARANTEED |
| CryptographicProvenance | write_per_receipt_ms | 0.059 |
| CryptographicProvenance | verify_1k_chain_ms | 2.53 |
| ZeroTrustLocalMesh | ca_gen_ms | 367.5 |
| ZeroTrustLocalMesh | cert_issue_ms | 333.8 |
| ZeroTrustLocalMesh | tls_version | 1.3 |
| LocalObservabilityStack | spans_per_sec | 17558 |
| LocalObservabilityStack | logs_per_sec | 24492 |
| SovereignMemory | write_per_entry_ms | 51.94 |
| SovereignMemory | encryption | AES-256-GCM |
| AIOSS_AuditChain | entries_per_sec | 232665 |
| AIOSS_AuditChain | hash_algo | SHA3-256 |

*Run ID loiskleinner/pax-benchmark-runner v3, 2026-10-02, Kaggle T4 x2 (2x 16GB VRAM), Ubuntu 22.04, Python 3.12. These are PAX L5 Narrow L2 General 27B model-level results — shared model component, not this project's verdict.*

## Project-level basis (this project's own measured checks)

| Basis check | Status | Observed |
|---|---|---|
| 10_nist_sp_800_53 | PASS | 12/12 controls evidenced (100.0%) |

## Verdict

CONTROLS EVIDENCED — all basis checks PASS

Verdict derives only from the basis checks above (actual runs, register recorded). Nothing here is copied from another project's assessment.

## Cryptographic integrity

- BENCH.json sha3-256: `fc7e1b5d82be8278e65427aa6890a90a4ac8586e824be86e856acaa4ca72ac02`
- Result register sha3-256: `3d6329e4a5e52b9516898f507052c88b1ffd2f90d041349f65992d830f26ba7f`
- Generated: 2026-10-06T18:11:54Z

*Anticloud FZ LLE · AIOSS Ledger Genesis: 8b4a8a4f6312dfbe885de8280716985637c163fd2a4b5590341d56db1cc4e560*

> Self-assessment only. No external audit has been performed. A SOC 2 / NIST independent audit is committed post-funding.
