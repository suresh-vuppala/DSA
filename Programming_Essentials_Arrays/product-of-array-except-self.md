# Product of Array Except Self

Given an array `nums` of `n` integers where `n > 1`, return an array `output` such that `output[i]` is equal to the product of all the elements of `nums` except `nums[i]`.

The problem must be solved without using division and in O(n) time.

## C++ Solution
```cpp
#include <vector>
using namespace std;

class Solution {
public:
    vector<int> productExceptSelf(vector<int>& nums) {
        int n = nums.size();
        vector<int> output(n, 1);
        int prefix = 1;
        for (int i = 0; i < n; ++i) {
            output[i] = prefix;
            prefix *= nums[i];
        }
        int suffix = 1;
        for (int i = n-1; i >= 0; --i) {
            output[i] *= suffix;
            suffix *= nums[i];
        }
        return output;
    }
};
```