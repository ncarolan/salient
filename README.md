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

#### [unisal](https://github.com/rdroste/unisal)
Droste, R., Jiao, J., & Noble, J. A. (2020). Unified Image and Video Saliency Modeling. [arXiv preprint arXiv:2003.05477](https://arxiv.org/abs/2003.05477).

#### [GazeGAN](https://github.com/CZHQuality/Sal-CFS-GAN)
Che, Z., Borji, A., Zhai, G., Min, X., Guo, G., & Le Callet, P. (2019). How is gaze influenced by image transformations? dataset and model. IEEE Transactions on Image Processing, 29, 2287-2300. https://arxiv.org/pdf/1905.06803.pdf

#### [MSI-Net](https://github.com/alexanderkroner/saliency)
Kroner, A., Senden, M., Driessens, K., & Goebel, R. (2020). Contextual encoder-decoder network for visual saliency prediction. Neural Networks.
https://arxiv.org/pdf/1902.06634v2.pdf


## Licenses
