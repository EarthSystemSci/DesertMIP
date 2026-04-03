# Experimental Design

## 📖 Overview
This page describes the experimental protocols for **DesertMIP** under the CMIP7 framework. The core objective is to isolate the climate responses and biogeochemical feedbacks associated with transient desertification and dynamic land-surface changes compared to static representations.

## 🧪 Experiment Tiers

### 🥇 Tier 1 (Required)
Core experiments that all participating models should run to be considered part of DesertMIP. These parallel standard CMIP7 DECK and historical simulations but include our dynamic bare-soil forcing.

| Experiment | Description | Years | Priority |
| :--- | :--- | :--- | :--- |
| `hist-desert` | Historical simulation with transient desert boundaries and dynamic bare-soil fraction. | 1850-2014 | Required |
| `ssp370-desert` | Future projection (SSP3-7.0 baseline) with projected continued desertification forcing. | 2015-2100 | Required |

### 🥈 Tier 2 (Recommended)
Additional experiments designed to isolate specific forcing mechanisms (e.g., separating dust radiative effects from surface albedo changes).

| Experiment | Description | Years | Priority |
| :--- | :--- | :--- | :--- |
| `hist-nodust` | Same as `hist-desert` but with dust radiative feedbacks disabled. | 1850-2014 | Recommended |
| `ssp370-static` | SSP3-7.0 run using a fixed pre-industrial (1850) bare-soil climatology for comparison. | 2015-2100 | Recommended |

### 🥉 Tier 3 (Optional)
Extended sensitivity experiments for specific research questions regarding idealized extreme land-degradation scenarios.

| Experiment | Description | Years | Priority |
| :--- | :--- | :--- | :--- |
| `ideal-desert` | Idealized 1% per year increase in global bare-soil fraction to test extreme model sensitivity. | 150 yrs | Optional |

## 🌍 Forcing Datasets
Experiments must use the official DesertMIP boundary conditions in conjunction with standard CMIP7 forcings:

* **Transient Land Cover:** DesertMIP official time-varying bare-soil and vegetation fractions ($f_{bare}$, $f_{veg}$) version 1.0.
* **Aerosol & GHG Forcings:** Standard CMIP7 historical and SSP3-7.0 atmospheric compositions.

Please refer to the [Data page](../resources/data.md) for download links and specific version information.

## ⚙️ Model Requirements
Participating models should:
* Be fully documented in the CMIP7 ES-DOC database.
* Include an interactive dust emission scheme sensitive to changing bare-soil fractions.
* Follow CMIP7 output naming conventions (CF-Compliant NetCDF).
* Submit all required Tier-1 variables to the ESGF nodes.

## 📅 Timeline

| Milestone | Target Date |
| :--- | :--- |
| Experimental Protocol Finalized | Q1 2026 |
| Forcing Datasets Released | Q2 2026 |
| First Model Submissions Expected | Q4 2026 |
| Initial Multi-Model Analysis Deadline | Q2 2027 |

*✉️ Have questions about the experimental design? Contact the [Steering Committee](../developers/committee.md) for further clarification.*
