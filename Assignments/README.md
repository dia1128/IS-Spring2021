
# Finding Local max/min in non-convex function with Visualization Using Pytorch


## Problems
* Write a pytorch code to find all local max and min values (dy/dx = 0) for the following function 
 y = 3x-6x3-x4+4 when x = [-6,1]

* Write a pytorch code to find all local max and min values for the following multivariate function 
 z = cos(x)sin(y) when x = [-pi,pi] and y=[-pi,pi]


## Local max/min : Animation in 2D
### This problem is solved in two approaches:
* First, where each points are considered and iterated given the boundary of x and collected all the local minimum or maximum points.
* Second, where a point was randomly selected from the range of (x,y) coordinates and the program stopped iterating when it came across the nearest local maxima or minima. The first approach is more time consuming than the second one. 

## Animation

![moving](https://user-images.githubusercontent.com/27954949/111938347-bbc6e100-8a97-11eb-8536-a6a91a7b9f5c.gif)

![moving3D](https://user-images.githubusercontent.com/27954949/118591539-f08aa800-b769-11eb-89a0-16f04b9ce8c3.gif)



