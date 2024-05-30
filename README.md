# Portsmouth-Crime
An analysis of street crime cases in portsmouth (using reported long and lat) to identify:
- The most frequent commited forms of crime.
- The most frequent location for crime.
- Any trends/differences in crime over the past 6 months (2023-10 - 2024-03)
The data was obtained using the the https://data.police.uk/ API. 

## Key take aways: 
### Most Frequent Commited Crimes by Date
![image](https://github.com/LiamBatiste/Portsmouth-Crime/assets/68031898/bbb216dd-247b-4934-923f-d7654b86183e)
- There is clearly a high amount of violent crime cases across the 6 months. Implications being that Portsmouth Police should be trained for positive handling. 
- Towards the later end of the year there appears to be an increase in the amount of vehicle crime. Implications being that greater resources should be allocated towards combatting car theft at the end of the year. 

### Most Frequent Locations of Commited Crimes by Date
![image](https://github.com/LiamBatiste/Portsmouth-Crime/assets/68031898/1b2eade0-b3c2-46a9-82f7-bc42c2315527)
- There is a progressive decrease in parking area crime over last 6 months. Implications being that if there are methods being applied to these locations to reduce crime levels, it should be replicated for other areas of high crime rate (Supermarkets and Guild Hall Walk in particular). 
- Increased recent crime rate at Jacob's Street. Implication being that more resources might want to be allocated for this location. 

## Lessons learnt: 
- I as an analyst need to be more methodical with what data I use so I can gain more actional insights, as the time series was redundant, given the date provided in the API does not necessarily correspond with the date the crime was commited.
- The data pulled using the API could have been automated using a data pipeline, given the difference between obtaining the data for each date was so minor (the date parameter of the API request).
