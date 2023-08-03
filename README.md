# Screw Detection

This C++ package locates and classifies screws and holes in camera images. The computer vision model is particularly simple as a random tree with only five features is generated. This makes the application simple and understandable while maintaining a good classification accuracy. The package was developed within the European project [SHAREWORK](https://sharework-project.eu/) and is part of a scientific publication at the European Signal Processing Conference (EUSIPCO) 2023.

Dependencies:
- OpenCV
- ROS (ROS wrapper only)

The original repository containing the library is located [here](https://github.com/nilsmandischer/sharework_screw_detection). Refer to the [screw_detection_ros](https://github.com/nilsmandischer/sharework_screw_detection_ros) for an example how to use this library.

Refer to this repository as:
Mandischer, Nils; Döbler, Sebastian; Corves, Burkhard
A Simple Screw-Hole Discrimination Pipeline for Deployment in Autonomous Manufacturing
European Signal Processing Conference (EUSIPCO), Helsinki, Finland, 2023.
DOI pending
