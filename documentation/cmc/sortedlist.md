# sortedlist.h

A SortedList is a dynamic array, meaning that you can store as many elements as you like and when its capacity is full, the buffer is reallocated. The elements are only sorted when a certain action requires that the array is sorted like accessing min() or max(). This prevents the array from being sorted after every insertion or removal. The array is sorted using a variation of quick sort that uses insertion sort for small partitions.
