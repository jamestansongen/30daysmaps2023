# 30daysmaps2023

This is my contribution to the #30DayMapChallenge for November 2023.\
About the #30DayMapChallenge , check out <https://30daymapchallenge.com/> !

## Introduction

### About me

I am a postgraduate student current undertaking a MSc in Urban Spatial Science at UCL (expected graduation = August 2024). \
My background is in geography/geographic information systems/remote sensing. My Bachelor's was a Joint-Degree between the National University of Singapore and University of North Carolina-Chapel Hill. \
My other interests include hiking, drone piloting/photogrpahy and board games.

### Day 12: South America

During my time at UNC-Chapel Hill, I had the opportunity to take a module dedicated solely to the Galapagos Islands. The islands, known for their unique and diverse ecosystems, played a pivotal role in shaping our understanding of evolution, as famously observed by Charles Darwin. The physical environment of the Galapagos provides an intriguing backdrop for studying geological processes and ecological diversity. On the other hand, examining the human environment on the islands allows us to examine the delicate balance between conservation efforts and sustainable development. Hoping to eventually get the opportunity to visit the Islands someday!

![Galapagos](Maps/Day12.png)

Data Source: [OpenGeoData FCD](https://geodata-fcdgps.opendata.arcgis.com/datasets/fcdgps::curvas-de-nivel-30m/explore) \
Image 1: [Iguna](https://pixabay.com/photos/iguana-galapagos-reptile-nature-894465/) \
Image 2: [Turtle](https://pixabay.com/photos/turtle-huge-the-galapagos-islands-4205792/) \
Image 3: [Albatross](https://unsplash.com/photos/white-and-black-bird-on-brown-stick-during-daytime-50Joxuqtp3s)

### Day 11: Retro

Was inspired by 1980s/1990s Japanese City Pop to make a neon map of Japan. Selected/exported groups of polylines from the boundary and changed each of their colour and glow to create the vibes.

![NeonJapan](Maps/Day11.png)

Data Source: [Geospatial Information Authority of Japan](https://www.gsi.go.jp/kankyochiri/gm_japan_e.html)

### Day 10: North America

I decided to make a heatmap of UFO sightings in 2016 🛸. The interactive map can be accessed at [UFO 2016 Sightings](https://lnkd.in/gDHwu6P8) 

![CapeTown](Maps/Day10.png)

Data Source: [kaggle](https://www.kaggle.com/datasets/utkarshx27/ufo-sights-2016-us-and-canada/)

### Day 9: Hexagons

I generated a hexagon map followed by a count of points in polygon in QGIS. The maps are informative in showing the distribution and number of outlets for various chains across the US.

![Hex1](Maps/Day9a.png)

![Hex2](Maps/Day9b.PNG)

![Hex3](Maps/Day9c.PNG)

![Hex4](Maps/Day9d.PNG)

Data Source: [Esri](https://hub.arcgis.com/maps/f12d05c1b4054fffa34f4ae8e7599f17)

### Day 8: Africa

Decided to follow [Helen McKenzie's](https://www.helenmakesmaps.com/post/how-to-joy-plot) tutorial on making a joy plot/ The tutorial was easy to follow and the output was really satisfying.

![CapeTown](Maps/Day8.png)

I made a joy plot of Cape Town, South Africa as it was the first African city I visited back in 2003. Table Mountain with an elevation of 1086m (bottom left) offers a breathtaking panorama of the city and it is home to adorable dassies (or rock hyrax). I would definitely recommend visiting!

Data Source: [USGS](https://earthexplorer.usgs.gov/)

### Day 7: Navigation

"Suspended between sea and sky, battered by the waves and the wind, lighthouses mark the battle lines between the elements. They guard the boundaries between the solid human world and the primordial chaos of the waters; between stability and instability; between the known and the unknown." - Where Light in Darkness Lies: The Story of the Lighthouse (Veronica della Dora, 2022)

![Click to view animated GIF](Maps/Day7b.gif)

Data Source: [Edinburgh DataShare](https://datashare.ed.ac.uk/handle/10283/2425?show=full) 

### Day 6: Asia

I decided to choose Singapore, my home, for the theme and the maps were designed according to some of the conversations I had with other people (including Singaporeans) after moving to London. The captions are not meant to take a shot at anyone but present the conversations in a humourous way. Do take the maps with a pinch of salt. The font used is called Singapore Sling which is a gin-based sling cocktail.

![Asia1](Maps/Day6a.PNG)

![Asia2](Maps/Day6b.PNG)

![Asia3](Maps/Day6c.PNG)

![Asia4](Maps/Day6d.PNG)

![Asia5](Maps/Day6e.PNG)

Data Source: [data.gov.sg](https://beta.data.gov.sg/collections/1621/datasets/d_142fd1a4da4e367a1a8323613af2f272/view), [GADM](https://gadm.org/download_country.html)

### Day 5: Analog Map

Drew various maps by hand, based on the Pokemon series.

![Analog](Maps/Day5.jpg)

While I lack the artistic talent, I would recommend looking up King of Maps, a map shop in Cusco, Peru. Their hand-drawn maps are hands down some of the most aesthetically pleasing and detailed maps I seen. I also appreciate how there is greater South American representation in their maps.

Data Source: Nintendo

### Day 4: A bad map

What makes a bad map? Is it the absence of good analysis and/or good visualisation?. Overall, poor analysis with good visualisation is probably more dangerous.

The map below is a mashup of random datasets I could find. Visually it is repulsive and I do not think much useful insights could be gleam from it.

![Everything](Maps/Day4.png)

Data Source: Numerous Sources

### Day 3: Polygon

Using data from The Food and Agriculture Organization of the United Nations, I extracted the most consumed starch in each country for 2021. 

![Most consumed starch meme](Maps/Day3a.png)

I then plotted two versions: a normal one and one where the polygons are filled with images of starches.

![Most consumed starch actual](Maps/Day3b.png)

Data Source: [Food and Agriculture Organization](https://www.fao.org/faostat/en/#data/FBS)

### Day 2: Lines

Extracted a hiking route from AllTrails and convert all the points into a polyline. I then georeference the file in QGIS against a basemap. The line changes colour with elevation which shows how the final push to the submit will be the most intense. I chose Snowdon as it is a hike I hope to conquer in my time here as well.

![Yr Wyddfa (Snowdon) via Miners' Track and Pyg Circular](Maps/Day2.png)

Data Source: [AllTrails](https://www.alltrails.com/en-gb/explore/trail/wales/gwynedd/yr-wyddfa-snowdon-via-miner-s-track-and-pyg-circular)

### Day 1: Points

I accessed and downloaded my Instagram Post data (refer to https://lnkd.in/eabi6Nz8 on how to get your own data & screenshot for how the data looks like. Only posts which were geotagged will have coordinates). 

![Instagram Post Raw Data](Maps/Day1b.png)

I subsequently extracted out the coordinates of my posts before plotting the points and setting the background to Instagram's colour scheme. From the map, most of the points are concentrated in Singapore (home) and US (where I spent a year abroad). 

![JTSE's Instagram Post with Coordinates](Maps/Day1a.png)

Given that there is more attention to the replicability of research, I will also be sharing the code I use and most of the datasets (except when it involves data privacy).

Data Source: Author's own
