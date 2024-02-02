# DSAassignment3


## Question 1


### Approach
<!-- Describe your approach to solving the problem. -->
I have used sliding window approach in this question. I have assigned two variables namely left and right. I have used a hash table to keep a track of the index at which a particular character has ocurred in the string (The elements have all been assigned a value -1 initially). Whenever we encounter a duplicate character, the value of left variable is changed so that the index at which that particular character has occured previously is left out of the sliding window. We then calculate the difference between the values of left and right so as to obtain the length of the longest substring without any repeating characters.

### Complexity
- #### Time complexity: O(n)

- #### Space complexity: O(n)


### Solution
The solution to this problem has been given at - https://leetcode.com/problems/longest-substring-without-repeating-characters/solutions/4668098/question-1/

![Screenshot 2024-02-03 012704](https://github.com/RaashiK16/DSAassignment3/assets/126188705/08692ce7-4a6f-4908-a71e-b3c55c7bcaac)
