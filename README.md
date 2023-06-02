# DistanciasIES

Project to help professor elaborate a prefered destination list of all high schools in Madrid.
Take KML archive with lat/long coordinates for all high schools.
Calculate distance and travel duration to all of them.

<br> -First version using OpenRouteService Matrix API. Only driving option.
<br> Input is address
<br> Output is a complete list of all high schools sorted by travel duration.

<br> -Second version using Google Maps Distance Matrix API. Includes transit and driving modes, taking traffic at departure time into account.
<br> Input is address, transport mode and departure time.
<br> Output is a complete list of all high schools sorted by travel duration. 
