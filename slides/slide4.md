# Visualising Real-World Spatial Data with Maps
<!-- .element: class="absolute top-left" style="font-size:1.5em;"-->
<b> Taxi Availability Map using the LTA Datamall API</b>\
\
My interest was piqued when I saw in a taxi booking app that the user could see \
where the taxi was in real-time. I was curious about how taxis were distributed \
across Singapore and how all the taxis were shown on the map. When I learnt that \
LTA allowed developers to access some traffic-related data, I decided to build a \
website that would plot available taxi locations on the map as well as automatically \
update the information as time passed.\
\
To build the website, I used HTML, Javascript, and CSS for the frontend and fetched \
the live location data using the LTA Datamall API. To display the locations, I used \
[leaflet.js](https://leafletjs.com/) together with [OpenStreetMap](https://www.openstreetmap.org/) to show it as an interactive \
map. The website also shows the total number of available taxis and the time of the \
last data update. 
<!-- .element: class="absolute top-left" style="top: 8%"-->