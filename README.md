# Bubble-Sort-Implementation
Write a program to implement the Bubble Sort algorithm, which sorts an array of integers in ascending order. The algorithm repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process continues until the list is sorted.
Explanation of the Algorithm:
Outer Loop: Repeats the passes over the array (n-1 passes are sufficient for sorting n elements).
Inner Loop: Compares adjacent elements and swaps them if they are in the wrong order.
Optimization: If no swaps are performed during a pass, the array is already sorted, and the algorithm stops early.
Descending Order: To sort in descending order, reverse the comparison (if (arr[j] < arr[j + 1])).
