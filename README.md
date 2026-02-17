## U.S. Traffic Accidents: Where, When and Why Severe Crashes Occur (2016-2023)

## Project Overview
This project analyzes U.S. traffic accident data from 2016-2023 to identify when, where and under what conditions severe crashes are most likely to occur.

The project combines statistical analysis in Python with an interactive Tableau dashboard to transform raw crash data into actionable, data-driven transportation safety recommendations.

The goal of this project is to support the Department of Transportation and local angencies in prioritizing interventions that reduce fatalities and serious injuries.

---

## Live Dashboard
[View the interactive dashboard on Tableau Public](https://public.tableau.com/shared/7Q5SNDY53?:display_count=n&:origin=viz_share_link)

---

## Key Business Questions
- When are severe crashes most likely to occur?
- How do weather conditions impact crash severity?
- Are crashes more severe at signalized or unsignalized loctions?
- Where are severe crash hotspots concentrated?
- How can these insights inform targeted safety interventions?

---

## Dataset
**Source: U.S. Traffic Accident Dataset (2016-2023)

This dataset includes:
- Date and time of crash
- Geographic locations (state, city, latitude, longitude)
- Weather conditions
- Traffic signal presence
- Crash severity classification

---

## Tools and Technologies
- Python (Pandas, NumPy, SciPy) - data cleaning, transformation and statistical analysis
- Jupyter Notebook - analytical workflow and hypothesis testing
- Tableau Public - interactive dashboard development and data storytelling
- GitHub - version control and project documentation

---

## Analytical Workflow
- Cleaned and standardized multi-year crash data
- Engineered a severe crash rate metric
- Aggregated crash outcomes by:
    - day of week
    - hour of day
    - weather condition
    - traffic signal presence
  - Performed chi-quared tests to evaluate the statistical relationship between crash severity and key contributing factors
 
  - Tableau was then used to build and interactive dashboard to:
  - - explore patterns by state, year and weather condition
    - compare values against the national average
    - highlight above and below-average risk periods

---

## Key Findings

Analysis of the full 2016-2023 dataset revealed:
- Severe crashes occur at significantly higher rates on weekends and during nighttime hours
- Adverse weather conditions (rain and snow) are associated with incrased crash severity (χ² test, p < 0.05).
- Crashes occuring away from traffic signals have more than double the severe crash rate compared to those at or near signalized locations (χ² test, p < 0.05).
- Severe crash risk increases throughout the day and peaks in the evening hours.

These patterns are consistent at the national level and can be explored interactively by state in the dashboard.

---

## Data-Driven Recommendations

Based on the findings, the following targeted strategies are proposed:

1. Implement weekend and nighttime safety interventions
Focus enforcement, DUI checkpoints, speed management and public safety messaging during the highest-risk periods.

2. Deploy weather-responsive speed management systems
Use variable speed limits, real-time traveler alerts and improved roadway visibility treatments during hazardous weather.

3. Prioritize safety upgrades at high-risk unsignalized locations
Install traffic signals where warranted and apply lighting, rumble strips and traffic-calming measures at severe crash corridors.

## Measuring Impact 

Success of those interventions can be evaluated by:
- Tracking severe crash rate trends over time
- Comparing before/after implementation periods
- Monitoring reductions in nighttime and weather-related severe crashes
- Evaluated upgraded locations against comparable control sites

---

## Dashboard Features
- Interactive state selection
- Dynamic filtering by year, state and weather condition
- Density map of crash hotspots
- Lollipop chart ghighlighting above and below-average risk hours
- Reference lines for overall average crash rate

---

## How to Use the Dashboard
1. Use the filters at the top of the dashboard to filter all visuals.
2. Also, in the map, select a state to filter all visuals (includes all years and all weather conditions).
3. Click away from the states to revert data back to all states
4. Hover over charts to view detailed values.
5. Compare values to the dashed average reference line to identify high-risk conditions.

---

## Dashboard Preview
<img width="1007" height="803" alt="image" src="https://github.com/user-attachments/assets/d8902641-9cdb-4291-a7db-760fa3cfee0c" />

---

## Project Value

This project demonstrates how statistical analysis and interactive visualizations can be combined to:

- Translate complex crash data into clear safety priorities
- Support evidence-based transportation policy
- Enable agencies to allocate resources where they will have the greatest life-saving impact

---

## Repository Contents
- US_Traffic_Accidents_Project.ipynb (data cleaning, feature engineering, statistical analysis and recommendations)
- README.md (Project documentation and dashboard link)
