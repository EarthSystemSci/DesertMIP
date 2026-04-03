# Output Variables & Data Submission

To rigorously evaluate the impact of dynamic desertification, modeling centers participating in DesertMIP are required to output a specific set of variables. These encompass land surface changes, aerosol emissions, and standard atmospheric responses.

## Requested Output Variables

### High Priority Variables (Tier-1 Core Request)
These variables are strictly required for all Tier-1 experiments (`desert-hist-dyn`, `desert-ssp245-dyn`, `desert-static-ctrl`) to capture the primary biogeophysical and aerosol feedback loop:

| Variable Name | CMIP Table | Frequency | Description |
| :--- | :--- | :--- | :--- |
| `tas` | Amon | Monthly | Near-surface air temperature |
| `pr` | Amon | Monthly | Precipitation (solid and liquid) |
| `sfcWind` | Amon | Monthly | Near-surface wind speed (crucial for dust emission) |
| `emidust` | AERmon | Monthly | Total primary emission rate of dust aerosol |
| `od550aer` | AERmon | Monthly | Aerosol Optical Depth at 550nm (total) |
| `lai` | Lmon | Monthly | Leaf Area Index |
| `albs` | Lmon | Monthly | Surface Albedo |

### Medium Priority Variables (Recommended)
Highly recommended for in-depth regional sensitivity analyses and surface energy budget closure:

| Variable Name | CMIP Table | Frequency | Description |
| :--- | :--- | :--- | :--- |
| `hfls` | Amon | Monthly | Surface Upward Latent Heat Flux |
| `hfss` | Amon | Monthly | Surface Upward Sensible Heat Flux |
| `mrso` | Lmon | Monthly | Total Soil Moisture Content |
| `rsds` | Amon | Monthly | Surface Downwelling Shortwave Radiation |

## Data Submission and Publication

All generated datasets must strictly adhere to WCRP CMIP7 protocols and FAIR principles.

### Naming Conventions
Files must be structured using the official CMIP7 file naming convention: 
`<variable>_<table>_<model>_<experiment>_<variant>_<grid>_<time>.nc`

*Example:* `emidust_AERmon_ModelName_desert-hist-dyn_r1i1p1f1_gn_198001-201412.nc`

### Quality Control Checklists
Before initiating the ESGF publication process, centers must verify:
 * Variables have been processed using the official CMOR library.
 * Global attributes contain accurate model and forcing configurations.
 * Time boundaries (`time_bnds`) are properly defined for transient runs.
 * Grid definitions comply with CF metadata standards.

Publication will occur through designated local or regional ESGF nodes. Detailed credentials and the official DesertMIP Data Request (DR) JSON files will be provided post-registration.
