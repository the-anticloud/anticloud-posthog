# Onboarding — POSTHOG

**Project:** POSTHOG  
**Category:** MARKETING_TOOLS  
**Upstream:** https://github.com/PostHog/posthog.git  
**Pinned commit:** `2a289c4dacbcd27e28a0197e3dbdd9f594538fa6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9d4f752e860d1a1f6a685a17a769f50bfdad7ee5e47091e7e2de2452f1aae386`  
**Date:** October 2026

## First hour

1. Read `README.md` — what the project is and what it measures.
2. Read `ISOLATED_LAB_RESULTS/03_Result_Register.md` — the 16 checks and their
   evidence hashes.
3. Run the suite: `python tools/run_bench.py --out BENCH.json`.
4. Verify a hash: recompute SHA3-256 of a file in `04_Evidence/` and compare.

## First day

- `10_TECHNICAL_HANDOFF` — architecture and interfaces
- `11_TUTORIAL_DEVELOPERS` — build and test
- `18_COMMAND_LINE_INTERFACE` — CLI reference
- `27_DEPENDENCIES` — the offline dependency mirror

## Getting help

lois@0-1.gg · 0-1.gg
