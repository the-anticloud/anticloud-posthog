# Students — POSTHOG

**Project:** POSTHOG  
**Category:** MARKETING_TOOLS  
**Upstream:** https://github.com/PostHog/posthog.git  
**Pinned commit:** `2a289c4dacbcd27e28a0197e3dbdd9f594538fa6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9d4f752e860d1a1f6a685a17a769f50bfdad7ee5e47091e7e2de2452f1aae386`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `2a289c4dacbcd27e28a0197e3dbdd9f594538fa6`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `9d4f752e860d1a1f6a685a17a769f50bfdad7ee5e47091e7e2de2452f1aae386`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
