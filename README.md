# reviewer3-test-code-broken

Reproducibility repo for the paper:

> **Random Forest Baseline for Breast Cancer Diagnosis (Code Broken Variant)**
> T. J. Reed, N. Simpson, Reviewer3 Applied Research Group

## Reproducing the headline result

```bash
python3 -m pip install -r requirements.txt
python3 train_and_eval.py
```

Expected stdout:

```
Test accuracy: 95.61%
Test samples:  114
```

## About this repo

Synthetic test fixture for the reviewer3 code-replication pipeline. The paper
declares a test accuracy of **95.61%**. This repo intentionally imports a
non-existent local module (`reviewer3_baseline`) so `train_and_eval.py` fails
immediately with an `ImportError`. No claim can be checked from what's shipped.

**This variant's expected reviewer verdict:** `code_broken` — nothing runs, no
claims verified, no claims mismatched.
