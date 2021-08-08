# Music Translation(From other type of the Music to the Pen-Beat Style Music)
PyTorch implementation of the method described in the [A Universal Music Translation Network](https://arxiv.org/abs/1805.07848).

<p align="center"><img width="70%" src="img/fig.png" /></p>

We present a method for translating music across musical instruments and styles. 
This  method is based on unsupervised  training of a multi-domain wavenet autoencoder, with a shared encoder and a 
domain-independent latent space that is trained end-to-end on waveforms.


This repository includes [fast-inference kernels written by nvidia](https://github.com/NVIDIA/nv-wavenet). The kernels 
were modified to match our architecture as detailed in the paper.

## Quick Links


## Setup

### Software

### Data


### Pretrained Models



## Training



### Single Node Training



### Multi-Node Training


## Inference


## License

You may find out more about the license [here](https://github.com/fairinternal/music-transfer/blob/music-oss/LICENSE).

## Citation
```
@inproceedings{musictranslation,
    title     = {A Universal Music Translation Network},
    author    = {Noam Mor, Lior Wold, Adam Polyak and Yaniv Taigman},
    booktitle = {International Conference on Learning Representations (ICLR)},
    year      = {2019},
}
```
