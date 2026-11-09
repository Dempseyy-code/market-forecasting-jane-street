# Market Forecasting on Jane Street Data

Forecasting short-term market responders from noisy, non-stationary real-world
data, with a focus on honest (time-based) validation.

**Data:** Kaggle's *Jane Street Real-Time Market Data Forecasting* competition
(anonymised production market data: 79 features, 9 responders). The data is not
included in this repo; download it from Kaggle after accepting the competition rules.

## Goal
Predict the target responder as accurately as possible, measured by the
competition's weighted R², while avoiding data leakage.

## Status
- [x] Data loaded and explored
- [ ] Validation scheme
- [ ] Baselines
- [ ] Neural models
- [ ] Analysis and write-up

## Findings so far
- The dataset has 10 partitions covering about 1,700 days and 20+ symbols per slice.
- Some features are entirely missing in early days and appear later in the
  dataset's history (features 00-04 are empty at the start, populated by the end).
  *(Exact switch-on dates: to be added.)*

## Methods
*(to be filled in)*

## Results
*(to be filled in)*

## What didn't work
*(to be filled in)*

## How to run
*(to be filled in)*
