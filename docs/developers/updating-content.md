# Data Submission and Diagnostic Workflows

Following the successful integration and execution of DesertMIP experiments, participating modeling centers are required to standardize and submit their outputs. This phase ensures that all multi-model ensemble data is harmonized, rigorously quality-controlled, and openly accessible to the global climate community.

## 🗂️ CMORization and Data Standards
To guarantee seamless inter-model comparability, all simulation outputs must strictly adhere to the CMIP7 data standards:
* **CF-Compliant NetCDF:** All output files must follow the latest Climate and Forecast (CF) metadata conventions.
* **CMOR Integration:** Variables must be processed using the Climate Model Output Rewriter (CMOR) to match the official DesertMIP Data Request tables.
* **Key Variables of Interest:** While standard CMIP diagnostic outputs are required, particular emphasis must be placed on archiving high-frequency datasets for dust emission fluxes, surface albedo, leaf area index (LAI), aerosol optical depth (AOD), and surface energy balance components.

## 🌐 Submission Pathways
DesertMIP is fully committed to the FAIR (Findable, Accessible, Interoperable, and Reusable) data principles.
1. **ESGF Nodes:** Fully coupled Tier-1 experimental outputs (e.g., `desert-hist-dyn`, `desert-ssp245-dyn`) will be published and hosted on designated Earth System Grid Federation (ESGF) data nodes.
2. **Configuration Metadata:** Centers must provide comprehensive documentation detailing their specific model configurations, the ingestion method for our dynamic masking, and any deviations from the baseline protocol.

## 🤝 Collaborative Open Science and Diagnostics
DesertMIP is not just a set of forcing data; it is a collaborative scientific framework. We actively encourage the international community to contribute to our shared diagnostic efforts:
* **Community Analysis Tools:** Scientists and developers are invited to submit their post-processing scripts, multi-variate evaluation pipelines, and machine learning diagnostic models to the DesertMIP [GitHub Repository](https://github.com/EarthSystemSci/DesertMIP).
* **Pull Requests
