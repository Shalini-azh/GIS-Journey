My GIS Learning Journey 

🌍 10 Largest Earthquakes (2000–2020)

  This repository contains my GIS learning files and outputs. I began my GIS learning journey with the Introduction to QGIS course by Spatial Thoughts (#Ujaval Gandhi), whose step-by-step methods guided me in building these maps.
My first project focuses on designing map layouts of the 10 largest earthquakes between 2000 and 2020, ranked by fatalities. This project helped me practice cartographic design, data visualization, and effective use of QGIS for real-world datasets.

📌 Project Overview

This project visualizes the 10 largest earthquakes between 2000 and 2020, highlighting their global impact in terms of deaths and spatial distribution.It helped me build these skills by importing data layers, applying symbology, adding labels and designing the map layout using QGIS.


🗂️ Data Sources
 
  Earthquake Data: NOAA National Centers for Environmental Information (NCEI) Significant Earthquake

  Fault Lines: GEM Global Active Faults Database (GEM GAF-DB)

  Land Data: Natural Earth Dataset

🛠️ Tools & Libraries Used
 
   1. QGIS: Spatial analysis and cartographic visualization

   2. Data Processing: CSV earthquake dataset cleaned and filtered for significant events (2000–2020)

   3. Cartography: Graduated symbols representing death tolls, labels for  major earthquake locations

   4. Plugins Used:

      MMQGIS (for data management)
 
      QGIS Labeling Engine




 Methodology
 
  1. Data Collection
   - Downloaded global earthquake records (2000–2020) from NCEI.
   - Extracted top 10 earthquakes based on casualties.shape files
   - Imported GEM fault line shape files and Natural Earth base maps.

  2. Data Preprocessing
   - Cleaned earthquake dataset (removed nulls, filtered timeframe).
   - Converted earthquake coordinates into spatial points (WGS84 projection).

  3. Map Creation in QGIS
   - Plotted earthquake points with graduated circle sizes proportional to the number of deaths.
   - Overlaid global fault lines.
   - Added labels for the top 10 earthquake events.
   - Styled map with grayscale landmass and red-highlighted earthquake markers.

  4. Export & Layout
   - Designed final layout using QGIS Print Composer.
   - Added legend, title, and data sources for clear readability.

🗺️ Map Explanation
 
  1. Red Circles → Represent earthquake events; circle size is proportional to deaths.
  
  2. Black Labels → Highlight the 10 largest earthquake events (2000–2020) with location & death toll.
  
  3. Thin Red Lines → Represent global fault lines.
  
  4. Base Layer → Natural Earth map for land boundaries.

Final Output of the Project:

<img width="3507" height="2480" alt="10 Largest earthquakes" src="https://github.com/user-attachments/assets/5c3b9c4e-799a-4c30-98b2-ba7af9a1b085" />



 Key Findings:
 
  1. The Haiti earthquake (2010) was the deadliest (316,000 deaths).
  
  2. The Indian Ocean earthquake & tsunami (2004) caused ~227,899 deaths.
  
  3. High-fatality events are strongly correlated with densely populated fault line regions.


 Created with QGIS | Author: *Shalini Seralathan* 

🙏 Credits 

Tutorial : [Introduction to QGIS by Spatial Thoughts - Ujaval Gandhi](https://courses.spatialthoughts.com/introduction-to-qgis.html#creating-maps)

🔹 Future Work / Next Steps

  🗂️ Add more projects from my GIS learning journey (remote sensing, spatial analysis, cartographic design).



