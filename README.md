# Collatz_with_Rationals
Collatz conjecture done on rational numbers

A friend asked about this using the concept of ["parity" on rational numbers with odd denominators](https://thatsmaths.com/2022/05/05/parity-and-partition-of-the-rational-numbers-part-i-the-three-parity-classes/) and how that would work in the collatz conjecture.

I wrote this up for fun, but it doesn't appear to exsist anywhere so I figured I might as well post it for you to stumble across. Have fun!

Things I noticed:
* Fractions still appear to get into cycles
* The number of cycles depends on the denominator of the fraction
* Some denominators go to other ones (like 15 goes to 3 and 5), but others (like 25) seem to not change denominators

This was also an excuse to learn Graphs.jl
