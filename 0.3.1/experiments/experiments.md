# Experimental Design & Protocols

The core objective of DesertMIP is to evaluate the impact of transient desert boundaries compared to traditional static masks. To achieve this, we have designed a tiered experimental protocol integrated within the CMIP7 framework.

## Tier-1 Experiments: Historical & Future Baselines
Tier-1 experiments are mandatory for participating modeling centers. They focus on isolating the effect of dynamic desert expansion and contraction.

* **DesertMIP-Hist (Historical):** 
  ESMs will run the standard historical simulation (1850–present), but the static bare-soil and vegetation fractions will be replaced by the DesertMIP transient forcing dataset. 
  *Key metric:* Evaluation of historical dust emission trends and regional surface energy balance.

* **DesertMIP-SSP (Future Projection):** 
  Based on a selected Shared Socioeconomic Pathway (e.g., SSP3-7.0), models will use projected dynamic desert boundaries up to the year 2100. This experiment tests the impact of severe desertification and its feedbacks on the climate system.

## Mathematical Formulation of the Forcing
In standard ESMs, the surface is partitioned into various fractions. DesertMIP provides updated time-varying arrays for bare-soil fraction ($f_{bare}$) and vegetation fraction ($f_{veg}$), ensuring mass and energy conservation such that:
$$f_{bare}(t) + f_{veg}(t) + f_{other}(t) = 100\%$$
Where $t$ represents the transient monthly time step.

## Synergies with Other MIPs
* **AerChemMIP:** DesertMIP provides the crucial dynamic source regions needed by AerChemMIP to accurately simulate future mineral dust aerosols and their radiative forcing.
* **LMIP (Land Surface, Snow and Soil Moisture MIP):** We collaborate closely with LMIP to ensure the dynamic boundary modifications are physically consistent with land-surface hydrology and soil thermodynamics.
