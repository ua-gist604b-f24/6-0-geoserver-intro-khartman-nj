
Q1: What is the URL of the WMS GetCapabilities request? = https://laughing-trout-g476w6q5qqj7fw997-8080.app.github.dev/geoserver/ows?service=WMS&version=1.3.0&request=GetCapabilities 
Q2: What is the URL of the WFS GetCapabilities request? = https://laughing-trout-g476w6q5qqj7fw997-8080.app.github.dev/geoserver/ows?service=WFS&acceptversions=2.0.0&request=GetCapabilities
Q3:  Refer to the PNG file
Q4 What does drawing order refer to? Which layer goes on top, the first or the last layer in the list? Drawing order is referring to the order layers are rendered in when recalled from the server. The Layer that is drawn first is the top layer the bottom is drawn last from the drawing order list
Q5  Refer to the PNG file
Q6: What is the WMS url for the single-tiled request? = https://fluffy-fishstick-69xxjr6jj65h9qv-8080.app.github.dev/geoserver/wms?service=WMS&version=1.1.0&request=GetMap&layers=spearfish&bbox=589425.9342365642%2C4913959.224611808%2C609518.6719560538%2C4928082.949945881&width=768&height=539&srs=EPSG%3A26713&styles=&format=application/openlayers#toggle 
Q7h: What is the WMS url for one of the tiled requests? What is the image size? =
https://fluffy-fishstick-69xxjr6jj65h9qv-8080.app.github.dev/geoserver/wms?SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&FORMAT=image%2Fpng&TRANSPARENT=true&STYLES&LAYERS=spearfish&exceptions=application%2Fvnd.ogc.se_inimage&SRS=EPSG%3A26713&WIDTH=768&HEIGHT=540&BBOX=598013.2737182097%2C4917344.261016253%2C605343.0139664675%2C4922488.440695696
Size = 208 KB
Q8: What is the URL of your coarse resolution sample of a WMTS url? What level does this tile refer to? Notice the differences. What are some of the fields that are unique to this url? = https://cautious-system-wrgxjx7979442pwj-8080.app.github.dev/geoserver/gwc/service/wmts?layer=spearfish&style=&tilematrixset=EPSG%3A4326&Service=WMTS&Request=GetTile&Version=1.0.0&Format=image%2Fpng&TileMatrix=EPSG%3A4326%3A11&TileCol=868&TileRow=518
Level = Level 11
Unique fields= Speare fish 
Q9: In the zoomed-out URL, what are the TileCol and TileRow? =
https://cautious-system-wrgxjx7979442pwj-8080.app.github.dev/geoserver/gwc/service/wmts?layer=spearfish&style=&tilematrixset=EPSG%3A4326&Service=WMTS&Request=GetTile&Version=1.0.0&Format=image%2Fpng&TileMatrix=EPSG%3A4326%3A10&TileCol=433&TileRow=258
TileCol=433
TileRow=258
Q10: In the zoomed-in URL, what are the TileCol and TileRow?https://cautious-system-wrgxjx7979442pwj-8080.app.github.dev/geoserver/gwc/service/wmts?layer=spearfish&style=&tilematrixset=EPSG%3A4326&Service=WMTS&Request=GetTile&Version=1.0.0&Format=image%2Fpng&TileMatrix=EPSG%3A4326%3A17&TileCol=55486&TileRow=33202
TileCol=55486
TileRow=33202
Q11: Why are they so different for the same location in the map?
 There are so many different locations and zoom levels in this map due to duffrent coarseness and zoom levels so that the end user can recall the information how they need. and the proper extent is covered in the map.
Q12: Is there a difference in the TileMatrix? %3A is an HTML encoding for a colon, :.What does the number after EPSG:4326 mean? 
Yes there is a difference when encoding using the TileMatrix %3A this helps determine the specific map coordinate system that you want to recall. The number after EPSG:4326 means the zoom level of that coordinate system for the map. 
