# Binomial Heap

## Description

University group project which consists of an implementation in C++ of a Binomial heap with multiple operations and efficiency tests. 

![image](https://user-images.githubusercontent.com/18242948/192794122-5e55fd49-92e9-4045-b687-d4f5a603f371.png)


## Motivation

Binomial heap is the perfect data structure for simple operations such as insert, delete and extract elements, but the strongest point of this structure, which differentiates it from others is the "Union" operation of two heaps in the shortest time ( O(log n) ). This operation helps unifying more sets of data as fast as possible.

## Operations

The following basic operations were implemented and tested on time complexity:

* Insert - insereaza(H ,x)
* Delete - sterge(H, x) 
* Minimum - findMin(H)
* Maximum - findMax(H,INT_MIN)
* Successor - successor(H, x)
* Predecessor - predecessor(H, x) 
* K-th element - k_element(H, k)
* Cardinal - cardinal(H)
* Find node - este_in(H, k)

## Notes

For the test cases, tests results and further elaboration, please see the documentation in the "Binomial Heap Final Report" pdf.
