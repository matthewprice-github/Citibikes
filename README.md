# Citibikes
Mapping NYC Citibike data with Tableau 

## Overview 
The purpose of this analysis was to visualize NYC citibike data in order to better convince investors that a bike sharing program in Des Moines is a solid business proposal. Being able to better visualize key data points like location of trip starts, location of trip stops, trip duration, and peak usage times, we are better able to present a complete story with data, which can be understood quickly and easily. 

## Results 
The Tableau Citibike visualizations can be found here: [Link to Dashboard](https://public.tableau.com/app/profile/matthew.price6357/viz/Citibikes_16266635568570/CitibikeStory?publish=yes) 

* **Most Popular Starting Locations**: A map of NYC outlining the most popular trip start locations for citibikes. Manhattan clearly has the highest density of trip starts, which makes sense, as it has the highest density population. There also could jsut be more available bike stations in Manhattan. 
* **Most Popular Ending Locations**: Almost exactly the same map as starting locations, which indicates that the majority of Citibike trips end in the same location where they begin, and the trips are circular. 
* **Checkout Times**: Outlines count of bike trips by trip duration. We can see that virtually all trips are under an hour, with the mode being 6 minutes. 
* **Checkout Times by Gender**: The same visual as before but broken out by gender. We see the volume of trips skew towards male, but male and female riders show the same behavior with trip duration. 
* **Trips by Weekday per Hour**: Shows peak times by hour for citibike trips. It makes sense that during the week peak usage is before and after working hours. On the weekend the trips are more evenly distributed thrughout the day. 
* **Trips by Gender (Weekday per Hour)**: Same view as above but split by gender. Again the volume is skewed towards men, but women and men share the same behavior here as well. 
* **User Trips by Gender by Weekday**: Outlines trips by days of the week, broken down by subscription level and gender. Here most of the observations are in the Male Subscriber bucket, so it is hard to glean patterns compared to the other bucket. On the side panel we can toggle off different cateogries to see more apples to apples comparisons. Looking at just male and female subscribers, they once again share the smae behavior, with trips more often happening during the weekday (except Wednesdays, curiously).  

## Summary

This data indicates a number of key points at a high level. It appears that average trip duration is very short. Almost all citibike trips are less than an hour, which the majority of trip durations being under 10 minutes. We can see that trips are often very localized, with trips starting and stopping at the same location. We also see that the peak usage on weekdays occur during commuting hours, while on weekends the trips are more evenly distributed throughout the day. 

Given all of these indicators, it appears that Citibikes in NYC are being used for short, convenient trips by the local population: commuting to work, running to the store, picking up food, for example. While men appear to be using Citibikes more than women, their trip behaviors do not appear to differ. One thing that could be useful to see for further analysis are the location of bike stations. We can see that Manhattan is clearly the highest trifficked area for Citibikes, buts Manhattan likely just has the highest density of bike stations. Finding usage data controlling for bike station volume would bring more clarity to which communities are utilizing the bikes at higher rates. 


