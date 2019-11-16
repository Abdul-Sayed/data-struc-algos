Time Complexity:

  There are best cases, worst cases, and average case scenarios for solving an algorithm. Optimizing the best case is unecesary, the average case is difficult to determine, so we optimize and compare algorithms only for the worst case. 

  Asymptotic time complexity; as size n of input => infinity 
  
  Generally the time complexity is related to size of input.
  Time complexity can be measured by the lines of executable code; declarations and assignments (not comparisons). As n => inf, loops stand out as contributing to the lines of executed code. Moreover, the loop as a whole can be considered as one unit of executable code. 

  A function with a single loop or multiple non nested loops has time complexity of n

  Nested for loops have time complexity of n^n, for n loops; a loop nested in an outer loop has n^2 time complexity. 

  Just count the number of nested loops that force you to go through your dataset 