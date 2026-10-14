# Students — CIRCULAR_ECONOMY_TOOLS

**Project:** CIRCULAR_ECONOMY_TOOLS  
**Category:** WASTE_MANAGEMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `4d992a61d6b231d947064a24485a8bee158b675a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `93e609899ff481ce4657af16f19717a165929ecbe4127e515f9a514016710c8d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4d992a61d6b231d947064a24485a8bee158b675a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `93e609899ff481ce4657af16f19717a165929ecbe4127e515f9a514016710c8d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
