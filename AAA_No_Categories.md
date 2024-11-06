// MULTIPLE meaning good for looking back again in the future 

### 2. Add Two Numbers 
* This is a linked list problem. As the list is reversed, it's easy to implement. 

### 3. Longest Substring Without Repeating Characters 
* A two-pointer one.
* Need to write it clean.
* Can use hash set or array to store the existing chars.

### 4. Median of Two Sorted Arrays 
* Good one for binary search, boundries checks
* MULTIPLE

### 5. Longest Palindromic Substring 
* Dp way is faster
* Center expanding is trivial but good to practice
* MULTIPLE

### 6. Zigzag Conversion 
* Missed a corner case at first but should use a more general way. 

### 7. Reverse Integer 
* Need to check the problem descriptions carefully. There are some constraints.

### 8. String to Integer (atoi) 
* Using long is easier to handle the edge cases. 

### 9. Palindrome Number 
* Reverse the number and compare.
* Reverse half of the number is also working.

### 10. Regular Expression Matching 
* A good one for a introduction of dp.
* Need to consider each case but not very complicated.
* MULTIPLE

### 11. Container With Most Water 
* Not a regular algorithm, need to think about the strategy of movements. 

### 12. Integer to Roman 
* Too easy but costs time to write. Should not be a good one.

### 15. 3Sum
* Two pointer solution. O(n^2)
* It's easy to implement after looking at the solutions.
* Need to figure out what is the fastest approach, what is the best possible complexity.
* MULTIPLE

### 16. 3Sum Closest
* Similar to 15 but just need to maintain a closest value. 
* Can use Math.abs but I used 2 values(for + and -) which is redundent. 

### 17. Letter Combinations of a Phone Number 
* Can use recursive function or fifo queue.

### 18. 4Sum 
* Approach good for problems > 4 as well.
* Need to pay attention to integer overflow.
* MULTIPLE

### 19. Remove Nth Node From End of List 
* An easy one. Use 2 pointers.

### 21. Merge Two Sorted Lists 
* Good and easy one.
* Could do recursive and iterative. 

### 22. Generate Parentheses 
* Easy backtracking 

### 23. Merge k Sorted Lists 
* The idea is not hard although it's a hard.
* In java, PriorityQueue is used as implementing a min-heap.

### 24. Swap Nodes in Pairs 
* An easy way is to use iterative approach, swap pair by pair and use constant space.
* Saw recursive way. Only need to use very simple implementation, but the stack space is O(n).

### 25. Reverse Nodes in k-Group 
* The idea is similar to 24. Used recursive way this time. 

### 29. Divide Two Integers 
* A good one to learn bit manipulating. 
* Doubt that will this really going to exist in an interview?
* MULTIPLE

### 30. Substring with Concatenation of All Words 
* Need to do a memorize to avoid tle.
* Learned that solution spending lots of time.
* MULTIPLE

### 31. Next Permutation
* Know the idea but took some time to get it right.
* No need to use sort function, just need to swap and reverse. 

### 32. Longest Valid Parentheses 
* Learned a smart way to use stack. The longest can be calculated while going through the string.
* MULTIPLE

### 33. Search in Rotated Sorted Array 
* Still learning. The key to this problem is to find the judgement of moving to left or right side.
* Why I still cannot resolve it by myself. 
* MULTIPLE

### 34. Find First and Last Position of Element in Sorted Array 
* Got the idea but a little bit redundent. 

### 36. Valid Sudoku 
* Done with the way to group 3 kinds into 3 9x9 tables.
* Found an approach that is really impressive using strings. 

### 37. Sudoku Solver 
* Used the basic idea of backtracking. The sudoku board is small, so not much optimizations.
* But the sutle details took me some time to debug. 

### 38. Count and Say 
* Just put the simplest idea. What is the meaning of this problem? 

### 39. Combination Sum 
* Another backtracking and didn't get it right at the first time.
* The idea is to make one move in each round.
* Found that it is the classic dp problem in discussions. But I'll do dp later. 

### 40. Combination Sum II
* Need to practive some backtrackings. 

### 41. First Missing Positive 
* So when the description mentions "O(1)" space, try to think about swaps?
* Didn't think of duplicate numbers at the first submit.

### 42. Trapping Rain Water 
* Got the idea pretty quick but... didn't resolve it by myself.
* MULTIPLE

### 43. Multiply Strings
* Think clearly. 



