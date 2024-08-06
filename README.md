# RaceAgainstTheCar

<img src="https://repository-images.githubusercontent.com/145345464/710bf900-7a04-11eb-8f2f-e5b9ec73c6b2">
Many are not aware how easy it is to win. Not only let them know, but let them feel too. And tap into their general competitiveness ...

Many people work a day a week to pay for their car, but here I'll only focus on traveling time of cars compared to bicycles.
I often found myself faster by bike, while planners like Google Maps predicted differently, which made me wonder why. Part is that these planners are (like most of the world, especially the USA where these most used planners come from) focusing on cars and quite often doing rather poorly for bikes (missing lots of bike paths and taking crazy, sometimes dangerous detours), but also ...
The top speed of cars is of course higher than that of bikes, but never reached. Regular modern <b>car navigation</b> takes maximum allowed speeds into account and delay because of traffic. However time to park and additional travel because of it is normally not taken into account, so it <b>is unrealistic taxi navigation</b>. What's also often not taken into account is that people on bicycles have a wider range of cruise speeds nowadays and can sometimes take little walking shortcuts. This project will try to compensate for these omissions.

Comparing isochrones ...
========================
Isochrones are lines showing how far you can get in any direction in a certain timespan, from a specific start point.
For a specific bicycle cruise speed the isochrones can be combined with those of the car into lines where one mode overtakes the other. Now there are 2 choices for adding additional lines:
- Lines that show time differences (between car and bike) for the same bicycle cruise speed. Which results in a different image for every speed.
- Lines that show for several bicycle cruise speeds where they are passed by cars. Which results in 1 static image.
Both options are nice measures for 'the race against the car'.

Staticly ...
=============
Put such a static picture under the nose of drivers, especially where they mingle, hoping to start a discussion. Perhaps a giant print above the door of <a href="https://duo.nl/open_onderwijsdata/primair-onderwijs/scholen-en-adressen/">all elementary schools</a>, for waiting parents to see. Or on the floor of a big in- or outdoor playing space of that same school. Or similar spots at big employers

... or Interactively
====================
The more your brain and body interacts with information, and the more it is connected to face (of own kids needing a future?) or place, the better it sticks. Maybe hook up the speed of a (hometrainer) bike to control the speed-dependent image? As long as you don't move the hometrainer bike a lot, within a certain speed you don't need to recalculate the image, so you don't need much processing power, or a screen even (a stack of prints and someone to operate will do).


If you can't win by bike yet
============================
The fastest option might be walking into your homeoffice or garden with your notebook or VRglasses instead of going to an office altogether, but as both meeting people and biking is healthy exercise you could also combine it with taking a train. Shorter driving times are helped by less cars a lot more than by expensive extra car infrastructure, so either way vote for bike-friendly parties.

Towards implementation:
=======================
- [car/bike ecological comparison](https://www.omnicalculator.com/ecology/car-vs-bike)
- I have a [Tacx](https://tacx.com/) hometrainer bike
- [openrouteservice.org](https://openrouteservice.org/)
- [iso4app.net](https://www.iso4app.net/net/)
- [OSM isochrones](https://wiki.openstreetmap.org/wiki/Isochrone)
- [osmnx](https://osmnx.readthedocs.io/en/stable/)
- [my isochrone question on GIS StackExchange](https://gis.stackexchange.com/questions/389494/how-to-osm-isochrone-center-transportmode-maxspeed-time-color-transparency)
- https://medium.com/@Urbica.co/hello-galton-e6e07a7164b7#effa

Possible interested parties:
============================
- https://www.tubantia.nl/enschede-e-o/goan-nieuwe-reisapp-voor-twente-regelt-vervoer-van-deur-tot-deur~a18f9f54/
- https://www.bloomberg.com/news/features/2022-07-30/how-ai-is-giving-real-world-streets-a-virtual-makeover

Other bike ideas:
=================
- A threeweeler bike that can takes turns fast Joiny https://www.tubantia.nl/hengelo/ms-patient-martin-is-trots-op-zijn-sportieve-driewieler-zo-n-scootmobiel-maakt-je-meteen-10-jaar-ouder~a0f0b5a2/
- Cycling supported by air pressure
- Cargobike with overhead solar panels providing shadow
- An ultralight body/tent around your bike to make it look like rediculous sized cars like for example a Ram Van or a F-150
- https://www.facebook.com/people/2020-Virtual-Bike-Race/100067891359095/
- ...
