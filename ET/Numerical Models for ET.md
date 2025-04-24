---
title: Process Based Models for ET
date: 2025-03-09
tags: [ET, modeling, energy balance, process-based models]
aliases: [ET Process Models]
summary: >
  This note provides an overview of process‐based models for evapotranspiration (ET), emphasizing their energy balance focus, key inputs, limitations, and examples such as VIC and RHESSys.
---
While physics of evaporation are well-understood; estimating the variables involved always require simplifications - the appropriate simplification depends on application (location, scale, time)
Appropriate model depends on Time/Space Scale and whether partitioning between E and T matters.

## Key Controls
- **Atmospheric Controls:**  
	  * Energy -  balance between incoming solar radiation, sensible and latent heat fluxes, and ground heat flux.
	  * Diffusion - vapor conductance (atmospheric conductance) depends on boundary layer perperties at the leaf surface (usually modelled by wind speeds, vapor pressure deficit)
- **Water availability:** 
	- Water availability depends on inputs, storage and loss (both through prior ET and drainage)
	- Hydrologic models and measurements are used to define this (link to hydrologic cycle model)
	
	
  
	- 


## Basic models
	
- [[Budyko Curve|Budyko ET]]
- Thornwaite
-  Penman/ Penman Monteith
- Machine Learning (non-physically based)

## ET from Hydrologic Models
[[Processbased Hydrologic models]]

	
	Evaluation of ET in hydrologic modeling context

ET from Remote Sensing Models


## Related Notes
- 

## Open Questions / Gaps
- How can parameter uncertainty be better constrained in heterogeneous landscapes?
- What are the most effective strategies for integrating high-resolution remote sensing data into process based models?

## Surprises / Novel Insights
- Recent studies have demonstrated that even minor adjustments in canopy resistance parameters can significantly impact overall ET estimates.
- Integration of machine learning techniques with traditional process based models is an emerging area that could enhance model performance and reduce computational demand.

*This note is part of a broader collection on ET modeling, providing insights into process based approaches and their application in hydrological research.*
