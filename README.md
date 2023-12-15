# Data 512 - Wildfire Impact Analysis Project
## Bismarck, North Dakota

## Project Goal
The course project delves deep into examining the ramifications of wildfires on a specific U.S. city. Summers in the western United States have witnessed an escalating occurrence of wildfires, disseminating smoke across multiple states. Proposed causes encompass factors like climate change, U.S. forestry policies, and heightened awareness. Our primary aim is to furnish invaluable insights to policymakers, city administrators, city councils, and civic institutions. These insights will empower informed decision-making to formulate effective strategies in mitigating future wildfire impacts. 

As part of this project, I conducted a comprehensive analysis focusing on the socio-economic ramifications of the wildfire on **Bismarck, North Dakota** from 1963 to the present day.

## Project Parts

### Part 1 - Common Analysis
Conducted a thorough analysis of wildfire impact on the selected city. Developed an initial prediction model for smoke and assessed its implications on various aspects including health, economics, services, education, and community differences.

### Part 2 - Extension Plan
Extended the initial analysis by modifying the smoke prediction model to estimate specific social or economic impacts on the city. Focused areas include health care, economics, services, education, and community differences. The objective was to provide actionable insights to city officials and residents.

### Part 3 - Presentation
Created a concise PechaKucha presentation summarizing the project findings. Presented the analysis results and implications to city officials, council members, and residents in an engaging format.

### Part 4 - Project Repository
Developed a fully documented repository and a comprehensive written project report. Compiled all analyses, models, and findings to inform policy makers, city managers, and civic institutions about potential future impacts and mitigation strategies.

## Licenses

### Repository License

This project has been licensed under the [MIT License](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/LICENSE).

### Reference Material and Reference License

Some code examples that were developed by Dr. David W. McDonald for use in DATA 512, a course in the UW MS Data Science degree program has been used in the analysis. This code is provided under the [Creative Commons](https://creativecommons.org) [CC-BY license](https://creativecommons.org/licenses/by/4.0/). Revision 1.1 - September 5, 2023

- #### Individual City Assignment
Everyone has been assigned a unique U.S. city for their individual analyses. To access the assigned city, refer to the [Google Spreadsheet](link-to-spreadsheet).

- #### EPA Air Quality History Example Script 1
[Data 512 - Part1_epa_air_quality_history_example.ipynb](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/06_reference_scripts/Data%20512%20-%20Part1_epa_air_quality_history_example.ipynb): Jupyter Notebook showcasing an example script related to EPA air quality history, aiding our analysis.
- ### Part1 - Wildfire Geo Proximity Example Script 1
[Data 512 - Part1_wildfire_geo_proximity_example.ipynb](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/06_reference_scripts/Data%20512%20-%20Part1_wildfire_geo_proximity_example.ipynb): Jupyter Notebook presenting an example script demonstrating wildfire geo proximity calculations for reference.

## Data Sources

### Souce Data
`USGS Data` - United States Geological Survey USGS Combined wildland fire datasets for the United States and certain territories, 1800s-Present (combined wildland fire polygons) is an open-source US public domain dataset containing the comprehensive data set of fires of polygon and attributes.  Link: https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81

`AQI Data` -  The [documentation](https://aqs.epa.gov/aqsweb/documents/data_api.html) for the API provides definitions of the different call parameter and examples of the various calls that can be made to the API. Some [additional information on the Air Quality System can be found in the EPA FAQ](https://www.epa.gov/outdoor-air-quality-data/frequent-questions-about-airdata) on the system. The US Environmental Protection Agency (EPA) Air Quality Service (AQS) API. https://docs.airnowapi.org/ This is a historical API and does not provide real-time air quality data. Page requests were utilized to collect the AQI particle index. This open-source information provided by https://www.airnow.gov/

`USDA Data` - Most of the information available from this site is within the public domain. Public domain information on the National Agricultural Statistics Service (NASS) Web pages may be freely downloaded and reproduced. However, it is requested that in any subsequent use of this work, USDA-NASS be given appropriate acknowledgment. Link: https://www.nass.usda.gov/datasets/

### Processed Data 2
- `02_data/01_source_data/` - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/02_data/01_source_data/README.md): Raw datasets utilized for analysis.
- `02_data/02_intermediate_data/` - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/02_data/02_intermediate_data/README.md): Cleaned and processed data files.
- `02_data/03_final_data/` - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/02_data/03_final_data/README.md): Immaculate, refined datasets ready for analysis.

### Attributions

- Dr. David W. McDonald - for providing code snippets that acted as guidelines in navigating newer APIs that I didn’t particularly have experience with.
- Aviva Munshi - for collaborating with the project approach and for providing technical assistance with the operational issues when I faced issues.
- Rhea Sharma - for collaborating with the project approach and for providing technical assistance with the operational issues when I faced issues.
- Nizan Howard - for collaborating with the project approach and for providing technical assistance with the operational issues when I faced issues.

