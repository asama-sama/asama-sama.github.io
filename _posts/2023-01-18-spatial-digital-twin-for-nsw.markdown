---
layout: post
title:  "Spatial Digital Twin for NSW"
date:   2023-01-18 10:17:00 +1100
categories: projects
---
Over the past 6 months at Monash University, I have been developing a Digital Twin based on several NSW public open data sources, and also view them historically. The types of data that we are collecting includes air quality, greenhouse gas emissions, weather, traffic volume, traffic incidents and crime.

Storing this data into a database, we allow users to view these sources historically as well as compare them against each other. 

Given two data sources e.g. air quality and traffic incidents, we can compare the different categories of these sources and find the correlation values between different categories.

That is, if air quality has "CO2", "NO2" and "Ozone" as categories, and traffic incidents has "breakdown", "crashes" and "heavy traffic", then we can find the correlations between each of the categories between air quality and traffic incidents.

If we see a particularly high (or low) correlation, we can then select these categories to compare in our graph and visually see what this correlation represents, and potentially find some interesting information.

There is a lot of further work to be done on this project but the ultimate goal is to use this application for smarter, better cities.

More information and code is available on this project [here](https://asama-sama.github.io/dt-server/).

You can go [here](https://www.youtube.com/watch?v=pQ8-jVs7FBk&ab_channel=AamirCheema) to watch me give a demo on the app.

Special thanks to my team on this project:
* Aamir Cheema
* Ammar Sohail
* Anwar Ulhaq
* Mohammed Eunus Ali

![Screenshot of digital twin comparison view](/assets/images/spatial-twin-screenshot.png)