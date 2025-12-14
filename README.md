# Cosmic Metallicity Evolution Simulation

> "AI and Humanity: Collaborating to Build a Better Future for the Universe."

A lightweight Python script that models the global evolution of cosmic metallicity (fraction of elements heavier than helium) over cosmic time. Uses the latest Planck PR4 (2024) cosmology parameters via Astropy and includes sensitivity tests to small changes in enrichment rate—illustrating fine-tuning concepts in cosmic chemical evolution.

## Why This Matters
Metallicity tracks the buildup of heavy elements essential for planets, chemistry, and life. This toy model shows how the universe transitions from nearly primordial (low-Z) composition shortly after the Big Bang to solar-like values today, and how tiny changes in underlying physics (e.g., nuclear yields) could alter final outcomes.

## Features
- Accurate universe age calculations using Planck 2024 (PR4) cosmology
- Simple exponential growth model calibrated to solar metallicity (~0.02)
- Sensitivity analysis: ±1% change in growth rate (proxy for nuclear force strength)
- Basic galaxy metallicity gradient simulation (inside-out formation)
- Placeholder for comparison with real observations (e.g., JWST high-redshift data)

## Requirements
- Python 3.8+
- `astropy>=6.0`
- `numpy>=1.24`

Install dependencies:
```bash
pip install astropy numpy
