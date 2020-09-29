# Sorting_Visualizer
# Built on HTML , CSS , JS , Bootstrap ;

This project is a Web Visualization tool for sorting algorithms.

# This project includes the following sorting algorithms
-------------------------------------------------------------------------------
1.bubble sort 
->Worst and Average Case Time Complexity: O(n*n). Worst case occurs when array is reverse sorted.

                    Best Case Time Complexity: O(n). Best case occurs when array is already sorted.

                    Auxiliary Space: O(1)

                    Boundary Cases: Bubble sort takes minimum time (Order of n) when elements are already sorted.

                    Sorting In Place: Yes

                    Stable: Yes

                    Due to its simplicity, bubble sort is often used to introduce the concept of a sorting algorithm.
                    In computer graphics it is popular for its capability to detect a very small error (like swap of
                    just two elements) in almost-sorted arrays and fix it with just linear complexity (2n). For example,
                    it is used in a polygon filling algorithm, where bounding lines are sorted by their x coordinate at
                    a specific scan line (a line parallel to x axis) and with incrementing y their order changes (two
                    elements are swapped) only at intersections of two lines 
---------------------------------------------------------------------------------
  2.Selection sort 
  -> In computer science, selection sort is an in-place comparison sorting algorithm. It has an O(n2)
                    time complexity, which makes it inefficient on large lists, and generally performs worse than the
                    similar insertion sort. Selection sort is noted for its simplicity and has performance advantages
                    over more complicated algorithms in certain situations, particularly where auxiliary memory is
                    limited.

                    The algorithm divides the input list into two parts: a sorted sublist of items which is built up
                    from left to right at the front (left) of the list and a sublist of the remaining unsorted items
                    that occupy the rest of the list. Initially, the sorted sublist is empty and the unsorted sublist is
                    the entire input list. The algorithm proceeds by finding the smallest (or largest, depending on
                    sorting order) element in the unsorted sublist, exchanging (swapping) it with the leftmost unsorted
                    element (putting it in sorted order), and moving the sublist boundaries one element to the right.

                    The time efficiency of selection sort is quadratic, so there are a number of sorting techniques
                    which have better time complexity than selection sort. One thing which distinguishes selection sort
                    from other sorting algorithms is that it makes the minimum possible number of swaps, n − 1 in the
                    worst case.

 -------------------------------------------------------------------------------------
 3. Insertion Sort
 ->     Insertion sort is a simple sorting algorithm that builds the final sorted array (or list) one item
                    at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort,
                    heapsort, or merge sort. However, insertion sort provides several advantages:

                    Simple implementation: Jon Bentley shows a three-line C version, and a five-line optimized
                    version[1]
                    Efficient for (quite) small data sets, much like other quadratic sorting algorithms
                    More efficient in practice than most other simple quadratic (i.e., O(n2)) algorithms such as
                    selection sort or bubble sort
                    Adaptive, i.e., efficient for data sets that are already substantially sorted: the time complexity
                    is O(kn) when each element in the input is no more than k places away from its sorted position
                    Stable; i.e., does not change the relative order of elements with equal keys
                    In-place; i.e., only requires a constant amount O(1) of additional memory space
                    Online; i.e., can sort a list as it receives it
                    Insertion sort iterates, consuming one input element each repetition, and growing a sorted output
                    list. At each iteration, insertion sort removes one element from the input data, finds the location
                    it belongs within the sorted list, and inserts it there. It repeats until no input elements remain.

                    Sorting is typically done in-place, by iterating up the array, growing the sorted list behind it. At
                    each array-position, it checks the value there against the largest value in the sorted list (which
                    happens to be next to it, in the previous array-position checked). If larger, it leaves the element
                    in place and moves to the next. If smaller, it finds the correct position within the sorted list,
                    shifts all the larger values up to make a space, and inserts into that correct position.

                    The resulting array after k iterations has the property where the first k + 1 entries are sorted
                    ("+1" because the first entry is skipped). In each iteration the first remaining entry of the input
                    is removed, and inserted into the result at the correct position, thus extending the result  
 ------------------------------------------------------------------------------------
 4.Merge Sort  
 ->    In computer science, merge sort (also commonly spelled mergesort) is an efficient, general-purpose,
                    comparison-based sorting algorithm. Most implementations produce a stable sort, which means that the
                    order of equal elements is the same in the input and output. Merge sort is a divide and conquer
                    algorithm that was invented by John von Neumann in 1945.[2] A detailed description and analysis of
                    bottom-up mergesort appeared in a report by Goldstine and von Neumann as early as 1948.[3]
                    Conceptually, a merge sort works as follows:

                    Divide the unsorted list into n sublists, each containing one element (a list of one element is
                    considered sorted).
                    Repeatedly merge sublists to produce new sorted sublists until there is only one sublist remaining.
                    This will be the sorted list.

                    Top-down implementation
                    Example C-like code using indices for top-down merge sort algorithm that recursively splits the list
                    (called runs in this example) into sublists until sublist size is 1, then merges those sublists to
                    produce a sorted list. The copy back step is avoided with alternating the direction of the merge
                    with each level of recursion (except for an initial one time copy). To help understand this,
                    consider an array with 2 elements. The elements are copied to B[], then merged back to A[]. If there
                    are 4 elements, when the bottom of recursion level is reached, single element runs from A[] are
                    merged to B[], and then at the next higher level of recursion, those 2 element runs are merged to
                    A[]. This pattern continues with each level of recursion 
 -------------------------------------------------------------------------------------                   
 5.Quick Sort 
 -> Quicksort (sometimes called partition-exchange sort) is an efficient sorting algorithm. Developed by
                    British computer scientist Tony Hoare in 1959[1] and published in 1961,[2] it is still a commonly
                    used algorithm for sorting. When implemented well, it can be about two or three times faster than
                    its main competitors, merge sort and heapsort.[3][contradictory]

                    Quicksort is a divide-and-conquer algorithm. It works by selecting a 'pivot' element from the array
                    and partitioning the other elements into two sub-arrays, according to whether they are less than or
                    greater than the pivot. The sub-arrays are then sorted recursively. This can be done in-place,
                    requiring small additional amounts of memory to perform the sorting.

                    Quicksort is a comparison sort, meaning that it can sort items of any type for which a "less-than"
                    relation (formally, a total order) is defined. Efficient implementations of Quicksort are not a
                    stable sort, meaning that the relative order of equal sort items is not preserved.

                    Mathematical analysis of quicksort shows that, on average, the algorithm takes O(n log n)
                    comparisons to sort n items. In the worst case, it makes O(n2) comparisons, though this behavior is
                    rare.
                    Algorithm
                    Full example of quicksort on a random set of numbers. The shaded element is the pivot. It is always
                    chosen as the last element of the partition. However, always choosing the last element in the
                    partition as the pivot in this way results in poor performance (O(n²)) on already sorted arrays, or
                    arrays of identical elements. Since sub-arrays of sorted / identical elements crop up a lot towards
                    the end of a sorting procedure on a large set, versions of the quicksort algorithm that choose the
                    pivot as the middle element run much more quickly than the algorithm described in this diagram on
                    large sets of numbers.

                    Quicksort is a divide and conquer algorithm. It first divides the input array into two smaller
                    sub-arrays: the low elements and the high elements. It then recursively sorts the sub-arrays. The
                    steps for in-place Quicksort are:

                    Pick an element, called a pivot, from the array.
                    Partitioning: reorder the array so that all elements with values less than the pivot come before the
                    pivot, while all elements with values greater than the pivot come after it (equal values can go
                    either way). After this partitioning, the pivot is in its final position. This is called the
                    partition operation.
                    Recursively apply the above steps to the sub-array of elements with smaller values and separately to
                    the sub-array of elements with greater values.

                    The base case of the recursion is arrays of size zero or one, which are in order by definition, so
                    they never need to be sorted.

                    The pivot selection and partitioning steps can be done in several different ways; the choice of
                    specific implementation schemes greatly affects the algorithm's performance.
 --------------------------------------------------------------------------------------    6. Heap Sort
 ->      Heap sort is one of the sorting algorithms used to arrange a list of elements in order. Heapsort
                    algorithm uses one of the tree concepts called Heap Tree. In this sorting algorithm, we use Max Heap
                    to arrange list of elements in Descending order and Min Heap to arrange list elements in Ascending
                    order.

                    Step by Step Process

                    The Heap sort algorithm to arrange a list of elements in ascending order is performed using
                    following steps...

                    Step 1 - Construct a Binary Tree with given list of Elements.
                    Step 2 - Transform the Binary Tree into Min Heap.
                    Step 3 - Delete the root element from Min Heap using Heapify method.
                    Step 4 - Put the deleted element into the Sorted list.
                    Step 5 - Repeat the same until Min Heap becomes empty.
                    Step 6 - Display the sorted list. 
--------------------------------------------------------------------------------------                                                                        