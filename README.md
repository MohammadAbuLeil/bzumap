# BZUmAPP-Android App

#Authors-info
Jehad Nasser - 1122084 <br />
Masoud Hababah - 1112098 <br />
Ammar Ghosheh - 1111494 <br />
Mohammad Abu Leil - 1112217

#Abstract
We decide to build a mobile application (Android) which increase student's productivity, and give visitors the best of joy by finding the shortest path between any two locations inside the university campus. No need for asking people and get lost anymore.

A lot of applications provide us with navigation services, such as Google-map, waze...etc, these applications are easy to use and have tons of features. But inside the university campus there is a lot of limitation so here we go. we will take advantages of Google's APIs to achieve that.

#About the JSON File
We are going to use Google Direction API, response will be in JSON, and request as shown in the next URL, it will have two sections of parameters,first one will be the format of the output(Response) and we are going to use JSON. The other section of parameters will be:

Origin: The address, textual latitude/longitude value, or place ID from which you wish to calculate directions.

Destination: The address, textual latitude/longitude value, or place ID to which you wish to calculate directions.

Key: It's the application's API key.

And there's more options..

Request general format: 
https://maps.googleapis.com/maps/api/directions/output?parameters
 
Example, shortest paths between Louvre Museum & Tour Eiffel:
https://maps.googleapis.com/maps/api/directions/json?origin=48.857708,%202.293996&destination=48.860901,%202.337668&key=AIzaSyDE-hob-Gny6J0oHg1SapzQkpqokKCYnC8

#Service 
it is in another repository called: webServiceCourse.
link: https://github.com/JehadNasser/webServiceCourse

#Client
we just add tow file to this repository: bzumap
they are DirectionFinder.java AND Place.java 

#Demo video will be sent via email

Thank you 


Copyright © 2016
