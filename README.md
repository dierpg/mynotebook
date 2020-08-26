# Goal
The main purpose of this project is to be an extensible portafolio for 
documenting my progress through specific tasks or problems related to software
development or science in particular computer science, math topics might arise 
from time to time, things saved in this project must meet one or all of the 
following criteria.

## Criteria

Must follow a specified format (in development).
Have to deal with a specific problem that's identifiable and must be explained 
as an introduction to the content being presented.

Explains pros and cons of the solutions being presented from experience in 
implementing or by citing content from other sources.

Is a diary of changes done to the project in wich case this must be contained
in a self contained file that details the activities done in the specific date.



## To do

### Term Summation
Given an array of integers, find all combinations of 3 integers that add to 0
Examples:
 [-1, 0, 1, 2, -1, -4] should return [[-1, -1, 2], [-1, 0, 1]]
 [-2,0,0,0,5,1,1,2,2,2] should return [[-2, 0, 2], [-2, 1, 1], [0, 0, 0]]

### Next Permutation 
Implement next permutation, which rearranges numbers into the lexicographically
next greater permutation of numbers. If the arrangement is not possible 
(aka. at the end of a permutation), cycle back to the beginning of the 
permutation.

Constraints:
 The replacement must be in-place and use only constant extra memory.
 Don't return anything - since the original input is being changed in-place, just check the original input

#### Examples:
 1,2,3 → 1,3,2
 3,2,1 → 1,2,3 (arrangement was at the end of the permutation)
 1,1,5 → 1,5,1

### Merge Sorted Array

Given two sorted integer arrays nums1 and nums2, merge nums2 into nums1 as one
sorted array.

Note:

 The number of elements initialized in nums1 and nums2 are m and n respectively.
 You may assume that nums1 has enough space (size that is equal to m + n) to 
 hold additional elements from nums2.

##### Example:
Input:
nums1 = [1,2,3,0,0,0], m = 3
nums2 = [2,5,6],       n = 3

Output: [1,2,2,3,5,6]


#### Constraints:

 -10^9 <= nums1[i], nums2[i] <= 10^9
 nums1.length == m + n
 nums2.length == n


### Add Binary

Given two binary strings, return their sum (also a binary string).

The input strings are both non-empty and contains only characters 1 or 0.

Example 1:
Input: a = "11", b = "1"
Output: "100"

Example 2:
Input: a = "1010", b = "1011"
Output: "10101"


#### Constraints:

 Each string consists only of '0' or '1' characters.
 1 <= a.length, b.length <= 10^4
 Each string is either "0" or doesn't contain any leading zero.
 
### Product of Array Except Self
Given an array nums of n integers where n > 1,  return an array output such that output[i] is equal to the product of all the elements of nums except nums[i].

##### Example:
Input:  [1,2,3,4]
Output: [24,12,8,6]

Constraint: It's guaranteed that the product of the elements of any prefix or suffix of the array (including the whole array) fits in a 32 bit integer.

Note: Please solve it without division and in O(n).


## Finished