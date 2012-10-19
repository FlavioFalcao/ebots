# ebots
Exploring evolutionary robotics through simulation experiments.

# Dependencies
  + Python 2.7
  + NumPy 1.6.2
  + matplotlib 1.2.x
  + MongoDB 2.2.0
  + PyMongo 2.3
  + Blender 2.63.a
  + MORSE 0.5.2

# How to Run
Open two separate terminal sessions and go to the `ebots/` directory. In one terminal execute `morse run stages/stage_name.py`, and in the other `python experiment-X.py`. A Blender window containing the simulation should appear.

# Experiments
## Experiment 1: Wall Follower
To follow a wall, or in a more general sense, to follow the contours of an object, is an important behavior for autonomous mobile robots. Robots operating in an unknown, unstructured environment use their sensors to perceive the surroundings and plan their motions or trajectories accordingly. [Read more...][wall-follower]

[wall-follower]: https://github.com/yarox/ebots/wiki/Experiment-1:-Wall-Follower
