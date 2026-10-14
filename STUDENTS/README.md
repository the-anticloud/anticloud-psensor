# Students — PSENSOR

**Project:** PSENSOR  
**Category:** LAPTOPS  
**Upstream:** https://github.com/chinf/psensor  
**Pinned commit:** `4270c903e8007017b80c6c817dd41cf699f00df1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cbc7048a497fef8e9f2ccf872d2c02f407d8c0068a4a8be29e16d20163ddd65a`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4270c903e8007017b80c6c817dd41cf699f00df1`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `cbc7048a497fef8e9f2ccf872d2c02f407d8c0068a4a8be29e16d20163ddd65a`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
