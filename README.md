# ukraine_nasa_firms_map_2022_2026

## Overview

This repository contains an **interactive Kepler.gl map** visualizing NASA FIRMS fire detection data over Ukraine during 2022–2026.  
The map aggregates detections into **monthly 3D Hexbin layers**, allowing users to explore temporal patterns and hotspots associated with the ongoing conflict zones.

The purpose of this project is **academic, OSINT, and research-focused** visualization of fire detections to support analysis of conflict dynamics, spatial intensity, and temporal trends.

---

## Features

- **Interactive 3D Hexbin map** of fire detections  
- **Monthly aggregation** of detections for easier temporal analysis  
- **Time animation** slider to explore changes over time  
- **Color and elevation** scaled by the number of detections  
- **Desktop-optimized view**; mobile browsers may require simplified or 2D layers  

---

## Usage

### 1. Live Map

Access the interactive map on GitHub Pages:  

[Click here to view the FIRMS Hexbin map](https://lazar-bit.github.io/ukraine_nasa_firms_map_2022_2026/firms_ukraine_hex.html)

> **Note:** For optimal performance, use a desktop browser. Mobile devices may not render large 3D Hexbin layers due to WebGL limitations.

---

### 2. Data

- **Source:** NASA FIRMS (Fire Information for Resource Management System)  
- **Coverage:** Ukraine, 24 February 2022 – 2026  
- **Format:** Monthly aggregated CSV processed in Kepler.gl  
- **Visualization:** Hexbin layer with elevation and color scaled by detection counts

---

### 3. Customization

To edit or re-export the map:

1. Open the Kepler.gl project file (not included here to reduce repo size)  
2. Adjust layers, hex radius, elevation scale, or time binning  
3. Re-export the HTML with your Mapbox access token  

> For large datasets, consider reducing hexbin resolution or splitting by year/month to optimize performance.

---

## Technical Notes

- **Visualization tool:** Kepler.gl
- **Map Hosting:** GitHub Pages  
- **Basemap:** Mapbox GL JS
- **HTML File Size:** 27 MB
- **Browser Recommendations:** Desktop Chrome/Firefox/Safari for full 3D interactive experience  

---

## References

- NASA FIRMS: [https://firms.modaps.eosdis.nasa.gov/](https://firms.modaps.eosdis.nasa.gov/)  
- Kepler.gl: [https://kepler.gl](https://kepler.gl)  
- Mapbox GL JS: [https://docs.mapbox.com/mapbox-gl-js](https://docs.mapbox.com/mapbox-gl-js)  

---

## Disclaimer

This visualization is **research and educational use only**. The data reflects fire detections and is used here as a proxy for analyzing conflict zone activity. Interpret with caution; FIRMS detections are **not independently verified for military operations**.
