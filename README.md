# Neural Decoding workshop @CCN2025

Hands-on tutorial notebooks for the workshop [`Language: In search of a neural code`](https://2025.ccneuro.org/k-and-t-language-neural-code/) at CCN2025.

In this tutorial, you will create simple but scalable linear and deep learning decoding pipelines for MEG during natural language processing tasks.
The tutorial will guide you through the different steps of loading publicly available MEG recordings, preparing the data for training, creating linear and deep decoder models neural network, training them, and analyzing their behaviour. We will showcase `exca` as a way to execute and cache seamlessly.

The tutorial is based on the open source packages [`MNE-Python`](https://mne.tools), [`exca`](https://github.com/facebookresearch/exca) and [`pytorch`](https://pytorch.org/) and is designed to be run using Google Colab. It uses MEG data from the [LibriBrain dataset](https://huggingface.co/datasets/pnpl/LibriBrain):
> Özdogan, Miran, et al. "LibriBrain: Over 50 Hours of Within-Subject MEG to Improve Speech Decoding Methods at Scale." arXiv preprint arXiv:2506.02098 (2025).

## Running notebooks in Google Colab

**Part 1**: [Linear decoding](https://colab.research.google.com/github/lucyzmf/NeuralDecoding-CCN2025/blob/main/part1-linear_decoding.ipynb)

**Part 2**: [Developing efficiently: cluster and caching](https://colab.research.google.com/github/lucyzmf/NeuralDecoding-CCN2025/blob/main/part2-exca.ipynb)

**Part 3**: [Decoding with deep learning](https://colab.research.google.com/github/lucyzmf/NeuralDecoding-CCN2025/blob/main/part3-deep_decoding.ipynb)

## Authors

[Linnea Evanson](https://scholar.google.com/citations?user=VgTpOTIAAAAJ&hl=en) \
[Lucy (Mingfang) Zhang](https://scholar.google.com/citations?view_op=list_works&hl=en&user=23vdTiQAAAAJ) \
[Hubert Banville](https://hubertjb.github.io/) \
[Jean-Rémi King](https://kingjr.github.io/)
