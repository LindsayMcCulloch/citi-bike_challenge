# citi-bike data analysis

**Tableau public workbook:** https://public.tableau.com/app/profile/lindsay.mcculloch/viz/citi-bike-visualisations/Januaryannualtrendsinciti-bikedata

The datasets and images used for this analysis can be located in this **GitHub repository:** https://github.com/LindsayMcCulloch/citi-bike_challenge

Completed by Lindsay McCulloch 

## Purpose

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilisation. Each month, bike data is collected, organised, and made public on the Citi Bike Data.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process.

The main purpose for the this analysis is to discuss any findings, through visualisations of January data for the years 2022, 2023 and 2024 and find noiceable trends and phenomenons within this specified period across a total of 133,498 rides 

![alt text](<Total rides per year.png>)

***Refer to Tableau public story***

## Analysis question 1: What trends can be observed between memberships recorded in January annually between 2022 to 2024?

Across the month of January in 2022, 2023 and 2024 there has been a total of 133,498 rides, with 106,418 rides amongst members and 27,082 casual rides. January 2022 had the lowest record rides amongst casual (6,731 rides) and members (20,031 rides) in comparison to January in the following two years. Despite the increase in casual riders in 2023 at approximately 200% from 2022, 2023 this trend did not continue in 2024 as riders reduced to just under 8,000 rides. In comparison members also increased at just over 200% from 2022 to 2023 and has stayed consistant in 2024 with only a 899 ride decrease as visualised in below graph.

![alt text](<Membership per year.png>)

From the data as visulised below, members are more likely to opt for a classic bike ride at 67,032 across all 3 annual months. The electric bike was the only other preference members chose for their citi-bike hire at a total of 39,384 rides. Unlike casuals though with 177 rides in total for the docked bikes, members did not keep their ride active and dock their bikes for later use during the 3 January periods. One other trend observed was that casual riders did not have a preference for classic (13,694) or electric bikes (13,211) with only a variance of 483 rides despite there being membership benefits that 'all new Citi Bike memberships and renewals will come with 60 free e-bike minutes' as promoted by nyc.streetsblog.org.
*Source:* https://nyc.streetsblog.org/2023/11/03/electric-avenue-e-citi-bikes-will-double-but-footprint-wont

![alt text](<Rideable type per member.png>)

The last observation made from the annual month data relative to membership status was that casual riders on average rode for a longer duration across all January periods with the a total average duration across 2022 to 2024 of 22.85 minutes per ride, where members averaged at an average duration of 12.73 minutes per ride across the 3 year period.  

![alt text](<Ride duration per membership.png>)

***Refer to Membership dashboard on Tableau workbook***

## Analysis question 2: What trends can be observed per rideable type January annually between the chosen period?

The total trips per rideable type has been measured as below, allowing us to explore the data and compare rideable type popularity in January each year. In 2022, we saw the least amount of rides total with classic bikes measuring at a total 16,952 rides and electric bikes popularity at just over 6k rides less. in 2023 this trend of popularity in classic bike rides almost tripled where electric bike rides only increased by just over 2.5k rides. Unsurprisingly given the e-bike popularity and increase in available e-bikes across the US, in 2024 the electric bike rides increased dramatically to 30,846 rides now exceeding the classic bike rides recorded in previous years for the month of January.

The docked bike riders, being those who choose to dock their bike whilst still keeping the ride active and allowing them to continue use of their citi-bike,  were significantly lower at only 77 rides in January. This trend of riders choosing to not dock their bikes for continued use was also recurring in 2023 with only 100 docked rides. Surprisingly in 2024 there was not a single bike docked with an active ride. This observation shows that riders are less likely to continue use after their trip is complete and reuse their same citi-bike. With further data this could open the investigation as to why this may be the case, some possible reasons could be the additional charges incurred on docked bikes to ensure "ownership" of bike until the rider requires the bike. Another could be the availaiblty of other bikes/full docking stations meaning other bikes are readily available for use at any given time for the rider and they do not need to worry about their original bike being used by another rider. 

![alt text](<Total trips per rideable type.png>)

The docked bikes recorded in 2022 and 2023 spent a comparable average duration at docking stations while under hire, with bikes in 2022 spending an average 138.4 minutes docked and 134.8 minutes docked in 2023.

