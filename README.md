# Drone-Simulator1
The main goal for this project is to try find good solution of small drone, flying inside indoor building without getting hit and crash. The project fully autonomous 2d drone simulator, this simulator is trying to be realistic as much as it can, with lidar sensors,gyroscope sensor ,optical flow sensor and speed sensor. We add a little bit noise to each sample to make it more realistic approach. Basic API with real-time info and also manual controlling. We also implemented kind of area mapping when the drone fly. This project written in Java.

we added Energy Escape,shortest way back home and Direction. 

in Energency Escape -  we added to the drone the ability to turn immediately if it is in danger, as a result it will not crush into the wall.

in shortest way back home  - we cuculated the shorthest path by adding edges between the nearest points on the flight and using Dijkstra algorithm.

in Direction -  to return home it chnges the angle between itself and the next point.
