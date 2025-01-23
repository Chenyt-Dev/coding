### 1249. Minimum Remove to Make Valid Parentheses 
* While the problem wants us to remove the minimum number of parentheses, we actually just remove the invalid parantheses that do not have a pair.
* This can be done by using a Stack to record the pos of left parentheses, and check if the right parentheses are valid or not. If in the end, there are still some left parentheses left in the stack, then they are not valid as well. Remove all the chars in the invalid positions.
* We are going over the string one time, checking the content of the stack after, and then construct the string. All of these 3 steps cost O(n), so the time complexity is O(n). 

### 680. Valid Palindrome II
* It's neat to write a helper function. Use a boolean to represent if we can delete a character or not.
* Worst case is that we need to check the whole string twice. So time complexity is O(n). 
