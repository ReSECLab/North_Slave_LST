# North-Slave-LST
The North Slave LST dataset is a lake surface temperature dataset for 535 lakes across the North Slave region of Canada

The North_Slave_LST folder contains sample dataset of certain lake in the from of tar.gz files.


FILE NAMES AND MEANING
Sample File name:
AcastaLake_19840428_ -115.564 _ 65.3783_-5.90_ -7.10_-6.50_17482_099.nc

Section of Name	Explanation of the section 
Lake name(AcastaLake) :- Name of lakes were predominantly derived from the Water file-Lakes and Rivers polygons data from Statistics Canada. Lakes unknown names were prefixed “No_Name_Lake” and a number.

Date(19840428) :- The date in the NetCDF file is in the format “YYYYMMDD” and represent the corresponding date the Landsat scene was captured.

Longitude (°)(-115.564) :-	The longitude represents a known longitude predominantly located at the centre of a lake when plotted against the latitude in decimal degrees. 

Latitude (°)(65.3783) :-	The latitude represents a known latitude predominantly located at the centre of a lake when plotted against the longitude in decimal degrees. 

Minimum Temperature (°C)(-5.90) :-	This is the minimum LST value retrieved from a lake for a given date which is the coldest part of the lake 

Maximum Temperature (°C)(-7.10) :-	This is the maximum LST value retrieved from a lake for a given date which is the warmest part of the lake 

Mean Temperature (°C)(-6.50) :-	Mean LST value calculated from the number of LST pixels retrieved for a lake on a given date.

Number of LST Pixels(17482) :-	Number of LST pixels retrieved on a given lake for a given date.

LST pixels coverage (%)(99) :-	Number of LST pixels retrieved the lake for a given date divided by the total number of pixels representing the lake.
