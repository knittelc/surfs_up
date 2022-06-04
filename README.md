# Surfs_up
PythonData environment includes: jupyter notebook, VScode, python , github, Anaconda navigator, flask, sqlite

# Purpose 
The client, W Avy, is looking to start a surf and ice cream business in Oahu, Hawaii.  He hired me to complete an analysis using a sqlite data file from different weather stations around Oahu.  Specifically the temperature data for June and December are included in this analysis for 2017 in Oahu.

The temperature, precipitaion, station numbers, and reportin activity of those stations are included in the data set.  The benfit of this code, is it can be manipulated to gather data for any time frame: month-by-month, for a year in the past.  It can also be pulled for just precipitation, just temperatures, or both to see coorelations.  Using these types of data and being able to turn them into lists, means any statistical data included in the python and pandas packages can be run on the set.

# Results:
The results were put into dataframes and then using the numpy describe function:  all kinds of mathmatical statistics can be shown quickly.  The number of data for both months are pretty close with June at 1700 and December at 1517;  It is also a great statistical amount as the minimum and maximum temps as well as the standar deviation and quartiles, giving the ability to analyze in one quick look rather than having to scroll through tables of data.

-- Some slight differences between June and December in Hawaii are the minimum and maximum temps:  With December's low at 56 and high at 83; June's low at 64 and high at 85.  Showing the band of weather that Hawaii sits in is pretty minimal in its fluxuation.  

-- The Average(mean) temperature for June is 74.9 and when looking at the quartiles they are all in the mid 70s (1st qtl: 73, mean: 75, 3rd qtl: 77) with a range of just 11 degrees (max temp - min temp); 

-- While December shows some slightly colder temperatures with the average(mean) at 71.04, and a bit more of a range with (1st qtl: 69, mean: 71, 3rd qtl: 74) with a range more than doubling Junes at a 27 degree swing.

![June Temps](https://user-images.githubusercontent.com/102183530/172026284-a9239439-45ae-4fbd-9675-666fac9768f6.png)
![Dec Temps](https://user-images.githubusercontent.com/102183530/172026286-dfce218e-c149-4d21-a2ca-3b49cc9b534e.png)

# Summary:

Recommendations for W Avy, would be that based on the initial look at data Hawaii looks like the perfect place for ice cream year-round.  A coupld other queries would be do continue to pull monthly data and be able to compare a month by month statistical analysis.  Of course the data could be grouped by month and turned into a line or bar graph, a box and whisker would give the best information as far as temperature goes.  I would also suggest the same analysis for precipitation.  Hawaii may have a rainy season, and other options could be added to the shop at these times, or converted like rain gear sold; hot chocolate on days below 60, etc.  I think being able have more information from other islands could also help in the expansion markets.  The other data I would recommend scraping or an API for is the surf data and combine them with the weather data.
