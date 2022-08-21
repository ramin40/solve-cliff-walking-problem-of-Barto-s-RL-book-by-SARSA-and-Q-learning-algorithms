# solve-cliff-walking-problem-of-Barto-s-RL-book-by-SARSA-and-Q-learning-algorithms
<img src='https://user-images.githubusercontent.com/74808396/185781603-c5aaf9e5-c906-4794-be73-b480bc0a482b.png' width='400' height='300'>


this repository is the implementation of cliff walking problem at page 132 Barto's book. this impementation is for educational purpose and you can copy and use it.

## SARSA and Q-learning algorithms
- SARSA:
<img src="https://user-images.githubusercontent.com/74808396/185782209-93ada0a5-4f68-4e5a-88e8-c7d823410834.png" width="300" height="200">
SARSA is an on-policy algorithm that updates action value function by TD target.<br />
how it works:
in the current state, S an action, A is taken and a reward, R recieved and ends up in next state, S1 and takes action, A1 in S1. Therefore, the tuple (S, A, R, S1, A1) stands for the SARSA.

- Q-learning:

<image src='https://user-images.githubusercontent.com/74808396/185782596-a70db5a4-b441-43b0-b0e0-399b6b3d04dc.png' width='300' height='200'>
Q-learning is an off-policy algorithm that updates the action value function by TD target.<br />
how it works:
in the current state, S an action, A is taken and a reward, R received and ends up in the next state, S1 now instead of taking action A1 unlike SARSA it computes all Q values associated with actions and selects the maximum possible value.

## environment

<img src="https://user-images.githubusercontent.com/74808396/185781308-a8a52703-08c3-485b-8ecd-8dba3821c63d.png" width="300" height="200">
in the cliff walking environment each episode begines from start point and ends at the goal point.<br />
you obtaine -1 reward for each step and -100 reward if you fall of the cliff. I've implemented environment code by myself and it's a part of the `cliff walking` jupyter notebook.

## how to run code
- run **cliff walking** notebook.
- heve fun :wink:
