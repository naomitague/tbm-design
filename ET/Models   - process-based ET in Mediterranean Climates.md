---
title: Process-Based Models for ET in Mediterranean Climates
date: 2025-03-09
tags:
  - ET
  - modeling
  - process-based
  - models
  - Mediterranean
  - climate
  - RHESSys
  - CLM
  - NOAH-MP
  - VIC
aliases:
  - ET Process Models
summary: |
  This note provides an overview of process-based models for investigating evapotranspiration (ET) in Mediterranean climates like the mountainous Western US. The table below summarizes key aspects including model name, features, typical scale/resolution, data requirements, advantages, and limitations.
---

The following table summarizes several process-based models that have been used for studying ET. These models focus on energy balance and hydrological processes, making them suitable for investigating ET in regions with Mediterranean climates.

| Model Name                                                       | Key Features                                                                                           | Typical Scale/Resolution                                   | Data Requirements                                                                               | Advantages                                                                                          | Limitations                                                                               |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| **VIC (Variable Infiltration Capacity)** #VIC                    | Grid-based hydrologic model; emphasizes water balance and energy fluxes                                | Macro-scale; daily or sub-daily time steps                 | Meteorological forcing (temperature, radiation, humidity, wind), soil and vegetation parameters | Robust for regional water balance studies; widely validated                                         | May oversimplify spatial heterogeneity; calibration can be challenging in complex terrain |
| **RHESSys (Regional Hydro-Ecologic Simulation System)** #RHESSys | Integrates hydrologic, ecological, and biogeochemical processes; flexible framework                    | Catchment to regional scale                                | Detailed meteorological data, land cover, soil, and topographic information                     | Coupled simulation of water, carbon, and nutrient cycles; effective in ecologically diverse regions | High data and computational demands; complex calibration and setup                        |
| **NOAH-MP** #NOAH-MP                                             | Multi-physics land surface model; simulates energy, water, and carbon cycles                           | Regional to global; flexible resolution                    | High-resolution meteorological forcing; detailed soil, vegetation, and topographic datasets     | Comprehensive representation of surface processes; used in weather and climate models               | Complexity may hinder ease of use; requires significant computational resources           |
| **CLM (Community Land Model)** #CLM                              | Advanced land surface model; incorporates detailed representations of energy, water, and carbon fluxes | Global to regional scale; high spatial resolution possible | Extensive climate forcing data, vegetation and soil characteristics                             | Integrates seamlessly with Earth system models; highly developed physics                            | Steep learning curve; computationally intensive                                           |
|                                                                  |                                                                                                        |                                                            |                                                                                                 |                                                                                                     |                                                                                           |

*Note: While these models have been successfully applied in various regions, calibration for Mediterranean climates—characterized by wet winters and dry summers—requires careful attention to local land cover, soil properties, and climate variability.*

## Related Notes
- [Fundamentals of ET](../01_Conceptual_Understanding/Fundamentals_of_ET.md)
- [Process Based Models for ET](Process_Based_Models_for_ET.md)
- [Hydrologic Perspective of ET](Hydrologic_Perspective_of_ET.md)

*This note is part of a broader collection on ET modeling, offering insights to help select the most appropriate process-based model for your research needs.*
