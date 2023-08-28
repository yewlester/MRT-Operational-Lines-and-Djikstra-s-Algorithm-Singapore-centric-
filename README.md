# A WIP project of mine that allows analysis of the MRT lines and stations that exist within the entire SMRT ecosystem
This repository is a small project of mine that allows a deep dive into the operational stations that the Singapore MRT has, and allows analysis of how many stations exist and what are the shortest paths from point A to B. Please click into MRT_Stations.ipynb to take a look at the compiled code.

In this, I am practicing (and also demonstrating) my ability to perform:

1) Web scraping (pd.read_html)
2) Data cleaning (Sorting stations into lines and emplacing 'NA' into cells that don't have a line attached)
3) Data visualisation (Bar chart to show amount of stations in different lines
4) Data analysis using Dijkstra's Algorithm (Calculating the shortest path from one station to another)

I used Jupyter Notebook as my IDE with Pandas, NumPY and matplotlib libraries to enhance the results of my analyses, and also to understand the back-end of how an application like Google Maps calculates for you the shortest distance required for your journey.
