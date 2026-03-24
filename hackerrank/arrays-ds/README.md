# Problem: Reverse Array

**Platform:** HackerRank 
**Difficulty:** Easy  
**Topic:** Arrays

---

## Problem Description

An array is a data structure that stores elements of the same type in a contiguous block of memory. In an array, 'A', of size 'N', each memory location has some unique index, 'i' (where 0 <= i < N), that can be referenced as 'A[i]'.

Your task is to reverse an array of integers.

---

## Input

4
1 4 3 2

## Output

2 3 4 1

## Explanation

The resolution of this problem was a quite simple.

I used 2 index variables, 'i' and 'j', inside a loop:
i increments every in each iteration while j decrements. 

- 'i' starts at the beginning of the array and increments each iteration
- 'j' starts at the end of the array and decrements each iteration

The loop repeats until the 'i' reach the midle of the array.


## Compleity

**Time** O(n)
**memory** O(1)
