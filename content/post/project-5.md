---
date: 2021-06-02
description: ""
featured_image: ""
tags: []
title: "Players Scouting Tool"
---

Scouting Tool is an application that lets you search, find, and analyze football players within the Top 5 European Leagues. The application is built with the python library “Streamlit”. The open data is scraped from Statsbomb via FBref for the season 2017-18 to current. Based on the selected season the app loads and processes the data from the webpage. The numbers are adjusted per 90 minutes and for the moment defensive metrics are not adjusted by the possession of the squad. If you do not select a new season, the load function would not take place since the data is saved in a repository inside the application. 

The objective of the app is to display the data in an elegant and efficient way using tables and visualizations. The app is divided in three components:


•   Advanced search

•   Compare

•   Player Profile

The advanced search component allows to filter the pool of players to create your own shortlist based on specific metrics and export it. It is planned to incorporate a similarity model so you can filter players based in a correlation of metrics. Shortly an article will be written about this. 

The next component allows to compare players based on a template for a selected position. Each template contains the metrics that are considered essential for each position. If you do not want to compare against a player, you can do it by the average of all the players of each metric in a selected league. The final output is a radar plot and a table. The radar boundaries represent the maximum values of production by all the pool of players in each metric. This can be improved by using the top 5% of all statistical production by the whole pool of players or even better by position, instead of using maximum values as boundaries. Later, it will be added the option to choose a radar with percentiles.

Finally, in the player profile component, a detailed report of a specific player would be displayed. It is not finished yet, but the idea is to incorporate heat maps such as shots maps. 

[Link to Players Scouting Tool](https://player-scout-tool.herokuapp.com/)