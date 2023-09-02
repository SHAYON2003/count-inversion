# count-inversion
counting the times numbers being swapped


What is Count Inversion?

Count Inversion is basically counting the number of times a particular has been swapped

There are some conditions:-

1. if (i<j) and arr[i]>arr[j] then , we can say that Inversion has to be done.
2. After fulfilling this criteria we can use the logic of merge sort and implement this code.
3. We need to create an extra space for that taking a temporary array and after all the functionalities is been done we shift the values of temporary array to an actual array.

4. The Time Complexity of this code is O(nlogn) is just same as Merge Sort.
5. Space complexity of Count Inversion code is O(n) is just same as Merge Sort
