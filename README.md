# Surfs_Up
## 1 Overview of The Project
Weather plays important aspect to open a surf n shake shop. A perfect weather to open surf n shake shop is sunny all through the year with enough rain to keep everything green, but not so much that you lose out on that ideal surfing and ice cream weather. To determine if the surf and ice cream shop business is sustainable year-round, this analysis will focus on June and December temperature analysis.
The following tasks will be performed in this analysis:
  1.	Create query to retrieve the June and December temperatures and precipitation
  2.	Create list for the June and December Temperatures and precipitation
  3.	Create Pandas DataFrame for the June and December Temperatures and precipitation
  4.	Summary statistic for June and December Temperatures and precipitation
  
## 2 Resources
Data Source: Hawaii.sqlite

Software: Python 3.7.6 , Jupyter notebook, Pandas library,Sqlite

## 3 Results
### 3.1 Temperature Comparison

<p align="center">
<img src="https://user-images.githubusercontent.com/88597187/138209253-e35ee311-5a14-48f6-ae67-f3ee94f36f7e.png"/>
<img src="https://user-images.githubusercontent.com/88597187/138209290-136773da-2629-42af-b42b-0c713514ff93.png"/>
</p>
<p align="center">
  <sub> Figure 1 Comparison between June and December Temperature </sub>
</p>


Figure 1 describe comparison between June and December Temperature:
 * The number of data collected is higher for June (1700) compared to December (1517)
 * The mean temperature for June is higher(74.94˚F) than December (71.042 ˚F) 
 * The standard deviation for December is higher (3.75) than June (3.26) which means that data is more spread out in December.
 * 1st quartile: 25% of all data is below 69 °F in December and 73 °F in June.
 * 3rd quartile 75% of all data is below 74 °F in December and 77 °F in June
 * The min temperature is 64°F for June and 56 °F for December 
 * The max temperature is 85 °F for June  83 °F for December

### 3.2 Precipitation Comparison

<p align="center">
<img src="https://user-images.githubusercontent.com/88597187/138209568-ee42b7e1-edf1-4673-be96-4a322206a70c.png"/>
<img src="https://user-images.githubusercontent.com/88597187/138209579-42cd6d98-d2a8-4e60-a8fc-3607f974fcc9.png"/>

</p>
<p align="center">
  <sub> Figure 2 Comparison between June and December Precipitation </sub>
</p>

Figure 2 describe comparison between June and December Precipitation:
  * The number of data collected is higher for June (1574) compared to December (1405)
  * The mean precipitation for June is lower (0.136) than December (0.22) 
  * The standard deviation for December is higher (0.54) than June (0.34) which means that data is more spread out in December.
  * 1st quartile: 25% of all data is below 0 both for June and December 
  * 3rd quartile 75% of all data is below 0.12 in December and 0.15 in June
  * The min precipitation is 0 for June and December
  * The max precipitation is 4.43 for June and 6.42 for December

## 4 Summary

The following is the summary of the comparison between June and December temperature and precipitation:
  * From the mean temperature we can see that there is not much difference on temperature between June and December. The mean and median are not far apart means that the data is not spread out. This indicates that the temperature is mild and warm all year round.
  * The maximum precipitation is far away from the mean, this can indicate that there is an outlier. The standard deviation is high, mean, and median or 2nd quartile are far apart, meaning that distribution of the data is highly spread out. To add information about the precipitation in all year round, two graph describing precipitation for year 2015 and 2016 is added. From Figure 3 and Figure 4, we can see that there is always an precipitation outlier in every month. But the average precipitation all year round is under 2

<p align="center">
<img src="https://user-images.githubusercontent.com/88597187/138209890-c8030d8a-278c-4d8f-aa1d-5d57a5ec58d2.png"/>
</p>
<p align="center">
  <sub> Figure 3 Precipitation for Year 2015 Graph </sub>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/88597187/138210045-ab99d058-1c55-4cc2-873a-c9d48321a802.png"/>
</p>
<p align="center">
  <sub> Figure 4 Precipitation for Year 2016 Graph </sub>
</p>

* The investor main concerned is the temperature are not warm enough and the rainfall frequency is too high. By comparing the data for temperature and precipitation, we can see that the temperature is mainly mild, warm and the rainfall is not that frequent for all year round.
