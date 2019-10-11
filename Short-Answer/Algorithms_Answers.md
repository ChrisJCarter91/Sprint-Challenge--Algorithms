#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - variable "a" is trying to get to n^3 but only getting n^2 each loop so will take n to get there


b)O(n^2) - while loop within a for loop gets this per my notes


c)O(n) - I'm going to go with this because subtracting 1 each call will run the variable "bunnies" amount of times until it hits the base. Less confident on this one but need to work on robots

## Exercise II


Set n to be a variable that represents the number of stories a building has

Set f to be the variable that an egg breaks at if dropped from

Write an equation that says if n is greaterthan or equal to f, the egg will break

So long as f is less than n, the function will have an O(n) run time as it is just checking to see if f is greater than or equal to n. 

If egg is thrown off the first floor (n = 1) the egg wouldn't break so the function would try at floor 2 (n = 2) and so on  until the egg reaches the floor where eggs go to die.