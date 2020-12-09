# Point Location using Kirkpatrick's method. 
An interactive implementation of Kirkpatrick's point location algorithm for CSE(355) (Computational Geometry).  

## Instructions

1) Click within the bounding triangle to create a simple polygon. Than select "Close the Polygon" when finished. 

2) Select "Triangulate the Polygon" to triangulate the polygon as well as the region outside the polygon but inside the bounding triangle. 

3) Select "Find Independent Set in the Polyon" to highlight a set of vertices in the resulting graph. 

4) Select "Remove Independent Set & Re-Triangulate" to remove the highlighted points and re-triangulate the "holes" left by their removal. 

5) Repeat steps 2 & 3 until the coarsest triangulation (the bounding triangle) is reached. 

6) Select a "query point" inside one of the faces of the base triangulation. 

7) Repeatedly select "Step to find the Point" to view each level of triangulation with the triangle containing the query point highlighted in yellow. 

8) Select "Locate Another Point in the Polygon" after scuessful finding the query point.

## Implementation

O(n) space complexity and O(n^2) time complexity for pre-processing the planar graph. O(log n) for point location queries. 
