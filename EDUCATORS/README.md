# Educators — PSENSOR

**Project:** PSENSOR  
**Category:** LAPTOPS  
**Upstream:** https://github.com/chinf/psensor  
**Pinned commit:** `4270c903e8007017b80c6c817dd41cf699f00df1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cbc7048a497fef8e9f2ccf872d2c02f407d8c0068a4a8be29e16d20163ddd65a`  
**Date:** October 2026

## Teaching with PSENSOR

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `cbc7048a497fef8e9f2ccf872d2c02f407d8c0068a4a8be29e16d20163ddd65a` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
