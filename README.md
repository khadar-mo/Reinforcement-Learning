# Reinforcement-Learning
Learning to walk eﬃciently

The Task is to train a bipedal robot to learn to walk eﬃciently in a 2D physics simulation. It should be sample eﬃcient, learning with the least amount of interaction with the environment as possible, and also it should learn to walk quickly—eventually running as quickly and smoothly as possible.


The task is to use deep reinforcement learning to train a small bipedal robot to learn to walk eﬃciently. First develop and train the agent in an easy version of the environment (BipedalWalker-v3) and, in a second step, run it in a much more challenging version (BipedalWalkerHardcore-v3). Both environments are provided by OpenAI Gym, which uses Box2D
for its physics simulation. After your agent consistently gets scores over 300 and you are happy with how quickly it converges when trained from scratch in the easy version, transition to the more challenging one.

## Restrictions

You must submit at least 1000 episodes of log data (unless your agent consistently reaches optimal scores in fewer than 1000 episodes).
Please keep the max environment step count as 2000. The paper.pdf is restricted to a maximum of 4 pages (excluding references).

## Hardcore environment 

After your agent consistently scores over 300 and you’re happy with its learning eﬃciency, train the agent on the BipedalWalkerHardcore-v3 environment and submit a separate hardcore video.mp4 and log.txt showcasing how well your agent performs in this much more diﬃcult setting. We will examine how well the agent navigates the terrain in this setting, but make sure to also present the convergence results of the basic environment.
