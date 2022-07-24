# Surfs_Up

## Project Overview
* In this analysis, we are aggrigating weather data for W. Avy, a potential investor in a surf and ice cream shop, in Oahu, Hawaii. He would like to determine weather patterens for the area before making his investment decision. In order to accomplish this, we will pull historical temperature data for the months of June and December, for W. Avy, to see if this is a viable business for the area. 

## Resources
* Data source: hawaii.sqlite
* Software: Python 3.9.12, Jupyter Notebook 3.1, SQLite 3.39

## Results 

* There is plenty of data received in order to perform reliable temperature calculations. 1700 temperature readings for the June data set ranging from 6/1/2010-6/30/2017 and 1517 temperature reading December data set ranging from 12/1/2010-12/31/2016.

* The minimum recorded temperature in the June data was 64 degrees fahrenheit and the maximum was 85. For Decembers data, the minimum temperature recorded was 56 degrees fahrenheit and the maximum was 83. 

![june_df_desc](https://github.com/BryantKlewer/Surfs_Up/blob/main/screen_shots/june_df_desc.png)
![dec_df_desc](https://github.com/BryantKlewer/Surfs_Up/blob/main/screen_shots/dec_df_desc.png)

* Overall, the temperature is relatively even between the June and December data sets with the average temperature in June being 74.9 and December being 71.0 degrees fahrenheit.

![june_hist](https://github.com/BryantKlewer/Surfs_Up/blob/main/screen_shots/june_hist.png)
![dec_hist](https://github.com/BryantKlewer/Surfs_Up/blob/main/screen_shots/dec_hist.png)


## Summary

* In summary, the average temperature is over 70 degrees fahrenheit between early summer and early winter. Given this information, surfing and ice cream would both be viable business options for W. Avy. The only potenital issue is see in making a business decision with the given data is that there is not enough of it. Having only temperature data for 1/6th of the year is not enough, there is also no incliment weather data, such as precipitation or tropical storms. In order for W. Avy to make a well informed business decision, I would recommend two additional pieces of information: year round temperature averages and year round rainfall averages. This information will allow for a complete picture of historical weather patterns so that W. Avy will know what to expect of this surfing and ice cream shop each month of the year. 
