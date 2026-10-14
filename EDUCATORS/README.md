# Educators — GITEA_PRIOR_DOCS

**Project:** GITEA_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/go-gitea/gitea  
**Pinned commit:** `2f9438022240346e9f9a706f01f2ccd4bf1f2a86`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `79e8a3d2bc21e38faba2d658f4d94d7e7014f8066bafab154f48c7e4cf64ff84`  
**Date:** October 2026

## Teaching with GITEA_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `79e8a3d2bc21e38faba2d658f4d94d7e7014f8066bafab154f48c7e4cf64ff84` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
