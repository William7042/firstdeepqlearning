Really ugly doodle jump with Deep Q Learning coded from scratch with PyTorch. This was my first introduction to reinforcement learning. 

Deep Q learning is different from traditional Q learning because instead of a Q table it just replaces it with a neural network which takes in a state and outputs q values for all possible actions. 

The agent uses two neural networks: a main network that gets updated every step and a target network that's updated less frequently to give stable training targets using the bellman equation. 

The Bellman equation  that the target q value of a given state action pair is equal to the immediate reward of it plus the expected max reward from the next state.

A Q value is just how much it expects an action to reward it in the future. 

Exploration vs Exploitation: We must use an epsilon value to force the model to explore, otherwise it won't learn anything. Epsilon is just the chance of it taking a random move. 

I also designed a reward function that would encourage the AI to navigate better.

