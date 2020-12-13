# Surfs_Up

## Overview
This is an analysis using basic python and sqlite database, corresponding to the challenge of finding out if weather data can help out about choosing a particular spot, "Oahu", for a sound investment decision of a surf and ice-cream shop. The analysis was done based on two data points concentrated as the month of the year (June and December)

## Results

The results show the following key differences:
- The mean temperature between the two points is slightly different, with June being 3 degrees warmer (74) than December (71)
- The minimum temperature for December is significantly lower in December (56) than in June (64), which might make December a bit chilly for business.
- There is less data points for December (1517) than June (1700). One reason might be that some stations are closed during December.


<img src=resources/june_temps.png></img>
<img src=resources/dec_temps.png></img>


## Summary

From the analysis performed, it would seem that Oahu enjoys an overall warm weather for surfing to be feasible. However, the below two queries can show some more insight as to whether December is the coldest month or not and how many days the lowest temperature for December is observed.

Checking for the month with lowest temperature shows that April might be the lowest temperature month, with temperature going as low as 53.

<img src=resources/Qr2.png></img>

Checking for the lowest temperature count shows that the lowest temperature for December (56) occured 12 times overall. 

<img src=resources/Qr1.png></img>
