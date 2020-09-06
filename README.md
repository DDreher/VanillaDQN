# Vanilla DQN

In this notebook a **vanilla Q-Network** is implemented with **Tensorflow 2.3** and trained to complete the **CartPole-v0** environment of the OpenAI gym.

The focus of this implementation is to get the algorithm to work and provide a starting point for further tweaks and experiments.    
Therefore: Simple architecture, simple task, no fancy extras.

The notebook is also available and ready to run on [Kaggle](https://www.kaggle.comvanilla-dqn-cartpole-tensorflow-2-3).

## This includes:
* Experience Replay / Replay
* An epsilon schedule
* The E-Greedy Policy
* The compute graph of the Deep Q-Network
* Weight synchronization between Q-Network and Target-Network
* Implementation of the training loop

## References

* Mnih et al. 2013, ["Playing Atari with Deep Reinforcement Learning"](https://arxiv.org/abs/1312.5602)
* Mnih et al. 2015, ["Human Level Control Through Deep Reinforcement Learning"](https://deepmind.com/research/publications/human-level-control-through-deep-reinforcement-learning)
