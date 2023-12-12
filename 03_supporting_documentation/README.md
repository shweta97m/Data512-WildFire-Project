# DATA512 Project Part 1 - Common Analysis

City Assigned - Bismarck, North Dakota

## Data/processed_data  
The datafiles listed below can be found in the ..Data/processed_data/ folder. These are the intermediate results obtained at different steps of the common analysis

### `AQI_DataPull_1963_2023_monthly.csv`

- **Description**: Contains the AQI information pulled from the API for the years 1963 to 2023. It is aggregated at the monthly level.

- **Columns**:
  - 'date': Last date of the month for which the AQI is recorded. 
  - 'aqi': The aggregated Air Quality Index estimated for every month.
  - 'pollutant_id' : Pollutant identifier



### `distance.csv`

- **Description**: Contains details shortest distance of each fire from the assigned city.

- **Columns**:
  - 'OBJECTID': Unique identifier for each fire feature.
  - 'shortest_dist': The distance between the wildfire and the city. 


### `wildfire_smoke_estimates.csv`   

- **Description**: Contains the smoke estimate with all the features that contributed to the smoke estimate for each fire from 1963 to 2023 that was 1250 miles from Bismarck, North Dakota.

- **Columns**:  
- 'OBJECTID': Unique identifier for each record.
- 'Fire_Year': The year in which the fire occurred.
-  'GIS_Acres': Area of the fire in acres according to GIS data.
- 'Shape_Area': Geometric area of the fire polygon.
- 'shortest_dist': The distance between the wildfire and the city.  
- 'days_fire_lasted' - The number of days for which the fire lasted.
- 'scaled_days_fire_lasted' - The number of days for which the fire lasted scaled 
- 'fire_intensity' - Intensity of the wildfire
- 'Year Difference'	- Time Difference in years between 2 overlapped fires 
- 'Area of Overlap' - Area of overlap between 2 fires in acres	
- 'Percentage of Overlap'- Percent of overlap between 2 fires in 
- 'overlap_component' - Factor of overlap between 2 fires
- 'scaled_overlap_component' - Scaled factor of overlap between 2 fires
- 'smoke_estimate' - Estimated smoke impact component


### `yearly_smoke_estimates.csv`

- **Description**: This is basically `wildfire_smoke_estimates.csv` merged with `AQI_DataPull_1963_2023_monthly.csv` aggregating over a year.

- **Columns**:  
- 'Year': The year of the monthly AQI estimate.  
-  'GIS_Acres': Area of the fire in acres according to GIS data.
- 'Shape_Area': Geometric area of the fire polygon.
- 'shortest_dist': The distance between the wildfire and the city.  
- 'fire_intensity' - Intensity of the wildfire
- 'scaled_overlap_component' - Scaled factor of overlap between 2 fires
- 'smoke_estimate' - Estimated smoke impact component
- 'aqi': The estimated Air Quality Index value for the corresponding year and month.   




### `wildfire_attributes.csv`

- **Description**: Contains details about fires that occurred after 1963.

- **Columns**:
   - 'OBJECTID': Unique identifier for each record.
   - 'USGS_Assigned_ID': US Geological Survey assigned identifier for the wildfire.
   - 'Assigned_Fire_Type': Type categorization of the assigned fire.
   - 'Fire_Year': The year in which the fire occurred.
   -  'Fire_Polygon_Tier': Tier classification for the fire polygon.
   -  'Fire_Attribute_Tiers': Attribute tiers associated with the fire.
   -  'GIS_Acres': Area of the fire in acres according to GIS data.
   -  'GIS_Hectares': Area of the fire in hectares according to GIS data.
   -  'Source_Datasets': Datasets from which the wildfire information is sourced.
   -  'Listed_Fire_Types': Types of fires as listed in the dataset.
   -  'Listed_Fire_Names': Names associated with listed fires.
   -  'Listed_Fire_Codes': Codes assigned to listed fires.
   -  'Listed_Fire_IDs': IDs corresponding to listed fires.
   -  'Listed_Fire_IRWIN_IDs': Incident Resource Inventory Network (IRWIN) IDs for listed fires.
   -  'Listed_Fire_Dates': Dates associated with listed fires.
   -  'Listed_Fire_Causes': Causes attributed to listed fires.
   -  'Listed_Fire_Cause_Class': Classification of fire causes.
   -  'Listed_Rx_Reported_Acres': Acres reported for prescribed burns.
   -  'Listed_Map_Digitize_Methods': Methods used for map digitization of listed fires.
   -  'Listed_Notes': Additional notes for listed fires.
   -  'Processing_Notes': Notes regarding the processing of wildfire.
   -  'Wildfire_Notice': Indicator for wildfire occurrence.
   -  'Prescribed_Burn_Notice': Indicator for prescribed burn occurrence.
   -  'Wildfire_and_Rx_Flag': Flag indicating overlap between wildfire and prescribed burn.
   -  'Overlap_Within_1_or_2_Flag': Flag indicating overlap within 1 or 2 years.
   -  'Circleness_Scale': Scale representing the circularity of the fire polygon.
   -  ' Circle_Flag': Flag indicating circularity of the fire polygon.
   - 'Exclude_From_Summary_Rasters': Flag indicating exclusion from summary rasters.
   - 'Shape_Length': Geometric length of the fire polygon.
   - 'Shape_Area': Geometric area of the fire polygon.
        

