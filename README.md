# Location-Analysis
Project aims to find optimize location for car mechanic shop in the State of Maryland using EDA and visualize with Folium map.

### Introduction: Business Problem

In this project our goal is to find most favorible location for a car mechanic shop in Maryland, USA. This report will be compatible with shareholders needs.

In accordance with shareholders request, we will find the best location which will be close to close to cities but not close range to any of compatition. Using data science methodology and instruments such as data analysis and visualization, this project aims to provide optimal location. Thus, we will compare Foursquare data to registered passenger vehicle data.

We will use our data science powers to generate a few most promissing neighborhoods based on this criteria. Advantages of each area will then be clearly expressed so that best possible final location can be chosen by stakeholders.

### Data

Based on our business problem we will need:

 * Passenger vehicle numbers in each city/county
 * Geolocation coordinates of each city/county
 * Number of existing mechanic shops in each city/county

Therefore, this project uses two main source of data. Our crucial data is registered passenger vehicles in Maryland, USA. This data can be retrieved from State of Maryland's open data source - https://opendata.maryland.gov/w/kqkd-4fx8/gz96-f9ea?cur=7U4SpQ1_sHa This data gives us important information on vehicle number from 2010 to 2020 in each county of Maryland. Even so, this data requires data cleaning, and wrangling.

In order to obtain geolocation, we will use Python's `Geocoder` package. Finally, we will use `Foursquare API` to obtain number of existing mechanic in each county with their names as well. Then, this information will be visualized on Python's Folium package map.

### EDA

<img src="https://github.com/oneofthemdata/Location-Analysis/blob/main/images/Registered_Vehicles.png" width="500" height="300">
<img src="https://github.com/oneofthemdata/Location-Analysis/blob/main/images/Mechanics_in_MD.png" width="500" height="300">
