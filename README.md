# DSA-
Welcome to the DSA (Data Structures and Algorithms) repository! This repository is dedicated to the study, implementation, and optimization of various data structures and algorithms. 


//LINEAR SEARCH 
Linear search, also known as sequential search, is a simple and straightforward algorithm used to find a specific element in a list or array. It works by checking each element of the list one by one until the desired element is found or the list ends.

How It Works

Start from the first element: Begin the search with the first element of the list.
Compare each element: Compare the current element with the target element.

Check for a match:

If a match is found, return the index of the element.
If no match is found, move to the next element.
Repeat: Continue this process until the target element is found or the end of the list is reached.
End of list: If the target element is not found by the end of the list, return an indication that the element is not present (often -1 or null).

Time Complexity

Best Case: O(1) – The target element is found at the first position.
Worst Case: O(n) – The target element is at the last position or not present in the list.
Average Case: O(n) – On average, the target element may be found in the middle of the list.

Space Complexity

O(1) – Linear search uses a constant amount of additional space.
