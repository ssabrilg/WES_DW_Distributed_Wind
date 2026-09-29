Code and analysis supporting:

**Abril Guevara, S., Pérez, P., Podgorny, S., Crook, P., Lockshin, J., and Phillips, C.:
Spatial and economic prioritization for distributed wind, *Wind Energy Science*,
2026 (in production).**

## Overview

This repository contains the analysis code for a study examining how distributed
wind (DW) deployment potential spatially aligns with residential energy burden (EB)
across the contiguous United States. The analysis combines parcel-level DW
techno-economic data from the Distributed Wind Energy Futures Study (DWEFS) with
county-level socioeconomic data (poverty, income, GDP, unemployment, ethnicity,
residential units) to compute energy burden and net energy return metrics, assess
spatial correlations with DW potential (AEP-to-demand ratio), and produce a weighted
state-level ranking and grouping framework.

## Contents

- `*.qmd` — Quarto source files containing the data processing, metric calculations
  (EB, NER, EB_GDP, NER_GDP, AEP_demand), correlation analysis (Pearson/Box–Cox and
  Kendall's tau), mixed-effect and state-level regression models, and figure
  generation used in the manuscript.
- `*.html` — Rendered Quarto output corresponding to each `.qmd` file, including
  code, narrative, and inline figures/tables.

## Data sources

This analysis draws on publicly available datasets described in Table 1 of the
manuscript, including:
- DWEFS cost-viable AEP values (Lockshin et al., 2025)
- U.S. Census Bureau SAIPE (poverty and income)
- U.S. Bureau of Economic Analysis (county GDP)
- U.S. Census Bureau (ethnicity, housing units)
- U.S. Bureau of Labor Statistics (unemployment)
- NLR SLOPE (electricity demand and expenditure)

Raw input datasets are not redistributed in this repository; see the manuscript's
Data Availability statement and Table 1 for source links.

## Reproducing the analysis

Files are intended to be run in Quarto (`.qmd`) and rendered to `.html`. [Add any
specific run order, environment/package requirements, or R/Python version notes
here.]

## Citation

If you use this code, please cite the associated manuscript (full citation to be
updated upon publication).

## Contact

Sara Abril Guevara — Sara.AbrilGuevara@nlr.gov
