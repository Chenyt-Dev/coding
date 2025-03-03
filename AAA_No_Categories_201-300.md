### 201. Bitwise AND of Numbers Range 
* So many tricks in bits.

### 202. Happy Number 
* Two pointers could save space. Using set seems has less operations. 

### 203. Remove Linked List Elements 
* Used one pointer. Can also do recursively. 

### 204. Count Primes 
* Used the way to start from 2, then delete all the not prime numbers. 

### 206. Reverse Linked List 
* Both iterative and recursive are fine. Iterative seems easier to write.

### 207. Course Schedule 
* Topology sort. 

### 208. Implement Trie (Prefix Tree) 
* Just implement the Trie tree. 

### 209. Minimum Size Subarray Sum 
* A sliding window question. 

### 210. Course Schedule II 
* Same topology sort, just need to output the order. 

### 211. Design Add and Search Words Data Structure 
* Used trie. For general matching character have to go through each child. 

### 212. Word Search II 
* Trie again. This time need to store the word and do a dfs.

### 213. House Robber II 
* Can reuse helper functions. 

### 214. Shortest Palindrome 
* Learned kmp a little bit. Would be surprised if saw this in an interview. 

### 216. Combination Sum III 
* I just used backtracking. Not sure when will have a problem with only 9 digits. 

### 218. The Skyline Problem 
* Split the buildings to begins and ends. The idea is to record the heights using pq and only put into result list if the highest height changes. 

### 219. Contains Duplicate II 
* Used a set. Not need the exact distance. 

### 220. Contains Duplicate III 
* Used buckets. Need to convert to long before doing operations. Easy to overflow. 

### 221. Maximal Square 
* Used dp. The size is depending on neighbors. 

### 222. Count Complete Tree Nodes 
* With the help of left and right most nodes. 

### 223. Rectangle Area 
* Learned some rectangle calculations. 

### 224. Basic Calculator 
* The ideas for calculators is similar, just use a stack and operate on each character.

### 226. Invert Binary Tree 
* Straightforward if do it recursively. 

### 228. Summary Ranges 
* Just simulate the procedure. 

### 229. Majority Element II 
* Kind of learned a new candidate algorithm. 

### 230. Kth Smallest Element in a BST 
* Used inorder. Can also use stack. 

### 231. Power of Two 
* Used a normal way. But using bit is faster.

### 233. Number of Digit One 
* Haven't taken time on this one. 

### 235. Lowest Common Ancestor of a Binary Search Tree 
* Only 3 situations. 

### 237. Delete Node in a Linked List 
* What's the meaning of this one. 

### 238. Product of Array Except Self 
* Similar to pre sum, this is pre product and post product. 

### 239. Sliding Window Maximum 
* Use Deque. 

### 240. Search a 2D Matrix II 
* Need to increase and decrease for different directions. 

### 241. Different Ways to Add Parentheses 
* Need to find all the results. Recursive and using a memo map. 

### 243. Shortest Word Distance 
* Use two pointers. 

### 244. Shortest Word Distance II 
* Use a map. 

### 245. Shortest Word Distance III 
* Similar, just need to compare the two words. 

### 246. Strobogrammatic Number 
* List the options. 

### 247. Strobogrammatic Number II 
* Recursively generate it. 

### 248. Strobogrammatic Number III 
* Similar idea to generate numbers but can use string compares to verify if in range or not. 

### 249. Group Shifted Strings 
* Made some keys for each group.

### 250. Count Univalue Subtrees 
* Judge by results of subtrees. Update the count when do dfs. 

### 251. Flatten 2D Vector 
* Need to keep it easy. 

### 252. Meeting Rooms 
* Just used the normal way to sort the intervals and then compare begins with last ends.

### 253. Meeting Rooms II 
* PriorityQueue and arrays sorts. 

### 254. Factor Combinations 
* Recursive method. Spent some time for the exit point. Need to restrict the rear numbers larger than prior ones to prevent duplicates.

### 255. Verify Preorder Sequence in Binary Search Tree 
* Use stack to keep updating low boundries. 

### 256. Paint House 
* Easy dp. 

### 257. Binary Tree Paths 
* Time to copy the strings are also counted. 

### 258. Add Digits 
* Are we expected to know math logic on this. 

### 259. 3Sum Smaller 
* Don't need to find each of the triples. 

### 260. Single Number III 
* Bit is still not familiar. 

### 261. Graph Valid Tree 
* Keys for union find: 1. find parent 2. number of edges

### 263. Ugly Number 
* Keep dividing with 2,3,5 see if we can get 1. 

### 264. Ugly Number II 
* Using 3 pointers is smart. 

### 265. Paint House II 
* Need to keep 2 min values. Still dp, need to keep last min values and indexes and current min values and indexes. 

### 266. Palindrome Permutation 
* Used counts. 

### 267. Palindrome Permutation II 
* Do the check then dfs. Think there's no easier way. 

### 270. Closest Binary Search Tree Value 
* Just need to go one side so not strictly need dfs. 

### 271. Encode and Decode Strings 
* Encode using string's length. 

### 272. Closest Binary Search Tree Value II 
* Use inorder to maintain the list.

### 273. Integer to English Words 
* Split the integers. Less time than I thought. 

### 274. H-Index 
* Using buckets is smart. 

### 275. H-Index II 
* Comparing with last part. 

### 276. Paint Fence 
* Need to do some infers. 

### 277. Find the Celebrity 
* Two conditions, need to be careful. 

### 278. First Bad Version 
* Always think of binary search for this kind of problem. 

### 279. Perfect Squares 
* Used dp. 

### 280. Wiggle Sort 
* Find invalid paris then can just swap them. 

### 281. Zigzag Iterator 
* Can use List<Iterator>. 

### 282. Expression Add Operators 
* Need to deal with multiply, other corner cases. 

### 283. Move Zeroes 
* Used a pointer. 

### 284. Peeking Iterator 
* A cache for recording the next element. 








