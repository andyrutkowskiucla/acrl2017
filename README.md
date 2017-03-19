## A Geospatial Mural
 

[Slides](https://slides.com/andyrutkowski/deck/live)


###Data:
[Google Drive] (https://drive.google.com/drive/folders/0B0GLYH70A2T7RDhyU1ZSMC1qZjQ?usp=sharing)

LA Murals 

Download Zip Shapefile of LA Neighborhoods.

 
###Hover code for CARTO:  
```
<div class="CDB-Tooltip CDB-Tooltip--isLight">
  <ul class="CDB-Tooltip">
<p><img width=100 src={{image_url}}></p>
  </ul>
</div>
```
##Toolkit

###Latlong and Geocoding
[Best latlong courtesy of UCLA's Yoh Kawano] (http://getlatlon.yohman.com/)

[Fun geocoding macro] (https://github.com/nuket/google-sheets-geocoding-macro)

### How to 
Bonus Odyssey.JS
Bring your CARTO visualization into Odyssey.JS and tell a story.

Use the following string to bring in your CARTO map:

http://username.cartodb.com/u/username/api/v2/viz/key/viz.json

Insert your username in both places where you see "username" and then use the key # which is the # between "builder" and "embed"

https://andyrutkowskiucla.carto.com/builder/6f637d56-fd6e-11e6-a253-0e233c30368f/embed

[Great David Rumsey Hack courtesy of Stace Maples](http://mapninja.github.io/CartoDB_Odyssey_Tutorial_for_Story_Maps/) Search for Rumsey and follow the directions.

Here is an example with a Rumsey map as well as a CARTO map:

```  
-baseurl: "http://georeferencer-0.tileserver.com//266b60e098fda1ddbe521ebff0e4d8676a549302/map/CGtnosESWB2NnsgVyjmQc5/201411301752-7AINSs/affine/{z}/{x}/{y}.png"  
-title: "Odyssey example FTW"
-author: "CartoDB"
-vizjson: "http://andyrutkowskiucla.cartodb.com/u/andyrutkowskiucla/api/v2/viz/6f637d56-fd6e-11e6-a253-0e233c30368f/viz.json"  
```
###Select Resources
Excel Workshop
[Excel Tutorial](https://github.com/ALADataViz/ala2016workshop/wiki/Excel-Tutorial)
###Reading 
[Collections as Data LOC](https://blogs.loc.gov/thesignal/2017/02/read-collections-as-data-report-summary/)
