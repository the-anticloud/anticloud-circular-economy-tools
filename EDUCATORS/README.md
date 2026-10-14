# Educators — CIRCULAR_ECONOMY_TOOLS

**Project:** CIRCULAR_ECONOMY_TOOLS  
**Category:** WASTE_MANAGEMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `4d992a61d6b231d947064a24485a8bee158b675a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `93e609899ff481ce4657af16f19717a165929ecbe4127e515f9a514016710c8d`  
**Date:** October 2026

## Teaching with CIRCULAR_ECONOMY_TOOLS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `93e609899ff481ce4657af16f19717a165929ecbe4127e515f9a514016710c8d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
