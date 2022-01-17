## Problem Statement

Use space-based satellite data combined with ground observations to find the impact caused during the COVID-19 period 

- Perform exploratory data analysis to find correlation between changes in the ground activities and impact on the environment
- Present a summary report on all your findings

## Project Structure

```markdown
├── README.md          <- The top-level README about this project
│
├── Reports            <- Folder containing summary report of the project 
│   └── README.md      <- Some details about the report and possibly content updates
│ 
│   
├── src                <- Source code aka Jupyter Notebooks for this project
    │
    ├── Notebooks      <- Notebooks related to the project
    |
    ├── Data           <- Datasets related to socio-economic factors, ground level air quality etc. 
    │
    ├── Visualizations <- Images of the results 
```

## Some Details about the Project

I considered about 4 factors for this project:

1. Air Quality
    - Considered satellite data of the major pollutants like SO2, NO2, Ozone, CO etc.
    - Visualized the data on India
    - Visualized ground level sensor data
2. Water Quality 
    - Visualized chlorophyll levels around the coasts of India
3. Socio-Economic Factors
    - Considered factors like GDP, Unemployment  Export-Import Ratio etc and analysed how COVID-19 impacted them
4. Land Use 
    - Looked at the NDVI level changes at different times

I also analysed COVID-19 in India as an introduction.

## Work to be done

- [ ]  Show the time series graphs of the pollutant with satellite data observations
- [ ]  Compare the time series with ground level observations
- [ ]  Compare factors like human development index, covid stringency index with other countries
- [ ]  Analyse more water quality indicators
- [ ]  Analyse more socio-economic factors with updated data
- [ ]  Bring in forecasts considering the absence of COVID-19
- [ ]  Perform proper land cover classifications using supervised learning and try to observe the changes through change detection
- [ ]  Make the EDA more presentable
- [ ]  Probably improve this boring README
- [ ]  You tell me the next ones...

