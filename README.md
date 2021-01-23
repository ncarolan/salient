# Saliency-Conditioned Image Generation


## Table of Contents
- [About](#about)
- [Dependencies](#dependencies)
- [Model](#model)
- [Training](#training)
- [Testing](#testing)
- [Pre-Trained Models](#pre-trained-models)
- [Acknowledgements](#acknowledgements)
- [Licenses](#licenses)

## About

This repository implements the model for saliency-conditioned image generation developed for my senior thesis at Amherst College. This model transforms mappings of visual saliency into artificially generated images with the same saliency distribution.

## Dependencies

In the root directory of this repository, execute:

```
pip install -r requirements.txt
```

- Note that this repository requires TensorFlow 1.13. 

- Training or evaluating a model requires a system with a GPU. For more details, see [Training](#training).

## Model

## Training

## Testing

## Pre-Trained Models

## Acknowledgements

This model would not be possible without the work of many others in developing saliency predictors and image generation models. In particular, I use code from the following papers and repositories:

#### [DeepGazeII](https://deepgaze.bethgelab.org/) 
Kümmerer, M., Wallis, T. S., & Bethge, M. (2016). DeepGaze II: Reading fixations from deep features trained on object recognition. [arXiv preprint arXiv:1610.01563](https://arxiv.org/pdf/1610.01563.pdf).

#### [SalGAN](https://github.com/imatge-upc/salgan)
Pan, J., Ferrer, C. C., McGuinness, K., O'Connor, N. E., Torres, J., Sayrol, E., & Giro-i-Nieto, X. (2017). Salgan: Visual saliency prediction with generative adversarial networks. [arXiv preprint arXiv:1701.01081](https://arxiv.org/pdf/1701.01081.pdf).

## Licenses
