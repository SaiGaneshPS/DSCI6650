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

Running [Part_1](https://github.com/SaiGaneshPS/DSCI6650/blob/main/RL-A1/Part_1) code located in the RL-A1 folder will produce a single figure window
which has two parts, Steps vs Average Rewards and Steps vs Optimal Action percentage.

## Part 2

This part tackles the non-stationary bandit problem by introducing drift change,
mean-reverting change and abrupt change to the means generated.

Once the changes are made, the performance of three algorithms are compared:
1. Optimistic Greedy Algorithm
2. Epsilon Greedy Algorithm with fixed Epsilon
3. Epsilon Greedy Algorithm with decreasing Epsilon

Running [Part_2](https://github.com/SaiGaneshPS/DSCI6650/blob/main/RL-A1/Part_2) code located in the RL-A1 folder will produce three box plot figures for each
change and this tells us about the terminal reward distributions.

# A_2
## Part 1

This [part](https://github.com/SaiGaneshPS/DSCI6650/blob/main/RL-A2/Question_1) uses a grid with 4 states:
* Blue (0,1) - Reward = 5, Action = Teleport to Red
* Green (0,4)  - Reward = 2.5, Action = Teleport to Red or Yellow (0.5 Probability)
* Red (3, 2) - More prone to go out of bounds, Reward = -0.5
* Yellow (4, 4) - Most prone to go out of bounds, Reward = -0.5

The task is to use three different algorithms:
1. Bellman equation
2. Iterative policy evaluation
3. Value iteration

To obtain the value function and the optimal policy for this grid.

## Part 2

In this [part](https://github.com/SaiGaneshPS/DSCI6650/blob/main/RL-A2/Question_2) there is one additional state:
* Black (4,0 & 2,4) - Terminating states in Part-2
AND the location of red square changes.

The task here is to compare two methods for the optimal policy:
1. Monte-carlo with exploration starts and Monte-carlo with epsilon-soft approach
2. Importance sampling

Additionally, we also observe the effect of switching two states in between iterations to see how the policies are affected.
