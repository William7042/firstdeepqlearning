Really ugly doodle jump with Deep Q Learning coded from scratch with PyTorch. This was my first introduction to reinforcement learning. 

Deep Q learning is different from traditional Q learning because instead of a Q table it just replaces it with a neural network which takes in a state and outputs q values for all possible actions. 

There's a main network and a target network, the only difference is target netwokr is the main network but updated much less frequently.

The algorithm behind deep q learning is the bellman equation, which says that the target q value of a given state action pair is equal to the immediate reward of it plus the expected max reward from the next state. The expected max reward uses the target network, and by doing this it gives the network a stable target to train towards. 

A Q value is just how much it expects an action to reward it in the future. 

Exploration vs Exploitation: We must use an epsilon value to force the model to explore, otherwise it won't learn anything. Epsilon is just the chance of it taking a random move. 


