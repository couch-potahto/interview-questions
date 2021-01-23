# TraceTogether Interview Question Set 1

There are __2__ questions in this set. You are free to use the language and IDE of your choice. YOu are expected to consider edge cases and come up with test cases on your own

###  Question 1

You have a total of _n_ coins you want to form in a staircase shape, where every __k__-th row must have exactly __k__ coins.
Given _n_, find the total number of full staircase rows that can be formed.

#### Example

n = 5
The coins can form the following rows:

x

x x

x x

Because the 3rd row is incomplete, we return 2

### Question 2

Given an array of intergers _nums_ and an integer target, return the __indices of the 2 numbers such that they add up to target__

You may assume each input would have __exactly 1 solution__, and you may not use the same element twice.

#### Example

Input: nums = [2,7,11,16], target = 9

Output: [0,1]

Because nums[0] + nums[1] == 9, we return [0,1]
