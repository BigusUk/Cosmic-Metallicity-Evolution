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

How to Run

Clone the repository
Run the script:

Bashpython metallicity_simulation.py
Example Output
textAt z=0 (age ~13.80 Gyr, PR4): Z ≈ 0.0196
At z=10 (age ~0.48 Gyr, PR4): Z ≈ 1.35e-05
+1% stronger: Z at z=0 ≈ 0.0212
-1% weaker: Z at z=0 ≈ 0.0182
Mean metallicity gradient at z=0:  ...
Model vs Observed Z at z=10:  ... vs 0.001
Customization

Adjust k (growth rate) for different calibrations (default 0.55 Gyr⁻¹ tuned to solar Z).
Modify the gradient slope to match specific galaxy observations.
Replace dummy high-z observed value with real JWST/CEERS or similar datasets.

Scientific Background

Cosmology: Planck Collaboration (2024) final data release (PR4 parameters).
Chemical evolution models: Exponential growth as a common toy approximation (Pagel 1997; Weinberg et al. 2017).
Metallicity gradients: Observed in Milky Way and high-z galaxies (e.g., Genovali et al. 2014; Curti et al. 2023 via JWST).
Fine-tuning implications: Stronger nuclear binding increases yields (e.g., MacDonald & Mullan 2009).
