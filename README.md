# Absorption Spectroscopy of Molecular Iodine

*Fourth-year undergraduate Physics laboratory project (University College Dublin)*

## Overview
This project involved acquiring and analysing optical absorption spectra of molecular iodine using a grating spectrometer. The goal was to extract molecular constants from real experimental data and model the vibrational structure of iodine using a physically motivated potential. The work combined hands-on experimental data acquisition with Python-based data processing, numerical analysis, and visualisation.

## What I did
- Acquired absorption spectra of molecular iodine using a laboratory spectrometer and calibrated the wavelength scale.
- Processed raw intensity data and converted it into absorbance for quantitative analysis.
- Implemented peak-finding and feature extraction routines to identify vibrational band structure.
- Assigned vibrational quantum numbers and extracted molecular constants from experimental trends.
- Performed numerical fitting to determine spectroscopic parameters and associated uncertainties.
- Implemented and visualised a Morse potential model to describe the excited electronic state.
- Generated publication-quality figures comparing experimental data, fitted models, and reference values.
- Structured the analysis in a clear, modular Jupyter notebook suitable for reuse and inspection.

## Technical focus
- **Programming & analysis:** Python, NumPy, SciPy
- **Visualisation:** Matplotlib
- **Data acquisition:** NI-DAQ interface via `pydaqmx_helper`
- **Scientific methods:** nonlinear curve fitting, goodness-of-fit testing, uncertainty propagation, residual analysis
- **Signal processing:** peak detection, baseline handling, data filtering
- **Modelling:** numerical implementation of molecular potential models
- **Workflow:** reproducible analysis using Jupyter notebook and version control with Git

## Repository structure
- `data/` – Raw and processed experimental data files
- `notebook.ipynb` – Jupyter notebook containing the full analysis pipeline
- `figures/` – Generated plots and visualisations used in the report
- `report.pdf` – Final PDF laboratory report
- `README.md` – Project overview and documentation

## Notes
The repository serves as a portfolio example, highlighting scientific programming, data analysis, and reproducible workflows rather than the theoretical derivation behind the experiment.

All data acquisition and analysis code used in the report PDF is available in the accompanying `.ipynb` Python notebook.  
Report submitted as part of assessed coursework.
