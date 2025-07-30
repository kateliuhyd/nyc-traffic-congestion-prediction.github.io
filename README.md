###  **Project Title**

**Predicting NYC Traffic Congestion Using Weather-Informed Machine Learning Models**

### **Project Description**

Developed a machine learning pipeline to predict traffic volume in New York City by integrating historical traffic and weather data. Applied data cleaning, feature engineering, and model training techniques using Python, pandas, and scikit-learn. Participated in the AI4ALL Ignite Accelerator, a national program promoting responsible AI development through hands-on, socially impactful projects. Our work highlights how weather conditions influence urban congestion, aiming to support smarter traffic planning and public safety strategies.

---

### **Problem Statement**

Urban congestion in New York City significantly affects commute time, safety, and emissions. Weather conditions like rain, snow, and wind exacerbate traffic delays and increase accident risks. Despite this, weather is often underutilized in traffic prediction models. Our project aims to close this gap by analyzing how different weather factors impact traffic volume across NYC boroughs—offering a data-driven approach to help inform city planning, emergency response, and transit optimization.

---

### Key Results

* Enriched over **100,000 traffic records** with hourly weather data using the Open-Meteo API (temperature, precipitation, wind, cloud cover).
* **Engineered 10+ weather and temporal features** to capture seasonal and situational patterns.
* Trained and evaluated **Linear Regression** and **Random Forest** models:

  * Random Forest achieved **R² ≈ 0.56**, revealing strong weather-volume correlations.
* Developed a **web-based interactive visualization** using FastAPI backend and Mapbox GL JS frontend.
* Synthesized findings into a **final presentation and demo**, highlighting borough-specific congestion insights.

---

### **Methodologies**

* Merged traffic and weather datasets by matching timestamp and geolocation (latitude, longitude).
* Queried Open-Meteo API to retrieve hourly weather conditions for each traffic data point.
* Engineered features including seasonality, borough, wind speed, cloud coverage, and precipitation.
* Trained and evaluated models using `scikit-learn` with metrics such as R², MAE, and RMSE.
* Visualized results using `folium`, `Mapbox GL JS`, and `matplotlib`.
* Deployed backend endpoints via `FastAPI` to serve filtered traffic data in GeoJSON format.

---

### **Data Sources**

* [NYC DOT Automated Traffic Volume Counts](https://data.cityofnewyork.us/Transportation/Automated-Traffic-Volume-Counts/7ym2-wayt)
* [Open-Meteo Historical Weather API](https://open-meteo.com/)

---

### **Technologies Used**

* Python
* pandas, numpy, scikit-learn
* Open-Meteo API
* FastAPI
* Mapbox GL JS
* folium, matplotlib
* Git, GitHub

---

### **Authors**

This project was completed in collaboration with:

* **Kate Liu** ([https://github.com/kateliuhyd](https://github.com/kateliuhyd))
* **Nnaemeka Okonkwo**
* **Sania**
* **Zahir**
* **Justin**
