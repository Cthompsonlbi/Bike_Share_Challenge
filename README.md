# Bike_Share_Challenge
Module 14
## Overview of Project:

The overview of this project is to create a visually stimulating story using Tableau that will inform and maintain the attention of the individuals reviewing the data  They will be able to flip through pages that will overlay information regarding Citi-Bike bike sharing business located in New York City and see if there is a potential use case in Des Moines Iowa.  We will achieve this by modifying the dataset using Python, Jupyter Lab, and Tableau.

### Purpose:
The purpose of this project is to create a data analysis through Tableau with direction from Kate to create attractive visualizations pulled from the dataset taken from a New York City set to help investors see the possibility of a successful launch of a bike share service in Des Moines.  The end product will be informative and draw up parallel between the two cities, while highlighting some of the more obvious differences.  Then a summary will be provided with suggestions of additional data that could be utilized to help the investors make a formed decision.

* A brief summary of the project will be written throughout the rest of this document but, the full report can be seen by accessing the link below.

[link to Tableau Data Story](https://public.tableau.com/app/profile/chad.thompson/viz/BikeShareChallenge_16434053059240/RideShare?publish=yes)

One of the drawbacks that Des Moines has starting a bike share business when compared to New York City is it's population.

* By referring to the images below, you can see how the two cities differ but, you will also notice some similarities.

![NewYorkDem](Resources/NewYorkDem.png) 
![DesMoinesDemo](Resources/DesMoinesDemo.png)

As you can see, population is the biggest thing to take into consideration.  NYC has 8.5 million people and a population density of 28,000/sq. mile. Des Moines has only 213,000 and a population density of 2400/sq. mile.  With a population size and density like NYC, you will have access to more customers and there will be more locations in a "bikeable" range.  However, the median age of the two cities are roughly the same. Des Moines has a male to female population of 1:1.  While NYC has a male to female population of .9:1. It will become evident later in this report as to why that may be beneficial to Des Moines.

Another topic to consider would be the weather and how Des Moines and New York City Compare.

* The following two screenshots highlight that average temperatures and rainfall for both cities.

![NYC_Weather](Resources/NYC_Weather.png)
![DesMoinesWeather](Resources/DesMoinesWeather.png)

As you can see by from the information above, the weather profiles for both cities are quite similar.  Des Moines does have slightly less rainfall than NYC, which could allow for more "bikerideable" days.

Now onto the data pulled from the datasets provided.  After plotting the data, we can see the majority of the bike rentals were done by individuals who are on a subscriber plan.  This is good news for Des Moines as it shows that the usuage rates of the bike share service in NYC is impacted very little by tourism. It is locals that are using the service.  Also, the majority of the users of the service are males which, is good news for Des Moines as their male to female ratio is more evenly split than the ratio of NYC. 

![addMapandLayer](Earthquake_Challenge/resources/addMapandLayer.png)

* Now the code below, allows us to access created maps to pull into our webpage for use in our display.  The API links below is what is displayed when the user changes map selection.

![maplayers](Earthquake_Challenge/resources/maplayers.png)

* The snippet below shows the use of d3 GeoJSON to access a JSON file and pull it into the webpage for use.  The snippet below shows code used to access the JSON file for earthquakes with a magnitude of 4.5 or greater.  There were two other d3 GeoJSON's created to access the data for tectonic plates and all earthquakes in the past seven days.

![d3JSONfileAccess](Earthquake_Challenge/resources/d3JSONfileAccess.png)

* Below you will find the use of a function that controls the styling of the GeoJSON data added for earthquakes in the past seven days. It controls the size, shape, and colors of the circles added for each earthquake.

![stylingfunctionAllEarthQuakes](Earthquake_Challenge/resources/stylingfunctionAllEarthQuakes.png)

* Now, let's repeat this but, using a function that controls the styling of the GeoJSON data added for earthquakes in the past with a magnitude of 4.5 or greater. It controls the size, shape, and colors of the circles added for each earthquake.

![stylingfunctionMajEarthQuakes](Earthquake_Challenge/resources/stylingfunctionMajEarthQuakes.png)

* This snippet below adds a popup functionality of magnitude information and location to each point that was plotted and styled from the functions above:

![PopupControl](Earthquake_Challenge/resources/PopupControl.png)

## Results:

The result is a visually appealing webpage with nice functionality.  It is user friendly and inviting and has the look and feel of well thought out and designed webpage.  It allows the user to interact with the webpage to modify the type of map and the information that overlays these maps.  It delivers upon all of Basil and Sadhana's request and requirements.

## Summary:
This was an interesting project, and I learned a lot.  I see many opportunities to use what I learned from this project with my current position at my company in my current role.

Something that would be an interesting add-on to this project is the addition of a GeoJSON layer for volcanoes.  Agreed, that volcanoes do not fall in the focus of this project, which has its focus on earthquakes but, it would be interesting to see the correlation between earthquakes, tectonic plates and volcanoes.  Perhaps it is something that I could circle back after bootcamp and try myself.
