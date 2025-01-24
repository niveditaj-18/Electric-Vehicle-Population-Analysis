# Electric-Vehicle-Population-Analysis
A data analytics research project analyzing the distribution, adoption trends, and environmental impacts of electric vehicles (EVs) using the Electric Vehicle Population Dataset. Visualizations and statistical analyses are performed to understand EV ownership patterns in Washington state.

## Overview
This project analyzes electric vehicle (EV) adoption trends in Washington state using data from the Electric Vehicle Population Dataset. We explore the distribution of EVs, adoption trends by vehicle type, and environmental impacts.

## Objectives
- Understand trends in EV adoption across regions and vehicle types.
- Analyze the environmental and financial effects of EVs.
- Compare driving habits of EV owners vs. conventional vehicle owners.

## Dataset
- **Source**: [Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- Includes details on location, vehicle type, make, model, and electric range.
- Vehicle type (BEV or PHEV)
- Manufacturer and model
- Electric range (in miles)
- Registration location (county, state)

## Technologies
- **Python**: pandas, numpy, matplotlib, seaborn
- **R**: tidyverse, ggplot2, plotly, sf
- **Visualization Tools**: Matplotlib, ggplot2

## Methodology
## Data Cleaning and Transformation
- **Duplicate Removal**: Eliminated duplicate rows to avoid double-counting.
- **Null Handling**: Identified and removed null values from critical columns.
- **Filtering**: Selected only records from Washington State for the analysis.

### Statistical Analysis
- Grouped data by **County** and **Manufacturer** to analyze distribution patterns.
- Geospatial visualizations to identify popular EV brands in each region.

### Visualizations
- **Bar plots:** Show top manufacturers and models of EVs.
- **Pie charts:** Highlight the distribution of BEVs vs. PHEVs.
- **Box plots:** Compare electric range distribution for different manufacturers and models.
- **Maps:** Show the most prevalent EV manufacturers by county.

---

## Key Findings
1. **Tesla Dominates**: Tesla is the most owned EV brand across Washington State, with **Model 3** being the most popular.
2. **BEVs Lead**: BEVs account for **76.9%** of EV ownership, indicating a clear consumer preference for fully electric vehicles over PHEVs.
3. **Increasing Electric Range**: Newer EV models have significantly higher electric ranges, which correlates with an increase in their adoption.
4. **Environmental Impact**: BEVs contribute significantly to reducing carbon emissions compared to conventional vehicles.



