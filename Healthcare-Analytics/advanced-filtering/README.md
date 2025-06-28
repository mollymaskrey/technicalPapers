# Adversarial Turbo Cascade Network (ATCN)

**Paper:** `ATCN.pdf`  
**Author:** Molly Maskrey  
**Date:** June 28, 2025

## Summary

The Adversarial Turbo Cascade Network (ATCN) introduces a novel architecture for medical prediction tasks inspired by turbo equalizers from aerospace communications. This proof-of-concept explores iterative adversarial training across two model stages to improve hospital readmission prediction using 3.7 million patient records.

- **Stage 1:** High-sensitivity generator
- **Stage 2:** High-specificity discriminator

While the ATCN framework operated as designed, initial results revealed significant limitations, including:
- Sensitivity of only **11.6%**
- Minimal iterative gains (+0.1%)
- Severe probability calibration issues

These results underscore key challenges in applying aerospace concepts to medical ML. The paper offers a technical foundation and roadmap for future research, including:
- Better feature engineering
- Calibrated models
- More effective adversarial feedback loops

## Status

This version is a functional prototype. It demonstrates conceptual feasibility but is **not yet clinically viable**. Future work is needed to improve sensitivity, calibration, and overall performance.