## Folder Structure 

Details of the folder structure are given in the [Project Folder Structure Guide](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/Project%20Folder%20Structure%20Guide.md)

### 01_src
- Source code repository - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/01_src/README.md): Core source code files reside here

### 02_data
- Data storage for the project - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/02_data/README.md): Contains source, intermediate and final data

### 03_supporting_documentation
- Repository for project-related documents and notes - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/03_supporting_documentation/README.md): Holds project-related documentation 

### 04_results_and_reports
- Storage for project reports and outcomes - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/04_results_and_reports/README.md): Project reports and visualizations' reflections

### 05_dependencies
- Third-party libraries and dependencies - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/05_dependencies/README.md): Repository for third-party libraries and packages. Contains the 'Reader' package.

### 06_reference_scripts
- Custom scripts and utilities - [Link to README](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/06_reference_scripts/README.md): Custom automation scripts for various project functionalities
   
### 99_archive
- Archival or backup copies of project files for safekeeping 

## Project Implementation

### Part 1 - Common Analysis

- Step 1: Data Acquisition - `Data512-WildFire-Project\01_src\01_Data512 - CommonAnalysis_Part1_Wildfire_DataPull.ipynb`
  - Acquire the Combined Wildland Fire Datasets - `Data512-WildFire-Project\02_data\01_source_data\USGS_Wildland_Fire_Combined_Dataset.zip` .
  - Obtain dataset documentation in ArcGIS and GeoJSON formats.
  - Find the assigned US city for individual analysis from the provided spreadsheet - `Data512-WildFire-Project\03_supporting_documentation\Data512 - WildfireProject - Part 1 - Wildfire Cities Assignments.xlsx`.

- Step 2: Create Fire Smoke Estimates -`Data512-WildFire-Project\01_src\03_Data512 - CommonAnalysis_Part1_Wildfire_DataAnalysis.ipynb`
  - Estimate smoke impacts on the assigned city for the last 60 years.
    - Consider annual fire seasons (May 1st - Oct 31st) and fires within 1250 miles.
    - Explore Python, ArcGIS, or GeoJSON readers for the wildfire data.
    - Calculate smoke estimates based on fire intensity, size, and proximity to the city.
    - Compare smoke estimates with available EPA Air Quality Index (AQI) data - `Data512-WildFire-Project\01_src\02_Data512 - CommonAnalysis_Part1_Wildfire_AQIPull.ipynb` 
    - Develop a predictive model for smoke estimates over the next 25 years (2024-2049). - `Data512-WildFire-Project\01_src\04_Data512 - CommonAnalysis_Part1_Wildfire_ModelPredictions.ipynb`

- Step 3: Visualize Analysis Aspects - `Data512-WildFire-Project\04_results_and_reports\02_results`
  - Produce graphs:  `Data512-WildFire-Project\01_src\04_Data512 - CommonAnalysis_Part1_Wildfire_ModelPredictions.ipynb`
    - Histogram of fires at various distances from the city.
    - Time series of total acres burned annually within specified distance.
    - Graph comparing fire smoke estimates for the city with AQI estimates.

- Step 4: Write and Reflect - `Data512-WildFire-Project\04_results_and_reports\01_reports\Data512 - WildFireProject_Part1_Reflection.pdf`
  - Explain visualizations:
    - Provide detailed explanations for each visualization's purpose and content.
    - Describe axes, underlying data, and processing methods briefly.
  - Reflect on collaborative activities:
    - Highlight learnings from addressing the research question.
    - Discuss collaboration's impact on problem-solving.
    - Attribute reused code, methods, and techniques explicitly.

### Part 2 - Extension Plan 

  - Purpose:
    - Inform the city council, city manager/mayor, and city residents about potential future smoke impacts.
    - Extend the initial prediction model for smoke to estimate social or economic impacts on the city.

  - Potential Focus Areas:
    - Health care, economics, services, education, community differences.
  
  - Model Enhancement:
    - Improve smoke impact model considering the azimuth between fire events and the assigned city.

  - Objective:
    - Results should inform future planning for the city council, city manager/mayor, and city residents.

  - Extension Plan - `Data512-WildFire-Project\04_results_and_reports\01_reports\Data512 -  WildfireProject_Part2_ExtensionPlan.pdf` 

  - Key Points in Extension Plan:
    1. Motivation/Problem Statement:
       - Importance to the community.
       - How it serves the community's needs.
    
    2. Impact Focus:`Data512-WildFire-Project\01_src\06_Data512 - ProjectExtension_Part2_AgricultureData_Acquisition.ipynb`
       - Choose one of the provided focus areas or propose a specific focus.
    
    3. Data or Model:`Data512-WildFire-Project\01_src\07_Data512 - ProjectExtension_Part2_AgricultureData_DataAnalysis.ipynb`
       - Additional data description, licensing, or leveraging existing models.
    
    4. Unknowns and Dependencies: `Data512-WildFire-Project\01_src\08_Data512 - ProjectExtension_Part2_AgricultureData_Forecasting.ipynb`
       - Factors impacting the analysis beyond control.
    
    5. Timeline to Completion:
       - Milestones and tasks breakdown.
       - Allocated time for the extension plan, presentation, and final report.

