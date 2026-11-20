# Genomic Selection and Prediction in Crop Breeding

**Status:** planned / in-progress / completed

## Objective
Evaluate genomic prediction models for a clearly defined trait and breeding population.

## Candidate models
- Mean/phenotypic baseline
- GBLUP
- rrBLUP
- Bayesian genomic regression
- Selected ML models, where justified

## Critical design decisions
- Define the prediction target and intended deployment scenario.
- Use population-aware validation (for example, random, family-wise or forward prediction as appropriate).
- Prevent related samples or repeated observations from leaking across folds when that would inflate performance.
- Tune models within training data only.
- Report accuracy/correlation, bias, calibration and uncertainty.
- Compare against meaningful baselines.

## Results
[Insert model comparison, validation design, plots, limitations and breeding implications.]
