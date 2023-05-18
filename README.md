# MY LEETCODE SOLUTIONS

I created this repo to properly ducument my leetcode solutions with explanations that are as personal to me as possible, so that i could always come back here for reference to any problem i may have previously solved. I will be working mainly in python.

* **1. Two Sum**
  * [Two_Sum](./Two_sum): Uses Dictonary in python to optimize the code.

* **Algorithim**
  * create a dictionary
  * Iterate over the nums list
  * find the complement of the current value in iteration
  * if the complement value exists in dictionary, return the value of
    the key in the dictionary and the current iteration value (i) as result
  * else store the complement value and current itration value(i) in the dictionary 
  
* **Problem statement**

  * Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

  * You may assume that each input would have exactly one solution, and you may not use the same element twice.

  * You can return the answer in any order.

Example 1:
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

Example 2:
Input: nums = [3,2,4], target = 6
Output: [1,2]

Example 3:
Input: nums = [3,3], target = 6
Output: [0,1]
 
* **Constraints:**
  * 2 <= nums.length <= 104
  * -109 <= nums[i] <= 109
  * -109 <= target <= 109
  * Only one valid answer exists.