### Part 3 - Project Presentation

- Project Presentation

  - Presentation Format:`Data512-WildFire-Project\04_results_and_reports\01_reports\Data 512 - WildfireProject_Part3_PechaKuchaPresentation.pdf`
    - PechaKucha style with 11 slides, each auto-advancing every 20 seconds.
    - Acceptable formats: PowerPoint or a set of 11 PDF pages.
    - No animations allowed in the PowerPoint deck.
  
  - Presentation Evaluation Criteria:
    - Professional research presentation.
    - Communicating research importance to a non-specialist audience (like explaining to a city council).
    - Accurate and compelling communication of findings and implications.
  
  - Submission Details:
    - Slide deck submission before the class session.
    - Deck assembled in groups by instructors for presentation order.
  
  - Key Tips:
    - Focus on a clear, concise message.
    - Extensive practice is crucial for effective delivery.

### Part 4 - Project Repository

#### Goal
Demonstrate expertise in human-centered data science by creating a comprehensive, understandable, impactful, and reproducible research artifact.

#### Repository Contents 
- [Github Repository Link](https://github.com/shweta97m/Data512-WildFire-Project) 
- [Google Drive Repository Link](https://drive.google.com/drive/folders/1352N8GNKq_DmBobbc2sG4cepJI_6BbRW?usp=drive_link)
- Written Document: Includes Common Analysis results and proposed Part 2 extension in a well-documented report or paper.
- Code: All code stored in notebooks with complete documentation.
- Data Descriptions: Detailed descriptions and source links for all utilized data with proper citation.
- Model Documentation: Complete documentation and citation for adopted or adjunctive models.
- Intermediate Data Documentation: Description of any intermediate data files created during the analysis.
- README File: Appropriate documentation in .md or .txt format.
- LICENSE File: Properly structured license information.

#### Report Details - 
- [Final Report (Github)](https://github.com/shweta97m/Data512-WildFire-Project/blob/main/04_results_and_reports/01_reports/Data512%20-%20%20WildfireProject_Part4_FinalReport.pdf)
- [Final Report (Google Drive)](https://docs.google.com/document/d/1wgp_uKzbenXNehcHnY8CxNyNXzgMkpxDODubWEPK
5RQ/edit?usp=drive_link)
1. Introduction: Outlines the importance, motivation, and real-world implications of the analysis.
2. Background/Related Work: Summarizes previous research and existing models related to the analysis.
3. Methodology: Details analytical methods and the human-centered considerations that influenced the study's design.
4. Findings: Present the results using figures and clear descriptions.
5. Discussion/Implications: Discusses the significance of findings and recommendations for stakeholders.
6. Limitations: Addresses limitations and potential biases within the study.
7. Conclusion: Restate research questions and findings, emphasizing the study's contributions to human-centered data science.
8. References: Lists all publications referred to in the text.
9. Data Sources: Provides links to all relevant data sources utilized in the analysis.


## Known Issues or Special Considerations with the Data

Special care and attention need to be given to this section if implementing this project.

- The dataset covers wildfires from 1963 to 2023, but limitations exist in pinpointing exact fire start and end dates
- Availability and reliability of Air Quality Index (AQI) data might vary across different regions
- Incorporating the selected attributes of fires into smoke impact estimation poses challenges due to data constraints
- The EPA's monitoring station coverage might not be exhaustive, affecting AQI estimations for specific cities
- AQI was only limited to particulate matter since there was limited information about the gaseous impact
- The missing values for AQI were filled with average values
- AQI API needs credentials and setup before we can request the data
- Runtime is significantly high for the USGS GeoJSON
- Parts 2 and 3 are implemented with a sole focus in mind and do not consider any additional Impacting factors
- Model Predictions are subject to uncertainty and a certain error margin should be expected
- Yield forecast methodology needs more refinement and statistical proof of the result
- Correlation is used to maintain a relationship between variables, however, correlation is not equal to causation. Causation testing is beyond the scope of the project
- The extended analysis is done for the county of Burleigh, of which Bismarck, North Dakota is a part 



This README provides an overview of the project's goal, emphasizing the analysis of wildfire impacts and the aim to provide valuable insights for city stakeholders and residents
