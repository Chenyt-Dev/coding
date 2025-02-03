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

### 227. Basic Calculator II 
* Looks like a classic calculator problem and it's not complicated.
* Used stack to save the numbers. For loop can also be used in stack, good to know.
* O(n). Need to write a neat version. 
* Need to take care of all corner cases. Do nothing at white spaces, when operator or end of the string, do operations with the prior numbers. 

### 88. Merge Sorted Array 
* Just store the numbers from the end of nums1.
* Time is O(m+n).

### 1650. Lowest Common Ancestor of a Binary Tree III
* This one can be solved using a hash set or purely 2 runners.
* When use hash set, we just check which one is the first common node.
* For runners, the distance to the root is a+l for p, b+l for q. We just let them keep running in their routes, until they meet which is na+mb+l, they will always meet at some point because the distance na+mb will always be reached. 

### 528. Random Pick with Weight 
* Use Random.nextInt(bound). Note the range is [0, bound), exclusive, so need to plus 1 after that.
* Then use binary search to find what is the index of the random number. Just a genaral search, not much corner case.

### 236. Lowest Common Ancestor of a Binary Tree 
* The difference between this and 1650 is that we can't access parent node now.
* We can just divide the cases: if they are on different sides of the current node, then current node is the lowest ancestor; if they are on same side, recursively search on that side and return it; while searching, if the current node is the same as one of p and q, then just return no matter where is the other one, it will fall into one case mentioned before.
* Worst case if that we have to traverse the whole tree, so it's O(n) while n is the number of nodes. 

### 162. Find Peak Element 
* We just need to find one peek in the array.
* When see O(log n), think about binary search.
* So when we see the elements are going higher, it's guaranteed that there's a peek on the higher side; if going lower, then there must be a peek on the opposite side. 

### 339. Nested List Weight Sum 
* This structure is similar to a tree, we need to calculate the value of each item multiples with the level.
* We can use a helper function to do it recursively or use a queue.
* We need to calculate each element, so time is O(n). Space is the depth, O(depth), worst case is O(n) - the depth is same as n. 

### 50. Pow(x, n) 
* For pow related problems, think about bit manipulations.
* For this question, we need to take care of boundries first, because Integer.MIN_VALUE will cause an overflow.
* Then calculate with bits, for 32-bit integers, we only need to calculate 32 times at most. O() is instant. 

### 71. Simplify Path 
* String.split("/") returns String[].
* I just follow the cases in the description, using a List<String> to record the current path.
* Corner case is when the List is empty then we are at root. And when we are at root, after ".." we are still at root. 

### 543. Diameter of Binary Tree 
* Search in each node, calc the diameter for each node, return the depth of that node. 

### 938. Range Sum of BST 
* Used recursive way. Each solution has similar idea. Need to stop if the current node equals one of the boundries. 

### 1570. Dot Product of Two Sparse Vectors 
* First, thinking of making 2 maps and traverse in one of them.
* Another way is to use List<int[]>, and use two pointers to traverse both vectors at the same time. This is also good with both time & space.
* Use int[], easy to write.
* If one is not sparse, we can still use List but binary search on the dense one. 

### 311. Sparse Matrix Multiplication 
* Follow up of 1570.
* Similar idea but 2D this time. Still use the List<int[]> method.

### 560. Subarray Sum Equals K 
* Got an elegant solution that has time complexity of O(n).
* Because the problem just needs the number, we don't actually need to know what are the start and end positions of the subarrays.
* We can use preSum to calculate the accumulated sum from beginning, then use map to store the previous presums and the time each of them appears. Then just calculate the number of sub sum with the ending position of the current position.

### 1091. Shortest Path in Binary Matrix 
* A BFS with visited as mem. O(mn) as we visit each position at most once.
* Corner cases are: [0][0] position is not 0; matrix is only 1x1. 

### 125. Valid Palindrome 
* Just two pointer. Not much edge case.
* Read description carefully. 

### 1. Two Sum 
* Use hash-map and one-pass. Take O(n) time. 

### 199. Binary Tree Right Side View 
* Can do dfs or bfs. The time complexities are same: need to visit each node of the tree O(n).
* For bfs, just use a queue, and put last node in the result; for dfs, visit right child first and put its value in result list.

### 1762. Buildings With an Ocean View 
* Easier to implement if going from right to left, using a linked list or stack.
* Can also go from left to right, just pop out lower buildings in the stack. 

### 56. Merge Intervals 
* Used sort and merged the intervals using a tail.
* Got the idea of using an interval tree without sorting but it's kind of taking too much time to implement. 

### 146. LRU Cache 
* Use linked list and map to make get and put O(1).
* Code is not difficult just need to get the idea. 

### 23. Merge k Sorted Lists 
* Use pq to maintain the min heap with k nodes.
* Time is O(nlogk) as we need to put n nodes in the pq.
* Need to remember the customized compare with pq. 

### 986. Interval List Intersections 
* Compare the 4 start/end points of two list node and then move the index one at a time.
* Just need to visit each interval once or twice so time is O(n). 

### 973. K Closest Points to Origin 
* Use quick select to just get the closest k points but don't need to sort them. Average time O(n), worst can be O(n^2) as the pivot can be bad.

### 129. Sum Root to Leaf Numbers 
* Recursively visit all the nodes. O(n) for visiting each node once. 



