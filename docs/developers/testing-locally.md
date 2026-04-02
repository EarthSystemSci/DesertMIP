# Offline and Standalone Testing

Before integrating the DesertMIP dynamic forcing datasets into fully coupled Earth System Models (ESMs), we strongly recommend that participating modeling groups perform offline or standalone testing of their land surface models (LSMs).

## Why Run Offline Tests?
Testing the dynamic bare-soil and vegetation fractions locally (in standalone mode) allows modeling centers to:
1. **Verify Data Ingestion:** Ensure the correct regridding and ingestion of the high-resolution DesertMIP forcing data into your specific model grid.
2. **Evaluate Surface Fluxes:** Assess the immediate impact of dynamic desert boundaries on surface albedo, sensible/latent heat fluxes, and dust emission without the complexity of atmospheric feedbacks.
3. **Save Computational Resources:** Identify and resolve any numerical instabilities or surface energy balance issues before committing expensive supercomputing resources to fully coupled historical or future runs.

## Recommended Testing Protocol
* **Single-Point/Column Runs:** Start by running your LSM at selected desert boundary grid cells (e.g., the Sahel region or Central Asia) where the dynamic forcing exhibits the highest interannual variability.
* **Regional Offline Runs:** Perform a regional simulation over major dust-source regions (e.g., North Africa, Middle East, Gobi Desert). We recommend driving the offline LSM with standard reanalysis data (e.g., ERA5 or MERRA-2) combined with the DesertMIP dynamic masks.
* **Validation:** Compare the offline dust emission fluxes and surface energy budgets against standard satellite products (e.g., MODIS surface albedo) and ground observations (e.g., AERONET).

## Technical Scripts and Tools
To facilitate this process, we will provide sample Python and NCL scripts for regridding the forcing data and setting up offline tests for common land surface models (such as CLM, JSBACH, and JULES). 

Please check our [GitHub Repository](https://github.com/EarthSystemSci/DesertMIP) for the latest tools and diagnostic scripts.
