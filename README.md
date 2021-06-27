# latlong

Hi, 

This application is meant to fetch latitude & longitude from OpenStreetMaps and also from Google Maps

This application fetches the lat longitude data on providing address from the input field or from POSTMAN tool with GET Method only, specifying the address field. 

Results are displayed from both service providers.

File structure:
controller/task.php
models/task.php
models/response.php
index.php
resources/  (Which hold all suportive css pages)

Front End:
I have used HTML CSS page + Jquery + Ajax

Backend
OOP PHP + Curl 
I have used OSM API (Which doesnt require any key)
Google API (Requires a Key)

Exceptions are thrown on certain conditions.

Install:

Download this application in to your localhost directory and you can run it via index page or via post man


Future Enhancement:

Right now app fetches only 1 latitude + longitude data each from OSM & Google Map, app can be modified to fetch multiple data based on the requirement









