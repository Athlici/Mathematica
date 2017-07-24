Mathematica Binder
==================

Collection of the Mathematica Notebooks I wrote over the years; published in the hopes of them being useful.
Feel free to contact me if you have questions or end up using one of them.

Table of Contents
=================

  * [RectanglePacker](#RectanglePacker)
  * [Miscellaneous](#Miscellaneous)

RectanglePacker
===============
Encoding of the 2D-Bin-Packing problem with orientations as a Mixed-Integer-Program.

This is then solved optimally by Mathematicas LinearProgramming function, but due to the hardness of the problem, the immaturity of the encoding, or the weakness of Mathematicas solver it is basically intractable for n>7.

![6 random rectangles](https://github.com/Athlici/Mathematica/blob/master/RectanglePacking/RectPacking.png)

Algorithms
==========
A few basic algorithms, implemented for my edification and published to subvert asinine homework of the type "use algorithm X to solve problem instance Y".

Simplex
-------
Optimise a linear program.

CYK
---
Decide word-membership in a CNF context free language.


Miscellaneous
=============

Enumerate Graphs by Vertex Degrees
----------------------------------
Simple recursive function to, given a list of vertex degrees, enumerate all graphs with those degrees.

In the current, primitive, version it gets swamped by isomorphic graphs.
