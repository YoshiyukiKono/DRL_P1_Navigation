# DRL_P1_Navigation

## Project Details

### Game
- Navigate an agent in a square world.
- The goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

### Reward
- A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.

### State space
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. 


### Action spaces
Four discrete actions are available, corresponding to:

* 0 - move forward.
* 1 - move backward.
* 2 - turn left.
* 3 - turn right.

### Training end condition - when the environment is considered solved

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.


## Getting Started

### Requirement
https://github.com/udacity/deep-reinforcement-learning#dependencies

https://pytorch.org/?utm_source=Google&utm_medium=PaidSearch&utm_campaign=%2A%2ALP+-+TM+-+General+-+HV+-+JP&utm_adgroup=PyTorch+Version&utm_keyword=%2Bpytorch%20%2Bversion&utm_offering=AI&utm_Product=PyTorch&gclid=Cj0KCQjw84XtBRDWARIsAAU1aM2zq_aOaEVOMcbRXR5UUKbRyy6k2amUoQ7J8z88762R1Y5pxokc_RsaArgrEALw_wcB

``
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
``
## Instructions




