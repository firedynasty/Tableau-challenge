# Tableau-challenge


### Introduction

The data that I analyzed with Tableau was from the NYC Citi Bike Data.  It is a bike sharing program that has gotten more riders every year since their inception (data up to 2017).  The data set had over millions of lines of code and I used Pandas to clean up the data to plot it out on Tableau.   You can view the public directory here: 

[Tableau](https://public.tableau.com/profile/stanley.tan?fbclid=IwAR29T45FWdEMJtAS6-aYydOjCr67QOCz0BjD6cl1kjd8MLXAYexVWvH2VxQ#!/vizhome/NYCBikeData_16107734162270/Story1?publish=yes)

The first thing I did to explore the data was to get zip codes and see which zip codes had the most trip duration activity.  Since I am new to Tableau, as I was working with the data, I wanted to find out how the data has looked over the years vs. simply for a month(as that is how the data comes in).  

![Image1](https://github.com/firedynasty/Tableau-challenge/blob/main/images/image1.jpg)

To obtain this data from many multiple CSVs, I used Pandas and a forloop to loop to over the data to combine to one big dataframe.  Using the groupby, that was to reduce the size of the dataframe so that Tableau could read it easily. 


![Image2](https://github.com/firedynasty/Tableau-challenge/blob/main/images/image2.jpg)

To explore the data further, I broke the data into viewing the separate genders.   


Historic weather was obtained https://www.ncdc.noaa.gov/cdo-web/ and charted against the graph.  It is interesting to note that as the weather gets better more people bike. 

![Image4](https://github.com/firedynasty/Tableau-challenge/blob/main/images/image4.jpg)



I wanted to see at which hours there is more activity and can be seen in the next image:

![Image5](https://github.com/firedynasty/Tableau-challenge/blob/main/images/image5.jpg)


For public officials who are looking at this data, the map below should be helpful.  Commute hours appear to be the most heavily used time in the system, so officials should make sure that bikes are available for use.  I would imagine in the morning when people are getting out of the subway they are jumping onto a bike or after getting off the ferry (if there is one) because there are two stations near the water that are heavily used for starting and ending a bike ride.  To retrieve bikes that are dropped off, it would be prudent to grab bicycles from heavily used end stations, which could be further explored by time. 

![Image6](https://github.com/firedynasty/Tableau-challenge/blob/main/images/image6.jpg)
