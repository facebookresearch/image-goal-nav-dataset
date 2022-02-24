# A dataset for Image-Goal Navigation in Habitat

This repo contains the training & evaluation data used in the paper 

**Memory-Augmented Reinforcement Learning for Image-Goal Navigation** [[Paper]](https://arxiv.org/abs/2101.05181)

## Description

The train (resp. evaluation) set is split in 72 (resp. 14) files corresponding to the scenes in Habitat.
Each scene contains episodes of various difficulty (Easy, Medium Hard & Extra) depending on the start/goal distance.
The histogram of number of trajectories with respect to start-goal distance per split is shown below.

![traj_distrib_plot](https://user-images.githubusercontent.com/35572460/150818160-f3381daf-f169-4a4f-9a24-8e989305452a.png)

## Citation
If you use this data in your research, please consider citing the paper as follows
```
@article{mezghani2021memory,
  title={Memory-augmented reinforcement learning for image-goal navigation},
  author={Mezghani, Lina and Sukhbaatar, Sainbayar and Lavril, Thibaut and Maksymets, Oleksandr and Batra, Dhruv and Bojanowski, Piotr and Alahari, Karteek},
  journal={arXiv preprint arXiv:2101.05181},
  year={2021}
}
```

## License
`image-goal-nav-dataset` is [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode) licensed, as found in the [LICENSE](LICENSE) file.

Some information in the data may be derived from the Gibson dataset, which is available under the [following license](http://svl.stanford.edu/gibson2/assets/GDS_agreement.pdf).
