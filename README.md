# kuburin-web
Kuburin is a web-based system that provides funeral things in indonesia.
Designed by Alfi Nurfazri || .
Builded by Naldi Nashih Ulwan || naldinashihulwan@gmail.com.


This system was build with JavaScript as its main language, NodeJS as its runtime and PostgreSQL as the DBMS.
The system uses Geo tracker from Mozilla, leaflet map, OSRM and also leaflet-routing-machine for additional feature.
Simple Additive Weighting method is implemented in the system to make a great recommendation features for users to choose their funeral location.

There are 3 dependencies :
1. PTSP, provides confirmation system for individual identification.
2. Bank, provides confirmation system for finance.
3. OSRM (implemented into docker),  provides Geo Location tracking, calculation, and routing.
