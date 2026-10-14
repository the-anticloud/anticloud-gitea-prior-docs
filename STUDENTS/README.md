# Students — GITEA_PRIOR_DOCS

**Project:** GITEA_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/go-gitea/gitea  
**Pinned commit:** `2f9438022240346e9f9a706f01f2ccd4bf1f2a86`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `79e8a3d2bc21e38faba2d658f4d94d7e7014f8066bafab154f48c7e4cf64ff84`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `2f9438022240346e9f9a706f01f2ccd4bf1f2a86`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `79e8a3d2bc21e38faba2d658f4d94d7e7014f8066bafab154f48c7e4cf64ff84`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
