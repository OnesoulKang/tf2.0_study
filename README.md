# tf2.0_study
This repository is for studying tf2.0 by following https://github.com/chagmgang/tf2.0_reinforcement_learning.

## DQN
$Y_t = r(s_t,a_t)+\gamma \: \underset{a}{\operatorname{\argmax}}Q_{target}(s_{t+1},a)$

## DDQN
$Y_t = r(s_t,a_t)+\gamma \: Q_{target}(s_{t+1},a) \text{ where } a=\underset{a}{\operatorname{\argmax}}Q_{main}(s_{t+1},a)$
### Environment
* Ubuntu 18.04
* Python 3.6.9
* TensorFlow 2.5.0
