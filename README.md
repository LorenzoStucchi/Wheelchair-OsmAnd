# Wheelchair profile for OsmAnd

It is possible to insert a routing profile in [OsmAnd](https://osmand.net/) dedicated for the wheelchair. The file is downloadable [here](routing_wheelchair.xml), there is a [guide](https://lorenzostucchi.github.io/Wheelchair-OsmAnd/) (in Italian) that explain how to insert the profile into the app.

## Options of the wheelchair profile

The routing considers only the sidewalks and not the streets, even if it is possible to consider also the residential streets ( highway = road / residential / unclassified / service / living_street ) with the parameter _allow_res_streets_. 

It is considered that it is never possible to overcome a staircase (highway = steps).

Three parameters could be set to describe the wheelchair:
* Width: the parameter _width_wheel_ represents the minimum space needed for the wheelchair to pass;
* Kerb height: parameter _max_kerb_, as the maximum height of kerb that the wheelchair could overcome;
* Inclination of paths: parameter _incline_max_, the maximum inclination that it is possible to overcome;

Also the smoothness of a path influence the time needed, the type of kerb is also considered.