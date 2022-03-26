Author: Yang Yuqi & Li Bowen, raw main.py is extracted from James Stewart
This File takes sets of data consists of 3 points which form triangles
Where slices can be built between triangles, the goal is to link all slices
together form a 3D version of the dataset given
See below for assignment reference:

# Build the triangles between two slices
#
# Slice 0 is above (at a higher y) than slice 1.
#
# Within each slice, the vertices are ordered in the right-hand
# direction with respect to the y axis.  That is, when looking from
# the origin up the positive y axis, the vertices will appear in
# CLOCKWISE order.
#
# When working with vectors, your code will be MUCH cleaner if you use
# the provided vector functions: add(), subtract(), scalarMult(),
# dotProduct(), crossProduct(), length(), normalize(), and
# triangleArea().  USE THESE FUNCTIONS AS NECESSARY.  DO NOT WRITE
# COMPONENT-WISE OPERATIONS IN YOUR OWN CODE WHERE THESE FUNCTIONS
# COULD INSTEAD BE USED.  DOING SO WILL CAUSE YOU TO LOSE MARKS.

