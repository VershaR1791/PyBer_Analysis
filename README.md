# PyBer_Analysis
Create data visualizations using python data, pandas library and Matplot library

## Overview of the analysis
As a newly hired Data analyst at a python based ride sharing app *PyBer*, this analysis requires creating data visualization to help find insights about the app access and ride charges based on city type. The exploratory analysis on large data stored in csv files will show the relationships between the type of city, total number of drivers and the total fares. Further, the analysis will also determine average fare per ride and per driver based on city type.

## Results 
The PyBer data summary based on the different city type is as seen in the below snahpshot.

![Pyber_data_summary](https://user-images.githubusercontent.com/84694664/126920818-9a71a7ca-aaf3-4bb8-b5f6-8404735af7d7.JPG)

- The total number of rides, drivers and fares is highest in the *'Urban'* areas and lowest in the *'Rural'* areas.
- The average fare per ride and per driver is highest in the *'Rural'* areas.

Using the *'pivot'* function based on date of the trip and the type of the city, the total fare is determined.

![Fares by City Type](https://user-images.githubusercontent.com/84694664/126920782-5c0fbe92-c099-489f-8bee-8faa79f7400e.png)

- The total fare is highest for the Urban cities
## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
- The average fare per ride and per driver is very high in the rural region compared to the urban and suburban areas. *'Pyber'* should implement promotional events such as discount offers, coupons codes that can be shared with friends/family to get first ride free and to encourage more drivers to drive to or from the rural areas. 
- There is an unsual spike in 3rd week of March total fares in every city type possibly due to spring break and more students using *'Pyber'* services during the holiday. The management can introduce special event for students during spring break such as pool with friends.
- The driver to ride ratio is lowest in rural areas indicating there is less driver availability in the rural regions. *'Pyber'* should partner with a hiring platform to enroll more drivers in the rural area.
