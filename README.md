# Voronoi Algorithm
This is a program that implements the Voronoi algorithm to generate a Voronoi diagram from a set of points and triangles.

## Requirements
The program uses the following Python libraries:

- `matplotlib`
- `numpy`
Make sure you have these libraries installed before running the program.

## Usage
1. Make sure you have the points.txt and triangulation.txt files in the same directory as the Python file.
2. Run the voronoi.py Python file.
3. A graph with the points and generated triangles will be displayed.
4. The vertices and edges of the Voronoi diagram will be calculated.
5. The user will be prompted to enter the coordinates of a point for interpolation.
6. The result of the interpolation will be displayed based on the selected type.
## Input Files
The program expects two CSV format text files to represent the points and triangulation:

### points.txt
The file should have the following format:
id,x,y,z
1,0.5,0.5,1.0
2,0.7,0.3,2.5
3,0.2,0.8,0.9
...

Each line represents a point and must contain four fields separated by commas: the point ID, the x and y coordinates, and the z value.

### `triangulation.txt`

The file should have the following format:

id,p1,p2,p3
1,1,2,3
2,2,4,5
3,3,6,7
...

## Result

The program will generate a graph with the points, triangles, vertices, and edges of the Voronoi diagram. In addition, it will perform a z-value interpolation for a user-entered point, depending on the selected type.

Enjoy the Voronoi algorithm!!!
