# Average of Air Quality throughout the years

1st Step: Divide every 'x Days' columns by number of measured days per 'Year' ('Good Days','Moderate Days', etc. / 'Days with AQI' ).
1st Step: Get the average value of each 'State' by getting the average of all 'County's by 'Year' (Group by 'Year' and 'State' aggregating remaining columns by mean value).
2nd Step: Get the average value of the entire country by getting the average of all 'State's by 'Year' (Group by 'Year' aggregating remaining columns by mean value).

![AQI_throughout_years](plots/AQI_throughout_years.png)
