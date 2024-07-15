# Dataset for "Integrated routing and scheduling problem for the airborne deployment of heterogeneous multistatic sonar networks in a coverage scenario"


As a complement to the research paper entitled "Integrated routing and scheduling problem for the airborne deployment of heterogeneous multistatic sonar networks in a coverage scenario", we here provide all 15 instances used. 

These instances, located in the ```data/instances``` folder at the root of this directory, comprise all the following files: 
- ```DEM.asc```: Digital Elevation Model (DEM) of the Area of Interest (AoI) in ESRI ASCII format;
- ```name_DEM.dat```: name of DEM in the global instance catalog (c.f. [global catalog](https://zenodo.org/records/10530247));
- ```sonobuoys_pb1.dat```: number of buoys of each type for problem no. 1 (+ lifetime in minutes); 
-  ```sonobuoys_pb2.dat```: number of buoys of each type for problem no. 2 (+ lifetime in minutes); 
- ```positions.dat```: positions of the various buoys after solving problem no. 1 (input data for problem no. 2); 
- ```max_coverage_rate.dat```: maximum coverage rate (%) after solving problem no. 1
- ```base.dat```: geographic coordinates of naval base (latitude, longitude);
- ```mission_duration.dat```: mission duration, in minutes.

In addition to this, we provide the ```performances.dat``` file in the folder ```data```, which contains all the performances, i.e. Range of the Day (RoD, km), for each of the compatible source-receiver pairs.