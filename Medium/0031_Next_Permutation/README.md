### **Step 1 — Find Pivot**

Find first index from right where `nums[i] < nums[i+1]`.
If **no such index**, array is in descending order → just reverse.

### **Step 2 — Find Next Greater Element**

Find the smallest element on the right of pivot that is **greater** than it.

### **Step 3 — Swap**

### **Step 4 — Reverse the Suffix**

After swapping, the right side is still decreasing → reverse it to make it smallest.
