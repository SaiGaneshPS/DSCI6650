# DSCI6650

# A_1
## Part 1

This part requires us to compare 4 algorithsm for a stationary bandit problem:
1. Greedy Algorithm
2. Epsilon Greedy Algorithm
3. Optimistic Greedy Algorithm
4. Gradient Bandit Algorithm

The parameters for the problem are:
k = 10;
steps = 1000;
runs = 1000;

Running Part_1 code located in the RL-A1 folder will produce a single figure window
which has two parts, Steps vs Average Rewards and Steps vs Optimal Action percentage.

## Part 2

This part tackles the non-stationary bandit problem by introducing drift change,
mean-reverting change and abrupt change to the means generated.

Once the changes are made, the performance of three algorithms are compared:
1. Optimistic Greedy Algorithm
2. Epsilon Greedy Algorithm with fixed Epsilon
3. Epsilon Greedy Algorithm with decreasing Epsilon

Running Part_2 code located in the RL-A1 folder will produce three box plot figures for each
change and this tells us about the terminal reward distributions.
