# Ethics — PSENSOR

**Project:** PSENSOR  
**Category:** LAPTOPS  
**Upstream:** https://github.com/chinf/psensor  
**Pinned commit:** `4270c903e8007017b80c6c817dd41cf699f00df1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cbc7048a497fef8e9f2ccf872d2c02f407d8c0068a4a8be29e16d20163ddd65a`  
**Date:** October 2026

## Position

PSENSOR is packaged for offline deployment with a verifiable audit trail. The
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
