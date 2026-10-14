# Educators — POSTHOG

**Project:** POSTHOG  
**Category:** MARKETING_TOOLS  
**Upstream:** https://github.com/PostHog/posthog.git  
**Pinned commit:** `2a289c4dacbcd27e28a0197e3dbdd9f594538fa6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9d4f752e860d1a1f6a685a17a769f50bfdad7ee5e47091e7e2de2452f1aae386`  
**Date:** October 2026

## Teaching with POSTHOG

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9d4f752e860d1a1f6a685a17a769f50bfdad7ee5e47091e7e2de2452f1aae386` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
