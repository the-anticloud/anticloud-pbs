# How to Update — PBS

**Project:** `PBS`
**Category:** SUPERCOMPUTER
**Domain:** supercomputer
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
PBS --version
PBS check-update
```

### Applying Updates
```bash
pip install --upgrade PBS
```

### Rolling Back
```bash
pip install PBS==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
