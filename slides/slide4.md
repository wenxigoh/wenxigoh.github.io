# Visualising Real-World Spatial Data with Maps
<!-- .element: class="absolute top-left" style="font-size:1.5em;"-->
<b> Taxi Availability Map using the LTA Datamall API</b>\
\
My interest was piqued when I noticed that taxi booking apps could display the \
real-time locations of nearby taxis. I was curious about how taxis were distributed \
across Singapore and how all the taxis were shown on the map. When I learnt that \
LTA allowed developers to access some traffic-related data, I decided to build a \
website that would plot available taxi locations on the map as well as automatically \
update the information as time passed.\
\
To build the website, I used HTML, JavaScript, and CSS for the frontend and fetched \
the live location data using the LTA Datamall API. To display the locations, I used \
<a href="https://leafletjs.com" target="_blank">leaflet.js</a> together with <a href="https://openstreetmap.org" target="_blank">OpenStreetMap</a> to show it as an interactive \
map. The website also shows the total number of available taxis and the time of the \
last data update. 
<!-- .element: class="absolute top-left" style="top: 8%"-->
![photo](https://ik.imagekit.io/bwxixksh1/grab-taxi-map)
<!-- .element: class="absolute fragment fade-left" style="top:3%; left:73%; width:24vw;">