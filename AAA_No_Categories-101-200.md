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

### 140. Word Break II 
* Can use dfs + memo. 

### 141. Linked List Cycle 
* Got the idea but also need to consider corner case before submitting. 

### 142. Linked List Cycle II 
* Do the logic by hand. Need to check input/output clearly. 

### 143. Reorder List 
* If no idea for list problems, think about reverse. 

### 147. Insertion Sort List 
* Just follow the steps in the description. 

### 149. Max Points on a Line 
* The idea is not complicated. Just need to be familiar with the slopes calculations. 

### 150. Evaluate Reverse Polish Notation 
* Just use a stack of numbers.
* So far only 150.

### 151. Reverse Words in a String 
* Using stack and stringbuilder need extra O(n) space.
* Can do this in place by converting to array and reversing twice. 

### 152. Maximum Product Subarray 
* Two pointers. Reset if meets zeros. 

### 153. Find Minimum in Rotated Sorted Array 
* Just keep it simple. Which half we want. Only need to compare with the right boundry. 

### 154. Find Minimum in Rotated Sorted Array II 
* Similar to 153. For duplicate numbers, just need to shink using r-- or l++ when the middle number is the same as right boundry. 

### 155. Min Stack 
* Use linked node to build a stack with a min value;

### 156. Binary Tree Upside Down 
* Just do what the description wants to do, recursively.

### 157. Read N Characters Given Read4 
* Used a temp buf to store and keep calling it until n chars. 

### 158. Read N Characters Given read4 II - Call Multiple Times 
* I used one pointer and I had to move the pointer each time. If use two pointers, then the code can be more clean. 

### 159. Longest Substring with At Most Two Distinct Characters 
* Sliding window is easier to extend. 

### 160. Intersection of Two Linked Lists 
* Using two pointers is better as there's no extra space and just need to traverse 2 times at most. 

### 161. One Edit Distance 
* Easy idea. But need to write it neat.

### 163. Missing Ranges 
* Easy one. Not sure about the purpose. Just going over each number. 

### 164. Maximum Gap 
* Not familiar with bucket sort. 

### 165. Compare Version Numbers 
* Used String.split, note that . is a special char in regex, need to use "\\."

### 166. Fraction to Recurring Decimal 
* Used map to store the idx that a repeat number showed up.
* not a fan of this kind of question in an interview. 

### 167. Two Sum II - Input Array Is Sorted 
* Need to think more.

### 170. Two Sum III - Data structure design 
* Still need a map and a list to traverse.

### 172. Factorial Trailing Zeroes 
* How many 5s. 

### 173. Binary Search Tree Iterator 
* Originally did a traversal and then both hasNext and next are O(1) but memory is O(n).
* Tried using stack, now memory is O(h) and both hasNext and next are still O(1).

### 174. Dungeon Game 
* Need to write code efficiently.

### 179. Largest Number 
* It's important to quickly estimate what is the optimized possible solution.
* For this one, sorting can not be avoided.
* Using concat is a good idea. 

### 186. Reverse Words in a String II 
* Reverse the whole string and then reverse each word. 

### 187. Repeated DNA Sequences 
* Seems like Set is faster than Map. 

### 188. Best Time to Buy and Sell Stock IV 
* Harder for considering the dp approach.

### 189. Rotate Array 
* Using 3 reverses can make it O(1) extra space. 

### 190. Reverse Bits 
* Bit manipulations. 

### 191. Number of 1 Bits 
* Even easier than 190. 

### 198. House Robber 
* Easy dp but not actually need a dp array. 

### 200. Number of Islands 
* A classic dfs. 


