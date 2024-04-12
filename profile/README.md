# Code repository for 2nd semester Java programming at UCN
Author: [Jakob Farian Krarup](mailto:jfk@ucn.dk) 😊

> This repository contains exercises, stubs and solutions for understanding 
> coding against databases, data structures, software design patterns and algorithms.
> It also contains code samples relating to [Java game programming](https://github.com/UCN-programming-2-JFK/JavaGameProgrammingCodesamples/tree/master), in case you would like to start a side project to elevate your coding skills.

## Part 1 - Databases

[Sample DAO architecture project](https://github.com/UCN-programming-2-JFK/SampleDaoArchitectureProject)  
Sample project for working with databases using the DAO pattern (Data Access Objects)
The project includes some best practices like defining interfaces for your data access classes to lower coupling and simplify testing.  
  
  
##  Part 2 - Data structures and algorithms

[Recursive folder size calculator](https://github.com/UCN-programming-2-JFK/RecursiveFolderSizeCalculator)
recursively finds the size of a folder including all subfolders and files
  
[Tree structures and composite pattern](https://github.com/UCN-programming-2-JFK/TreeStructures)
two solutions: 
- Binary tree
  - shows the two classes necessary for creating a Binary Tree data structure and implements code to print tree preOrder, inOrder and postOrder
  - code to get the size of the tree
  - gives example of a binary tree iterator implementation
- Composite pattern
  - sample implementation of the [Composite]([url](https://en.wikipedia.org/wiki/Composite_pattern)) software design pattern 

[Binary search trees](https://github.com/UCN-programming-2-JFK/BinarySearchTrees)
sample implementation of a binary search tree with find(data) and insert(data) methods  
Includes both a version with integer data and a generic version  
JUnit tests included

[Directed and undirected graph implementation](https://github.com/UCN-programming-2-JFK/Graphs)  
This project includes both a matrix and list implementation of the internal data structure and has a Graph interface to show how it is easy to swap implementation objects if they adhere to the same contract.  
The project is implemented with a Vertex class that contains a string.
The project includes a gui which generates a maze (breadth first and depth first), converts it to a graph with all intersections being vertices and then finds the path through the maze.  
![image](https://github.com/UCN-programming-2-JFK/.github/assets/3811290/97cbab7a-0444-4ba1-9a86-cb63f11256cb)




