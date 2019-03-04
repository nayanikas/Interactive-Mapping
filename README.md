Reflective Analysis 

This map highlights boundaries of wildland fires in conterminous United States, Alaska, Hawaii and Puerto Rico for the period of 1984 though 2016. All fires reported are greater than 1,000 acres in the western United States and greater than 500 acreas in the eastern U.S. It aims to assess the frequency, extent and magnitude (size and severity) of all wildland fires (includes wildfires, wildland fire use, and prescribed fires). Through the colour scheme, this map allows the user to extrapolate if wildfires (size and severity) are starting to become more common (effects of climate change?) or if prescribed fires in a certain region can cause negative feedback effects (e.g controlled fires can cause more severe natural wildfires in the future). 

Choosing a darker background allowed for each fire boundary to show up more clearly. National parks, buildings, roads and city boundaries were set to merge into the background as it is not completely pertinent to the information displayed which allows for a more sound visual heirarchy. Opactity was set to 0.7 which allows for polygons to be placed over each other without blocking the previous years (if there was an overlap). Different decades had different colours associated with them (e.g Dark red for 80's, red for 90's etc..). In terms of interactivity, I chose to use a 'time slider' so that the map user can shift through each year to see fires of that specific year only (colour associated too). I also added to the option to see wheather fires were either - Wildfires, Wildland Use Fires or Prescribed Fires for each year. 

Firstly, I had issues with the zoom of the initial map. Due to the large volumes of data, mapbox only allowed me to create a map where data could only be viewed at a zoom-level of 4. This was not ideal as it doen't allow the user to view burn patterns on a bigger scale (original map was slightly smaller than state view), to overcome this, the map had to be simplified to allow for greater zoom levels. However, even with the current map's zoom level, Alaska, Hawaii and Puerto Rico is not shown (user had to drag to the state). Another issue is that for some reason, the event listener doesn't update the time slider, so while it works, the year doesn't change as you move the slider. And finally, the buttons that highlight the fire type can be unreliable. 

There is a lot of room for improvements - in the future, I would like to loop the slider instead of the user having to drag it each time this would allow for a map that 'flows' better. It would also be nice to combine the map with other factors. For example, studies have shown that droughts can increase the danger of damaging fires, so mapping out regions that have on-going droughts (can be done though a choropleth map). 


Due to the size, the map takes a hot minute to load!
Find the map here: https://nayanikas.github.io/Interactive-Mapping/BurnSeverity.html



![alt text](https://raw.githubusercontent.com/nayanikas/Interactive-Mapping/master/Screen%20Shot%202019-03-03%20at%208.56.45%20PM.png)
