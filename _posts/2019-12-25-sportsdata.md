---
layout: post
title: NBA Data Visualization and Virtual Match Simulation
subtitle: Using Dash User Interface to Visualze Player/Team Performance based on 2019-2020 NBA Player Data
image: /img/nba_cover.png
bigimg: /img/nba.png
tags: [Data Engineering, Data Visualization]
---

In this data science project, an entire data science pipeline was built from scratch: Obtaining raw data from website, storing data inside database (MongoDB), retrieving and processing data from database and visualizing data based on users' queries. Specifically, the data we are using is dynamic and it is constantly acquired from the web. We then renew such data into the MongoDB database, making the updated data ready to be renewed. Once a new query is input throguh the dash user interface, our program is able to retrieve the data from the database, calculate the values we need and utilize such data to conduct data visulization. Scuh values are also utilized for calculating the result of virtual matches. The figure below shows the architecture design of our data engineering pipeline.
![](/img/nba_archi.png){:height="49%" width="49%" .center-block :}
Please take a look at our final screencast [here](https://drive.google.com/file/d/1Va7-h8roagSQ0-7eA0EM4iLNC2IY-Zpi/view) (or below) demonstrating the usage of user interface and how this pipeline was designed. The source code can be found at this [repository](https://github.com/data1050projectfall2019/data1050project). You can fork it to your own git repository and run it on [gitpod](https://www.gitpod.io/) or your local environment. The server will be able to automatically start.


<iframe width="560" height="315" src="https://www.youtube.com/embed/Mw5dIwNEuYk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

