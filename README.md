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

# Insights derived from the data:  
![stations_per_city](https://user-images.githubusercontent.com/20832632/132625104-7fdbe93a-6c27-42ed-8528-d7ffd6152b87.png)

SFO has the maximum number of stations followed by San Jose.

![pic2](https://user-images.githubusercontent.com/20832632/132631600-6dcaf44e-7a10-482d-865e-59dae384e044.png)

The year 2013 had the least number of available bikes per hour - half of that was available in 2015.  
The year 2014 has the maximum number of available bikes.  
In the line graph above , we can see a dip in the lines around 8am and then again during 17pm, signifying the maximum usage of bikes during those hours.  
