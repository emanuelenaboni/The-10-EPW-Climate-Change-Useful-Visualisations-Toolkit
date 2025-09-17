# ΔEPW Climate-Change Visualisation Toolkit for Rhino/Grasshopper

> Ten Grasshopper modules to compare baseline vs future weather (ΔEPW) using Ladybug Tools.

[![Release](https://img.shields.io/github/v/release/emanuelenaboni/The-10-EPW-Climate-Change-Useful-Visualisations-Toolkit)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#license)

## Why
Design and communication tools for climate-change scenarios (SSP/RCP). Hourly deltas and summaries for early-stage decisions.

## Requirements
- Rhino 6/7/8
- Ladybug Tools for Grasshopper (tested with LBT 1.9.x)
- Two EPW files: baseline + scenario (ΔEPW)

## Quick start (2 minutes)
1. Download the latest release assets from **Releases**.
2. Open any `.gh` in `/modules`.
3. Provide paired EPW files (baseline & scenario) as indicated on canvas.
4. Toggle scenario/intervals; read the on-canvas panels for deltas and interpretation.

## The 10 modules (at a glance)
1. ΔT Calendar + Violin  
2. ΔGHI Timeseries + Hourly-Delta Calendar  
3. ΔIlluminance & Sky Cover  
4. Seasonal Sun Path + Overhang Optimizer  
5. Psychrometric (Actual/Future/Delta)  
6. Comfort Strategies Stack  
7. Natural Ventilation (Actual/Delta + Monthly)  
8. EN 16798 Adaptive Comfort  
9. ΔUTCI (Actual/Future/Delta)  
10. Thermal Comfort Strategies (summary)

## Gallery
<small>(Add one image per module from `/assets/images`, with alt text.)</small>

## Notes & limitations
- Modules visualize deltas; they do **not** replace full simulation.
- Use appropriate SSP/RCP scenarios and EPW morphing methods.

## Cite
If you use this toolkit, please cite (see **Cite this repository** sidebar or `CITATION.cff`).

## Acknowledgements
In collaboration with M. Turrini. Built on Ladybug Tools and the EPW ecosystem.

## License
MIT – see [LICENSE](./LICENSE).
