



# Bechmark



## CIFAR10_LT

Using ResNet-32 as backbone.

Imbalance factor = 100

|                      |  Acc  |
| :------------------: | :---: |
| MetaSAug (CVPR 2021) | 80.66 |
|   BLMS (CVPR 2020)   | 84.9  |



## CIFAR100_LT

Using ResNet-32 as backbone.

Imbalance factor = 100

|                      | Many | Medium | Few  |  All  |
| :------------------: | :--: | :----: | :--: | :---: |
| MetaSAug (CVPR 2021) |  -   |   -    |  -   | 48.01 |
|   RIDE (ICLR 2021)   | 69.3 |  49.3  | 26.0 | 49.1  |
|   BLMS (CVPR 2020)   |      |        |      | 50.8  |



## Places365_LT

Using ResNet-50 as backbone.

|      |      |        |      |      |
| :--: | :--: | :----: | :--: | :--: |
|      | Many | Medium | Few  | All  |
|      |      |        |      |      |
|      |      |        |      |      |
|      |      |        |      |      |



## ImageNet_LT

Using ResNet-50 as backbone.

|                      | Many | Medium | Few  |  All  |
| :------------------: | :--: | :----: | :--: | :---: |
| MetaSAug (CVPR 2021) |      |        |      | 47.39 |
|   RIDE (ICLR 2021)   |      |        |      | 55.4  |
|      CBD (2021)      | 68.5 |  52.7  | 29.2 | 55.6  |



## iNaturalist18

Using ResNet-50 as backbone.

|                      | Many | Medium | Few  |  All  |
| :------------------: | :--: | :----: | :--: | :---: |
| MetaSAug (CVPR 2021) |  -   |   -    |  -   | 68.75 |
|   RIDE (ICLR 2021)   | 70.9 |  72.4  | 73.1 | 72.6  |
|      CBD (2021)      | 75.9 |  74.7  | 71.5 | 73.6  |



# Awesome-Long-Tailed

Papers related to long-tailed tasks







## Re-weighting



## Sampling



## Meta Learning

(MetaSAug) [MetaSAug: Meta Semantic Augmentation for Long-Tailed Visual Recognition](https://arxiv.org/pdf/2103.12579.pdf) CVPR 2021

(BLMS) [Balanced Meta-Softmax for Long-Tailed Visual Recognition](https://papers.nips.cc/paper/2020/file/2ba61cc3a8f44143e1f2f13b2b729ab3-Paper.pdf) NIPS 2020

[Rethinking Class-Balanced Methods for Long-Tailed Visual Recognition from a Domain Adaptation Perspective](https://arxiv.org/pdf/2003.10780.pdf) CVPR 2020

[Meta-Weight-Net: Learning an Explicit Mapping For Sample Weighting](https://arxiv.org/pdf/1902.07379.pdf) NIPS 2019





## Data Augmentation





[Feature Space Augmentation for Long-Tailed Data](https://arxiv.org/pdf/2008.03673.pdf) ECCV 2020

[M2m: Imbalanced Classification via Major-to-minor Translation](https://arxiv.org/pdf/2004.00431.pdf) CVPR 2020

[Deep Representation Learning on Long-tailed Data: A Learnable Embedding Augmentation Perspective](https://arxiv.org/pdf/2002.10826.pdf) CVPR 2020

[Feature Transfer Learning for Deep Face Recognition with Under-Represented Data](https://arxiv.org/pdf/1803.09014.pdf) CVPR 2019

[Memory-based Jitter: Improving Visual Recognition on Long-tailed Data with Diversity In Memory](https://arxiv.org/pdf/2008.09809.pdf) preprint

[FASA: Feature Augmentation and Sampling Adaptation for Long-Tailed Instance Segmentation](https://arxiv.org/pdf/2102.12867.pdf)

 preprint

> 1. Augmentation is performed in the feature space.
> 2. For a class to be augmentated, we can compute its mean features from current batch data and then update it in a momentum way. So we can generate virtual features by firstly randomly sampling variation from a gaussian prior and add the variation to the mean feature.



## Multiple Experts

(RIDE) [Long-tailed Recognition by Routing Diverse Distribution-Aware Experts](https://arxiv.org/pdf/2010.01809.pdf) ICLR 2021

(CBD) [Class-Balanced Distillation for Long-Tailed Visual Recognition](https://arxiv.org/pdf/2104.05279.pdf) preprint 