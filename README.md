# landmark-detection-and-tracking

Implementation of a simultaneous localisation and mapping (SLAM) algorithm in a simulation of a moving robot. The robot moves (with some motion uncertainty) in a 2D environment with several randomly placed landmarks which it must sense (with some measurement uncertainty) to both determine its own position and map out the landmarks in the environment as it moves. SLAM is achieved through the use of the [Kalman filter](https://en.wikipedia.org/wiki/Kalman_filter).

A comparison between actual and predicted robot/landmark positions (after 50 simulated steps and measurements) is shown below.

<img src="https://github.com/callumcanavan/landmark-detection-and-tracking/blob/master/images/example.png" alt="drawing" width="450"/>

I completed this project as part of the Udacity Computer Vision nanodegree which provided the blank notebooks and several other functionalities. Algorithm implementations and experiments with parameters/inputs were completed by myself.

# Depends
```
numpy seaborn
```
