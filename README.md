Its a very simple and small code using two functions only, about which we will talk in details later. 
First lets get started with the pre-requisites.

## Pre-Requisites
-folium: Folium is a powerful Python library that helps you create several types of Leaflet maps. 
The fact that the Folium results are interactive makes this library very useful for dashboard building

## Installing libraries
     pip install folium
     
*Now lets get started with code

## Importing libraries
     import folium

## Taking coordinates
     locate = folium.Map(location=[longitude,latutude])
     
Here 'locate is the name given to the location whose coordinates are fetched using folium.map() function.
The user needs to fulfil longitude and latitude respectively before running the program.

## Saving as HTML file
     locate.save("location1.html")
     
Locate is saved using the save() function in a custom HTML file (here named as location1.html)
