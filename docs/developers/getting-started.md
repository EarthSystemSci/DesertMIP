# Getting Started

Welcome to the participation overview for DesertMIP. Climate modeling groups participating in the CMIP7 cycle are actively encouraged to incorporate our transient surface boundary datasets into their experimental runs. 

The general workflow for a modeling center's participation in DesertMIP involves the following phases:

## 📝 Phase 1: Registration and Expression of Interest
Modeling centers interested in conducting DesertMIP experiments can initiate their participation by getting in touch with the coordinating team (Prof. Marzieh Mokarram, Prof. Huayu Lu, and Dr. Mohammad Jafar) to register their model. This coordination ensures that participating groups receive the latest updates, technical support, and notifications regarding forcing data releases.

## 📥 Phase 2: Data Access and Harmonization
DesertMIP provides time-varying, high-resolution datasets for bare-soil and vegetation fractions designed to replace conventional static climatologies.

* **Current Status:** The Tier-1 forcing datasets are currently undergoing final quality control and validation processes.
* **Data Access:** Upon finalization, all datasets will be hosted publicly on ESGF nodes and mirrored on Zenodo for robust access. Necessary resources, including download links, wget scripts, and Python APIs, will be made available on the Resources page.

## ⚙️ Phase 3: Experimental Configuration
During this phase, participating centers will integrate the dynamic forcing datasets into their respective land-surface and atmospheric modules. Detailed mathematical formulations and specific protocols for `desert-hist-dyn` and future SSP scenarios are outlined on the Experiments page. Synergetic configurations with LMIP and AerChemMIP are highly anticipated, as these integrations are crucial for evaluating subsequent thermodynamic and dust-radiation feedbacks.

## 📤 Phase 4: Output Harmonization and Submission
To maintain analytical consistency across all participating models, the resulting outputs are expected to comply with standard CMIP7 data formats. Variables will be CMORized in accordance with the official CMIP7 Data Request. Comprehensive instructions for standardizing and uploading model results to the Earth System Grid Federation (ESGF) infrastructure will be provided as the submission phase approaches.

## 🛠️ Technical Support and Collaboration
For any technical considerations regarding the implementation of the forcing datasets, regridding processes, or model integration, participating teams can utilize the project's GitHub Repository to track issues or correspond directly with the technical support team.
