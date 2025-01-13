# US Accidents Analysis

This repository contains an in-depth analysis of the **US Accidents Dataset** available on [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). The dataset includes detailed information about traffic incidents across the United States, enabling us to explore patterns, trends, and factors contributing to these incidents.

---

## Table of Contents
1. [General Understanding of the Data](#1-general-understanding-of-the-data)
2. [Severity and Impact Analysis](#2-severity-and-impact-analysis)
3. [Temporal Analysis](#3-temporal-analysis)
4. [Spatial Analysis](#4-spatial-analysis)
5. [Weather and Environmental Factors](#5-weather-and-environmental-factors)
6. [Infrastructure-Related Questions](#6-infrastructure-related-questions)
7. [Dataset](#dataset)
8. [How to Use](#how-to-use)
9. [Contributing](#contributing)

---

## 1. General Understanding of the Data
- **Dataset Shape**: The dataset contains `{number of rows}` rows and `{number of columns}` columns.
- **Missing Values**: Columns with missing values include `{list columns}`. Strategies such as imputation and removal were applied.
- **Data Types**: Reviewed and adjusted as necessary (e.g., `Start_Time` converted to datetime).
- **Duplicate Rows**: `{number of duplicate rows}` duplicate rows were found and removed.

---

## 2. Severity and Impact Analysis
- **Severity Distribution**: The dataset captures incidents in Severity levels (1 to 4), with **{Level}** being the most frequent.
- **Correlations**:
  - Certain weather conditions (e.g., fog, rain, snow) are associated with higher Severity.
  - Severity also correlates with Time of Day and Distance (`Distance(mi)`).

---

## 3. Temporal Analysis
- **Time of Day**: Most incidents occur during the **{morning/afternoon/evening/night}**.
- **Days and Months**: Peaks in incident frequency were observed on **{specific days/months}**.
- **Duration of Incidents**: The average incident duration is **{calculated duration}**.

---

## 4. Spatial Analysis
- **Geographical Hotspots**:
  - **City**: The highest number of incidents occurred in **{City Name}**.
  - **County**: **{County Name}** records the most incidents.
  - **State**: **{State Name}** has the highest number of incidents.
- **Geographical Distribution**: High-traffic urban areas show dense clusters of incidents.
- **Distance Analysis**: The average distance of incidents is **{calculated distance}**, varying by location and severity.

---

## 5. Weather and Environmental Factors
- **Weather Impact**: Adverse weather conditions (e.g., rain, snow, fog) significantly increase incident frequency and severity.
- **Visibility Trends**: Reduced visibility strongly correlates with higher incident frequency and severity.
- **Most Common Weather Conditions**: The top weather conditions during incidents are **{list of conditions}**.

---

## 6. Infrastructure-Related Questions
- **Infrastructure Features**:
  - Features like **Junctions**, **Traffic Signals**, and **Crossings** are associated with higher severity levels.
  - These findings suggest a need for targeted safety measures in these areas.

---

## Dataset
The dataset used for this analysis can be downloaded from [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents).

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/KhanAmin7/US_Accidents_EDA_project

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt


## Contributing
Contributions are welcome! Feel free to:

- Fork the repository and submit a pull request.
- Open issues for questions, suggestions, or bugs.

---

Thank you for exploring this project! If you find it helpful, please give it a ⭐ on GitHub. 😊

