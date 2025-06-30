# Aircraft Risk Analysis for Aviation Expansion


## 1. Project Overview

The project analyzes aviation accident data from the U.S. National Transportation Safety Board (NTSB) to uncover trends that can guide safer aircraft procurement and policy decisions. The goal of this project is to support stakeholders such as civil aviation authorities, aircraft manufacturers and airline safety teams in identifying factors associated with accident severity. These include aircraft type, weather conditions and flight phases.

The dataset contains data from 1962 to 2023. The tools used were Python and Tableau. Python was used for data cleaning and exploration, while Tableau was used to design an interactive dashboard to support decision-making.

## 2. Business Problem

Despite major safety improvements, fatal aviation accidents still occur. The Aviation Division is expanding its fleet and needs data-driven guidance to:

- Identify safer aircraft makes

- Understand conditions contributing to fatal outcomes

- Improve safety during high-risk flight phases

This analysis answers key questions such as:

1. Which aircraft types have the lowest accident rates and severities?
2. What conditions are associated with fatal incidents?
3. How have aviation safety trends changed over time?


## 3. Stakeholders

The key business stakeholders play a crucial role. These include:

- Civil Aviation Authorities who enhance regulatory policies

- Aircraft manufacturers who track and improve design safety

- Airline Safety Teams for risk planning and pilot training

- Accident Investigators who identify patterns behind incidents


## 4. Dataset Summary

The summary of the National Transportation Safety Board (NTSB) dataset is as follows.
- It holds accident records from 1962–2023.
- The key features include the Aircraft make, damage level, weather condition, the phase of the flight and the injury counts.

The project undertook several steps. In data preparation for instance, missing values were removed.

There are identified limitations.Some records contain Unknown values, particularly in the weather and flight phase fields.


## 5. Dashboard Summary

Using Tableau, five worksheets were built and one interactive dashboard. The summary is as follows:

### 1. Top 10 Aircraft Makes with Least Injuries  
A horizontal bar chart showing manufacturers with the fewest fatal, serious and minor injuries.  
Airbus, Airbus Industries and PIPER had the lowest injury totals.  

### 2. Fatal vs. Non-Fatal Accidents by Weather Condition  
The visual used is a bar chart comparing fatal accident counts by weather type.

Fatal accidents were highest under Visual Meteorological Conditions (VMC), with 12,259 fatalities, followed by Instrument Meteorological Conditions (IMC) with 3,463 fatalities.

This trend is likely influenced by the higher frequency of flights during clear weather conditions.  

### 3. Fatal Accidents by Aircraft Damage Level  
Aircraft classified as 'Destroyed' accounted for 12,630 fatal accidents, while those with 'Substantial' damage reported 4,817 fatalities. Minor damage and unknown cases had fewer than 500 combined fatalities.

This indicates that severe aircraft damage is a strong predictor of fatal outcomes.

### 4. Phase of Flight vs Fatal Accidents  
The highest fatality counts occurred during the “Unknown” phase with 6,594 fatalities, followed by 'Maneuvering' with 3,183 and 'Cruise' with 2,786. 

The Phases of Flight like 'Taxi' and 'Standing' had the lowest fatality numbers.

The findings show greater risk during active flight phases.

### 5. Injuries by Phase of Flight  
A stacked bar chart is used for the visual representation.

The 'Unknown', 'Cruise' and 'Takeoff' phases accounted for the highest totals of injuries across all severity levels.

These phases appear more vulnerable and require targeted safety attention.


## 6. The Key Insights

The key insights from the findings are as outlined below: 
- Fatalities are most common in destroyed aircraft and during approach, cruise and maneuvering phases.
- Some manufacturers like Airbus report low injury numbers over a period of time.
- VMC conditions recorded more fatal incidents, likely due to higher flight volume because of clear weather.
- There are Data limitations such as 'Unknown' values which shows the need for better standards for reporting.


## 7. How to Use This Dashboard

The dashboard was created in Tableau Public and consists of 5 worksheets and 1 main dashboard. Each chart was designed to answer a specific question.

A color scheme was used for clarity. In addition, the dashboard features interactive elements such as filters, tooltips and legends which help in data exploration.

[View the full dashboard on Tableau Public](https://public.tableau.com/app/profile/jessica.gichimu/viz/AviationAccidentRiskDashboard/AviationAccidentRiskDashboard19622023?publish=yes)



## 8. Files in This Repository

Full data analysis in Python - (https://github.com/JessicaGichimu/DS-Phase1-Project/blob/master/Project.ipynb)

Tableau dashboard workbook - (https://public.tableau.com/app/profile/jessica.gichimu/viz/AviationAccidentRiskDashboard/AviationAccidentRiskDashboard19622023?publish=yes)

Final stakeholder presentation slides - https://github.com/JessicaGichimu/DS-Phase1-Project/blob/master/presentation.pdf

Cleaned dataset used in data analysis - https://github.com/JessicaGichimu/DS-Phase1-Project/blob/master/aviation_dashboard_data.csv

Static PDF version of the dashboard - https://github.com/JessicaGichimu/DS-Phase1-Project/blob/master/aviation_dashboard.pdf

Project overview and documentation - https://github.com/JessicaGichimu/DS-Phase1-Project/blob/master/README.md

Interactive dashboard for stakeholder use - https://public.tableau.com/app/profile/jessica.gichimu/viz/AviationAccidentRiskDashboard/AviationAccidentRiskDashboard19622023?publish=yes

## 10. Conclusion

This project demonstrates how aviation accident data can aid in making safer decisions.

Insights from the data analysis help regulators, manufacturers and operators minimize risk and allocate resources where they are most needed.

By combining the data, data visualizations and actionable recommendations, the project ensures data-driven aviation safety planning.

## 11. Recommendations

This project provides informed data driven insights that may be useful for:

1. Choosing safer aircrafts.  
2. Better preparation by pilots under specific weather conditions.  
3. Observing safety during the critical flight phases. 
4. Strengthening reporting for areas not well documented.