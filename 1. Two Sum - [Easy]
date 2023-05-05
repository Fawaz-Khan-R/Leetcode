"""
Three Methods exist for solving this problem
brute force
Two pointer method
Hashmap method
"""
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        
        d = {}
        for i, j in enumerate(nums):
            r = target - j
            if r in d: return [d[r], i]
            d[j] = i