From the below pie chart it is shown that the average duration in 2022 of actual rides in January was 23.95 minutes per ride across both rideable types. where in 2023, the duration of rides across both types was almost halved. in 2024 this number has again decreased to just under 9 minutes per ride across both classic and electric e-bikes. From this trend we can see people are spending less time using the citi-bikes for each ride and it can be hypothesised that this is likely caused by greater availability of bikes across the city and potentially due to increased popularity causing more people to use the bikes for short trips/errands and recreationally rather than as a mode of transport. As recounted by John MacArthur, a transport researcher at Portland State University in a publication made by The Guardian; 'Half of all trips made by Americans are under three miles – a distance ebikes can easily conquer. Suddenly, cycling isn’t just a fitness activity or something done for fun by small children – it is a method to run errands and get to work in car-centric America.'
*Source:* https://www.theguardian.com/environment/2023/dec/22/ebike-boom-america-sales

![alt text](<Ride duration per rideable type.png>)

The next measure of which rideable type is more popular for each weekday did not produce and significant trends for observation as you can see in below chart. This might be due to the lack of monthly data available in the specific dataset being measured and trends may be better observed in a monthly format for a full 12 months rather than a year on year comparison. 
Overall there was no significant weekday preference for riders in January between 2022 to 2024. The data is quite scattered showing preferences for both rideable types increasing middweek in 2022. where in 2023 the start of the week showed greater preference for both rideable types before remaining relatively spread during the end of the week. In 2024 however the use of citi-bikes saw significant drops at the end of the week in comparison to previous years and no hypothesis on weekday preference can be made without further investigation as to what the influencing factors may be.

***Refer to Rideable type dashboard on Tableau public workbook*** 

## Station Analysis:

**What are the top 10 stations in the city for starting a journey?**

![alt text](<Top 10 starting stations.png>)

**What are the top 10 stations in the city for ending a journey?**

![alt text](<Top 10 ending stations.png>)

**What are the bottom 10 stations in the city for starting a journey?**

![alt text](<Bottom 10 starting stations.png>)

**What are the bottom 10 stations in the city for ending a journey?**

![alt text](<Bottom 10 ending stations.png>)

From the data as visualised in the above graphs, it was found that Hoboken terminal - River St & Hudson Pl was the most popular starting station across the combined 3 year January periods. This same station is the second most popular end station for all citi-bike riders. Interestingly the Grove Street PATH station is the second most popular station for riders starting their journey and is the most poular end station location overall. With Grove Street only falling 25 rides short of most popular starting station.

These two stations are located in New Jersey and are direct stops at railway station terminals. From this it can be assumed riders are utilising the citi-bike system to get them to and from the railway stations during their daily commutes.

In contrast the least popular stations for riders to begin their journey, tied at 1 ride per station throughout the overall data period are; Broadway & W 41 St, Greenwich St & Hubert St, Mercer St & Spring St, Motorgate, and S 3 St & Bedford Ave. 

The least popular stations for riders to end their journey consisted of just over 50 stations in the outskirts of city zones, having recorded only one ride per station throughout the month of January between 2022 to 2024.

***Refer to station popularity dashboard on Tableau public workbook***

By using the below maps as a visual, you can see which stations have increased popularity based on the marker size and it can be easily itentified which stations are of greater popularity as both end and starting points. 
It is notable from the data and the visualisations that station popularity is greatly influenced by the stations proximity to public transport terminals and city centres.

![alt text](<Start station popularity.png>)
![alt text](<End station popularity.png>)

***Refer to station popularity map on Tableau public workbook***

## Summary

in sumarry for January 2022, 2023, 2024 cit-bike data;

* There has been a total of 133,498 rides
* 106,418 member rides and 27,082 casual rides
* Members opted for classic bike hire across all 3 annual months
* Casual riders are more likely to dock their hired bike for later use
* Casual riders had no preference for classic or electronic e-bikes
* Casual riders are more likely to ride for a longer duration than members
* Citi-bike hires were less popular in 202, than more recent years
* As of 2024 electric bikes have become more popular amongst citi-bike riders
* In 2022 and 2023 the number of bikes docked was comparible whilst there were no bikes docked in 2024 whilst under hire
* Overall there was no significant weekday preference for riders
* Stations closer to city centres and public transport terminals are more likely to attract citi-bike riders 

## Acknowledgments 

Datasets provided by © Lyft, Inc. 2024 at https://citibikenyc.com/system-data