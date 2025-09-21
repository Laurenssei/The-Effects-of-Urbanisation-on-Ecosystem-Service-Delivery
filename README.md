# The-Effects-of-Urbanisation-on-Ecosystem-Service-Delivery
# The Effects of Urbanisation on Ecosystem Service Delivery: Implications for Provisioning and Regulating Services

📄 Full Report: [View Analysis](The Effects of Urbanisation on Ecosystem Service Delivery/ Implications for Provisioning and Regulat.pdf)

## Overview
This project examines the impacts of urbanization on provisioning (e.g., crops/food, freshwater, fuelwood, medicinal plants) and regulating (e.g., air quality, climate, flood, soil erosion control) ecosystem services in Kumasi, Ghana, using a 2025 survey of 156 residents from Aboabo, Atonsu, and Susanso. Findings reveal severe degradation, with 73.7% reporting reduced crops/food availability and 77.6% for flood regulation, driven by habitat destruction (75.0% high impact) and water pollution (71.8%). Urbanization rate significantly influences fuelwood and crops (p<0.01), while employment status affects perceptions (p=0.023). Strategies like environmental education (72.4% support) and sustainable urban planning (59.6%) are favored, with strong community participation (57.7%) and green space importance (80.1%). Implications emphasize integrated, participatory planning to mitigate declines and enhance service delivery for urban resilience.

## Objectives
- Investigate the impact of urbanization on the availability and accessibility of key provisioning ecosystem services in Kumasi.
- Examine the effects of urbanization on regulating ecosystem services in Kumasi.
- Identify the primary socio-economic and environmental factors driving ecosystem service degradation in Kumasi.
- Explore how urban planning strategies can enhance the delivery of ecosystem services in Kumasi.

## Dataset Summary
- **Source**: Primary survey data from residents in Aboabo, Atonsu, and Susanso communities, Kumasi, Ghana (2025).
- **Sample Size**: 156 respondents.
- **Key Variables**: Demographics (age, gender, education, employment, community); urbanization indicators (rate, infrastructure, CBD nearness, land cost); ecosystem services (provisioning/regulating changes, degradation index); environmental impacts (habitat destruction, biodiversity loss, water pollution); planning perceptions (green spaces importance, strategies, participation).

## Methods
- Descriptive statistics (frequencies, percentages, means) and visualizations (bar plots, histograms, heatmaps) for profiling demographics, service changes, and impacts.
- Inferential analyses including chi-square tests for associations (e.g., urbanization rate vs. services), ANOVA for group differences (e.g., employment vs. degradation), ordinal logistic regression for predictors (e.g., urbanization on service changes), correlation matrices, and PCA for dimensionality reduction.
- Composite degradation index and severity rankings to quantify cumulative effects; strategy priority matrix and phased implementation framework for planning insights.

## Key Findings
- Provisioning services degrade severely (73.7% for crops/food, 73.1% for fuelwood), increasing with urbanization rate (e.g., 80.6% crops in rapid areas; significant for fuelwood/crops, p<0.01); freshwater (60.9%) and medicinal plants (53.8%) less affected.
- Regulating services show high negative impacts (77.6% flood regulation, 72.4% air quality), with severity rising in rapid urbanization (74.5–81.6%); significant associations for air quality/soil erosion (p<0.05); ecological drivers like habitat destruction (75.0%) and water pollution (71.8%) dominate.
- Primary drivers: Urbanization rate (regression p=0.004, ANOVA p=0.001) and employment status (ANOVA p=0.023); older groups (55–64: 50.0% high degradation) more affected; communities vary (Aboabo highest mean index 2.755).
- Urban planning: Green spaces highly valued (80.1%, Susanso 92.6%); preferred strategies: environmental education (72.4%), traditional knowledge (64.7%); integrated approaches favored (53.2% four+ strategies); participation strong (57.7%, older groups 60.0%); phased framework prioritizes education/planning for high impact.



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, MASS (for ordinal regression), FactoMineR (for PCA), corrplot

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "MASS", "FactoMineR"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). The Effects of Urbanisation on Ecosystem Service Delivery: Implications for Provisioning and Regulating Services.
