# Data & Resources

DesertMIP is committed to open science and providing high-quality forcing datasets for the climate modeling community.

## Forcing Datasets
Our primary output for ESM developers is the **DesertMIP Transient Boundary Dataset (v1.0)**. 
* **Spatial Resolution:** Native $0.25^\circ \times 0.25^\circ$ (regridded to standard CMIP resolutions).
* **Temporal Resolution:** Monthly transients.
* **Format:** NetCDF4 (CF-compliant).

This dataset is derived from a combination of high-resolution satellite products (including ESA WorldCover and MODIS) and machine learning-driven algorithms that predict future boundary shifts under various SSPs.

## Data Access
*The forcing datasets for Tier-1 experiments are currently undergoing internal validation.* 
Once the GMD protocol paper is published, the data will be hosted on the **Earth System Grid Federation (ESGF)** and a secondary mirror on **Zenodo** with a registered DOI for easy access.

## Code Repository
All pre-processing scripts, boundary generation algorithms, and evaluation notebooks used by the DesertMIP steering committee will be available in our GitHub organization under an MIT License. Researchers are encouraged to use these tools to process the forcing data for their specific ESM grids.
