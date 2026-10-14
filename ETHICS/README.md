# Ethics — POSTHOG

**Project:** POSTHOG  
**Category:** MARKETING_TOOLS  
**Upstream:** https://github.com/PostHog/posthog.git  
**Pinned commit:** `2a289c4dacbcd27e28a0197e3dbdd9f594538fa6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9d4f752e860d1a1f6a685a17a769f50bfdad7ee5e47091e7e2de2452f1aae386`  
**Date:** October 2026

## Position

POSTHOG is packaged for offline deployment with a verifiable audit trail. The
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
