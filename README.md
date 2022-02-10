# A dataset for Image-Goal Navigation in Habitat

This repo contains the training & evaluation data used in the paper [Memory-Augmented Reinforcement Learning for Image-Goal Navigation](https://arxiv.org/abs/2101.05181)

The train (resp. evaluation) set is split in 72 (resp. 14) files corresponding to the scenes in Habitat.
Each scene contains episodes of various difficulty (Easy, Medium Hard & Extra) depending on the start/goal distance.
The histogram of number of trajectories with respect to start-goal distance per split is shown below.

![traj_distrib_plot](https://user-images.githubusercontent.com/35572460/150818160-f3381daf-f169-4a4f-9a24-8e989305452a.png)
