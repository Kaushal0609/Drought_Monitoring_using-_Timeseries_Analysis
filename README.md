# Agricultural Drought Monitoring using Time-Series Satellite Data and Google Earth Engine

**Authors**:  
- Kaushal Kathiriya (DAIICT - 202319013)  
- Mit Borda (DAIICT - 202319008)  

**Guide**:  
- Mr. Abhishek Danodia, Department of Agriculture & Soil, IIRS

---

## 📋 Project Overview
This project aims to monitor agricultural drought conditions using time-series satellite data processed via **Google Earth Engine (GEE)**. Through the analysis of NDVI, LST, and other remote sensing indicators, we assess drought patterns and their impacts on agriculture.

## 🚀 Tools and Technologies
- **Google Earth Engine (GEE)**: For satellite data analysis and time-series computation.
- **Satellite Imagery**: Used to observe changes in vegetation and soil moisture.
- **Python/JavaScript**: For data processing within GEE.
- **QGIS**: For spatial data preprocessing.
- **GeoServer** (optional): For publishing geospatial datasets.

## 🎯 Objective
To develop a system capable of detecting and monitoring agricultural droughts using satellite-based vegetation health indicators (e.g., NDVI) and land surface temperature (LST) over time.

## 📊 Dataset
- **Time-Series Satellite Data**: Includes vegetation indices (NDVI), land surface temperature (LST), and soil moisture data accessed via GEE.
- **Other Spatial Data**: May include administrative boundaries or crop area boundaries.

## 🛠 Methodology
1. **Data Collection**: Satellite imagery from Google Earth Engine, covering NDVI, LST, and other relevant datasets.
2. **Data Preprocessing**: Cleaning and preprocessing spatial and temporal data for accurate analysis.
3. **Drought Indicators Calculation**:
   - **NDVI**: To assess vegetation health.
   - **LST**: To monitor surface temperature deviations.
4. **Drought Detection**: Detect and monitor drought based on deviations in vegetation and soil moisture levels.
5. **Visualization**: Using GEE visualization tools or exporting processed data for further analysis in external GIS platforms like QGIS.

## 📈 Results
This project produces spatial and temporal maps highlighting agricultural drought-prone areas. These maps can assist in understanding the severity and spread of drought across regions.

## 🔮 Future Scope
- **Additional Data Layers**: Incorporating rainfall data, crop yield statistics, and other environmental indicators to improve drought detection and provide more robust insights into its impacts.
- **Automation**: Developing an automated system that continuously monitors and updates drought status using real-time satellite data.

---

## 🛠 How to Run
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repository.git
