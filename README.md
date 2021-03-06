# Purity

This repository has the implementations of various algorithms and data
structures. Everything is implemented in [Haskell](https://www.haskell.org/).
Most, if not all, algorithms and data structures use recursion in some way. The
primary goal of the repository is to have a collection of high-performance and,
preferably, minimal implementations of algorithms and data structures.

## Why Haskell?

Haskell's type system allows for very expressive code. Functions are
first-class citizens (think of variables) which opens up a whole new world of
algorithms and data structures. Furthermore, so-called divide-and-conquer
approach to problem-solving (breaking down a problem into simple steps and
dealing with the smaller subproblems making the problem-solving a lot more
efficient) comes naturally with Haskell and is endorsed by the philosophy and
design of the language. Besides, its lazy evaluation by default can make
algorithms run extremely fast by not computing the values which are not going
to be used.

## Current implementations

### Data Structures

_Basic data structures_

- [Binary search tree](https://github.com/oniani/purity/blob/master/src/data-structures/basic-structures/BinarySearchTree.hs)
- [Binary tree](https://github.com/oniani/purity/blob/master/src/data-structures/basic-structures/BinaryTree.hs)
- [Fraction](https://github.com/oniani/purity/blob/master/src/data-structures/basic-structures/Fraction.hs)
- [Linked List](https://github.com/oniani/purity/blob/master/src/data-structures/basic-structures/LinkedList.hs)
- [Queue](https://github.com/oniani/purity/blob/master/src/data-structures/basic-structures/Queue.hs)
- [Stack](https://github.com/oniani/purity/blob/master/src/data-structures/basic-structures/Stack.hs)

_Geometric data structures_

- [Line](https://github.com/oniani/purity/blob/master/src/data-structures/geometric-structures/Line.hs)
- [Triangle](https://github.com/oniani/purity/blob/master/src/data-structures/geometric-structures/Triangle.hs)

### Algorithms

_Searching algorithms_

- [Binary search](https://github.com/oniani/purity/blob/master/src/algorithms/searching/BinarySearch.hs)
- [Exponential search](https://github.com/oniani/purity/blob/master/src/algorithms/searching/ExponentialSearch.hs)
- [Interpolation search](https://github.com/oniani/purity/blob/master/src/algorithms/searching/InterpolationSearch.hs)
- [Linear search](https://github.com/oniani/purity/blob/master/src/algorithms/searching/LinearSearch.hs)

_Sorting algorithms_

- [Bogosort (DO NOT RUN ON YOUR MACHINE! If interested, just look at the implementation)](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/Bogosort.hs)
- [Bubble sort](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/BubbleSort.hs)
- [Counting sort](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/CountingSort.hs)
- [Insertion sort](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/InsertionSort.hs)
- [Merge sort](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/MergeSort.hs)
- [Quicksort](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/Quicksort.hs)
- [Selection Sort](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/SelectionSort.hs)
- [Shellsort](https://github.com/oniani/purity/blob/master/src/algorithms/sorting/Shellsort.hs)

_Sequence generation algorithms_

- [Arithmetic Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/ArithmeticGenerator.hs)
- [Calkin-Wilf Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/CalkinWilfGenerator.hs)
- [Catalan Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/CatalanGenerator.hs)
- [Collatz Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/CollatzGenerator.hs)
- [Stern's Diatomic Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/DiatomicGenerator.hs)
- [Fibonacci Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/FibonacciGenerator.hs)
- [Geometric Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/GeometricGenerator.hs)
- [Lazy Caterer's Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/LazyCatererGenerator.hs)
- [Magic Square Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/MagicSquareGenerator.hs)
- [Prime Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/PrimeGenerator.hs)
- [Recamán's Sequence Generator](https://github.com/oniani/purity/blob/master/src/algorithms/sequence-generation/RecamanGenerator.hs)

_Miscellaneous algorithms_

- [Base Converter](https://github.com/oniani/purity/blob/master/src/algorithms/miscellaneous/BaseConverter.hs)

## License

[MIT License](LICENSE)
