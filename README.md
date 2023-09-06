# An analysis of existing operational MRT railway network stations and their lines
This is a WIP project of mine that takes the Wikitable dataset from https://en.wikipedia.org/wiki/List_of_Singapore_MRT_stations to allow the calculation of the shortest route between two stations.

In this, I am practicing (and also demonstrating) my ability to perform:

1) Web scraping (pd.read_html)
2) Data cleaning (Sorting stations into lines and emplacing 'NA' into cells that don't have a line attached)
3) Data visualisation (Bar chart to show amount of stations in different lines)
4) Calculating the shortest path between 2 stations using Dijkstra's Algorithm

I used Jupyter Notebook as my IDE with Pandas, NumPY and matplotlib libraries to enhance the results of my analyses, and also to understand the back-end of how an application like Google Maps calculates for you the shortest distance required for your journey.
