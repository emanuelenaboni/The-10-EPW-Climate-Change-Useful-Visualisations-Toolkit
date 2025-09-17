# ΔEPW Visualisation Toolkit for Rhino/Grasshopper

A set of 10 Climate Change Visualisation (CCV) modules for design using paired EPW files (current vs future). Outputs include ΔT calendar + violin, ΔGHI and ΔIlluminance/Sky Cover charts, Seasonal Sun Path + Overhang optimizer, Psychrometric deltas, Natural Ventilation window analysis, EN 16798 adaptive comfort, and ΔUTCI.

[![DOI](https://zenodo.org/badge/<your-github-id>.svg)](https://zenodo.org/badge/latestdoi/<your-github-id>)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Requirements
- Rhino 6/7/8 with Grasshopper
- Ladybug Tools for Grasshopper **v1.9.0** (recommended)  
  See install guide and Pollination installer notes.

## Install
1. Install Ladybug Tools (LBT) for Grasshopper (see link).
2. Clone/download this repo.
3. Open any `.gh` file in `modules/` and set your **paired EPW** inputs.

## Quickstart
- Provide two EPW files (baseline & scenario) and select the **scenario toggle** (SSP/RCP).  
- Each module outputs hourly/seasonal plots and delta stats ready for early-stage design decisions.

## Modules
1. ΔT Calendar + Violin  
2. ΔGHI timeseries + hourly‐delta calendar  
3. ΔIlluminance & Sky Cover  
4. Seasonal Sun Path + Overhang optimizer  
5. Psychrometric (actual/future/delta)  
6. Comfort Strategy Stack  
7. Natural Ventilation (actual/delta + monthly)  
8. EN 16798 Adaptive Comfort (actual/future/delta)  
9. ΔUTCI (actual/future/delta)  
10. Thermal Comfort Strategies (summary)

## Data
- Use EPW from [EnergyPlus Weather] or CMIP-based ΔEPW datasets. Place in `data/` (see examples).

## Citing
Please cite via the `CITATION.cff` or DOI badge above.

## Authors
Emanuele Naboni (ORCID: https://orcid.org/0000-0002-6381-6491) — Marcello Turrini 

## License
MIT
