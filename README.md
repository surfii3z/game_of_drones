# Hyperparamters Optimization in game of drones
The approach is inspired by the winner (the report is available on the official website). It is the improve version of genetic algorithm (though)
# Prerequisite
1) Install game of drones binaries following the instructions from the official website
`https://github.com/microsoft/AirSim-NeurIPS2019-Drone-Racing`
2) Install tensorflow object detection API (used for gate detection)
`https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md`
3) python >= 3.6
# Run
Open two terminals
1) for running airsim binaries
```
cd /path/to/AirSim_Qualification
./AirSimExe.sh -windowed -opengl4
```
2) for running hyperparameter optimization
```
cd /path/to/game_of_drones/baselines
python baseline_racer_baseline_GA.py
```
# Result
https://drive.google.com/open?id=1fdOiCOEi4pfexpmxc5TYRRgIfK8mZU0AeVxHSTPYrJ0


	
