# 🛰️ Seasonal River Turbidity Analysis Using NDTI in Prayagraj, India (2019–2024)

This project analyzes seasonal turbidity variation in the **Ganga–Yamuna river system** in **Prayagraj, Uttar Pradesh**, using the **Normalized Difference Turbidity Index (NDTI)** derived from **Sentinel-2** imagery. The goal is to understand how **seasonal hydrology and human river activity (ritual bathing, crowd gatherings)** affect water clarity across time and space.

##  Study Area
- **Location:** 15 km buffer around Prayagraj city, covering **Ganga**, **Yamuna**, and the **Triveni Sangam**
- **Why important?** Site of the **largest human river-bathing events** on Earth (e.g., Kumbh Mela, Magh Mela)

##  Tools & Platforms
- **Google Earth Engine (GEE):** Image preprocessing, index generation, masking
- **Python Libraries:** `pandas`, `numpy`, `matplotlib`, `sklearn`, `folium`, `geemap`

## Methods Overview
- Preprocessing using cloud/haze masking (SCL)
- NDWI to isolate water pixels
- NDTI calculation on masked river region
- Compound ΔNDTI maps (year-to-year turbidity change)
- Z-score & linear regression for anomaly detection and trend modeling
- Crowd-mapping using Folium

## Key Findings

- 🔴 **Turbidity is Increasing in May (Pre-Monsoon)**  
  Human-induced turbidity is rising steadily during May — likely driven by increasing ritual activity, tourism pressure, and reduced water flow during the dry season.

- 🌧️ **October Shows More Stable, Nature-Driven Variation**  
  Turbidity in October is more erratic and controlled by monsoon runoff. No strong rising or falling trend was observed.

- 📍 **Turbidity Hotspots Align with Ghats**  
  High-NDTI zones frequently appear near major ghats like **Sangam**, **Daraganj**, and **Arail**, especially in pre-monsoon years.


