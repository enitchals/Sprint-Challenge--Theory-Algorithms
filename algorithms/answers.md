# Exercise 1

## a

O(n)

## b

O(n) ... but depending on the values of x and the array items, couldn't this end up in an infinite loop?

## c

O(n^3)

## d

O(n^2)

## e

O(n^4)

## f

O(1)

## g

O(n)


# Exercise 2

## a - Given an array `a` of `n` numbers, design a linear running algorithm to find the maximum value of `a[j] - a[i]`, where `j>= i`.

function maxValueDiff(arr) {
    for (let i = 0; i<arr.length; i++) {

    }
}

## b - Q: Suppose you have an n-story building and plenty of eggs. Suppose an egg is broken if it is thrown off floor f or higher, and unbroken otherwise. Devise a strategy to determine the value of f to minimize the number of dropped eggs.

A: Start by dropping an egg from floor n/2. If that egg breaks, then focus your further testing on the lower half of the floors. If it survives, focus on the upper half. Perform this operation recursively, each time narrowing the range of possible values of f by half.


# Exercise 3

## a - suppose we implement quicksort so that the pivot is always chosen to be the first element of the array. What is the running time of this algorithm on an input array that is already sorted? Why?

## b - suppose we implement quicksort so that the pivot is always magically chosen to be the median element of the array. What is the running time of this algorithm? Why?