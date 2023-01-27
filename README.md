# Multi-agent Reinforcement Learning with Graph Q-Networks for Antenna Tuning

Supplementary material for our paper:

Maxime Bouton, Jaeseong Jeong, Jose Outes, Adriano Mendo, Alexandros Nikou, "Multi-agent Reinforcement Learning with Graph Q-Networks for Antenna Tuning," in *IEEE/IFIP Network Operations and Management Symposium (NOMS)*, 2023.

**Abstract:**
> Future generations of mobile networks are expected to contain more and more antennas with growing complexity and more parameters. 
> Optimizing these parameters is necessary for ensuring the good performance of the network. 
> The scale of mobile networks makes it challenging to optimize antenna parameters using manual intervention or hand-engineered strategies. 
> Reinforcement learning is a promising technique to address this challenge but existing methods often use local optimizations to scale to large network deployments. 
> We propose a new multi-agent reinforcement learning algorithm to optimize mobile network configurations globally. 
> By using a value decomposition approach, our algorithm can be trained from a global reward function instead of relying on an ad-hoc decomposition of the network performance across the different cells. 
> The algorithm uses a graph neural network architecture which generalizes to different network topologies and learns coordination behaviors.
> We empirically demonstrate the performance of the algorithm on an antenna tilt tuning problem and a joint tilt and power control problem in a simulated environment. 