# 🏥 Medical Facility Thematic Map

This project aims to identify **areas lacking adequate medical facilities** through spatial analysis, thematic mapping, and machine learning.

📍 **Goal**: Provide insights into healthcare accessibility gaps using geospatial tools and data.

---

## 🧭 Project Overview

### Key Objectives:
- Map the **distribution of medical facilities** across a region
- Identify **underserved areas**
- Create a **probability surface** to visualize potential zones needing medical infrastructure

---

## 🛠️ Tools & Technologies

- **QGIS** – Spatial data extraction & preprocessing
- **ArcGIS** – Thematic map generation
- **PostgreSQL + PostGIS** – Spatial database creation
- **SQL** – Data management and queries
- **Python + Machine Learning** – Probability map generation
- **Shapefiles** – For base maps and spatial layers

---

## 📌 Methodology

1. **Data Collection**:
   - Location data for medical facilities # 🏥 Medical Facility Thematic Map

This project aims to identify **areas lacking adequate medical facilities** through spatial analysis, thematic mapping, and machine learning.

📍 **Goal**: Provide insights into healthcare accessibility gaps using geospatial tools and data.

---

## 🧭 Project Overview

### Key Objectives:
- Map the **distribution of medical facilities** across a region
- Identify **underserved areas**
- Create a **probability surface** to visualize potential zones needing medical infrastructure

---

## 🛠️ Tools & Technologies

- **QGIS** – Spatial data extraction & preprocessing
- **ArcGIS** – Thematic map generation
- **PostgreSQL + PostGIS** – Spatial database creation
- **SQL** – Data management and queries
- **Python + Machine Learning** – Probability map generation
- **Shapefiles** – For base maps and spatial layers

---

## 📌 Methodology

1. **Data Collection**:
   - Location data for medical facilities and schools from OSM
   - Administrative boundaries shapefiles

2. **Data Integration**:
   - Load and clean datasets
   - Import into PostgreSQL with PostGIS
   - Connect QGIS to the PostGIS database for visualization

3. **Thematic Mapping**:
   - Use QGIS & ArcGIS to generate thematic maps showing:
     - Density of medical facilities
     - Areas with low accessibility

4. **Probability Surface Creation**:
   - Train a machine learning model to predict **likelihood of facility presence** based on spatial and demographic features.

---

