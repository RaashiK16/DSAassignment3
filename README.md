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



## Question 2


### Approach
<!-- Describe your approach to solving the problem. -->
The approach I have used here is to use a vector to store the pickup position along with the number of passengers as a pair ({start,passengers}) and the dropoff position with the number of passengers but in negative ({end,-passengers}). This way, when we sort the obtained vector, we would be able to accordingly add and remove passengers.


### Complexity
- #### Time complexity: O(n)

- #### Space complexity: O(n)


### Solution
The solution to this problem has been given at - https://leetcode.com/problems/car-pooling/solutions/4672747/question-2/

![Screenshot 2024-02-03 235841](https://github.com/RaashiK16/DSAassignment3/assets/126188705/73b1c4bd-b548-45da-a70c-b47946cd97cc)



## Question 3


### Approach
<!-- Describe your approach to solving the problem. -->
I have used the DFS Approach to solve this problem. We first convert the adjacent matrix into an adjacency list. Then using the DFS Approach, we visit each element and find out if it has already been visited or not.


### Complexity
- #### Time complexity: O(n)

- #### Space complexity: O(2n)


### Solution
The solution to this problem has been given at - https://leetcode.com/problems/number-of-provinces/solutions/4672877/question-3/

![Screenshot 2024-02-04 003119](https://github.com/RaashiK16/DSAassignment3/assets/126188705/ecaa8c18-1961-4144-8a4f-c737b0732d14)




## Question 4


### Approach
<!-- Describe your approach to solving the problem. -->
I have used the Dijkstra's Algorithm for this question, since we are asked to find the minimum time and hence the shortest path. We create an adjacency list that stores the vertices and edgeweights. Next we implement the Dijkstra's algorithm to find the least time required to reach that node from the k-th(source) node. Then, we check what is the maximum time to reach a particular node among the nodes that can be reached.



### Complexity
- #### Time complexity: O(V+E)

- #### Space complexity: O(V+E)


### Solution
The solution to this problem has been given at - https://leetcode.com/problems/network-delay-time/solutions/4672920/question-4/


![Screenshot 2024-02-04 004113](https://github.com/RaashiK16/DSAassignment3/assets/126188705/acc9ccff-a7f0-48f4-b955-803c59f9905d)




## Question 5


### Approach
<!-- Describe your approach to solving the problem. -->
I have used the TrieNode class in this problem. Each node has a map of children nodes, where the keys are characters and the values are pointers to other TrieNode objects.
The insert method inserts a string into the trie by iterating over the characters in the string and creating new nodes. The search method searches for a string in the trie by iterating over the characters in the string and following the child nodes. If the end of the string is reached and the is_word flag is set, the string is found in the trie. The startsWith method checks if there is a previously inserted string that has the given prefix by following the child nodes of the root node until the end of the prefix is reached. If all characters in the prefix are found, the method returns true.



### Complexity
- #### Time complexity: O(L) where L is the length of the word

- #### Space complexity: O(N∗L) where N is the number of words and L is the length of the longest word.


### Solution
The solution to this problem has been given at - https://leetcode.com/problems/implement-trie-prefix-tree/solutions/4672990/question-5/


![Screenshot 2024-02-04 005926](https://github.com/RaashiK16/DSAassignment3/assets/126188705/b44a9fae-c6ee-47e8-8712-8301d102c297)










