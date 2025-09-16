# Barcelona Traffic Accidents (2014–2024)

> **Final project from IT Academy Data Analytics Bootcamp:** end-to-end analysis of Barcelona traffic accidents (2014–2024) with data cleaning, geospatial analysis, interactive maps, and dashboards to identify hotspots and trends.

---

## 🔍 Project Overview

This project explores **10 years of traffic accident data in Barcelona**, focusing on identifying temporal patterns, geographical hotspots, and accident severity trends.  
It demonstrates an **end-to-end analytics workflow**: from cleaning and merging 15 annual datasets, to geospatial analysis, enrichment with POIs, and interactive visualization using Python and Power BI.

---

## 🎯 Objectives

- Clean and standardize multi-year CSV datasets into a single, analysis-ready table.
- Analyze accidents by **year, month, weekday, and hour** to find patterns.
- Identify **hotspots** and risky intersections across districts and neighborhoods.
- Enrich data with **Points of Interest (POIs)** (schools, metro, hospitals) via Overpass API.
- Evaluate the impact of **COVID-19** and the **Low Emission Zone (ZBE)** on accident trends.
- Build **interactive visualizations** (maps and dashboards) to support decision-making.

---

## 🧰 Tech Stack

- **Language:** Python 3, Jupyter Notebook  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, GeoPandas, Folium, OSMnx, Shapely  
- **Visualization:** Plotly Express, Folium (interactive maps), Power BI  
- **Data Sources:** Open Data BCN (Guardia Urbana accident datasets)  
- **Other Tools:** Overpass API (POI extraction)

---

## 🌍 Interactive Maps & Storytelling

Explore the key interactive visualizations for this project:

- **Cluster Hotspots (Gradient Map)**  
  [🔗 View Map 1](https://vernicarb.github.io/barcelona-traffic-accidents-2014-2024/maps/1-mapa_cluster_gradiente.html)

- **Hourly Accident Heatmap (with Time Slider)**  
  [🔗 View Map 3](https://vernicarb.github.io/barcelona-traffic-accidents-2014-2024/maps/3-heatmap_accidentes_por_hora.html)

- **Weekly Accident Heatmap (by Day of Week)**  
  [🔗 View Map 4](https://vernicarb.github.io/barcelona-traffic-accidents-2014-2024/maps/4-mapa_calor_accidentes_por_dia.html)

---

## 📈 Interactive Story (Flourish)

Explore the full interactive data story:  
[🔗 View Flourish Story](https://public.flourish.studio/story/3162925/)

---

## 📑 Project Report

For a detailed summary, view the full project report:  
[📄 Download PDF](https://github.com/Vernicarb/barcelona-traffic-accidents-2014-2024/raw/main/barcelona-traffic-accidents-report.pdf)


---

## 📊 Key Findings (Highlights)

- **Accidents dropped by ~23%** between 2021–2024 compared to pre-COVID years (2014–2019).
- **Peak accident hours:** evenings and weekends, especially Fridays.
- **Top hotspots:** concentrated in a few critical intersections and districts.
- **Policy impact:** COVID-19 lockdowns and the introduction of the Low Emission Zone (ZBE) correlate with a significant decrease in accidents.
- **Vehicle severity mix:** higher severity with motorcycles and vans, lower with bicycles.
