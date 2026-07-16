# Pandeia Engine Tutorial

A hands-on guide to the [JWST Exposure Time Calculator (Pandeia Engine)](https://jwst-docs.stsci.edu/jwst-exposure-time-calculator-overview/jwst-etc-pandeia-engine-tutorial) in Python.

## Setup

1. Create a virtual environment and install dependencies:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
   Use `pandeia.engine==2026.2` for JWST, or `2026.1` for Roman.

2. Download the [reference data](https://outerspace.stsci.edu/spaces/PEN/pages/77530136/Pandeia+Engine+Installation) and arrange it under `data/` as shown in [`0_setup.ipynb`](0_setup.ipynb).

3. Run [`0_setup.ipynb`](0_setup.ipynb) to confirm it works.

## Notebooks

- [`0_setup.ipynb`](0_setup.ipynb) — install check and environment setup
- [`1_guide.ipynb`](1_guide.ipynb) — inputs, reports, and configuring a calculation

### Examples
- [`examples/2_nircam_time_to_depth.ipynb`](examples/2_nircam_time_to_depth.ipynb)
- [`examples/3_nircam_depth_from_time.ipynb`](examples/3_nircam_depth_from_time.ipynb)
- [`examples/4_nirspec_time_to_depth.ipynb`](examples/4_nirspec_time_to_depth.ipynb)
- [`examples/5_nirspec_depth_from_time.ipynb`](examples/5_nirspec_depth_from_time.ipynb)
- [`examples/6_backround_at_target.ipynb`](examples/6_backround_at_target.ipynb)
- [`examples/7_nirspec_coverage.ipynb`](examples/7_nirspec_coverage.ipynb)
- [`examples/8_nircam_readout_efficiency.ipynb`](examples/8_nircam_readout_efficiency.ipynb)
