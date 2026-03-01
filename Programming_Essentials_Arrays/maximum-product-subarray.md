# Maximum Product Subarray

Given an integer array `nums`, find a contiguous non-empty subarray within the array that has the largest product, and return the product.

## C++ Solution
```cpp
#include <vector>
using namespace std;

class Solution {
public:
    int maxProduct(vector<int>& nums) {
        int maxProd = nums[0];
        int minProd = nums[0];
        int result = nums[0];
        for (int i = 1; i < nums.size(); ++i) {
            int n = nums[i];
            if (n < 0) swap(maxProd, minProd);
            maxProd = max(n, maxProd * n);
            minProd = min(n, minProd * n);
            result = max(result, maxProd);
        }
        return result;
    }
};
```