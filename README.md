# Assignment - Basic Data Structures and Algorithms

> Introduction to data structures and algorithms


## Introduction

So far we've explored the different types in JS.  When we studied classes/objects we use 'real' objects to mimic behaviors in our programs.  Until now, the way we stored objects didn't really matter.  Ensuring that we don't prematurely optimize code, we've deferred some things until we knew they were a problem.  Some of that changes with this brief lesson on data structures and algorithms.
   
There are two parts: data structures, and measuring optimizations.  Measure the efficiency of our algorithms is done using a mathematical notation `O(n)` or the 'Big O'.  The best case scenario for any algorithm is to remain linear as we process over time.  The 'Big O' helps us identify things we can do to make our searching more performant.

### Why does structure matter?

More or less the way that we structure our data will enable us to optimize finding it.  For example, doing a algorithm that takes our data, sorts it, then places the middle element at the top of a tree like structure will allow us to seek data quicker because we can ask if the value we seek is between the tree nodes. We will discuss this later in this assignment.

Let's explore a couple of data types and observe how they might help us do soem things that the normal data types couldn't.

### Stack (LIFO)

The definition of a `stack` is a structure that contains linear data.  Think of something like a stack of books.  Stacks will maintain their order as items are added and subtracted from the stack.  In our example, we'd most likely add a book to the top of a stack. Especially if there were a lot of books stacked on each other. It would become inconvenient to juggle the books, place a book within the stack, and place the remaining books on top or below the newly added book.
 
The functions available to a stack are:

* `.push(value)` - adds a value to the top
* `.pop()` - removes from the top the most recent value


### Queue (FIFO)

A `queue` is another type of data structure that also aims at storing linear information.  A queue behaves similarly to the DMV where upon arrival you are asked to take a number.  Each time a worker finishes their work, a new number is retrieved in sequential order from the starting number until all the people have been accounted for.
  
The functions available on a queue are: 

* `.enqueue(value)` - adds a value to the queue
* `.dequeue()` - removes a value from the queue



## Assignment

### Resources

* [Data Structures in JavaScript](https://code.tutsplus.com/series/data-structures-in-javascript--cms-772)

