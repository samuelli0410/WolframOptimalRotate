# WolframOptimalRotate
Rotate a 3D object to best display its shape and features.

## Description

Given any non-transparent 3D object, it is impossible to confidently discern the exact shape of the object by looking upon it from a stationary, single viewpoint. Due to all the possible configuration of faces that are hidden to the stationary viewpoint, a rotation around the object is most effective in confidently determining the object’s shape. My goal is to create a function that will return a video of the optimal rotation of any given 3D object to illustrate its shape. I chose this project because of my passion for 3D printing and design, as well as my interest in geometry.

## Details:

ResourceFunction["OptimalRotate"][obj]: displays an animation of the 3D object obj in optimal rotation.

ResourceFunction["OptimalRotate"][obj,n]: displays an animation of the 3D object obj in optimal rotation with n points on the rotational path.

ResourceFunction["OptimalRotate"] accepts three-dimensional graphics objects in Graphics3D and MeshRegion.

The more points on the rotational path, the clearer the animation will be for visualizing the shape and features of the object.

n must be a positive integer.
