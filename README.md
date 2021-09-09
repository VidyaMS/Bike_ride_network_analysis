# Bike_ride_network_analysis. 
######################################################################.      
Data source : https://www.kaggle.com/benhamner/sf-bay-area-bike-share/version/2.   

Bike ride data from around 70 stations in SFO is made available in the files mentioned below:  
trip.csv - contains the trip data with the details such as the start and end stations, date of the trip , duration of the trip , subscription type, zipcode etc.    
status.csv - which contains the date wise availability of bikes in the stations.     
station.csv = which contains the station details such as the GIS coordinates, 
  
Weather data is made avilable in weather.csv with details such as max , min temperature , humidity, pressure , wind direction details etc.  
All the start and end dates are from 29th Aug 2013 to 31st Aug 2015.  
#####################################################################

### Insights derived from the data:  
![stations_per_city](https://user-images.githubusercontent.com/20832632/132625104-7fdbe93a-6c27-42ed-8528-d7ffd6152b87.png)

SFO has the maximum number of stations followed by San Jose.

![pic2](https://user-images.githubusercontent.com/20832632/132631600-6dcaf44e-7a10-482d-865e-59dae384e044.png)

The year 2013 had the least number of available bikes per hour - half of that was available in 2015.  
The year 2014 has the maximum number of available bikes per hour.    
In the line graph above , we can see a dip in the lines around 8am and then again at 17pm, signifying the maximum usage of bikes during those hours.  

### Network Analysis.  

![g1](https://user-images.githubusercontent.com/20832632/132632471-b797e196-afd8-4419-98c1-506c4ca94bd3.png)

The graph network above depicts station ids by their connections (connected due to bike trips) with the other stations. The ones marked in orange are those with max connections and those in pink are with least connections. For e.g the station id 70 - San Francisco Caltrain (Townsend at 4th)	, 72 - Civic Center BART (7th at Market) have the max connections between stations. Station id 27 - Mountain View City Hall and station id 30 - Evelyn Park and Ride	in Mountain View city have the least connections.  

#### Stations with maximum number of trips.  

![g4](https://user-images.githubusercontent.com/20832632/132711695-31b05d69-3808-4573-9f84-44fb0f0a8fc7.png)

The graph network depicts those stations that have the top 100 bike trips.  
The station ids marked in orange have the top 10 bike trips.
The trips are marked by green line - for trips > 4000 , blue line for trips between 2500 and 4000  and red lines for trips less than 2500.  

#### Stations with maximum total duration of bike trips.

![g3](https://user-images.githubusercontent.com/20832632/132710884-5b9e395d-708a-4ba0-bac1-df54693bf180.png)

The graph network depicts those stations that have the top 100 durations of bike trips.  
The station ids marked in orange have the top 10 durations
The trips are marked by green line - for duration  > 4500K  , blue line for durations between 2500 K and 4500 K   and red lines for durations less than 2500 K.  
