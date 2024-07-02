# citi-bike_challenge

This is the repository for Monash University Data Analytics Bootcamp Module 18 Challenge

Tableau Public Workbook: https://public.tableau.com/app/profile/lindsay.mcculloch/viz/citi-bike-visualisations/Januaryannualtrendsinciti-bikedata

## Contents

* `citi-bike_data_query.ipynb` Jupyter notebook containing the query to merge January citi-bike data from JAN 2022, JAN 2023 and JAN 2024
* `2022-2024_combined_citi-bike_data.csv` CSV export file containing the combined 2022, 2023 and 2024 data tht will be used by Tableau for visualisations
* `citi-bike-visualisations.twb` Tableau public workbook containing the visualisations/dashboard/story for this data

**Analysis folder**
* `citi-bike data analysis.md` is a markdown file containing the written analysis for this challenge 
* `.png` files for each visualisation used in the `citi-bike data analysis.md`

**Resources folder**
* `JC-202201-citibike-tripdata` csv file that contains the citi-bike data for JAN 2022
* `JC-202301-citibike-tripdata` csv file that contains the citi-bike data for JAN 2023
* `JC-202401-citibike-tripdata` csv file that contains the citi-bike data for JAN 2024

## Key analysis questions

* What trends can be observed between memberships recorded in January annually between 2022 to 2024?
        
* What trends can be observed per rideable type January annually between the chosen period?

* What are the top 10 stations in the city for starting a journey?

* What are the top 10 stations in the city for ending a journey?

* What are the bottom 10 stations in the city for starting a journey?

* What are the bottom 10 stations in the city for ending a journey?

## Background

Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicise and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilisation. Each month, bike data is collected, organised, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Instructions

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

1. Design 2–5 visualisations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

2. Create one of the following visualisations for city officials:

    * **Basic:** A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

    * **Advanced:** A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

*The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.*

3. Create your final presentation:

    * Create a Tableau story that brings together the visualisations, requested maps, and dashboards.

    * Ensure your presentation is professional, logical, and visually appealing.

## Considerations

Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City municipal departments. Your data and analysis need to be presented in a way that is focused, concise, easy to understand, and visually compelling. Your visualisations should be colourful enough to be included in press releases, and your analysis should be thoughtful enough to inform programmatic changes.

## Assessment

Your final product will be assessed on the following metrics:

* Analytic Rigor

* Readability

* Visual Appeal

## Requirements

**Map (25 points)**

* Markers for all bike stations (5 points)

* Station markers indicate popularity by color, size, shape, or some other means (5 points)

* Ability to change marker data based on month and year (5 points)

* Sections are marked by zip code (5 points)

* A write-up on the trends that were discovered while making the map (5 points)

**Visualisations (25 points)**

* 4-10 total visualisations (5 points)

* A total of 2 Tableau dashboards, each dedicated to a specific data discovery (5 points)

* Dashboards are named appropriately (5 points)

* Data is cleaned such that data entry errors are removed and columns are correctly typed (5 points)

* Visualisations can logically be used to explore the data (5 points)

**Tableau Story (25 points)**

* Individual visualisations are used (5 points)

* Dashboards are used (5 points)

* A map is used (5 points)

* Visualisations on the same page are clearly related to one another (5 points)

* The story is informative and easy to navigate (5 points)

**Analysis (25 points)**

* Analysis is written in a markdown file or included in the Tableau Public workbook (5 points)

* Analysis describes the dashboards and any interesting data discoveries contained within them (5 points)

* Analysis on the chosen city official requested map detailing any noticeable trends (5 points)

* The written analysis references specific visualisations and interactive features (5 points)

* The document is written in a manner that a non-technical reader could understand (5 points)

## Resources

BCS Xpert Learning assistant

https://help.salesforce.com/s/articleView?id=001458294&type=1

https://community.tableau.com/s/question/0D54T00000C6GifSAF/a-combined-calculated-field-from-date-and-time

https://help.tableau.com/current/pro/desktop/en-us/maps_options.htm

https://community.tableau.com/s/question/0D54T00000C5emOSAR/is-it-possible-to-add-to-the-pop-up-boxes-that-appear-on-the-map-graph-in-the-dashboard-to-add-more-attributes-instead-of-having-to-click-through-to-the-actual-data-table-while-in-the-dashboard

https://community.tableau.com/s/question/0D54T00000C6XKaSAN/formula-to-convert-longitude-and-latitude-fields-into-post-code

https://help.tableau.com/current/pro/desktop/en-us/maps_custom_territories.htm

https://nyc.streetsblog.org/2023/11/03/electric-avenue-e-citi-bikes-will-double-but-footprint-wont

https://www.theguardian.com/environment/2023/dec/22/ebike-boom-america-sales

## Acknowledgments 

Datasets provided by © Lyft, Inc. 2024 at https://citibikenyc.com/system-data
