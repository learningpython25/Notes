```python
# 1
def first_last6(nums):
  return nums[0] == 6 or nums[-1] == 6

# 2
def same_first_last(nums):
  return len(nums) >= 1 and (nums[0] == nums[-1])

```