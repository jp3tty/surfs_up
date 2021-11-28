# surfs_up


## Overview of Analysis

This analysis reviews the weather patterns around Oahu, Hawaii to determine if a surf and ice cream shop can sustain steady business year-round. Monthly temperature and precipitation information, sourced from a SQLite database, will help make this determination through SQLAlchemy queries in a Jupyter notebook. Ideally, consistent warm weather and just enough rainfall to keep everything green will provide the optimal conditions for sustaining a surf and ice cream shop.

Paticular insterest is placed on June and December. By comparing the weather patterns on Oahu during these two months, we will be able to reach a conclusion on weather or not to open a surf and ice cream shop.


## Results
Two classes, "measurement" and "station," from the SQLite database provide all the information required to conduct the analysis. Temperature and precipitaction information gathered from the measurement class and location information was assessed through the station class.

The dataset reveals 9 stations gathering weather information around Oahu and the precipitation measurements they gathered are  shown between Aug. 23, 2016 to Aug. 23, 2017.

![year_rainfall_plot](https://github.com/jp3tty/surfs_up/blob/main/Images/year_rainfall_plot.PNG)


## Summary

Average yearly precipitation table:
![year_prec_table](https://github.com/jp3tty/surfs_up/blob/main/Images/year_prec_table.PNG)


Frequency of measure temperatures for Oahu:

![year_temp_observed](https://github.com/jp3tty/surfs_up/blob/main/Images/year_temp_observed.PNG)


June temperatures:

![june_temps](https://github.com/jp3tty/surfs_up/blob/main/Images/june_temps.PNG)


December temperatures:

![dec_temps](https://github.com/jp3tty/surfs_up/blob/main/Images/dec_temps.PNG)


June and December data reinforces the positive business decision.