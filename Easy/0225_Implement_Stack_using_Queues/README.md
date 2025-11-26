# **Approach 1: Using a Single Queue**

We use **1 queue**, and for every `push(x)` we:

1. Add `x` to queue
2. Rotate the previous elements to the back (so `x` comes to the front)

# **Time Complexity**

| Operation | Complexity |
| --------- | ---------- |
| push      | O(n)       |
| pop       | O(1)       |
| top       | O(1)       |
| empty     | O(1)       |
