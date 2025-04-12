# Islamic Family Food Hamper Distribution Optimization

## Overview

This project, developed as part of a data science initiative, aims to enhance the efficiency of food hamper distribution by the **Islamic Family** organization in Edmonton. By leveraging historical distribution data and key socio-economic indicators, this analysis identifies geographic regions with high or low demand, enabling better-targeted outreach and resource allocation.

## Objective

To:
- Analyze historical food hamper distribution data in Edmonton.
- Identify socio-economic trends that correlate with hamper demand.
- Pinpoint areas that require more support or could benefit from mobile distribution units.
- Provide actionable insights to improve accessibility and service delivery.

## Dataset

The project uses:
- Historical food hamper request and delivery records.
- Publicly available socio-economic data (e.g., census income, population density).
- Geographic boundary data for neighborhood-level analysis.

## Methods

Key techniques include:
- Data cleaning and preprocessing.
- Exploratory data analysis (EDA).
- Correlation analysis between socio-economic indicators and hamper demand.
- Geographic heatmapping and clustering.
- Visualization of distribution trends using Python libraries such as `pandas`, `matplotlib`, `seaborn`, and `folium`.

## Key Findings (Summary)

- Specific neighborhoods showed consistently high demand for food hampers.
- Demand correlates strongly with lower household income and higher population density.
- Some underserved areas could benefit from mobile distribution points due to distance from fixed centers.

## Tools & Technologies

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn, Folium
- GeoPandas (if used)
- Open-source socio-economic datasets

## How to Run

1. Install required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn folium geopandas
   ```

2. Open the notebook file:
   ```
   Islamic Family Food Hamper Optimization.ipynb
   ```
3. upload the data 
4. Follow the step-by-step cells to explore the data and visualizations.

## Future Work

- Incorporate real-time data feeds (if available).
- Develop a predictive model for future hamper needs.
- Build an interactive dashboard for stakeholders.

## Acknowledgments

- Islamic Family for providing access to distribution data.
- Open Data Edmonton and Statistics Canada for socio-economic datasets.
