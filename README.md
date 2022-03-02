# PythonSorting
### How do you sort in Python?
The easiest way to sort is with the sorted(list) function, which takes a list and returns a new list with those elements in sorted order. The original list is not changed. It's most common to pass a list into the sorted() function, but in fact it can take as input any sort of iterable collection.
### How does Python sorting work?
The Python way is a hybrid sorting algorithm which is derived from merge and insertion sort. For smaller runs (up to a minimum run size of 64) Timsort internally picks insertion sort, otherwise merge sort is being used. Its worst-case and average complexity is O(n log n), but the best-case performance is O(n)
### What is difference between sort and sorted in Python?

