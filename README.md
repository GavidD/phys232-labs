# PHYS 232 – Laboratory Notebooks

This repository contains my lab work for **PHYS 232** at UBC Okanagan, including data analysis, plotting, and written discussion implemented as Jupyter notebooks.

## Repository structure

- `Template.ipynb` – Base notebook used as a starting point for each lab (imports, plotting style, report layout).
- `BlackBody/` – Blackbody radiation experiment notebooks and associated data files.
- `Brownian_Motion/` – Brownian motion experiment notebooks, tracking data, and analysis.
- `Stirling Engine/` – Stirling engine thermodynamics lab notebooks and results.
- `Thermal-Waves/` – Thermal wave propagation lab materials.
- `PHYS231.py` – Shared helper functions for numerical work and plotting used across multiple labs.
- `.ipynb_checkpoints/` – Auto-generated Jupyter checkpoint files.

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/GavidD/phys232-labs.git
   cd phys232-labs
   ```
2. Create and activate a Python environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. Install dependencies (adjust as needed):
   ```bash
   pip install numpy scipy matplotlib pandas jupyterlab
   ```
4. Launch Jupyter:
   ```bash
   jupyter lab
   ```
   Then open any of the lab notebooks from the file browser.

## Usage notes

- Notebooks assume the existing folder structure and use relative paths to data and to `PHYS231.py`, so keep the layout intact when running them.
- If a notebook does not render correctly on GitHub, you can download it and open it locally in JupyterLab, or view it via [nbviewer](https://nbviewer.org).

## License

These materials are primarily for coursework and personal study.  
If you would like to reuse or adapt anything here, please open an issue or contact me first.
