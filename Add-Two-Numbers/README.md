# ADD TWO NUMBERS

* **1. Add Two Numbers**
  * [Add_Two_Numbers](./Add_Two_Numbers): Adds two numbers in different linked lists

* **Algorithim**
  *Create an empty result linked list and a pointer current to keep track of the current node.
  *Initialize carry to 0.
  *Enter a loop that continues until both input linked lists are traversed, and there is no carry left.
  *Within the loop:
     *Retrieve the value of the current digit from l1 and l2 (or 0 if the current list is already traversed).
     *Calculate the sum of the two digits along with the carry and update the carry for the next iteration.
     *Create a new node with the value of the sum digit and set it as the next node of the current pointer.
     *Update current to point to the newly created node.
     *Move l1 and l2 to the next nodes if they exist, or set them to None.
  *After the loop, return the next node of the result linked list, which represents the starting node of the sum linked list.

* **Problem statement**
  *You are given two non-empty linked lists representing two non-negative integers.
  *The digits are stored in reverse order, and each of their nodes contains a single digit.
  *Add the two numbers and return the sum as a linked list.

  *You may assume the two numbers do not contain any leading zero, except the number 0 itself.

 
* **Example 1:**
  *Input: l1 = [2,4,3], l2 = [5,6,4]
  *Output: [7,0,8]
  *Explanation: 342 + 465 = 807.

* **Example 2:**
  *Input: l1 = [0], l2 = [0]
  *Output: [0]

* **Example 3:**
  *Input: l1 = [9,9,9,9,9,9,9], l2 = [9,9,9,9]
  *Output: [8,9,9,9,0,0,0,1]
 

* **Constraints:**
The number of nodes in each linked list is in the range [1, 100].
0 <= Node.val <= 9
It is guaranteed that the list represents a number that does not have leading zeros.