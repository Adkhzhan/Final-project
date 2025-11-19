# Finding the Best Neighborhood in Pittsburgh
## A Data-Driven Analysis of Safety & Quality of Life
### Final Project

---

## The Big Question: What Makes a Neighborhood "The Best"?

Pittsburgh is a city of unique and diverse neighborhoods. But how can we objectively compare them?

Our project aims to answer this question by analyzing public data.

**Our Primary Metric: SAFETY**

---

## Project Goals

1.  To **gather and process** public data on crime, traffic behavior, and air quality.
2.  To **analyze** this data to identify patterns and rank neighborhoods.
3.  To **visualize** our findings for a clear, data-driven comparison.
4.  To definitively name the safest (and least safe) neighborhoods in Pittsburgh based on our data.

---

## Our Methodology: Three Pillars of Analysis

We focused on three key datasets to build our "Safety" score:

1.  **Crime & Arrests**
    *   **Source:** `arrests_2024_to_sept_2025.csv`
    *   **Analysis:** `Arrests...Deng.ipynb`
    *   **Method:** Counted total felonies, misdemeanors, and infractions by neighborhood.

2.  **Traffic & Driving Behavior**
    *   **Source:** (Traffic count data)
    *   **Analysis:** `TrafficCount.ipynb`
    *   **Method:** Compared the median driving speed to the posted speed limit.

3.  **Environmental Quality**
    *   **Source:** `air_quality_data.csv`
    *   **Analysis:** `Thomas_Eaton_Air_Quality.ipynb`
    *   **Method:** Assessed local air quality metrics (a key factor for health and safety).
  
      
# Pittsburgh Neighborhood Safety & Quality of Life Analysis

This repository contains the data analysis for a final project to identify the "best" and "worst" neighborhoods in Pittsburgh. The analysis is based on several key public datasets to create a composite view of neighborhood quality of life.

The primary metric for this analysis is **SAFETY**, which we've broken down into:

1.  **Public Safety (Crime):** Analysis of arrest records.
2.  **Traffic Safety (Driving Behavior):** Analysis of speeding and traffic patterns.
3.  **Environmental Quality:** Analysis of air quality data.

## Project Components

This project is broken down into several key data analysis notebooks:

* **`Arrests_2024_to_Sept_2025_pittsburgh_Deng.ipynb`**: This notebook analyzes arrest data from 2024-2025, counting the number of felonies, misdemeanors, and infractions to quantify crime rates by neighborhood.
* **`TrafficCount.ipynb`**: This notebook analyzes traffic data to identify areas with dangerous driving, primarily by comparing the median vehicle speed against the posted speed limit.
* **`Thomas_Eaton_Air_Quality.ipynb`**: This notebook analyzes local air quality data, another important factor in overall quality of life.

This project is broken down into several key data analysis notebooks:

Arrests_2024_to_Sept_2025_pittsburgh_Deng.ipynb: This notebook analyzes arrest data from 2024-2025, counting the number of felonies, misdemeanors, and infractions to quantify crime rates by neighborhood.

TrafficCount.ipynb: This notebook analyzes traffic data to identify areas with dangerous driving, primarily by comparing the median vehicle speed against the posted speed limit.

Thomas_Eaton_Air_Quality.ipynb: This notebook analyzes local air quality data, another important factor in overall quality of life.

## SO IN CONCLUSION

**Best/Safest Neighborhood** : Allegheny West, with 2 felonies,	12 misdemeanors,	24 infractions and 2 unlabeled arrests arrests from 2024 - September 2025
 The median driving speed here is 20.0 when the limit is 25.0. People are driving very carefully here.
 
 Another great neighborhood worth mentioning would be Swisshelm Park, with no felonies,	no misdemeanors,	no infractions and 7 unlabeled arrests arrests from 2024 - September 2025


 **Worst Neighborhood** : Central Business District	, with 371 felonies,	1449 misdemeanors,	371 infractions and 345 unlabeled arrests from 2024 - September 2025
 Although the median driving speed here is 22.0 when the limit is 25.0 and people are driving very carefully here, there are just way too many arrests happening here (especially misdemeanors)
 
 <img width="773" height="509" alt="image" src="https://github.com/user-attachments/assets/3f30d263-59f5-43b9-9934-4cffa347e0e9" />
 



 Crafton Heights have the most dangerous and reckless drivers. Their median speed is 37.0 when the speed limit is 25.0!
<img width="712" height="105" alt="image" src="https://github.com/user-attachments/assets/217d0cfc-5074-4c45-ab2f-44f88e77f6a5" />
