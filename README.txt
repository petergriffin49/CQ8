STAIRCASE

Time complexity: O(n^2), because there is a nested for loop
Space complexity: O(c) because the only variable is an input integer, no other data structures are created



ALTERNATING CHARACTERS

Time complexity: O(n), since each recursion step does a small if statement check, then gives another recursion problem with a string length that is 1 character smaller. This linear problem progression of 1 character change makes it O(n)

Space complexity: O(n), since the input provides a string of any size to work with 

Recursive definition:
base case: f(0) = 0		(input string length is 0)
recursive case: f(n) = f(n-1)		(string length smaller by 1 with each recursive call)
