# Project Report

## Learning Algorithm

#### hyperparameters

|  Name  |  Value  |　|
| ---- | ---- | ---- |
|BUFFER_SIZE | int(1e5)  | replay buffer size|
|BATCH_SIZE | 64         | minibatch size|
|GAMMA | 0.99            | discount factor|
|TAU | 1e-3              | for soft update of target parameters|
|LR | 5e-4               | learning rate |
|UPDATE_EVERY | 4        | how often to update the network|


### The model architectures for neural networks.

## Plot of Rewards

A plot of rewards per episode is included to illustrate that the agent is able to receive an average reward (over 100 episodes) of at least +13. 

### The number of episodes needed to solve the environment.

|  Model  |  The number of episode  |
| ---- | ---- |
|  Base  |  About 15 |
|  Dueling Q Network  |  TD  |
|  Double DQN  |  TD  |
|  Prioritized Experience Replay  |  TD  |

## Ideas for Future Work

The submission has concrete future ideas for improving the agent's performance.

