# Citi Bike Analytics

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

## ETL

The data was extracted from [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage and the chosen period was the month of October from the year 2021 and 2022 (files: JC-202110-citibike-tripdata.csv & JC-202210-citibike-tripdata).

These files were transformed by loading them into Pandas dataframes, the compatibility was checked and then merged utilising the concat function into a a final "2021-2022_df.csv"

This final file was then loaded into Tableau to proceed with the analysis and uncover the determined phenomenom.

## Phenomena to be analysed

* What are the most popular stations for Starting trips and the busiest periods?
* How has the type of ryde share changed in the period of time selected, the rider type, and overall ride amount?

## Findings

### Phenomenom 1

Overall and consistenly over both years,  the most popular stations are in respective order:

- Grove St PATH
- Hoboken Terminal - River St & Hudson Pl
- South Waterfront Walkway - Sinatra Dr & 1 St
- Hoboken Terminal - Hudson St & Hudson Pl

And the busiest periods during the week are around stardard working schedule, there prior to 9AM and post 5PM is when most activity occurs.

As for the weekend, Saturday has more traffic flow than Sunday and the busier period is between 9Am and 5PM.

### Phenomenom 2

From comparing both years, a increase of 5.76% in the use Electric Bikes is seen and the membership base for both the classic and the electric bikes has significantly increased.

In terms of the overall ride amount, it only increased by 796 rides.

### Interesting findings

* (Slide 3-4)  From visualising the maps for all starting-ending trips, we can see tha most trips remain within Jersey City. A minimal amount of them cross over to Manhattan or beyond into NYC
