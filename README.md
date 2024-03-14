# Data Visualization Project

## Data

The data I propose to visualize for my project is a real-time feeds of the earthquake data generated by [USGS.gov](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). This dataset contains the data of earthquakes that happened on earth in the past 30 days.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Plot earthquakes on the world map to show:
   - If seismic activity majorly happen along the edge of tectonic plates?
   - Which part of the earth has the most seismic activity in the past 30 days?
 * Is there any correlation between the magnitude of earthquake and the depth of earthquake?
 * Are there any interesting patterns of the earthquakes at the region with the most seismic activity?
 * Make interactions such as:
   - Brushing (to select cirlces)
   - Zooming (to zoom in and zoom out on the map)
   - Dragging (to rotate the map)
   
## Sketches

![image](https://github.com/Ljz2018/dataviz-project-CS573-proposal/blob/master/Sketch01.jpg)

How is the data visualized:

* Make a world map.
* Add tectonic plates boundries onto the world map.
* Use circles to represent the earthquakes. Plot the earthquakes on the world map according to its longitude and latitude.
* Circle sizes will be based on the value of magnitude of the earthquakes.
* Colors will be added to the circles to show the depth (or time) of the earthquake.

What are the interactions:

* Use tooltip to show infomation (including Magnitude, Location, and Depth) about each earthquake when hover on to the circle.
* Associate each circle(earthquake) with its own webpage(a url) at USGU.gov. By clicking the circle, the user will be directed to the information page of this earthquake.
* Add brushing and zooming in this dataviz to select ceritan earthquakes on tha map. And make a line chart of the seleceted earthquakes to check if there are any intereting patterns.
* Add dragging in this dataviz to rotate the world map.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a world map with earthquakes plotted onto it. 

[![image](https://github.com/Ljz2018/dataviz-project-CS573-proposal/blob/master/Screen%20Shot%2001.png)](https://vizhub.com/Ljz2018/32391bf1ef224afa9cf55c1efcbb75e0)

A scattor plot of time vs magnitude. The color of the dots represent the depth of the earthquakes.

[![image](https://github.com/Ljz2018/dataviz-project-CS573-proposal/blob/master/Screen%20shot%2002.png)](https://vizhub.com/Ljz2018/6f179af027ab4495b08506720de46bed)

## Open Questions

Previous questions:

* How to pull data from an API
* How to associate url with the cirlce in data viz
* How to rotate the angle of a 2D map

Thanks to Professor Kelleher. He helped me on solving the above questions.

More questions to add:

* Any ideas of what other plots or charts that I can make from this set of data?

(describe any fear, uncertainty, or doubt you’re having about the feasibility of implementing the sketched system. For example, “I’m not sure where to get the geographic shapes to build a map from this data” or “I don’t know how to resolve the codes to meaningful names” … Feel free to delete this section if you’re confident.)

## Milestones (6 weeks to go)

Week 1:

* Add dragging to rotatet the angle of the map.
* Add colors to the circles.
* Use data from the API for the scatter plot.

Week 2:

* Add tooltip on circles
* Add zooming 

Week 3:

* Add brushing to select circles on map.
* Correlate brushing selected circles with the scattor plot.

Week 4:

* 

Week 5:

*

Week 6:

* Record the vedio presentation of the final project.


