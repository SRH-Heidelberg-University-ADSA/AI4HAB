## 📁 Dataset Overview

### 1. **Bathing Water Sites Data (2023)**  
- Source: European Environment Agency (EEA)  
  🔗 [EEA Bathing Water Data](https://www.eea.europa.eu/en/datahub/datahubitem-view/c3858959-90da-4c1b-b9ca-492db0e514df)  
- Description:  
  Contains information about public bathing water sites across Europe, filtered for Germany → 2023.  
  Includes site names, geographic coordinates, annual water quality status, and EU compliance levels.

- Key Features:  
  - Bathing site name and ID  
  - Latitude & longitude  
  - Overall water quality classification  
  - Compliance with EU Bathing Water Directive

### 🏖️ Bathing Water Data – 5 V’s**

|    V           |   Explanation   |
|----------------|------------------|
|   Volume       | Records of 2292 bathing water sites in Germany, with yearly updates. Filtered for 2023. |
|   Velocity     | Updated annually. |
|   Variety      | Spatial attributes (name, location), legal compliance, and quality ratings. |
|   Veracity     | Published by the **European Environment Agency (EEA) using standardized EU regulations. |
|   Value        | Ensures safe recreation, public health monitoring, and long-term water safety trends. |


---

### 2. **General Water Quality Data (2023)**  
- Source: LUBW (Landesanstalt für Umwelt Baden-Württemberg)  
  🔗 [LUBW Water Data Portal](https://umweltdaten.lubw.baden-wuerttemberg.de/)  
- Description:  
  Seasonal water quality readings from rivers, lakes, and reservoirs in Baden-Württemberg. The data includes **physical**, **chemical**, and **biological** indicators relevant for detecting pollution and harmful algal bloom (HAB) risk.

- Key Parameters:  
  - pH, temperature  
  - Nitrate, phosphate, oxygen concentration  
  - Electrical conductivity  
  - Sampling site metadata

---

## 🔍 5 V’s of Big Data (Compared)
### 💧 General Water Quality Data – 5 V’s

|      V         | Explanation |
|----------------|------------------|
|   Volume       | Records collected from the 1863 measuring stations across 142 water bodies in BW, with seasonal splits (summer & winter). |
|   Velocity     | Updated seasonally with some sites measured more frequently like after afer 30 days. |
|   Variety      | Physical (temperature, pH), chemical (nitrate, phosphate), biological, and locational data. |
|   Veracity     | Provided by LUBW, the state environmental agency, ensuring accurate, standardized monitoring. |
|   Value        | Crucial for predictive modeling, early HAB warning systems, and environmental sustainability studies. |


---

## 🧠 Purpose

These datasets are used to:
- Build AI models to detect early signs of **Harmful Algal Blooms (HABs)**
- Monitor trends in **seasonal water quality** across BW
- Improve **public health advisory** systems near bathing zones

## 🔗 Folder Structure

```plaintext
/DATA
│
├── bathing_water_2023.xlsx         # Data from EEA
├── water_quality_2023.xlsx         # LUBW winter measurements
└── site_info.xlsx                  # Metadata with site coordinates and elevations
