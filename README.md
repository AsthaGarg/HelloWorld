HelloWorld
==========
Files:

1. SortingQuickSort.html:
Display the array on html page (which is uploaded when document is ready)

2. Sort.css
Used for styling the html file.(such as font family, color etc)

3. QuickSort.js
Used jquery for running the algorithm and also for adding animation in html page.


Algorithm: QuickSort| Runtime: O(n Log(n)) average, O(n^2) worst case.|Memory: O(Log(n))

Description:
If the array contains only one element or zero elements then the array is sorted.

If the array contains more then one element then:

1. Select an element from the array. This element is called the "pivot element". For example select the element in the middle of the array.

2. All elements which are smaller then the pivot element are placed in one array and all elements which are larger are placed in another array.

3. Sort both arrays by recursively applying Quicksort to them.

4. Combine the arrays

Quicksort can be implemented to sort "in-place". This means that the sorting takes place in the array and that no additional array need to be created.

