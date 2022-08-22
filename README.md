## ABOUT ##
This project was completed for EE5271 (Robot Vision) at the University of Minnesota-Twin Cities for Fall 2021.
Contributors: Bharath Sivaram, Isaac Kasahara, & Chase Anderson 

This project used ICP (iterative closest point) and filtering technique to build a 3D model of an object in motion from partial views.
For our case, a backpack was used. However the code can be altered to fit any 3D object of the same size with enough discernable features. 

# Instructions For Running Code (testComputerVisionKinect_rev4.m)
Note: Please run code by section

## 1: Data Collection

The first 3 sections in our matlab code will only run if you have an XBOX 360 Kinect attached and running on the computer.

## 2: Method 1

We included example point clouds from the kinect data capture in the previous section.  Run the first section under this method to display the icp alignment between each frame and the newly transformed 3D model
Run the second section to display the model + movement from the transforms.

## 3: Method 2

We included example point clouds from the kinect data capture in the previous section.  Run the first section under this method to display the build up of out model from the consecutive frames.
Run the second section to display the model + movement from the transforms.
