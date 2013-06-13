jsOctree
========

A Javascript octree using threejs.

[Click here](http://mochapanda.com/jsOctree/octree_example.html) to view the example.

This octree uses [threejs](http://threejs.org/), but could easily be modified to use your own WebGL wrapper (the only thing used are the Vector classes and Mesh for visualization).

How to tune the octree
------

Maximum entities per node:
`Octree.prototype.entities_per_node`

Maximum depth:
`Octree.prototype.max_depth`

Reimplement `Octree.prototype.intersects` function to suit your needs (eg. to intersect OBB, convex hull or else).
