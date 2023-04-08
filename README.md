Introduction:  

A well-known divide-and-conquer sorting algorithm is merge sort. Any traversable data structure, such as a list, may have its values sorted. Merge sort splits the input list in half, then repeats the algorithm on each half before combining the two sorted halves. The algorithm in my project starts at the top and works its way down, breaking the list down into smaller and smaller portions until just the individual items remain. It then goes back to the top, verifying that the merging lists are in the sorted order. 

 

Tool Used: 

Python programming language is utilized to develop code for my project, and an online IDE is also used to run the code. 

 

Algorithm: 

In order to visualize my project's problem, 

 

 

 

Merge Sort Function, 

This is the recursive way to merge sort implementation. The following are the steps to generate the sorted list using this method: 

Find out the middle element of unsorted list. 

Within the recursive scenario, the list is divided into left_elements and right_elements, and the list is divided in half using the Python floor division operator. 

This way divided unsorted list until obtain the single element of base case.  

To retrieve the left and right halves, use the python slice syntax and give that list to a recursive call to the merge_sort function. 

Using While, keep looping until processed all of the values in both halves of the list. 

If the value at left_list is smaller than the value at right_list, left_elements[left_list] is assigned to the sorted_list slot and left_list is incremented. If not, then right_elements[right_list] is chosen. 

As a result, the values assigned by sorted_list =[] are all sorted. 

One of the parts may not have been covered completely at the end of this loop. Its values are simply allocated to the remaining places in the list. And with that, the merge sort is complete. 



Description automatically generated 

Input list for merge sorting- 

test_List = [3, 4, 5, 2, 1, 8, 7, 9, -2] 

 

Output: 

Sorted numerial index found = [-2, 1, 2, 3, 4, 5, 7 ,8 9] 

 

