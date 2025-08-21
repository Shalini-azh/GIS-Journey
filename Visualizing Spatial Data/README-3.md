Visualizing Spatial data

The goal of the project is to show the choropleth map based on population density.

**Concept:** 

* Joins  
* Data Normalization

**Data Source:**

* nynta\_2010(New York Neighborhood Tabulation Areas) shape file.

* New\_York\_City\_Population\_By\_Neighborhood \_Tabulation\_Areas.csv

**Methods:**

* Add the nynta\_2010 shapefile, and New\_York\_City\_Population\_By\_Neighborhood \_Tabulation\_Areas.csv  to the map canvas  
* Filter only 2010 year data from the tabular data using Filter option (Query builder)									  
* Joining attributes by field tool(processing toolbox): Joined the tabular data using the field name nynta code as a joining field  
* Population data is populated into the nytna shape file and created separate gpkg file for the year 2010 with population.   
* Population density per square mile is calculated for the new field called population density using the field calculator \= 5280\*5280\*(population/shape\_area)(people per sq mile)  
* Choropleth map is created for the spatial distribution of the population density with 6 classes and quantile equal count method.

**Data Normalization:**

Visualized the spatial distribution of the population density in the form   of a choropleth map.

**Final output:**

	The New York City Population density map was created for the year 2010\.

**Sources and Credits:**

* Data: NYC OpenData Portal.  
    
* Tutorial: Ujaval Gandhi (Spatialthoughts)  
    
* Map: Shalini Seralathan using QGIS

