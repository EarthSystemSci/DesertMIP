# Advanced Modular and Offline Testing

Before integrating the DesertMIP dynamic boundary datasets into fully coupled Earth System Models (ESMs), participating modeling groups are highly encouraged to perform modular, uncoupled, or standalone testing of their respective sub-components (e.g., land-surface, aerosol, and atmospheric modules).

## 💡 Rationale for Modular Testing
Evaluating the dynamic forcing in an isolated or semi-coupled environment provides several critical advantages:
1. **Grid-scale Ingestion Validation:** Ensures that the high-resolution, spatiotemporal boundary conditions are accurately mapped onto the native model grids using advanced, mass-conserving interpolation techniques.
2. **Component-level Sensitivity:** Allows centers to isolate and evaluate immediate physical responses—such as perturbations in the surface energy balance, aerodynamic roughness, and baseline dust emission rates—without the confounding noise of full atmospheric feedbacks.
3. **Computational Optimization:** Identifies potential numerical instabilities or energy closure issues in a computationally efficient environment prior to executing resource-intensive transient historical or future scenarios.

## 📋 Recommended Testing Protocols
Rather than prescribing specific algorithms, we recommend adopting generalized, state-of-the-art testing frameworks:

* **Idealized and Single-Column Frameworks (SCMs):** Utilize 1-D or limited-domain configurations to strictly test surface-atmosphere parameterizations over regions with the highest interannual variability in desert boundaries (e.g., transition zones).
* **Regional High-Resolution Testbeds:** Drive standalone modules with standard high-fidelity reanalysis forcing (e.g., capturing realistic meteorology) combined with the DesertMIP dynamic masks over primary dust-source regions. 
* **Multi-variate Diagnostic Validation:** Employ comprehensive, data-driven evaluation pipelines to benchmark offline outputs against a suite of multi-sensor Earth Observation (EO) products and ground-based measurement networks before proceeding to coupled runs.

## 💻 Diagnostic Pipelines and Support
To ensure broad compatibility across diverse modeling architectures, the DesertMIP technical team will provide open-source, generalized pre-processing pipelines. These include scalable regridding tools and spatiotemporal diagnostic scripts designed to be framework-agnostic.

For the latest integration guidelines, regridding utilities, and diagnostic packages, please visit our [GitHub Repository](https://github.com/EarthSystemSci/DesertMIP).
