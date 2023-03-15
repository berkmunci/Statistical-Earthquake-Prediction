# Statistical-Earthquake-Prediction
## Project Target:
Analysis of previous earthquakes and estimation the magnitude of the largest earthquake to be observed in the next 40 years in a selected region.
## Required Data for satisfy project target: 
for each point: date, latitude, longitude,	depth (m),	magnitude (ML) values. 
## Desired Outputs: 
-Estimated the magnitude of the largest earthquake to be observed in the next 40 years in the selected region.
-Distribution of Earthquakes by Years
-Maximum Observed Earthquake Magnitudes by Year
## Project Phases:
  ##  1) DATA COLLECTION PHASE
  - Data of earthquakes that occur in a certain distance from a center is downloaded from https://deprem.afad.gov.tr/event-catalog
  ##  2) DATA PREPERATION PHASE
  - Dataframe is created with date, latitude, longitude,	depth (m),	magnitude (ML) values.
  - Earthquakes with a magnitude of greater or equal than 4.5 that took place after 1982 and at a certain distance from that center were selected.
  ##  3) DATA PROCESSING AND VISUALIZATION PHASE
  - Earthquakes which occured in last 40 years are observed. <br/>
  ![output1](https://user-images.githubusercontent.com/114949587/225333211-d20505cd-5139-4972-bab9-415e323351d1.png)
  - Earthquakes which occured in last 40 years with M>=4.5 ML are observed. Data points are fitted with a line and the largest possible earthquake magnitude in a 40-year period is estimated.<br/>
  ![image](https://user-images.githubusercontent.com/114949587/225331888-b1040db0-934b-4ceb-bd8f-8bc6a5ae9874.png)
  - Data analysis of previous earthquakes are showed below.<br/>
  ![output3](https://user-images.githubusercontent.com/114949587/225334224-6a0798ec-f37c-46e6-98af-57f479ea92a0.png)
  ![output4](https://user-images.githubusercontent.com/114949587/225334845-2a01c7d1-cb39-41e9-814e-1de75975655e.png)
  
  
