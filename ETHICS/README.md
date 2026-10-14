# Ethics — CIRCULAR_ECONOMY_TOOLS

**Project:** CIRCULAR_ECONOMY_TOOLS  
**Category:** WASTE_MANAGEMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `4d992a61d6b231d947064a24485a8bee158b675a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `93e609899ff481ce4657af16f19717a165929ecbe4127e515f9a514016710c8d`  
**Date:** October 2026

## Position

CIRCULAR_ECONOMY_TOOLS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
