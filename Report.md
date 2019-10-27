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


### The model architectures for neural networks

#### Base
- Linear(state_size, fc1_units)
- Linear(fc1_units, fc2_units)
- Linear(fc2_units, action_size)

#### Dueling Q network

- Linear(state_size, fc1_units)
- Linear(fc1_units, fc2_units)
  - Linear(fc2_units, action_size)
  - Linear(fc2_units, 1)
- Output = val + adv - adv.mean(1, keepdim=True).expand(-1, adv.size(1))

## Plot of Rewards

A plot of rewards per episode is included to illustrate that the agent is able to receive an average reward (over 100 episodes) of at least +13. 

### The number of episodes needed to solve the environment.

|  Model  |  The number of episode  |
| ---- | ---- |
|  Base  |  729|
|  Dueling Q Network  |  794  |
|  Double DQN  |  616  |
|  Prioritized Experience Replay  |  TD  |

## Ideas for Future Work

The submission has concrete future ideas for improving the agent's performance.

