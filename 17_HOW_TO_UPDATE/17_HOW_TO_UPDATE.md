# How to Update — POSTHOG

**Project:** `POSTHOG`
**Category:** MARKETING_TOOLS
**Domain:** marketing tools and analytics
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
POSTHOG --version
POSTHOG check-update
```

### Applying Updates
```bash
pip install --upgrade POSTHOG
```

### Rolling Back
```bash
pip install POSTHOG==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
