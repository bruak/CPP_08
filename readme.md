# CPP Module 08

This repository contains the exercises for CPP Module 08, focusing on C++ Standard Template Library (STL) containers, iterators, and algorithms.

## Overview

This module explores the powerful features of the C++ Standard Template Library, including various containers like vectors, lists, maps, and sets, along with their associated iterators and algorithms. The exercises demonstrate how to use these components effectively to write more efficient and reusable code.

## Exercises

### Exercise 00: Easy find

An introduction to STL containers and algorithms through a templated function that finds a value in a container.

#### Features:
- Implementation of a template function that works with any STL container
- Use of STL iterators to traverse container elements
- Exception handling for when an element is not found
- Template specialization for different container types

#### Implementation Details:
- Template function that accepts a container and a value to find
- Use of STL's algorithms like `std::find`
- Proper error handling using exceptions or return values
- Compatibility with various container types (vector, list, deque, etc.)

### Exercise 01: Span

A class that can store a series of integers and provide operations to analyze them.

#### Features:
- `Span` class that can store N integers
- Methods to add numbers individually or in ranges
- Functions to find the shortest and longest spans (differences) between stored numbers
- Exception handling for various error conditions

#### Implementation Details:
- Internal storage using an STL container (likely vector)
- Implementation of `addNumber` method for single number addition
- Implementation of templated `addRange` method for adding multiple numbers
- Efficient algorithms to find shortest and longest spans

### Exercise 02: Mutated abomination

An exploration of creating your own templated container with iterator support.

#### Features:
- Custom templated container class
- Iterator implementation for traversing the container
- Support for standard container operations
- STL algorithm compatibility

#### Implementation Details:
- Templated class that can store elements of any type
- Implementation of proper iterator class(es)
- Required methods for container functionality
- Member functions that mimic STL container behavior
- Compatibility with STL algorithms

## STL Components Covered

### Containers
- Sequence containers (vector, list, deque)
- Associative containers (set, map)
- Container adaptors (stack, queue)

### Iterators
- Iterator categories (input, output, forward, bidirectional, random access)
- Iterator operations
- Custom iterator implementation

### Algorithms
- Non-modifying sequence operations (find, for_each)
- Modifying sequence operations (transform, copy)
- Sorting and related operations (sort, merge, min/max)
- Numeric operations (accumulate)

## Compilation

Each exercise comes with a Makefile that supports the following commands:
- `make`: Compile the program
- `make clean`: Remove object files
- `make fclean`: Remove object files and executable
- `make re`: Recompile the entire program

## Requirements

- C++ compiler with C++98 standard support
- Linux/macOS environment
- All code must compile with the following flags:
```
c++ -Wall -Wextra -Werror -std=c++98
```

## Notes

These exercises demonstrate important C++ concepts such as:
- Generic programming with templates
- Code reusability through the STL
- Efficient algorithms and data structures
- Iterator design pattern
- The power and flexibility of the STL ecosystem

While the STL provides many ready-to-use tools, understanding how they work internally enhances your ability to use them effectively and create custom solutions when needed.