# Array-Element-occurance-more-than-n-2-times
Question :  Find the majority element among given array that have more than n/2 occurrence 
Here n is size of array.


solutions
1. Use Brute Force Method
      Count every element's frequency and compare
     Time complexity :  O(n^2)
     Space complexity: O(1)

2. Sort array or for sorted array
     Count for same element and compare
     Time complexity :  O(n)
     Space complexity: O(1)

3. Use Hash Map
     Time complexity :  O(n)
     Space complexity: O(n)

4. Boyer-Moore Majority vote algorithm
     During travese for same element add 1 to frequency and for different element reduce 1 from frequency
     At last the element present more than n/2 times has frequency more than 0
     Time complexity :  O(n)
     Space complexity: O(1)
