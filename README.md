# Climate Action

> Take urgent action to combat climate change and its impacts
>
> Climate change is now affecting every country on every continent. It is disrupting national economies and affecting lives, costing people, communities and countries dearly today and even more tomorrow. Weather patterns are changing, sea levels are rising, weather events are becoming more extreme and greenhouse gas emissions are now at their highest levels in history. Without action, the world’s average surface temperature is likely to surpass 3 degrees centigrade this century. The poorest and most vulnerable people are being affected the most.

Follow the link to read more from the UN: [Climate Action]

## Dataset Summary
Early data was collected by technicians using mercury thermometers, where any variation in the visit time impacted measurements. In the 1940s, the construction of airports caused many weather stations to be moved. In the 1980s, there was a move to electronic thermometers that are said to have a cooling bias.

The Berkeley Earth Surface Temperature Study combines 1.6 billion temperature reports from 16 pre-existing archives. It is nicely packaged and allows for slicing into interesting subsets (for example by country). They publish the source data and the code for the transformations they applied. They also use methods that allow weather observations from shorter time series to be included, meaning fewer observations need to be thrown away.

## Dataset Download and Information
| Link                     | Description |
| ------------------------ | ----------- |
| [Dataset and DB Backups] | This links you to a Google Drive where all of the data CSVs have been placed along with a MySQL and PostgresSQL backup. |
| [Berkeley Earth]         | A link to the study mentioned above. |

Global Land and Ocean-and-Land Temperatures (GlobalTemperatures.csv): 

| Column Name                                | Description |
| ------------------------------------------ | ----------- |
|  Date                                      | starts in 1750 for average land temperature and 1850 for max and min land temperatures and global ocean and land temperatures |
| LandAverageTemperature                     | global average land temperature in celsius |
| LandAverageTemperatureUncertainty          | the 95% confidence interval around the average |
| LandMaxTemperature                         |  global average maximum land temperature in celsius |
|  LandMaxTemperatureUncertainty             | the 95% confidence interval around the maximum land temperature |
| LandMinTemperature                         |  global average minimum land temperature in celsius |
| LandMinTemperatureUncertainty              | the 95% confidence interval around the minimum land temperature |
| LandAndOceanAverageTemperature             | global average land and ocean temperature in celsius |
| LandAndOceanAverageTemperatureUncertainty  | the 95% confidence interval around the global average land and ocean temperature |

Other files include:  
- Global Average Land Temperature by Country (GlobalLandTemperaturesByCountry.csv)
- Global Average Land Temperature by State (GlobalLandTemperaturesByState.csv)
- Global Land Temperatures By Major City (GlobalLandTemperaturesByMajorCity.csv)
- Global Land Temperatures By City (GlobalLandTemperaturesByCity.csv)

## Team Repository Links
[CA-C1]  
[CA-C2]  
[CA-C3]   
[CA-P1]  
[CA-P2]  
[CA-P3]  
[CA-P4] 

[CA-C1]: https://github.com/CharlestonDigitalHubHackathon/CA-C1
[CA-C2]: https://github.com/CharlestonDigitalHubHackathon/CA-C2
[CA-C3]: https://github.com/CharlestonDigitalHubHackathon/CA-C3
[CA-P1]: https://github.com/CharlestonDigitalHubHackathon/CA-P1
[CA-P2]: https://github.com/CharlestonDigitalHubHackathon/CA-P2
[CA-P3]: https://github.com/CharlestonDigitalHubHackathon/CA-P3
[CA-P4]: https://github.com/CharlestonDigitalHubHackathon/CA-P4
[Climate Action]: https://www.un.org/sustainabledevelopment/climate-change-2/
[Dataset and DB Backups]: https://drive.google.com/drive/folders/1EW0YP1whln-wppTYMP4CeXOVf1os5SI7?usp=sharing
[Berkeley Earth]: http://berkeleyearth.org/about/
