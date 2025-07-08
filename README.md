# Wells, Crops, and Crisis

This project explores the spatial and temporal patterns of groundwater depletion in Tulare County, California from 2004 to 2024. Using well data, spatial statistics, and USDA Cropland Data Layers, it investigates potential relationships between groundwater decline and surrounding landcover—particularly in agricultural zones.

The interactive webpage presents findings through maps, charts, and embedded media, highlighting the most severely impacted areas and summarizing key trends in both water level decline and land use behavior.

---

## 🔍 Key Questions

- Which wells experienced the greatest long-term declines in groundwater?
- Are these declines spatially clustered?
- How have groundwater levels changed year to year?
- What types of landcover are most common near the most severely affected wells?

---

## 🛠 Tools & Methods

- **GIS Software**: ArcGIS Pro (spatial analysis, buffering, clustering)
- **Statistical Techniques**: Getis-Ord Gi* (Hot Spot Analysis), Linear Regression (Slope & Change), K-Means Clustering (Multivariate grouping)
- **Data Handling**: Python (data prep & field automation), ModelBuilder (batch processing & tabulation)
- **Web Visualization**: Leaflet.js (interactive mapping), HTML, CSS, JavaScript, Lightbox, Chart exports, Responsive layout

---

## 🗂 File Structure

```
/index.html                  → Main project page  
/css/style.css              → All page styling  
/images/                    → Graphics, charts, and imagery  
/hotspots.html              → Hot Spot map  
/hotspots99.html            → 99% confidence level map  
/multivariate.html          → Clustered well map  
/multivariate13.html        → Focus map on the “Severe 13” wells  
/cdl.html                   → Cropland Data Layer (CDL) animation  
```

---

## 📊 Data Sources

- **Well Locations & Measurements**: California Department of Water Resources, 2024  
- **Landcover Raster Imagery**: USDA National Agricultural Statistics Service (NASS), 2007–2024  
- **County Boundary Data**: California Natural Resources Agency, 2024

---

## 📅 Project Date

May 2025

---

## 👤 Author

Jason Runnells

> This project was developed as part of a broader portfolio exploring environmental and geographic topics through spatial analysis and visual storytelling.
