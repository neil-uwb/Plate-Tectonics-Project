# Plate-Tectonics-Project
Project for B ME 450

https://github.com/neil-uwb/Plate-Tectonics-Project/blob/master/Plate%20Tectonics%20Project.ipynb

Neil Skilton

Dr. Abadi

B ME 450

3/2/2020

# Intro:

The focus of this project from a programming perspective is on learning how to plot geographic coordinates on a map in python. The focus of this project from an ocean engineering standpoint is on familiarizing with the frequency and causes of seismic activity. For this specific project, we will focus on seismic data from the Juan de Fuca Plate from 2010 to 2020. In addition, we will take a closer look at April 2015 to see if there are any anomalies in the data. Finally, we will examine both the divergent and transform regions of the plate to see what patterns are present with respect to magnitude and location along the boundary.
  
# Data Collected:

The first step of this project was figuring out how to ingest the data. Since there was only a need for 2 data sets, I downloaded the data directly off the USGS Earthquake Catalog: one set for 2010 to 2020 and one set for just April 2015. Once the data was ingested, I went to a website where I could make an image of a map specific to the bounding box I specified in my data pulls. This image was then displayed behind both of my plots. The only unique part of my data is that instead of running with changing sizes of circles for denoting the magnitude of the earthquake, I went with a heat map for the magnitude that is paired with a legend on each graph. Given how rare it would be to get very high magnitude data, and low magnitude data was too common, I ingested everything between 2.5 and 10, but the legend for the heatmap only goes between 2.5 and 6. Bellow is a graph showing all the data I used for this project and the image made for all of the plots.
 
![](https://github.com/neil-uwb/Plate-Tectonics-Project/blob/master/Map.PNG)

![](https://github.com/neil-uwb/Plate-Tectonics-Project/blob/master/fig2.png)

# Analysis:

One thing I found quite interesting about this data was how clearly the boundaries were defined. If we compare the graph above with a picture showing the plate, it becomes very clear that these earthquakes tend to be centralized around these boundaries, which makes sense given that is where the most geological disturbances occur.

The one point of confusion that I had came from the lack of intensity. I was under the impression that the intensity along the plate would be a lot higher that what was recorded. Looking at the data above, it appears that getting anything above a magnitude 4.5 is quite rare, which I found surprising.
  
 ![](https://github.com/neil-uwb/Plate-Tectonics-Project/blob/master/plates.png)[3]
 
The image above is also helpful in deciphering the second part of the analysis of this data. Looking at the picture, it appears that there are volcanoes that exist under the water. When these erupt, the expectation is that there is high seismic activity. Looking at the graph below, there is one points off the coast of Oregon that spiked in magnitude. This is where I am guessing that there was a volcanic eruption. This guess was confirmed by a paper that was written on the “Explosive processes during the 2015 eruption of Axial Seamount, as recorded by seafloor hydrophones”. That name should sound familiar as it was one of the OOI locations that we were interested in, which was located off the coast of Oregon.
 
![](https://github.com/neil-uwb/Plate-Tectonics-Project/blob/master/fig3.png)

The last portion of this analysis involves both the divergent and transform boundaries that line the Juan de Fuca Plate. Below are the zoomed in data sets of both regions.

![](https://github.com/neil-uwb/Plate-Tectonics-Project/blob/master/fig4.png)

![](https://github.com/neil-uwb/Plate-Tectonics-Project/blob/master/fig5.png)
 
The graph of the divergent data stands out to me as being a point that is releasing a lot of pressure, like opening a can of soda. Lots of small seismic activity where pressure is being relieved, since that portion of the plate is moving away from the North American Plate. Even when looking at the graph with all the data put together, the high density of low energy seismic activity stands out as a hot spot.

The transform boundary is a lot more confusing to me. The seismic activity here is a lot more sporadic. In my mind, this could be due to the fact that between the plates there may not always be an opening to the core or any form of contact between the two plates, which would limit the amount of seismic activity. This would explain the low density/infrequency of the points, but the scattering of the points still baffles me.
  
# Conclusion:

Given the data above and the analysis provided, I have concluded that seismic activity depends on both where boundaries exist, but also the type of boundaries. Boundaries that see more direct interaction with each other or the hot core below will have more seismic activity, but passing plates will have far less activity, as they may not disturb the ground they sit on or each other. The difference in boundary having an effect on seismic activity is something that I would never have though of, and something I find quite interesting as a possible reason.
 
# References:
[1]     OpenStreetMap. (2020). Export | OpenStreetMap. [online] Available at: https://www.openstreetmap.org/export#map=5/51.500/-0.100 [Accessed 2 Mar. 2020].

[2]   	Dzurisin (2013). Subduction of the Juan de Fuca Plate beneath the North American Pla.... [online] Usgs.gov. Available at: https://www.usgs.gov/media/images/subduction-juan-de-fuca-plate-beneath-north-american-pla [Accessed 2 Mar. 2020].

[3]	    Caplan-Auerbach, J., Dziak, R., Haxel, J., Bohnenstiehl, D. and Garcia, C. (2017). Explosive processes during the 2015 eruption of Axial Seamount, as recorded by seafloor hydrophones. Geochemistry, Geophysics, Geosystems, 18(4), pp.1761-1774.

