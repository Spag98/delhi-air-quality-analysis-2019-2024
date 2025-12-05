# Delhi Air Quality Spatial Analysis (Mini Project)
This repository contains a mini data analysis project exploring air pollution trends in Delhi using a multi-year (2019–2024) air-quality dataset.
The project focuses on practicing data cleaning, visualization, statistical analysis and understanding real-world pollution patterns.

## Objectives (Current Scope):

- Load and clean multi-year pollution data
- Conduct basic exploratory analysis of PM₂.₅ and other pollutants
- Generate seasonal, daily, and long-term trend visualizations
- Identify peak pollution episodes using percentile-based methods
- Perform simple statistical comparisons ( pre- vs post-intervention periods)
- Visualize pollution hotspots using spatial data.
- Perform city- and district-level aggregation and mapping.
- Incorporate **geospatial analysis techniques** such as:
  - Point-in-polygon analysis (to map sensors to boundaries)
  - Buffer analysis (identify regional hotspots)
  - Zonal statistics (mean/max pollutant levels per district)
  - Heatmaps and choropleth maps for spatial storytelling
- Analyze the temporal evolution of PM2.5 and its potential policy relevance (e.g., GRAP activation dates in 2023).
- This project uses Python, Pandas, Matplotlib, and Seaborn and is structured for a Jupyter Notebook workflow.


> **Note:** This project will be expanded further.
---


## Dataset
The project uses the dataset: **processed_aqi_data.csv** (sourced from Kaggle).

**Dataset Overview:**
- Time span: 2019 – 2024  
- Pollutants: CO, NO₂, O₃, PM10, PM2.5, SO₂  
- Air Quality Index (AQI) and AQI category  
- Geolocation: latitude, longitude  
- Temporal features: timestamp, hour, day, month, year, day_of_week, is_weekend


---

## Future Work
- Incorporate **satellite NO₂ or PM2.5 data** (e.g., Sentinel-5P) for cross-validation
- Perform **statistical analysis** of GRAP interventions
- Add **interactive dashboard** with folium or Plotly

---




