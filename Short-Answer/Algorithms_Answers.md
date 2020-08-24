#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
[ANSWER] O(n) This would be running linearly since as the size of n increases and the steps it takes to finish grows at the same time.
b)
[ANSWER] O(n log n) Since the algorithm is using a for loop (linearly) and a while loop (exponentially), it will be going at a linearithmic rate

c)
[ANSWER] O(n) this is another linear one since it is using recursion to loop through however many bunnies there are. 

## Exercise II
The strategy I would use for this is to use a binary search recursively to maximize efficiency and have a low space/time complexity.

I'd first set two variables (start and end)

start would equal 0 (first index) and then end would be the last index of the array

Then I would set the middle by getting the middle index in between low and high (low + high) and also have to make sure that number is an integer

I would then check if the middle of that array is the target (or the floor number the egg breaks)

If the middle of the array is not the floor it breaks on then it will check if the floor is greater than or less than the middle.

If the floor needed to break is greater than the middle index it will set the new low to where the middle index is, and if its less then it will do the same except instead of low it will be the high is set to where the middle index is.

Then it will call the function again and do it over until it reaches the floor.

