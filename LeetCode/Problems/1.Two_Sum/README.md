## Problem Description:

Problem Link: [Two Sum](https://leetcode.com/problems/two-sum/)
Rating: 3/5

Algorithm:
1. Iterate through the given array from index `i=0 to i<length(array)-1`.
2. Inside the code of the first iteration, again iterate through the code from `j=i+1 to j<length(array)`.
NOTE: The above method will make sure that the same element is not used twice according to the given condition.
3. Now, if `array[i]+array[j]==target`, then return the value of indexes **i** and **j**.
NOTE: Since, it is given in the condition that there exists a solution for every problem and the solution occurs only once. So, we can return the required indexes once we find the solution.

Additional Information: 
Find your solutions attached alongwith this directory in the following links:
[JavaScript](./1.Two_Sum.js)

Contributors: 
1 - [Bikash Kalita](https://www.github.com/bikash-kalita-code)

