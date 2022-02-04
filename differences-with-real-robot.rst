Differences with Real Robot
###########################

The following data is available on a real Nao, but not available in the simulated robot:

* Sonar Sensors
* Touch Sensors
* Battery Status


The simulation server **does not provide camera images**. Instead, **simulated vision data**
including balls, robots, and field lines are published.
The simulated vision in the simulator does not report field features (Corners, Circle, T-Junctions,
X-Junctions, etc.)