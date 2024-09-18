# Plan: Coastal Flooding and Climate Change Impacts in Maine

## Approach
The technical objective of this project is to analyze and visualize the impact of sea level rise in Maine by comparing historical sea level measurements with future projections under various climate change scenarios. This includes utilizing NOAA tide and water-level data, sea-level rise projections, and digital elevation models to map out areas most at risk of flooding. By modeling both low and high tide scenarios and correlating them with predicted sea level increases for 2030, 2050, and 2100, we aim to provide actionable insights for policymakers. The project will focus on visualizing worst-case scenarios and their impact on infrastructure, communities, and ecosystems to help guide adaptation strategies. 

To achieve this, the project will employ Geographic Information System (GIS) software, Python data analysis libraries (e.g., Pandas, Matplotlib), and NOAA’s sea-level rise visualization tools. The data will be cleaned, processed, and combined into interactive visual models. Additionally, we will produce a set of maps showing the extent of coastal flooding under different scenarios and timelines.

## Project Management

### Milestones & Roles:
- **Data Collection and Cleaning (Week 1):** Collect data from NOAA, Maine GeoLibrary, and USGS; clean and process the data.  
- **Data Analysis (Week 2-3):** Analyze current tide and sea level data, identify trends, and model future predictions.
- **Visualization Creation (Week 4):** Create maps and figures to visualize the flooding impacts on infrastructure and communities under different sea level rise scenarios.
- **Report and Presentation (Week 5):** Compile findings, complete documentation, and prepare for final presentation.

### Timeline:
- **Week 1:** Data collection and cleaning
- **Week 2-3:** Data analysis and trend modeling
- **Week 4:** Visualization and interactive model creation
- **Week 5:** Documentation, report writing, and final presentation

### Risks:
- **Data Availability:** Incomplete or outdated data could delay the project. I'll mitigate this by using multiple data sources.
- **Computational Challenges:** Processing large datasets and generating detailed visualizations may be resource-intensive. We'll allocate extra time for technical troubleshooting.
- **Unforeseen Climate Model Variability:** If predictions vary widely, it may be difficult to offer concrete conclusions, but the project will still present a range of possibilities.

## Stakeholder Involvement
The stakeholder, Susana Hancock, PhD, will review and approve the initial proposal.md. Regular updates will be provided to ensure alignment with stakeholder expectations. A meeting with the instructor will be arranged to discuss feedback and suggestions. Further meetings with stakeholders will be coordinated through Dave Munger for XN project guidance.

## Exploratory Data Analysis (EDA)
We will generate several figures showing:
1. Historical sea level rise trends in Maine over the past 50 years.
2. Projected sea level rise impacts under different climate scenarios (1.5 ft, 3.9 ft, 8 ft).
3. Geographic areas at risk under these projections, with overlaid infrastructure and population data.

### Code for Recreating Figures:
The code for data cleaning, analysis, and figure creation will be shared in the GitHub repository. The repository will contain instructions on how to recreate the figures using Python scripts (utilizing Pandas, Matplotlib, and GeoPandas).

