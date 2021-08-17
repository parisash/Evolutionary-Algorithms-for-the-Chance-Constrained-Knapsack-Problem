# Evolutionary-Algorithms-for-the-Chance-Constrained-Knapsack-Problem

Implementation Evolutionary Algorithms for the Chance-Constrained Knapsack Problem with Python

Algorithm (1+1) EA
1: Choose x ϵ 〖{0,1}〗^n uniformly at random.
2: while stopping criterion not met do
3:    y ← flip each bit of x independently with probability of 1/n;
4:    if f(y) ≥ f(x) then
5:      x ← y;
6:    end if
7: end while

