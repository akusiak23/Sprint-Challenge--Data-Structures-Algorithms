Add your answers to the Algorithms exercises here.

**Exercise I**:

1. O(n), it will run until it reaches n^3, loop increments by n^2.
2. O(n^3), loops 3 times per loop, and constant on last loop O(1).
3. O(n), runs until it hits 0, depends on input(bunnies).

**Exercise II**:
To limit the amount of broken eggs we grab the amount of floors and find the midpoint, n = n // 2. Egg is dropped, if broken we are above _f_ floor, so we take the midpoint of current floor and test again. If not broken we are below _f_ floor. Continue the binary search until we find _f_ floor.
