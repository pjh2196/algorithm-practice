# 1. Two Sum

## Problem
Given an array of integers `nums` and an integer `target`,
return indices of the two numbers such that they add up to target.

## Example
nums = [2,7,11,15], target = 9  
Output: [0,1]

nums = [3,2,4], target = 6
Output: [1,2]

nums = [3,3], target = 6  
Output: [0,1]

## Approach
- Iterate through all pairs using nested loops
- Avoid using the same index twice
- If nums[i] + nums[j] equals target, return [i, j]

## Time Complexity
O(n²)

## What I Learned
- Difference between value and index
- Why we use range(len(nums))
- Why j can start from i+1 to avoid duplicate checks