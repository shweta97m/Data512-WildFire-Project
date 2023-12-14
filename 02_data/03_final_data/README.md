# Data512-WildFire-Project
## Folder Contents

Directory: `Data512-WildFire-Project/02_data/03_final_data/`

This guide outlines the functional data organization critical to our project, highlighting the specific purpose of each dedicated data directory.
The datafiles listed below can be found in the /02_data/03_final_data/ folder. These are the final results obtained at different steps of the common analysis

### `final_yearly_wildfire_data_w_smokeestimate_aqi.csv`

**Description**: This is basically `wildfire_smoke_estimates.csv` merged with `AQI_DataPull_1963_2023_monthly.csv` aggregating over a year.

- **Columns**:  
- 'Year': The year of the monthly AQI estimate.  
-  'GIS_Acres': Area of the fire in acres according to GIS data.
- 'Shape_Area': Geometric area of the fire polygon.
- 'shortest_dist': The distance between the wildfire and the city.  
- 'fire_intensity' - Intensity of the wildfire
- 'scaled_overlap_component' - Scaled factor of overlap between 2 fires
- 'smoke_estimate' - Estimated smoke impact component
- 'aqi': The estimated Air Quality Index value for the corresponding year and month.   

### 'predicted_data'

- **Description**: Contains forecasted values for various attributes related to crop production and wildfire impact, corresponding to specific time indexes.

- **Columns**:
  - 'index': Time index for the forecasted values.
  - 'COMMODITY_DESC': Description of the crop commodity.
  - 'AREA HARVESTED': Forecasted value for the area harvested.
  - 'AREA PLANTED': Forecasted value for the area planted.
  - 'smoke_estimate': Forecasted smoke estimate.
  - 'num_fires': Forecasted number of fires.
  - 'PRODUCTION': Forecasted crop production.
  - 'YIELD': Forecasted crop yield.
  - 'numeric_index': Numeric representation of the time index.


This structured data architecture ensures a clear progression from raw inputs to refined, analysis-ready outputs, crucial for our project's success.


