# NYC-Rodent-Sightings
The analysis and prediction of rat sightings using Big Data techniques.

Approach:
a) Preprocessing :
Preprocessing is one of the most important steps in order to obtain efficient data for analysis and prediction. Preprocessing is done here in order to remove the unwanted columns in the data. Further, some of the data in the columns needed to be type casted, so that the computation process was made smoother. Some of the required columns also had unnecessary data present and the unwanted information had to be removed. These entire steps account for data cleaning.

b) Usage of other datasets:
Using other relevant data like NYC Subway Station data and the data of NYC Litter Baskets in order to plot the Subway station locations and the Litter Basket locations on the map. Plotting them on the map along with the rat sightings will give us a clear understanding of the density of rat sightings near the subway station and Litter Baskets.

c) Analysis of the Data:
Using the refined data, analysis is done based on the following factors.
● Month
● Year
● Location
● Borough
- The months in which rat sightings are seen
- Year in which a rat sighting is reported
- Plotting the Location on the map where a rat is spotted
- In which Borough( Brooklyn, Manhattan, Queens, Staten Island, Bronx) majority of the rat sightings are reported
● Apartment - Based on the type of the apartment ( 3+ Family Apartment Building, Hospital, Parking lot/ garage, etc.)

d) Visualisation:
The analysis of data can be explained in the best possible way using visualization techniques. The major visualization tools used for this project are Plotly and Folium. Plotly is used for plotting the relevant histograms, Line Graphs, and Pie Charts, whereas, Folium is used to plot the heat map showing rat sightings, subway stations, and litter baskets of NYC.