# Frequently Asked Questions (FAQs)

## General Questions

**What is DesertMIP?**  
DesertMIP (Desertification Model Intercomparison Project) is an endorsed CMIP7 project designed to evaluate the climate impacts of transient desert boundaries and dynamic land-cover changes, comparing them against traditional static surface masks.

**How do I participate?**  
Modeling groups interested in participating should first review our experimental protocols (Tier-1). Please contact the Steering Committee to formally register your Earth System Model (ESM).

**Is my model eligible?**  
Any ESM participating in CMIP7 that includes an interactive land-surface model capable of prescribing external time-varying bare-soil and vegetation fractions (<i>f</i><sub>bare</sub>, <i>f</i><sub>veg</sub>) is eligible.

## Data Questions

**Where can I find DesertMIP data?**  
All forcing datasets and model outputs will be hosted on the official Earth System Grid Federation (ESGF) nodes under the CMIP7/DesertMIP project tag.

**How should I cite the data?**  
When using DesertMIP datasets, please cite our official experimental design paper (currently in preparation for Geoscientific Model Development - GMD) along with the specific DOIs assigned to the ESGF datasets.

**What variables are available?**  
We focus heavily on land-surface and aerosol feedback variables. Key required variables include dust emissions (`emidust`), surface wind (`sfcWind`), and leaf area index (`lai`). Please refer to the Data page for a complete list.

## Technical Questions

**What forcing datasets should I use?**  
Participating models must use the official DesertMIP transient forcing dataset, which provides updated monthly arrays for bare-soil and vegetation fractions from 1850 to 2100.

**What is the experiment naming convention?**  
We strictly follow the CMIP7 naming conventions. For example, files must be named using the following format:  
`<variable>_<table>_<model>_<experiment>_<variant>_<grid>_<time>.nc`

## Contributing to This Site

**How do I suggest changes to this website?**  
The DesertMIP website is open-source. You can suggest changes by submitting an issue or a Pull Request (PR) directly on our GitHub repository.

**Have a question not answered here?**  
Contact the Steering Committee for further assistance.
