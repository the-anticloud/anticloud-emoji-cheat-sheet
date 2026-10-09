# Students — EMOJI_CHEAT_SHEET

**Project:** EMOJI_CHEAT_SHEET  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/ikatyang/emoji-cheat-sheet  
**Pinned commit:** `d4ccec71e64d090a936d83cea31af45c7e851d8f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fdbfdacdc6c1121cea85208272194e9d78aa168e98a9e7c6edc7f4ad071b445e`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `d4ccec71e64d090a936d83cea31af45c7e851d8f`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `fdbfdacdc6c1121cea85208272194e9d78aa168e98a9e7c6edc7f4ad071b445e`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
