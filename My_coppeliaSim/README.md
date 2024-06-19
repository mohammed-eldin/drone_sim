# Coppelia Rail Simulation
Simulation of a UAV on a rail section. The scene to use is `base_drone_scene`.

## Notes for use 
ROS custom messages need to be added manually in coppelia: You can use the coppelia of this repository directly or you can replace the file 'libsimExtROS.so' of your coppelia with the one in this repository.

## How to run it
Download the repo in your linux PC, execute the script `coppeliaSim.sh`

## Note
This simulation is part of my master thesis project, for more info see the correspondant chapter of the written paper.

LINK ALLA TESI

## Other thesis repos
This simulation must be used with another repo of the thesis project:

- The ROS package for the interface, control and recognition of the rail: <https://github.com/LorenzoCausa/UAV_Rail_inspection>

To use the method on a real UAV see also:
 - The bridge application between Linux computer and the drone controller: <https://github.com/LorenzoCausa/bridge_DJI_ROS>
