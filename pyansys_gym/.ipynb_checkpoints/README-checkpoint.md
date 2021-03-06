**Status:** Archive (code is provided as-is, no updates expected)

# pyansys CartPole 

This is an implementation of the CartPole using MAPDL as the physics solver.
It is packaged a an environment for [OpenAI Gym](https://gym.openai.com/) with the use of pyansys.

## CartPole

The CartPole is a classic problem used for benchmarking control algorithms.
It consists of a stiff inverted pendulum that we seek to balance upright by applying constant forces
at the base to either the left or the right, one timestep at a time.

The CartPole has been packaged as an OpenAI Gym environment.  OpenAI is an arena for 
reinforcement learning research that attracts professionals and enthusiasts.  With this audience in mind
the environment could be exposed and benefit from state of the art control implementations, among them, 
those using machine learning (e.g., reinforcement learning)

# Installation

```bash
cd pyansys_gym
pip install -e .
```
