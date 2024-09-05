# Binary-Search-Algorithm
Binary Search Algorithm using Python. An Iterative and Recursive approach

Binary Search takes advantage of a collection of elements that is already sorted by ignoring half of the elements after just one comparison. 

1. Compare x with the middle element.
2. If x matches with the middle element, we return the mid index.
3. Else if x is greater than the mid element, then x can only lie in the right (greater) half subarray after the mid element. Then we apply the algorithm again for the right half.
4. Else if x is smaller, the target x must lie in the left (lower) half. So we apply the algorithm for the left half.

We can implement Binary Search in two ways -> Recursive approach and the Iterative approach.

**Time Complexity: O(log n)**
**Auxiliary Space: O(1)**

Reference: https://www.geeksforgeeks.org/python-program-for-binary-search/
