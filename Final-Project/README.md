<div style="text-align:center"><h2><b>Clustering Tehran venues based on each district & neighborhoods</b></h2>
<h5>By Ali Yamini</h5>
<h5>29 September 2019</h5>
</div>

***1.	Introduction***
<p>
<b>1.1	Background</b><br><br>
Tehran is a very big city in terms of the number of districts and population. Tehran has over 22 districts with a population of 12 million people(2018) which makes it the second of most populated cities in the middle east after Istanbul. A big city like Tehran has lot’s of neighborhoods and many venues.<br><br>
<b>1.2	Problem</b><br><br>
Unfortunately a big city like Tehran doesn’t have a good analysis of their venues. For example a tourist doesn’t know the best places in Tehran based on each neighborhood so In this project we are going to cluster each neighborhood in 22 districts of Tehran based on their top 10 venues in each neighborhood.<br><br>
<b>1.3	Interest</b><br><br>
The output of this project can be very helpful for tourists or anyone who is interested in finding the best venues of Tehran. 
</p>

***2.	Data acquisition***
<p>
Surprisingly, Tehran doesn’t have a clean database for data scientists. As a data scientist you have to pretty much collect everything you need yourself. So my first step would be to collect districts and neighborhoods data from here and put each one of them in a row of my Dataframe. After this step I will collect the coordinates for my neighborhoods to plot my data on a map. Coordinates will be collect by Geopy library. For the Final step, I will get my venues data based on each neighborhood using Foursquare API which surprisingly has a valuable database for the city of Tehran.
</p>
