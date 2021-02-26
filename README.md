# Surfs_Up
## Overview
The purpose of this analysis is to study temperature data in Oahu for the months of June and December. This study will determine if opening a Surf shop in the location is feasible. We can determine if the Surf shop is sustainable year-round by studying temperature data from June and December. I used SQLite and Pandas to perform this analysis.

### Results
<img src = "https://github.com/Kee2u/Surfs_Up/blob/main/Resources/June_temps.PNG?raw=true" width = '150'> <img src = "https://github.com/Kee2u/Surfs_Up/blob/main/Resources/December_temps.PNG?raw=true" width = '182'>
  - Mean
     - The mean of the December temperatures is not too much colder than June. It is in the 70s which is a comfortable temperature for surfing.
     
  - Minimum temperature
     - The minimum temperature is in the low 60s for June and in the low 50s for December. This can be too cool for surfing. The minimum temperature in December is 8 degrees lower than the minimum temperature in June. 
  
  - Count
     - There are more datapoints for June than for December. 
     
### Summary
Overall, it looks like Oahu has comfortable surfing temperatures year round. Based on the percentiles, most of the data points (75%) are in the 70s for both December and June. It is a great location to open a Surf shop.
Before we go forward, it is a good idea to look at precipitation data as well:

#### Precipitation
From the standard deviations, we can see that there is little to no rainfall 75% of the time. We do see large max rainfall amounts (4.4" for June and 6.4" for December). This is something to keep in mind when opening the shop. Business will be poor during periods of torrential rainfall.

<img src = "https://github.com/Kee2u/Surfs_Up/blob/main/Resources/June_prcp.PNG?raw=true" width = '180'> <img src = "https://github.com/Kee2u/Surfs_Up/blob/main/Resources/December_prcp.PNG?raw=true" width = '180'>
