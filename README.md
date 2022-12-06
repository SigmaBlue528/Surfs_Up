# Surfs_Up

Project Overview:

Bonilla Analytics has been contracted by the chairman of a group of investors (W. Avy) to collect and analyze analytics from weather data (specifically weather for the months of June and December) to determine which island within the archipelago of Hawaii would return the quickest return on investment for the entity known as Icy Reef shop.  

Objective:

Perform data analysis for the island of Oahu in the State of Hawaii. 
Summarize the data and determine whether Icy Reef shop is a sustainable, profitable, and viable investment for business all year around. 

Software used:

  •	Data Source: hawaii.sqlite
  •	Software: Python, Jupyter Notebook, SQLite, SQLAlchemy, Pandas

Analysis of Data and Results
  •	Using Python, Pandas functions and methods, and SQLAlchemy, we have filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December respectively.
  
  • For each month, we have then converted those temperatures to a list. Finally, we have created a DataFrame from the list, and generated the summary statistics for June and December. (See Table 1 and Table 2 below)

    	Table 1: Summary statistics for June temperature       

    	Table 2: Summary statistics for December temperature 
                   
         
Table 1 and 2 shows us the following:
  •	The average temperature is 71 degrees Fahrenheit in December which is slightly lower than the average temperature in June (74.94 degrees). However, the 70s are the right temperature to surf without being too cold or too hot.
  
  •	The minimum temperature is 56 degrees in December while it is 64 degrees in June. However, 56 degrees is not considered cold and wearing a basic wetsuit could help the surfer maintain his/her body temperature.
  
  •	The maximum temperature is 83 degrees in December and 85 degrees in June. This shows that even in December this Island has hot days.

Summary
  1.	Summary Statistics for the station with the highest number of observations
  In this part, we have repeated the previous work, but we have chosen data from one station only; The station that has the highest number of observations. To see if this would affect our results. (See Table 3 and 4)

      	Table 3: Summary statistics for June temperature from 1 station

      	Table 4: Summary statistics for December temperature from 1 station


  Table 3 and 4 show us the following:
  •	The average temperature has dropped a little. It is almost 70 degrees Fahrenheit in December and 73.2 degrees in June which is still a good temperature to surf without being too cold or too hot.
  •	There is not any huge difference in numbers that we should consider. We can say that these tables confirm the results of tables 1 and 2. 
  •	It is worth mentioning that in all tables the temperatures in the 1st quartile are in the 60s which shows that the number of days with temperatures in the 50s is low.

  2.	Summary Statistics for Precipitation:
  Moreover, we have determined the summary statistics for precipitation for the months of June and December respectively (See Table 5 and 6)

      a.	Table 5: Summary statistics for June precipitation                                                              

      b.	Table 6: Summary statistics for December precipitation


  •	Table 5 and 6 show that the average precipitation is 0.1 for June and 0.2 for December, which is considered light rain.

Conclusion:
On 12/08/2022 Bonilla Analytics concluded the objectives that were initially set forth in the beginning of this proposal. It has been determined that the proposed business entity known as Icy Reef shop is in fact viable, sustainable, and (most likely will be) profitable for business year-round on the island of Oahu in the State of Hawaii. The data also points to other potential revenue streams that might not have originally been considered in the initial business proposal. These potential revenue streams include:

  o	Renting or selling wet suits.
  
  o	Selling of Tourist products such as towels and local art.
  
  o	Selling of consumables such as sunscreen, sunblock, snacks, and beverages (alcoholic and non-alcoholic).
  
  o	Establishing a venue for live music.
  
  o	Establishing a restaurant. 
  
  o	Selling shaved ice.
  
  o	Renting/selling of lockers for personal items.
  
  o	Selling of electricity via charging stations (with energy produced from solar panels on the roof).

