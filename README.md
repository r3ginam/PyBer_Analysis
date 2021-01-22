# :red_car: PyBer Analysis :blue_car:

## Project Overview

This project seeks to summarize ride-sharing data by city type (urban, suburban, and rural) for a company named PyBer. The vizualizations depicted in the **Results** heading were created using Matplotlib and Pandas. The **Summary** aims to give suggestions to decision-makers at PyBer. 


<details>
 <summary> Resources </summary>

- **Software:** Python 3.9.1, Jupyter Notebook 6.0.3, VS Code 1.52.1
- **Data Sources:** [PyBer_ride_data.csv](https://github.com/r3ginam/PyBer_Analysis/blob/main/Resources/PyBer_ride_data.csv), [city_data.csv](https://github.com/r3ginam/PyBer_Analysis/blob/main/Resources/city_data.csv)

</details>


## Results 

<p align="center">
  <img src="analysis/Fig1.png">
</p>
_Note: Circle size correlates with driver count per city, while each dot represents a different city._

The chart above shows that Urban cities have the highest volume of rides on average, yet the lowest average fares. The highest fares in the dataset are in rural cities, but rural cities have the lowest amount of total rides. 


<p align="center">
  <img src="analysis/Fig2.png">
</p>

The boxplots depicted above show that urban cities have the greatest variance in the number of rides, while rural cities have the smallest variance. This dataset also shows that there is one outlier in the urban ride count data. The average number of rides in urban cities is 24 rides, which is 4 times greater than the rural ride count (6 rides).


<p align="center">
  <img src="analysis/Fig3.png">
</p>

Above, the boxplot shows that the average fare for rural rides is greater than the urban rides' average and the upper quartile limit, meaning that about 3/4 of the fares for urban cities are less than the rural cities fares. The boxplot also shows that there are no outliers in this dataset. Suburban rides have a smaller range of fares than either of the other two city types. 


<p align="center">
  <img src="analysis/Fig5.png">
</p>

While rural cities had the highest _average_ fares, urban cities still had the highest percent of _total_ fares, with 62.7% of the total. 


<p align="center">
  <img src="analysis/Fig6.png">
</p>

This pie chart aligns closesly with the previous chart, showing that 68.4% of the total rides correspond to urban cities.


<p align="center">
  <img src="analysis/Fig7.png">
</p>

With the addition of this pie chart, we can conclude that 2.6% of all the drivers gave 5.3% of all the rides (see the yellow sliver of this graph and the last one). The salmon colored piece of this chart and the last indicate that 80.9% of drivers gave 68.4% of the rides. This could indicate that fewer drivers are needed in urban areas, and slightly more are needed in rural and suburban areas.


<p align="center">
  <img src="analysis/fig8.png">
</p>

This graph shows the total fares over time for January to the end of April 2019. All three city types have a spike in total fares in late February, and then dip back down in early March. 


## Summary 

In conclusion, the data team has the following recommendations for addressing disparities among the three city types:
 
 :small_orange_diamond: Keep the amount of drivers in rural cities the same beccause as it stands, they are generating a higher percent of fares than they have drivers as proportionally compared to urban and suburban cities.
 
 :small_orange_diamond: Market your service to people in urban cities, where there are the most drivers in order to create more demand for the service. 
 
 :small_orange_diamond: Add drivers in suburban cities where you are currently earning nearly 1/3 of your total money.

[For a look at this project's Jupyter Notebook, please click here.](https://github.com/r3ginam/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)
