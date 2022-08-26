# PyBer-Analysis - Module 5 Challenge

## Overview of the Pyber analysis:

This week, students were introduced to Matplotlib, a powerful library that works directly with Python, Pandas, Numpy and SciPy. Matplotlib provides high-performance charting and plotting capabilities, thereby making it possible for the analyst to produce impactful data visualizations, including line charts, bar charts, scatterplots and pie charts. In addition to gaining a familiarity with these tools, students were given a real-world simulation to see how Matplotlib can be used to present data to senior managers. The ***PyBer Analysis*** model incorporates key concepts and skills development that will help students build a foundation in Matplotlib. These include:

- Getting acquainted with the Matplotlib library
- Creating charts using two Matplotlib methods for graphing data – 1) MATLAB’s plotting syntax and functionality and, 2) an object-oriented interface
- Developing line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib
- Adding, modifying and formatting features of Matplotlib charts
- Learning how to add error bars to line and bar charts
- Determining mean, median, and mode using Pandas, NumPy, and SciPy statistics

The ***PyBer Analysis*** simulation model offers a real-world example where Omar, your boss, assigns a project for you to analyze ride-share data across cities grouped into three city types: Urban, Suburban and Rural. Using Python and the libraries listed above, your job is to create insights and analysis that highlights the differences in ride-sharing data among the different city types including total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 


## Summary of Results:  

Based on the analysis, Urban cities have the most Rides and the most Drivers, but the lowest Average Fare per Ride and lowest Average Fare per Driver. On the other hand, Rural cities have fewer Rides and fewer Drivers, but have the highest Average Fare per Ride and highest Average Fare per Driver. Suburban cities fall between Urban and Rural on all four metrics. 

![](https://github.com/vjtrom/PyBer-Analysis/blob/main/analysis/Cities_Summary.png)

**Given these metrics, Total Fares can be calculated in two ways:**

1)	Total Rides x Average Fare per Ride, and
2)	Total Drivers x Average Fare per Driver

When multiplying these out, it is shown that Urban cities produce the most Revenue (Total Fares) at $39.9k / (63%), followed by Suburban cities at $19.4k / (30%), and Rural cities at $4.3k / (7%), 

Total Revenue across all cities is $63.6k. The Average Fare per Ride across all three city types is $26.75 and the Average Fare per Driver across all three city types is $21.37. 

![](https://github.com/vjtrom/PyBer-Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary:

Based on the data, here are three recommendations that might be considered:

1.	**Increase Urban Fares to drive more revenue** - Depending upon relative price inelasticity (i.e., price increases don’t materially affect the number of Rides), increase the Fares in Urban cities in order to boost Revenue. As an example, a rate increase of 10% in Urban cities will boost overall Revenue (Total fares) by $4.0k or 6.3%.

2.	**Increase # of Rural and Suburban Drivers to drive more revenue** – Assuming that demand remains the same (i.e., rides per driver remains the same), increase the number of drivers in both the Rural and Suburban cities. Increasing the number of drivers in these two city types by 10% will boost overall Revenue by $2.4k or 3.7%.


3.	**Lower Suburban Fares to drive more demand** – Since Suburban Fares per Ride are 26% higher than Urban fares per Ride, try lowering them to increase demand (i.e., the number of rides). For example, if lowering Suburban Fares per Ride by 10% from $30.97 to $27.87 can increase the total Suburban rides by 20%, then overall Revenue will increase by $1.5k or 2.4%.

**Implementing all three of these recommendations would increase Revenue by $7.9k or 12.4%, from $63.6k to $71.4k.**


