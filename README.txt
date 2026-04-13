
# 🚔 Predictive Crime Analytics – Dallas

## 📌 Overview
This project analyzes real-world Dallas police incident data to uncover crime patterns, temporal trends, victim demographics, geographic clusters, and future crime trends.

The goal is to transform raw public safety data into meaningful insights that can support proactive planning, trend monitoring, and data-driven decision-making.

---

## 📊 Dataset
- **Source:** Dallas Open Data – Police Incidents
- **Type:** Real-world public safety / crime incident data
- **Source Link:** https://www.dallasopendata.com/Public-Safety/Public-Safety-Police-Incidents/yn72-daik

---

## 🛠️ Data Preprocessing
The dataset required multiple preprocessing steps before analysis:

- Loaded CSV data using robust encoding and delimiter handling
- Removed duplicate records
- Handled missing values in text-based columns using `"Unknown"`
- Filtered invalid and future year values
- Cleaned records for trend and demographic analysis
- Extracted location-based information for spatial clustering

---

## 🔍 Exploratory Data Analysis
The analysis focused on identifying meaningful crime patterns across Dallas, including:

- **Top 5 crime categories**
- **Year-wise incident trends**
- **Year-over-year growth analysis**
- **Victim demographic distributions**
- **Geographic clustering of crime-prone regions**

---

## 🤖 Modeling & Analytical Techniques

### K-Means Clustering
Applied clustering techniques to group crime-prone regions and identify spatial patterns across Dallas.

### Time-Series Forecasting
Used **ARIMA** to model and forecast crime trends over time, helping estimate future incident patterns.

---

## 📈 Key Insights
- Identified the most frequent crime categories reported in Dallas
- Analyzed yearly changes in crime incidence
- Explored victim demographics across race, ethnicity, and gender
- Detected region-wise crime clusters using location-based analysis
- Forecasted future crime trends using time-series modeling

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly
- Scikit-learn
- Folium
- Geopy
- Statsmodels

## 📂 Project Structure

```text
Predictive_Crime_Analytics_Dallas/
│
├── notebooks/
│   └── Predictive_Crime_Analytics.ipynb
│
├── results/
│   ├── Yearly_Crime_Trend.png
│   ├── YOY%_Growth.png
│   ├── TOP5_CrimeTypes.png
│   ├── K-Means_Crime_Clusters.png
│
├── .gitignore
├── README.md
├── requirements.txt
```

---

## 📊 Sample Results

### Top 5 Crime Types
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/c4c3d4d6-c235-4f52-b7c1-4ebee28ba94a" />


### K-Means Crime Clusters
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/82932b91-a7c9-468f-b02b-1133f9a9dc7e" />


---

## 🚀 Future Improvements

- Apply hotspot prediction and advanced forecasting methods
- Integrate Power BI for enhanced reporting

---

## ⭐ Conclusion
This project demonstrates how data analytics, clustering, and forecasting can be used on real-world crime data to reveal patterns, support public safety analysis, and enable data-driven planning.
