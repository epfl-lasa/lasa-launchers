# KUKA LWR @LASA Simulation 
This package runs a simulation of the KUKA LWR robot in the LASA lab (EPFL) with the velocity/position controllers provided the IAI lab (Uni Bremen).

In order to run this code, install the following packages beforehand:
 
```
sudo apt-get install ros-indigo-pr2-mechanism-model ros-indigo-pr2-controller-manager ros-indigo-control-toolbox ros-indigo-pr2-mechanism-controllers
```

In addition to this, you need to have two more repos from code-iai in your workspace:

```
$ git clone https://github.com/code-iai/iai_control_pkgs
$ git clone https://github.com/code-iai/iai_common_msgs
```
