# South_Fulton
## Group Members: Fred, Nika, Peter, Zhengyi
Datastory please refer google doc.

## TRI Data source
### Dataset description
The Toxics Release Inventory (TRI) is an information resource available through the Environmental Protection Agency that can help you learn about the management and release of toxic chemicals in your community. The TRI Program was established in 1987 out of the Emergency Planning and Community Right-to-Know Act. Today, there are over 21,000 facilities that report data to TRI nationwide, and it covers over 800 toxic chemicals. 

We mainly use the TRI [Dataset](https://github.com/2zOu2/South_Fulton/blob/main/South%20Fulton%20TRI%20data%202020-2022.csv) around South Fulton. It is directly downloaded from the TRI website.
#### Pollution Map 
##### Code Description
Using the folium library, we visualizes these data on an interactive map centered on South Fulton. The map features a choropleth overlay that shows varying pollution levels across different ZIP Codes, color-coded from yellow to red. A color scale legend aids in interpreting the pollution levels. Additionally, markers indicate specific facilities, displaying detailed information such as the facility name and total releases. Details about code is here: [TRI_MAP_Code](https://github.com/2zOu2/South_Fulton/blob/main/TRI_DATA_Analysis_Code.ipynb)

##### Map Demo
We aim to create an interactive map to tell the data story, and we have a [Chemical Pollution Map](https://github.com/2zOu2/South_Fulton/blob/main/pollution_map.html) and 
[Water Pollution Map](https://github.com/2zOu2/South_Fulton/blob/main/monitoring_site_map.html) 

 
#### Rank of the most released chemicals
##### Description
We use pyplot package to display the top 5 chemical pollutants for each category and year from 2020 to 2022. Results are [here](https://github.com/2zOu2/South_Fulton/tree/main/Results)

## USGS Water Quality
### Please download the zipfile in the Github and find the details of this dataset and analysis code





