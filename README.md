# Real Estate Development Proposal

**Overview**: For Project 1 in Metis, groups were asked to utilize MTA Subway traffic data to explore a hypothetical business use case. This project is based on the idea of approaching luxury building developers with the proposal of using data-driven analytics to aid in the decision of where to build their next development. 

By analyzing MTA station traffic patterns and key neighborhood characteristics (income, demographics, the presence of other luxury buildings in the area), the aim is to provide actionable insights around potentially favorable building sites. 

**Factors to consider:**
---
* Proximity to a subway stop
* Proximity to a favorable line 
* Journey time to areas with high office building density in most profitable sectors
* Foot traffic

**Methodology:**
---
We first set out to identify the station with the most exits in the morning (defined as 7-11am) during the weekdays. By doing this, we could get a sense for the station that is heavily utilized by commuters looking to get to work in the morning. We then explored the lines that pass through that station, with the goal of finding stations that are linked to the station identified in the first step, and that satisfy two criteria (listed in order of importance):
1. They are located within neighborhoods with relatively high median incomes, and 
2. They have relatively low number of entrances during work day mornings (again defined as 7-11am)

**Results**
---
Since we were more concerned with finding an area with incomes capable of sustaining a luxury development than we were with finding low foot traffic, we first identified neighborhoods with relatively high median income levels. The heat map below shows relative income levels (as well as foot traffic) among neighborhoods served by the 4 and 5 subway lines. Median income levels were taken from the [following link](https://ny.curbed.com/2017/8/4/16099252/new-york-neighborhood-affordability), and then scaled to be between zero and one.

![alt text](https://github.com/ErickDWalker/MTA-Subway-Analysis/blob/master/img/Income_Entries_Neighborhood_Heatmap.png?raw=true)

Downtown Brooklyn emerged as the neighborhood with the highest relative median income. Though it also appeared to have the highest entries, this number represents an aggreagation of multiple stations, and so can be misleading. To get around the aggregation issue, we then looked at the weekday morning turnstile entrances for individual stations. 

![alt text](https://github.com/ErickDWalker/MTA-Subway-Analysis/blob/master/img/Income_Entries_Station_Heatmap.png?raw=true)

Among the downtown Brookly stations, we found that the Nevins street station best satisfied both of our conditions.
