# Software Design

## Algorithms - How are we gonna solve this?
  - Algorithms are just a set of instructions that are used to solve a problem or perform a task, all based on the
    cleverness and creativity of the designer. People have invented many ways to solve problems, and some of these
    are so common that they have been given names, like "sorting" and "searching" algorithms.
    > - Binary Search Algorithm - Code walk-through and Complexity Analysis
    > - https://www.youtube.com/watch?v=LdjkZ2vQapI
    > - Animated Interactive Visualizations with pseudocode for many common data structures
    > - https://www.cs.usfca.edu/~galles/visualization/Algorithms.html

## Time Complexity - How long is this gonna take?
  - ### BiG IDEA - Let's have a standard way to communicate about how long an algorithm will take to run
  - The "time complexity" of a program is a measure of how the "running time" of the program grows as the "input size"
    of the program grows.
  - Also known as "Algorithmic Complexity" or "Big O notation"
  - The "time complexity" is usually expressed as a "big O" notation, which is a way to express the "upper bound" of
    the "running time" of the program.
  - The "big O" notation is a way to express the "upper bound" or maximum expected of the worst-case running time of a program.
  - 4 Types of Time Complexity:
      - O(1) - "Constant Time" - The running time of the program does not change as the input size of the program grows.
      - O(log n) - "Logarithmic Time" - The running time of the program grows as the logarithm of the input size of the program.
      - O(n) - "Linear Time" - The running time of the program grows as the input size of the program.
      - O(n^2) - "Quadratic Time" - The running time of the program grows as the square of the input size of the program.

    [<img src="assets/bigo.png" width="350"/>](https://www.youtube.com/watch?v=XMUe3zFhM5c)

    > - Learn Big O notation in 6 minutes 📈
    >   - https://www.youtube.com/watch?v=XMUe3zFhM5c
  
  - Shorthand:
    - If you are doing a simple lookup in an array, it's O(1) because the time it takes to find the value in the array
      does not change as the size of the array grows.
    - If you are looping over items, it's O(n) because the time it takes to loop over the items grows as the size of the
      array grows.
    - If you are looping over items that are also looping over items, it's O(n^2) because the time it takes to loop over
      the items grows as the square of the size of the array grows.
    - Each time you add another loop, the time complexity grows as the square of the size of the array grows.
    - If you are doing a binary search, and each time you search you are cutting the size of the array in half,
      it's O(log n) because the time it takes to search grows as the logarithm of the size of the array grows.

## Communicating Software Designs - How do we talk about these things with other people? 
  - ### The Line, The Box and The Layers
    - At the time when structured programming took off, the concept of "Software Design" was introduced
      as people created more complex software systems with more complex requirements and larger teams of people working
      together to create the software.
    > - Software Design: Ep2 : 2nd Law of Software Design
    >     - https://www.youtube.com/watch?v=fh1a74WWvJQ
    > - Software Design: Ep3 : Conceptual Layers
    >     - https://www.youtube.com/watch?v=8R7hoC3OuPo
    > - Software Design: Ep4 : 3rd Law of Software Design
    >     - https://www.youtube.com/watch?v=nCxhJ_51fjA 

- [Continue Reading - Class Oriented Programming](08-ClassOrientedProgramming)
- [Back to Index](README.md)