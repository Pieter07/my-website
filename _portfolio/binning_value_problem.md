---
title: "Binning Value Problem"
excerpt: "A variant of the multiple knapsack problem."
collection: portfolio
---

For this problem, one is given a set of numbers, and a set of bins with target values.

One must then allocate the given set of numbers, to the bins, to minimize the difference between the sum of the numbers in each bin and said bin's target value across all bins. Furthermore, each value can only to one bin or no bin at all.

I solved this problem, through representing it as a linear programming problem. Once this was done, I used discrete-optimization techniques to minimize the differences according to some objective function.

All of the above was implemented in a python program, which can be found [here](https://github.com/pieter07/BinningValueProblem)