# Linear_Search

This is a simple program that implements the Linear Search algorithm. It searches for a given target value in a array of integers and returns the position of the target value if found or -1 if not found.

Algorithm
Start with the main function.
Declare an integer array 'arr' and initialize it with values.
Declare an integer variable 'n' and assign the number of elements in the array 'arr'. Alternatively, you can calculate 'n' as: sizeof(arr) / sizeof(arr[0]).
Declare an integer variable 'target' and assign the value to be searched.
Call the 'linear_search' function with arguments: 'arr', 'n', and 'target'.
Inside the 'linear_search' function:
a. Declare an integer variable 'i' to use as a loop counter.
b. Loop through the array 'arr' from index 0 to 'n-1' using a 'for' loop.
i. Check if the element at the current index 'i' is equal to the target value.
ii. If yes, return the index 'i' as the result.
c. If the loop completes without finding the target value, return -1 as the result.
Back in the main function:
a. Store the result of the 'linear_search' function in an integer variable 'result'.
b. Check if 'result' is equal to -1.
i. If yes, print "Target value not found in the array."
ii. If no, print "Target value found at index: " followed by the value of 'result'.
End the main function.

![image](https://user-images.githubusercontent.com/126075191/234510963-c320b4b7-0184-4b93-a8f2-ccffab45d082.png)


OUTPUT:
<img width="634" alt="linear_search" src="https://user-images.githubusercontent.com/126075191/234511487-d3906568-7721-434d-8227-ef18b9bf4d66.PNG">



