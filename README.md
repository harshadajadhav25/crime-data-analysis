# Crime Data Analysis & Visualization (LAPD)

## Overview
Analyzed 1M+ Los Angeles crime records to identify trends by location, time, and crime type.  
Built interactive Tableau dashboards to communicate insights through maps, time-series trends, and category breakdowns.

## Tech Stack
- Python: Pandas, NumPy
- SQL
- Tableau
- Data Cleaning & Preprocessing

## Dataset
- LAPD Crime Data (Los Angeles Open Data)
- Full Dataset (not hosted in repo due to size):  
  🔗 [Crime Data from 2020 to Present – Data.gov](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)
- Published by: Los Angeles Police Department (LAPD)  
- Features: ~1 million records, 28 columns, covering crime type, time, location, victim demographics, and weapons used.

## What I Did
- Cleaned and standardized raw records (missing values, duplicates, normalization)
- Created analysis-ready features (date/time fields, categories, geographic columns)
- Performed exploratory analysis to identify:
  - Hotspots by area/division
  - Crime trends over time (monthly/yearly patterns)
  - Top crime categories by region
- Designed Tableau dashboards:
  - Geospatial maps for hotspot analysis
  - Time series trend charts
  - Category breakdowns and comparisons

## Key Insights (Examples)
- Identified high-frequency crime areas and top crime categories per region
- Found peak times/days for specific crime types
- Observed time-based patterns that can support resource allocation decisions

## 📁 Project Structure

```
📦 Crime-Data-Analysis/
├── 📒 Crime Data Analysis.ipynb         # Main Jupyter Notebook
├── 📄 crime_data_sample.csv             # Small sample dataset (1,000 rows)
├── 📄 LAPD_Crime_Dashboard.twbx         # Tableau dashboard file
└── 📄 README.md                         # Project documentation
```

---
## 🔗 Large Dataset Downloads

Due to GitHub’s file size limits, large datasets used for this project are hosted externally:

- [Download Full Dataset (CSV)](https://drive.google.com/file/d/1PIJ_RnvUV77WFqUuUg_RPOEJfw9mcWrx/view?usp=sharing)
- [Download Cleaned Dataset (CSV)](https://drive.google.com/file/d/1Zuk4Yl3SE8YYo_cYw7L47GwGbdRNlt7R/view?usp=sharing)

## 📊 Visual Insights (Tableau & Python)

Here are a few of the visualizations used in our analysis:

### 🔫 Weapons Used by Gender
![Weapons by Gender](images/weapons_by_gender.png)

### 🕒 Crime by Hour of Day
![Crime by Hour](images/crime_by_hour.png)

### 🌍 Top Crime Categories
![Top Areas](images/top_crime_category.png)

You can explore the full dashboard on Tableau Public or with the provided `.twbx` file.

---

## 🔍 Summary of Findings

- **Women** were more frequently victims of bodily force than men.
- **2024 saw a decrease** in overall crime compared to 2020–2023.
- **Central Area** had the most criminal activity overall.
- **77th Street Division** reported the highest number of violent and firearm-related crimes.
- **Most crimes occur around noon**, although this could be skewed by how time was recorded.

---

## 🔮 Future Scope

- The LAPD dataset is **updated daily**.  
  We propose creating an **automated ETL pipeline** using tools like **Apache Airflow**, **AWS Lambda**, or **Cloud Functions** to:
  - Fetch the latest data daily from data.gov
  - Clean and preprocess it
  - Update a **live Tableau or Power BI dashboard**

- Potential to integrate **machine learning models** to:
  - Predict high-risk crime hours and locations
  - Identify seasonal or demographic crime trends
  - Offer proactive insights to city officials and law enforcement

- Incorporate data from **previous decades** to compare trends over a longer timeline.

---

## Author
Harshada Jadhav  
LinkedIn: https://www.linkedin.com/in/harshada-jadhav/
