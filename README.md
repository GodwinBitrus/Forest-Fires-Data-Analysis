
# FOREST-FIRE-DATA-ANALYSIS

## Project Overview
This project analyzes forest fire data to evaluate how variables such as moisture content, temperature, wind speed and other weather conditions impact forest fires. The results highlight significant insights that can predict spatial trends, guide allocation of firefighting resources and improve strategies for reducing wildfire risks.

## Data Sources
This analysis is conducted using a "Forest Fire" dataset that records environmental and meteorological conditions. The dataset includes the following columns:

**X,Y** => Spatial coordinates within the Montesinho park map.
**Location** => Specific site or region where the data was collected.
**Month** => Month of observations.
**Day** => Days of the week of the observations.
**Season** => Seasons of the year (e.g, winter, summer).
**DC** => The drought code (DC) reflects long-term dryness in deep soil layers; Indicates potential for persistent fires
**FFMC** => The Fine Fuel Moisture Code indicates mositure content of surface fuels
**DMC** => The Duff Moisture Code measures moisture in moderately deep, compact organic layers; relates to fire spread potential
**ISI** => The Initial Spread Index combines wind and fuel moisture to estimate potential fire spread rate.
**Temp** => The temperature in degree centigrade.
**RH** => The Relative Humidity at the time of observation measures the percentage of moisture content in the atmosphere; lower values means drier conditions.
**Wind** => Wind speed, influencing fire spread
**Rain** => Amount of rainfall
**Area** => Burnt forest area

## Tools Used
Excel: Data Cleaning

SQL Server: Data Analysis

Power BI: Data Visualization

## Data Cleaning & Pre-Processing
Data cleaning and pre-processing were carried out at the initial stage to ensure data quality and the following tasks were performed;

Data loading and inspection
Correcting data type
Creating additional numeric columns
Data cleaning and formatting

## Exploratory Data Analysis (EDA)
The EDA process examines the Forest Fire dataset to analyze variable distributions, detect anomalies and identify relationships between environmental factors and fire occurrence, thereby answering the following key questions:

1. what Locations have the highest propensity to experience forest fires?
2. what locations actually experience forest fires?
3. What season is forest fires most likely to occur?
4. what month has the largest burnt area by forest fires?

## Results/Findings
Distribution of Fire Occurrence: Most fire records are concentrated in summer and early autumn (July–September), while winter and spring months show fewer fire incidents. This suggests a strong link between dry seasons and fire ignition.
Fire Danger Indices: Higher FFMC values are associated with larger fires, showing that dry litter and fine fuels ignite easily.
Burned Area: Most records show small burned areas (<1), meaning large-scale fires are less common. However, a few extreme cases (outliers) show hundreds of hectares burned, highlighting the skewed distribution. The results highlight key insights in seasonality, climate influence and fire distribution, providing essential direction for prevention strategies, emergency planning, and environmental policy in wildfire management.

## Recommendations
Based on the analysis, here are some recommendations:

1. Strengthen Seasonal Monitoring: Focus surveillance and firefighting resources during peak fire months (July–September) when risk is highest.
2. Use Fire Danger Indices for Early Warning: Implement real-time tracking of FFMC, DMC, DC, and ISI values as they are more reliable predictors of fire outbreaks than temperature or rainfall alone.
3. Target High-Risk Zones: Prioritize central and human-accessible parts of the park for fire patrols, as these show higher fire frequencies.
4. Enhance Public Awareness & Human Activity Control: Educate local communities and visitors about fire risks, especially in dry seasons, and enforce stricter fire-use regulations near high-risk zones.
5. Promote Climate Adaptation Strategies: Integrate fire risk insights into forest management and reforestation plans, ensuring vegetation types less prone to fire are considered.
6. Expand Data Collection: Collect longer-term, multi-regional fire data to improve generalization, capture climate change effects, and strengthen predictive accuracy.

## Limitations
This analysis has several limitations; they include the following:

1. Geographic Limitation: The dataset only covers the Montesinho Natural Park in Portugal, which means the findings may not generalize to other regions with different climates, vegetation or human activity.
2. Timeframe Restriction: Data was collected over a limited period and does not reflect long-term climate trends such as global warming, which significantly affects fire frequency and severity.
3. Limited Variables: Important factors like vegetation type, soil moisture, human activities, lightning strikes and firefighting interventions are missing, limiting the explanatory power of the dataset.
