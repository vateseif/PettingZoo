---
title: "RLlib: PPO for Pistonball (Parallel)"
---

# RLlib: PPO for Pistonball

This tutorial shows how to train a [Proximal Policy Optimization](https://docs.ray.io/en/latest/rllib/rllib-algorithms.html#ppo) (PPO) model on the [Pistonball](https://pettingzoo.farama.org/environments/butterfly/pistonball/) environment ([parallel](https://pettingzoo.farama.org/api/parallel/)).

After training, run the provided code to watch your trained agent play vs itself. See the [documentation](https://docs.ray.io/en/latest/rllib/rllib-saving-and-loading-algos-and-policies.html) for more information.


## Environment Setup
To follow this tutorial, you will need to install the dependencies shown below. It is recommended to use a newly-created virtual environment to avoid dependency conflicts.
```{eval-rst}
.. literalinclude:: ../../../tutorials/Ray/requirements.txt
   :language: text
```

## Code
The following code should run without any issues. The comments are designed to help you understand how to use PettingZoo with RLLib. If you have any questions, please feel free to ask in the [Discord server](https://discord.gg/nhvKkYa6qX).

### Training the RL agent

```{eval-rst}
.. literalinclude:: ../../../tutorials/Ray/rllib_pistonball.py
   :language: python
```

### Watching the trained RL agent play

```{eval-rst}
.. literalinclude:: ../../../tutorials/Ray/render_rllib_pistonball.py
   :language: python
```
