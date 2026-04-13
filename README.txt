# 📊 Predictive Crime Analytics – Dallas

## 📌 Overview
This project analyzes Dallas police incident data to uncover crime patterns, temporal trends, victim demographics, geographic clustering, and future incident trends.

The analysis focuses on:
- identifying top crime categories
- studying yearly crime trends and year-over-year changes
- exploring victim demographics
- performing region-wise clustering analysis
- forecasting future crime counts using time-series modeling

---

## 📊 Dataset
- **Source:** Dallas Police Incidents dataset
- **Type:** Real-world public safety / crime incident data
- **Source Link:** https://www.dallasopendata.com/Public-Safety/Public-Safety-Police-Incidents/yn72-daik/data_preview

---

## 🛠️ Data Preprocessing
The notebook includes:
- robust CSV loading with multiple encodings and delimiters
- duplicate removal
- null handling for text columns using `"Unknown"`
- removal of invalid / future year values
- filtering and cleaning for analysis-ready data
- extraction of geographic information from point/location fields

---

## 🔍 Exploratory Data Analysis
The project explores:
- **Top 5 crime types**
- **Year-wise crime incident counts**
- **Year-over-year crime trend analysis**
- **Victim demographics** by gender, race, and ethnicity
- **Crime type and region-wise clustering**

---

## 🤖 Modeling & Analytics
### K-Means Clustering
Used to identify spatial and crime-pattern groupings across Dallas regions.

### Time-Series Forecasting
Used **ARIMA** to forecast future crime counts and visualize projected trends.

---

## 📈 Key Insights
- Identified the most frequent crime categories in Dallas
- Analyzed yearly variations in reported incidents
- Explored demographic distributions of victims
- Clustered crime-prone regions using geospatial and categorical features
- Forecasted future crime patterns for planning and decision support

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

---

## 📂 Project Structure

```
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

## 📊 Results
The notebook generates:
- top crime type visualization
- year-wise incident trend charts
- year-over-year trend analysis
- victim demographic visualization
- clustering-based geographic analysis
- ARIMA-based crime forecasting plots


## 📊 Sample Results


### Top 5 Crime Types
results/TOP5_CrimeTypes.png


### Crime Clusters
results/K-Means_Crime_Clusters.png
---

## 🚀 Future Improvements
- build interactive dashboards for real-time monitoring
- enhance forecasting with richer temporal and seasonal features
- integrate Tableau or Power BI dashboards for reporting

---

## ⭐ Conclusion
This project demonstrates how data analytics, clustering, and forecasting can be applied to real-world crime data to support public safety analysis and data-driven planning.