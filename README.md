# surfs_up


## Overview of Analysis

This analysis reviews the weather patterns around Oahu, Hawaii to determine if a surf and ice cream shop can sustain steady business year-round. Monthly temperature and precipitation information, sourced from a SQLite database, will help make this determination through SQLAlchemy queries in a Jupyter notebook. Ideally, consistent warm weather and just enough rainfall to keep everything green will provide the optimal conditions for sustaining a surf and ice cream shop.

Paticular insterest is placed on June and December. By comparing the weather patterns on Oahu during these two months, we will be able to reach a conclusion on weather or not to open a surf and ice cream shop.


## Results
Two classes, "measurement" and "station," from the SQLite database provide all the information required to conduct the analysis. Temperature and precipitaction information gathered from the measurement class and location information was assessed through the station class.

### Precipitation
The dataset reveals 9 stations gathering weather information around Oahu and the precipitation measurements they gathered are  between Aug. 23, 2016 to Aug. 23, 2017.

![year_rainfall_plot](https://github.com/jp3tty/surfs_up/blob/main/Images/year_rainfall_plot.PNG)

The plot shows Oahu got over 4" of precipitation on 4 days for the giving period.

The table below shows the average daily precipitation.

![year_prec_table](https://github.com/jp3tty/surfs_up/blob/main/Images/year_prec_table.PNG)

As seen in the table, the average (mean) daily precipitation was 0.18 inches. From the plot and table, we conclude that Oahu was mostly sunny throughout the day and experienced low rainfall.

### Temperature
The yearly average Oahu temperature was found to be 72 degress F with a low of 54 degrees F and high of 85 degrees F.

The frequency of temperature measurements from Oahu's most active measurement station can be seen below.

![year_temp_observed](https://github.com/jp3tty/surfs_up/blob/main/Images/year_temp_observed.PNG)

The negative skew of the indicates that a majority of daily high temperatures on Oahu are higher than the 72 degree F average.

![june_temps](https://github.com/jp3tty/surfs_up/blob/main/Images/june_temps.PNG) ![dec_temps](https://github.com/jp3tty/surfs_up/blob/main/Images/dec_temps.PNG)




* The average temperatures for June and December are above 70 degrees.
* Both months have similar standard deviations in their temperatures.
* Given that the statistics for these months are similar, it is safe to assume Oahu's temperature is consistently above 70 degrees throughout the year.

## Summary





June and December data reinforces the positive business decision.