# PythonSorting
### How do you sort in Python?
The easiest way to sort is with the sorted(list) function, which takes a list and returns a new list with those elements in sorted order. The original list is not changed. It's most common to pass a list into the sorted() function, but in fact it can take as input any sort of iterable collection.
### How does Python sorting work?
The Python way is a hybrid sorting algorithm which is derived from merge and insertion sort. For smaller runs (up to a minimum run size of 64) Timsort internally picks insertion sort, otherwise merge sort is being used. Its worst-case and average complexity is O(n log n), but the best-case performance is O(n)
### What is difference between sort and sorted in Python?
sort() function is very similar to sorted() but unlike sorted it returns nothing and makes changes to the original sequence. Moreover, sort() is a method of list class and can only be used with lists. Parameters: key: A function that serves as a key for the sort comparison.
### Python - Sorting Algorithms
~ Bubble Sort<br/>
~ Merge Sort<br/>
~ Insertion Sort<br/>
~ Shell Sort<br/>
~ Selection Sort<br/>
### Bubble Sort
By using a bubble sort, you can sort data in either ascending or descending order. Starting from the first element in a list, a bubble sort will compare the first and second elements. If the first element is greater than the second, a swap occurs.
### Merge Sort
Merge sort is one of the most efficient sorting algorithms. It works on the principle of Divide and Conquer. Merge sort repeatedly breaks down a list into several sublists until each sublist consists of a single element and merging those sublists in a manner that results into a sorted list.
### Insertion Sort
The Python insertion sort works like sorting game cards. To use the insertion sort, you create two lists: a sorted and unsorted list. You compare each item in the unsorted list until you sort that item. The insertion sort is a common standard algorithm in the Python language.
### Shell Sort
The first step in shell sort is to decide the gap/interval. Let us take interval = 4. Thus, we will select pairs of elements present at an interval 4 from each other and swap them if they are out of order. After performing this step, we will simply apply insertion sort on this array.
### Selection Sort
A Python selection sort divides a list into two small lists. One list represents the sorted elements. The other list contains the unsorted elements. The selection sort finds the smallest or highest values in each iteration and moves those values to the ordered list.
