# scp_exteded_work

Research workspace to maintain all material in one place: Colab notebooks, datasets, math derivations, papers, and results.

## Scope of this repository

This repo is organized around an adaptation of Chang et al.'s chance-constrained SCP framework.

- **Reused baseline (with citation):**
  - Chance-constrained obstacle avoidance formulation (Gaussian, erf-based Theorem-1 style bound)
  - Lossless convexification idea for control constraints
  - SCP iterative structure (M2a -> M2b)
- **Your adaptation / contribution:**
  - Radar detection zone avoidance application
  - Radar-physics based detection radius (radar range equation inspired modeling)
  - Distribution-free Cantelli/Chebyshev style chance-constraint bound
  - Simplified point-mass double-integrator dynamics with acceleration control
  - Open-source solver workflow (e.g., CLARABEL) with synthetic scenarios/datasets

## Recommended citation wording

In your writing, keep attribution and novelty explicit, for example:

> We adapt the chance-constrained SCP framework of Chang et al. to radar-avoidance and further propose a distribution-free reformulation based on Cantelli/Chebyshev bounds.

## Repository structure

```text
scp_exteded_work/
├── notebooks/   # Google Colab and experiment notebooks
├── datasets/    # Synthetic or collected datasets
├── math/        # Derivations, proofs, and notes
├── papers/      # Drafts, PDFs, and reading material
├── references/  # Bib files, citation notes, related links
├── src/         # Reusable Python modules/scripts
└── results/     # Generated outputs, plots, tables
```
