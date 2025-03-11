---
title: Process Based Models for ET
date: 2025-03-09
tags: [ET, modeling, energy balance, process-based models]
aliases: [ET Process Models]
summary: >
  This note provides an overview of process‐based models for evapotranspiration (ET), emphasizing their energy balance focus, key inputs, limitations, and examples such as VIC and RHESSys.
---
## Overview
Process based models for evapotranspiration (ET) simulate the physical processes governing water and energy exchanges between the land surface and the atmosphere. These models typically focus on the energy balance and mass conservation, integrating various physical processes to predict ET under diverse environmental conditions.

## Key Characteristics
- **Energy Balance Focus:**  
  Most process based models simulate ET by calculating the balance between incoming solar radiation, sensible and latent heat fluxes, and ground heat flux.
- **Physical Processes:**  
  They incorporate processes such as soil moisture dynamics, canopy resistance, stomatal conductance, and evaporation from bare soils.

## Key Inputs
- **Meteorological Data:**  
  - Solar radiation, temperature, humidity, and wind speed.
- **Land Surface Characteristics:**  
  - Soil properties (e.g., texture, moisture capacity), vegetation type, leaf area index (LAI), and canopy cover.
- **Hydrological Parameters:**  
  - Precipitation, runoff, and groundwater contributions.
- **Topography:**  
  - Elevation and slope can influence the distribution of energy and water.

## Downsides / Limitations
- **Complexity and Data Requirements:**  
  These models require detailed, high-resolution data, which may not be available for all regions.
- **Parameter Uncertainty:**  
  Calibration of numerous parameters can introduce uncertainties, particularly in heterogeneous landscapes.
- **Computational Demand:**  
  Process based models can be computationally intensive, especially when applied at high spatial resolutions or over large areas.
- **Simplifications:**  
  Despite their complexity, models often simplify certain processes or interactions, which can limit accuracy in specific conditions.

## Examples of Process Based Models
- **VIC (Variable Infiltration Capacity):**  
  A macroscale hydrological model that simulates water balance and energy fluxes using grid-based computations.
- **RHESSys (Regional Hydro-Ecologic Simulation System):**  
  Integrates hydrological, ecological, and biogeochemical processes to model landscape dynamics and ET.
- **Other Models:**  
  Models like NOAH-MP and CLM (Community Land Model) also incorporate process based approaches to simulate ET as part of broader land surface and climate modeling frameworks.

## Related Notes
- 

## Open Questions / Gaps
- How can parameter uncertainty be better constrained in heterogeneous landscapes?
- What are the most effective strategies for integrating high-resolution remote sensing data into process based models?

## Surprises / Novel Insights
- Recent studies have demonstrated that even minor adjustments in canopy resistance parameters can significantly impact overall ET estimates.
- Integration of machine learning techniques with traditional process based models is an emerging area that could enhance model performance and reduce computational demand.

*This note is part of a broader collection on ET modeling, providing insights into process based approaches and their application in hydrological research.*
