# Sorting Algorithms

## Properties of   Sorting Algorithms
A Sorting algorithm is:
* __In-place__ if it does not require additional memory except, perhaps, for a few units of memory
* __Stable__ if it preserves the relative order of elements with identical keys
* __Input-insensitive__ if its running time is fairly independent of input properties other than size

## Selection Sort
While running time is quadratic, selection sort makes only about __n exchanges__

Selection sort is a good algorithm for sorting small collections of large records. (Good for small n)

makes only about n exchanges.

___In-place? Yes___

___Stable? Not stable___

___Input-insensitive? Yes___

__Best Time Complexity: O(n^2)__

__Worst Time Complexity: O(n^2)__

## Analysing Brute Force  String Matching
__Pattern p__: a string of __m__ characters to search __for__

__Text t: a__ long string of __n__ characters to search __in__

Basic operation: comparison p[j] = t[i+j]

For each n - m + 1 positions in t  we make up to m comparisons

Assuming m much larger than n: O(mn) comparisons. 

But for __random text__ over reasonably large alphabet 
(e.g. English), __average__ running time is linear in n

There are better algorithms, for smaller alphabets such as binary strings or strings of DNA nucleobases. But for many
purposes, the brute-force algorithm is acceptable.
