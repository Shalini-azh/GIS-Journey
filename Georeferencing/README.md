**Georeferencing** 

**Introduction**

This exercise 3 is part of my learning journey with the [Introduction to QGIS tutorial Spatial Thoughts by Ujaval Gandhi](https://courses.spatialthoughts.com/introduction-to-qgis.html#georeferencing).

The objective of the process is assigning real world coordinates to the scanned map or image so it can be used with the other spatial data. 

## **Objective**

* To understand and apply the basics of **georeferencing in QGIS**.  
* To use ground control points (GCPs) to align a scanned historical map with actual geographic coordinates.  
* To generate a georeferenced raster that can be overlaid with vector and raster datasets.

---

## **Steps Followed**

1. Loaded the scanned raster map (Bengaluru) into QGIS.  
2. Opened the **Georeferencer tool**.  
3. Plotted Ground Control Points (GCPs) by matching features (roads, rivers, landmarks) on the scanned map with reference OSM standard map service.  
4. Selected a transformation method (e.g., **Polynomial 1 / Thin Plate Spline** depending on dataset).  
5. Choose the output coordinate reference system (CRS).  
6. Executed the georeferencing process to create the output raster.  
7. Verified alignment by overlaying the georeferenced map with vector layers.

---

## **Tools & Software**

* **QGIS (latest stable version)**  
* **Georeferencer Plugin** (built into QGIS)


---

## **Output**

* Georeferenced raster image aligned to the correct CRS.  
* Visualization showing proper overlay with other spatial datasets.
* [Bangalore_1924_modified.tif](https://github.com/user-attachments/files/21945775/Bangalore_1924_modified.tif)



---

## **Learning Outcome**

* Learned the complete workflow of **georeferencing in QGIS**.  
* Understood how to choose transformation methods and control point placement for accuracy.  
* Gained hands-on practice in creating georeferenced maps suitable for analysis and visualization.

---

