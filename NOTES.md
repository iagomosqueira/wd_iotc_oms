---
title: "Strategies for the conditioning of operating models for IOTC stocks"
author: "C Edwards (Cescapecs), R Hillary (CSIRO), I Mosqueira (MWR), A Preece
(CSIRO), D Rosa (IPMA) A Williams (CSIRO)."
tags:
---

# ISSUES

- MSE as exploratory analysis vs. SA as consolidative analyses have different aims: characterize dynamics with uncertainty vs. providing best estimate of status and potential.

# SOLUTIONS

- Decouple OM and SA development
- Condition OMs based on life history + priors + explaining of data (looser than fitting).
- ABC algorithms
- Important to capture well emergent properties: productivity, variability and , plus status.

# EXAMPLES

## ICES WKLIFEX

- Used data-limited OMs (Fisher et al, 2020) to test a three-element decision rule, rfb, that alters the value of the TAC based on changes in stock trend from an index of abundance (r), an exploitation proxy target derived from the mean length in the catch (f), and a biomass safeguard reducing the catch advice once the stock falls below a threshold (b). Simulation testing of the rule (Fischer et al., 2021a) has led to its application on at least two stocks: 

- Plaice (Pleuronectes platessa) in divisions 7.h-k (Celtic Sea South, southwest of Ireland) https://doi.org/10.17895/ices.advice.7824

- Sole (Solea solea) in divisions 8.c and 9.a (Cantabrian Sea and Atlantic Iberian waters) https://doi.org/10.17895/ices.advice.7866

## IPHC

- Based on SS3 but with added spatial stuff.

## SBT

- OM diverged from SA, less so at the moment.

## Gadget 

- Multispp model as OM, MPs based on single species models.

# References

Sharma, R. Levontin, P., Kitakado, T. Kell, L., Mosqueira, I. Kimoto, A. Scott, R. Minte-Vera, C. De Bruyn, P., Ye, Y., Kleineberg, J., Walton, J. L., Miller, S. and Magnusson, A. 2020. Operating model design in tuna Regional Fishery Management Organizations: Current practice,issues and implications. Fish and Fisheries. doi 10.1111/faf.12480.

Fischer, S. H., De Oliveira, J. A. A., and Kell, L. T. 2020. Linking the performance of a data-limited empirical catch rule to life-history traits. ICES Journal of Marine Science, 77: 1914–1926.

Fischer, S. H., De Oliveira, J. A. A., Mumford, J. D., Kell, L. T. 2021a. Application of explicit precautionary principles in data-limited ﬁsheries management. ICES Journal of Marine Science 0: 1-12.

Fischer, S. H., De Oliveira, J. A. A., Mumford, J. D., and Kell, L. T. 2021b. Using a genetic algorithm to optimize a data-limited catch rule. ICES Journal of Marine Science, 78: 1 311 – 1 323.

