# dsor_simulation
Simulation of DSOR vehicles

## Installation
Create a folder and clone the repo:

```shell
mkdir -p ~/catkin_ws_sim/src
git clone --recurse-submodules [repository_link] ~/catkin_ws_sim/src/.
```

Follow the README at the farol submodule and compile. To launch the code, simply run in different shells:

```shell
roslaunch simulation_bringup start_scenario.launch
roslaunch simulation_bringup start_vehicle.launch
```
