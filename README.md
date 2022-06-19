# Data Structures

## What are data structures?

A way of organizing data so that it can be used effectively.

An abstract data type (ADT) is an abstraction of a data structure that provides only the interface to which a data structure must adhere to. Examples include List, Queue, and Map. Implementation of a List (DS) include Dynamic Aray and Linked List.

So the Data Structure defines <i>how</i> an abstract data type is implemented.

# Algorithms

## What are algorithms?

## Characteristics of an algorithm

1. Input
2. Output
3. Definiteness -- a human must be able to define and solve
4. Finiteness -- must terminate at some point
5. Effectiveness -- has only necessary things

# Big O Notation

## Overview

Big-O Notation gives an upper bound of the complexity in the worst case, helping to quantify performance as the input size becomes arbitrarily large.

1. How much time does this algorithm need to finish?
2. How much space does this algorithm need for its computation?

# Techniques

## Sliding Window

[Watch first part of this video](https://www.youtube.com/watch?v=MK-NZ4hN7rs)

**When to spot to use this**

- Things we iterate over sequentially (interested in continguous sequence of elements)
  - strings, arrays, linked lists
- Finding the minimum, maximum, longest, shortest, whether it contains
  - calculate something (running average)

**Question variants**

- Fixed length variant (i.e. maximum sum subarray of size K)
- Dynamic variant (i.e. smallest sum greater than or equal to some value S)
- Dynamic variant with auxillary data structure (i.e. longest substring with no more than K distinct characters)
- String permutation
