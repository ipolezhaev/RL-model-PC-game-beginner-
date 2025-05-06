# Reinforcement learning(RL) model Flappy Bird

Let's build a simple reinforcement learning (RL) model using Q-learning and a minimal custom environment — no gym needed.

We'll simulate a very basic game like Flappy Bird:

The agent is running in a 1D world.

Obstacles appear randomly.

The agent can either "jump" or "do nothing".

If it doesn't jump over an obstacle, it loses.

✅ High-Level Overview of the game
#### State:

   0 = no obstacle ahead
   
   1 = obstacle ahead
   
#### Actions: 

  0 = do nothing
  
  1 = jump

#### Reward:

  +1 for surviving a step
  
  -10 for hitting an obstacle

We'll implement:

A custom environment
A Q-table
Q-learning loop

Output
The agent learns:

To jump when there's an obstacle (state=1)

To do nothing when it’s safe (state=0)

Over time, the Q-values reflect these decisions.


