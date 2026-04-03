# Getting Started

Welcome to the participation guide for DesertMIP. We actively encourage climate modeling groups participating in the CMIP7 cycle to incorporate our dynamic desert boundary datasets into their experimental runs.

Here is the step-by-step guide on how your modeling center can participate in DesertMIP:

<!-- اگر فلوچارت را آماده کردید، آن را در پوشه assets با نام workflow.png ذخیره کنید -->
<p align="center">
  <img src="../assets/workflow.png" alt="DesertMIP Participation Workflow" width="700" style="border-radius: 8px; margin: 20px 0;">
</p>

## :material-account-plus: Step 1: Express Interest and Register
If your modeling center is interested in running DesertMIP experiments, please get in touch with the co-chairs (Prof. Marzieh Mokarram & Prof. Huayu Lu) to register your model. This ensures you receive the latest updates, technical support, and notifications regarding forcing data releases.

## :material-database-download: Step 2: Access the Forcing Data
DesertMIP provides time-varying, high-resolution datasets for bare-soil and vegetation fractions to replace static climatologies. 
* **Current Status:** The Tier-1 forcing datasets are currently undergoing final quality control and validation. 
* **Download Access:** Once finalized, all datasets will be hosted publicly on ESGF nodes and mirrored on Zenodo for easy access. Download links, `wget` scripts, and Python APIs will be provided on the Resources page.

## :material-cogs: Step 3: Experimental Setup
Modeling centers are required to integrate our dynamic forcing into their land-surface and atmospheric modules. Please review the Experiments page for detailed mathematical formulations and the specific protocols for `desert-hist-dyn` and future SSP scenarios. Ensure synergy with your LUMIP and AerChemMIP configurations, as these interactions are crucial for evaluating dust-radiation feedbacks.

## :material-cloud-upload: Step 4: Output Submission and CMORization
To ensure consistency across all participating models, all outputs must comply with standard CMIP7 data formats. Variables must be CMORized according to the official CMIP7 Data Request. Detailed instructions for uploading your model results to the Earth System Grid Federation (ESGF) will be provided closer to the submission phase.

## :material-lifebuoy: Technical Support
If you encounter technical issues regarding the implementation of the forcing datasets, regridding processes, or model integration, please open an issue on our GitHub Repository or reach out to the project's technical team.
