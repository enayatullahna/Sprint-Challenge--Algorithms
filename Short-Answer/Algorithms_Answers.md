#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(n): The function is dependent upon input value of n.

b)
O(n^2) there are two nested loops. needs to perform an operation for each value in the input data.

c)
This runtime is O(n). The function depends upon input value n(bunnies)

## Exercise II

- I would choose stratagy depending on priorities.

- First thing we need to do is find the midpoint. 

- If the egg breaks, we need to check if the egg breaks the same way using only the lower half of the floors remaining. 

- if the egg doesn't break, we need to check the same way with the upper half discarding the lower half (low + high) / 2. 

- Then continue to recurse until we are left with two floors(which will be our base case), lower half should not break, upper half should break.

- 0(log n)
