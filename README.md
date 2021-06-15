# Bitcoin_Summer_of_code

# Logic

Applied Knapsack algorithm for implementation of Greedy based technique where we are doing the following:-

1. Sorting the transactions in the order of fee/weight.
2. Using a set (implementing a heap structure) we check if all the parents are already present in the block or not.
3. If step 2 is true, we include the transaction and update fee and weight and erase it from current set otherwise, go to next higher transaction.

The Time complexity for solution is O(N^2).
