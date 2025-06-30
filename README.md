# ndvi-change-detection
Detecting land use change using NDVI and Sentinel-2 data in Google Earth Engine
# Land‑Use Change Detection Demo

This repository contains a **Google Earth Engine** script that computes and visualizes NDVI‑based land‑use change between 2016 and 2024 over a region near Bengaluru, India. It demonstrates the geospatial AI skills essential for real-time environmental monitoring and carbon-sequestration analytics.

---

## 📊 Live Demo

> **Interactive Map:**  
> [View the NDVI Change Detection Demo on GEE] https://code.earthengine.google.com/49564988c46228079881cb71a3d33d81

---

## 🗺️ Screenshots

| NDVI 2016 | NDVI 2024 | ΔNDVI (Change) |
|:---------:|:---------:|:--------------:|
| !![image](https://github.com/user-attachments/assets/e8aa5f6a-58a1-4767-b5c1-70edbcde1abe)
(before.png) | !![image](https://github.com/user-attachments/assets/73a602c9-4516-44dc-bff9-73580f3c2aae)
(after.png) |
![image](https://github.com/user-attachments/assets/f6816803-8f52-4b26-816c-1f6b053c874b)
(change.png) |

---

## 🧰 How It Works

1. **Area of Interest**  
   Defines a 20 × 20 km tile around Bengaluru.

2. **Data Source**  
   Loads Sentinel‑2 L1C imagery (`COPERNICUS/S2`), filters by date and cloud cover (< 20 %).

3. **NDVI Calculation**  
   Uses the Normalized Difference Vegetation Index (bands B8, B4) for 2016 and 2024.

4. **Change Detection**  
   Computes `ΔNDVI = NDVI_2024 – NDVI_2016` and styles it with a red‑white‑blue palette.

5. **Visualization**  
   Adds three map layers:  
   - `NDVI 2016` (brown→green)  
   - `NDVI 2024` (brown→green)  
   - `NDVI Change` (red→white→blue)

---

## 🚀 Getting Started

To explore or modify:

1. Open the [Earth Engine Code Editor](https://code.earthengine.google.com).  
2. Create a new script and **paste** the contents of `earthengine_script.js`.  
3. Click **Run** and view the map layers.  
4. Adjust the `aoi`, dates, or cloud filters as desired.

---

## 📂 Repo Structure
land‑use‑change‑demo/
├── earthengine_script.js # Main GEE script
├── before.png # NDVI 2016 screenshot
├── after.png # NDVI 2024 screenshot
├── change.png # ΔNDVI screenshot
├── README.md # Project overview
└── LICENSE # MIT or your preferred license

---

## 🤝 Why It Matters

This demo illustrates my ability to build **scalable geospatial AI pipelines**—from acquiring satellite data to computing environmental indices and visualizing change. It’s directly applicable to **real‑time carbon monitoring**, **land‑use analytics**, and **sustainability projects**


