Add your answers to the Algorithms exercises here.

Exercise I:

a) Runtime for this algorithm is O(n) as we are looping once through our data, indicating that out time complexity scales in a lenear fashion in relation to the input size.

b) Total runtime for this aglorithm is O(n^4).  We have four nested for loops, and performance squares with the size of our input data.

c) This algorithm has a linear runtime, O(n).  Our performance scales directly proportional to n, and in addition, n is decreasing in size by 1 with each recursive call.

Exercise II:

If we think of our building height as a sorted list, we can implement a binary search as our strategy to find the heighest floor to drop and egg from without breaking instead of testing each individual floor.   For example, if we had a 100 story building, we drop an egg from the midpoint of floor 50.  If it breaks, we know we have to move down.  If it doesn't, we know we have to move up.  Binary search allows us to halve the number of floors we drop an egg from with each attempt, and we keep halving until we find our floor.


Binary search has a time complexity of O(Log n), or Logarithmic time.