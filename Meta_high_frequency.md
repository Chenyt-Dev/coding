### 1249. Minimum Remove to Make Valid Parentheses 
* While the problem wants us to remove the minimum number of parentheses, we actually just remove the invalid parantheses that do not have a pair.
* This can be done by using a Stack to record the pos of left parentheses, and check if the right parentheses are valid or not. If in the end, there are still some left parentheses left in the stack, then they are not valid as well. Remove all the chars in the invalid positions.
* We are going over the string one time, checking the content of the stack after, and then construct the string. All of these 3 steps cost O(n), so the time complexity is O(n). 

### 680. Valid Palindrome II
* It's neat to write a helper function. Use a boolean to represent if we can delete a character or not.
* Worst case is that we need to check the whole string twice. So time complexity is O(n). 

### 314. Binary Tree Vertical Order Traversal 
* I made a mistake to use dfs first but that couldn't work because dfs is not always going top-down for each column.
* Then switched to BFS, I used two queues: one for nodes, one for indexes. Also maintain a value of start index to help get the correct column in the result list.
* For each node we visit once, so time complexity is O(2^h), h is height. Maximum space needed is the width of the tree, which is also O(2^h).

### 215. Kth Largest Element in an Array 
* Priority queue or heap look quick to implement but I think it wants people to use quick select.
* Quick select is similar to quick sort, but now we only need the kth element.
* Had some time to deal with the TLE issue. The quick way to solve is skip the same values.
* On average, it could take just O(n). But it needs a good pivot each round. Or worst case it will take O(n^2). 

### 408. Valid Word Abbreviation 
* A problem without much to care. Corner cases are also only 1.
* O(n) time complexity.

