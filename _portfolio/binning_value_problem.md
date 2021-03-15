---
title: "Binning Value Problem"
excerpt: "<a title='Dake, CC BY-SA 2.5 Generic &lt;https://creativecommons.org/licenses/by-sa/2.5&gt;, via Wikimedia Commons' href='https://commons.wikimedia.org/wiki/File:Knapsack.svg'><img width='512' alt='Knapsack' src='https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/Knapsack.svg/512px-Knapsack.svg.png'></a><br>
A variant of the multiple knapsack problem."
collection: portfolio
---

For this problem, one is given a set of numbers, and a set of bins with target values.

One must then allocate the given set of numbers, to the bins, to minimize the difference between the sum of the numbers in each bin and said bin's target value across all bins. Furthermore, each value can only to one bin or no bin at all.

I solved this problem, through representing it as a linear programming problem. Once this was done, I used discrete-optimization techniques to minimize the differences according to some objective function.

All of the above was implemented in a python program, which can be found [here](https://github.com/pieter07/BinningValueProblem)