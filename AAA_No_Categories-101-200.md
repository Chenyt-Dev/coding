### 102. Binary Tree Level Order Traversal 
* Used pre order traverse and dfs.

### 103. Binary Tree Zigzag Level Order Traversal 
* Inorder traversal is a smart way but I think using queue for bfs is better. 

### 105. Construct Binary Tree from Preorder and Inorder Traversal 
* Can get the idea from the definitions of each traversal. Can use map to speed up. 

### 106. Construct Binary Tree from Inorder and Postorder Traversal 
* Similar problem. Used map this time. 

### 107. Binary Tree Level Order Traversal II 
* Still used dfs. Just inserting the values reversely. BFS is also good to use. 

### 108. Convert Sorted Array to Binary Search Tree 
* Used recursive way. 

### 109. Convert Sorted List to Binary Search Tree 
* A sorted array can be treated as a preorder traversal.

### 110. Balanced Binary Tree 
* Do a dfs and return the heights (or minus value as inbalanced). 

### 111. Minimum Depth of Binary Tree 
* Used dfs and had to take care of each corner cases. Had to say bfs is much better here. 

### 112. Path Sum 
* Find a path and stop. 

### 113. Path Sum II 
* Use dfs to traverse the tree.
* When calculating the time complexity, need to consider the time to copy the path. 

### 114. Flatten Binary Tree to Linked List 
* There are some really good solutions for this. 

### 115. Distinct Subsequences 
* A dp problem. Need to understand the transition process. 

### 116. Populating Next Right Pointers in Each Node 
* Used queue but recursive is also easy to implement.

### 117. Populating Next Right Pointers in Each Node II 
* Good to learn the level traversal.

### 120. Triangle 
* From top to bottom and checked bounderies. If do from bottom to top then no need to do this. 

### 121. Best Time to Buy and Sell Stock 
* Find the max difference. 

### 122. Best Time to Buy and Sell Stock II 
* Sum up each up hills. 

### 123. Best Time to Buy and Sell Stock III 
* Need to understand how to combine the two buys. 

### 124. Binary Tree Maximum Path Sum 
* The key is that when return, we only want one side but for calculating, we need both sides. 

### 127. Word Ladder 
* Good for BFS. 

### 126. Word Ladder II 
* Took really long time on this but it's just a bfs+dfs.
* Using set instead of list is good for reducing the duplicates on each level. 

### 128. Longest Consecutive Sequence 
* The idea to always checking when the number is the leading number in a sequence is a good idea.
* Need to keep in mind that there are duplicates in the list and we need to traverse the hash set instead. 

### 129. Sum Root to Leaf Numbers 
* Just going down the tree with numbers. 

### 130. Surrounded Regions 
* Just dfs in boundries.

### 131. Palindrome Partitioning 
* Use dp to pre-calculate the palindromes and then dfs. 

### 132. Palindrome Partitioning II 
* Not easy to think of the dp way for palindrome problems. 

### 133. Clone Graph 
* Used map to record visited nodes. 

### 134. Gas Station 
* We just need to find the position with accumulated gas, so no need to try each circle. 

### 135. Candy 
* Got the idea from the solutions. Need to dimplify the question. 

### 136. Single Number 
* Just do xor. 

### 137. Single Number II 
* Learned the idea but how to explain in an interview that how I come up with that idea. 

### 138. Copy List with Random Pointer 
* Inserted the new nodes into the original list and then split them. 

### 139. Word Break 
* Consider dp but not recursive. 


