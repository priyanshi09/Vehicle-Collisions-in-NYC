# Vehicle-Collisions-in-NYC

Spatial Analytics Project on analysis of Vehicle Collisions in New York City.

New York City, like other major urban areas, has a high density of both vehicle and human traffic. Vision Zero,     
an action plan created by Mayor Bill de Blasio, is a major city project to reduce traffic-related injuries and deaths.    
The objective of this project, which is to identify areas of New York City that are at high risk for vehicle collisions using a      
model based on a combination of weighted factors, will provide insights to which areas of the city Vision Zero efforts should be focused on. In this spatial analysis we defined the time period in which collisions are happening as between      
January 1st, 2015 to January 1st, 2016.

The vehicle collision data was obtained from NYPD open data and cleaned in python for this spatial analysis.    
The population data used in this spatial analysis was retrieved from the U.S. Census Bureau and delineated by census tracts.      
This dataset was combined with MTA Ridership information to incorporate commuters, tourists, and other population influxes into the city.      
The U.S. Census Bureau shapefile contains population characteristics from the 2010 Census as well as geographic information for mapping (GEOID). The data was clipped to the boroughs of New York City in ArcGIS. 

To assess the safety in  terms of number of Collisions per census tract, we took the Safety Score ( point data) from MIT media lab which has given safety scores for the segment of streets. This score is perceived safety and based on crowdsourcing data. 
