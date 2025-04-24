---
title: Empirical Models for ET – The Budyko Curve
date: 2025-03-09
tags: [ET, modeling, empirical models, Budyko curve, hydrology]
aliases: [ET Empirical, Budyko ET]
summary: >
  This note describes the use of empirical models for evapotranspiration (ET) with a focus on the Budyko curve. It explains the basic principles, step-by-step approach, key inputs, limitations, and provides context for how the Budyko framework is used in hydrological analysis.
---

## Overview
Empirical models for ET are designed to estimate long-term water and energy balance using observed data. One of the most renowned empirical approaches in hydrology is the Budyko curve, which relates the long-term ratio of actual ET to precipitation with the ratio of potential ET (reflecting energy availability) to precipitation. This note explains the Budyko approach step by step.

## Step-by-Step Explanation of the Budyko Curve

1. **Fundamental Principle:**  
   - The Budyko curve provides a conceptual framework that expresses how available water (precipitation) is partitioned between evapotranspiration (ET) and runoff over long time periods.
   - It recognizes that, in the long-term, catchment water balance is controlled by both energy availability (affecting potential ET) and water supply (precipitation).

2. **Key Variables:**
   - **P (Precipitation):** Total long-term precipitation input to the system.
   - **PET (Potential Evapotranspiration):** The energy-driven maximum ET rate assuming unlimited water.
   - **ET (Actual Evapotranspiration):** The realized water loss from the catchment, which is usually less than or equal to PET.

3. **The Budyko Relationship:**  
   - The curve is often expressed in a dimensionless form:
$$
\frac{ET}{P} = f\left(\frac{PET}{P}\right)
$$

   - This equation means that the ratio of actual ET to precipitation is a function of the ratio of potential ET to precipitation.

4. **Interpreting the Curve:**
   - **Water-Limited Regime:** When precipitation is low relative to energy (high 
     $$
     \frac{PET}{P}
     $$), ET is strongly limited by water availability.
   - **Energy-Limited Regime:** When precipitation is high relative to energy (low 
     $$
     \frac{PET}{P}
     $$), ET approaches PET, being constrained primarily by available energy.


5. **Calibration and Application:**  
   - The empirical Budyko curve is calibrated using long-term observational data from catchments or regions.
   - It provides insights into the balance between water supply and energy demand, and is used to evaluate changes in climate, land cover, or water management practices.

## Key Inputs for the Budyko Model
- **Meteorological Data:**  
  Measurements of precipitation (P) and meteorological variables needed to estimate PET (e.g., temperature, solar radiation, humidity).
- **Catchment Characteristics:**  
  Information about soil properties, vegetation cover, and topography may be used to refine the model.
- **Long-Term Averages:**  
  Budyko analysis typically uses long-term (annual or multi-year) averages to smooth out short-term fluctuations.

## Downsides / Limitations
- **Simplicity vs. Complexity:**  
  While the Budyko curve provides a useful first-order estimate, it oversimplifies complex hydrological processes by focusing on average behavior over long periods.
- **Parameter Uncertainty:**  
  Calibration of the curve may introduce uncertainties, particularly when applying the model to diverse climates or land-use conditions.
- **Temporal Resolution:**  
  It is best suited for long-term averages and may not capture short-term dynamics in ET.

## Example: Application in Regional Water Balance Studies
- **Use Case:**  
  Researchers often use the Budyko curve to compare water balance across catchments with different climatic conditions. For instance, by plotting \( \frac{ET}{P} \) against \( \frac{PET}{P} \), one can assess whether a region is more water- or energy-limited.
- **Adaptability:**  
  The framework can be extended or modified to account for specific factors (e.g., vegetation type or human impacts) by incorporating additional calibration parameters.

## Data & References
- **Measurement Techniques:**  
  Long-term meteorological records and catchment data are critical for calibrating and validating the Budyko model.
- **Key Literature:**  
  Research articles and case studies that explore the application of the Budyko curve in different climatic and geographic settings.

## Related Notes
- [Process Based Models for ET](Process_Based_Models_for_ET.md)
- [Fundamentals of ET](../01_Conceptual_Understanding/Fundamentals_of_ET.md)
- [Hydrologic Perspective of ET](Hydrologic_Perspective_of_ET.md)

## Open Questions / Gaps
- How can the Budyko framework be refined to better account for seasonal variability and land use changes?
- What are the limitations of applying the Budyko curve to rapidly changing climates?

## Surprises / Novel Insights
- Recent studies suggest that coupling the Budyko curve with remote sensing data can improve the estimation of ET in heterogeneous landscapes.
- Modifications to the traditional Budyko approach are emerging to better capture the influence of vegetation dynamics on long-term water balance.

*This note is part of a broader collection on ET modeling, providing an in-depth look at empirical approaches with a focus on the Budyko curve.*
