# Code repository for 2nd semester Java programming at UCN
Author: [Jakob Farian Krarup](mailto:jfk@ucn.dk) 😊

> This repository contains exercises, stubs and solutions for understanding 
> coding against databases, data structures, software design patterns and algorithms.
> 
> It also contains code samples relating to [Java game programming](https://github.com/UCN-programming-2-JFK/JavaGameProgrammingCodesamples/tree/master), in case you would like to start a side project to elevate your coding skills.  
> ![image](https://github.com/UCN-programming-2-JFK/.github/assets/3811290/fb781187-d611-40a8-b1ad-23af752acf39)


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
This project includes two graph implementations with either a matrix or a list implementation of the internal data structure.  
Both classes implement the same Graph interface to show how it is easy to swap implementation classes if they adhere to the same contract.  
The project is implemented with a Vertex class that contains a string.  
JUnit tests included.
The project includes a gui which generates a maze (breadth first and depth first), converts it to a graph with all intersections being vertices and then finds the path through the maze.  
  
![MazeSolver](https://github.com/UCN-programming-2-JFK/.github/assets/3811290/d5e63c28-7a9a-4129-8f24-1d1410780763)

[Backtracking algorithm](https://github.com/UCN-programming-2-JFK/jfk.exercises/tree/master)  
Excercise skeletons (gui framework for visualization) and sample solutions for three classic problems that can all be solved using the backtracking algorithm:
- Eight Queen
- Maze
- Sudoku  
![image](https://user-images.githubusercontent.com/3811290/200328432-e5c3a156-623d-4ce6-a118-1c940f11c820.png)
![image](https://user-images.githubusercontent.com/3811290/200328340-8edf18b6-33a4-4ae3-9752-432f42fbe483.png)
![image](https://user-images.githubusercontent.com/3811290/200328362-470976bf-8628-499a-ad1f-2b28a2f70a15.png)

[Observer pattern](https://github.com/UCN-programming-2-JFK/ObserverPatternExercise)  
Exercise to practice implementing the observer design pattern. The exercise models a LAN party where different subscribers want to be notified when a match between two teams has ended.  

[Lambda Accounts](https://github.com/UCN-programming-2-JFK/LambdaAccounts)  
Code samples of how to use lambdas to filter data from a collection

[Concurrency](https://github.com/UCN-programming-2-JFK/Concurrency)  
Sample code for multithreaded programming in Java

[Map Reduce example](https://github.com/UCN-programming-2-JFK/MapReduceExample)  
Code exercise with sample solution using .parallelStream() and higher order funcions for reporting  progress and for time-taking.


