# GAN Image Synthesis Papers Collection

A collection of image synthesis using GANs.
Papers are ordered in arXiv first version submitting time (if applicable).
Issues, PRs, Emails, Discussions, ... are all welcomed!



[TOC]

## Vanilla Image Synthesis
| Note | Model    | Paper                                                        | Conference | paper link                                     | code link                                                    |
| ---- | -------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
|      | CR-GAN   |                                                              |            |                                                |                                                              |
|      | StyleGAN | A Style-Based Generator Architecture for Generative Adversarial Networks | CVPR 2019  | [1812.04948](https://arxiv.org/abs/1812.04948) | [NVlabs/stylegan](https://github.com/NVlabs/stylegan)        |
|      | BigGAN   | Large Scale GAN Training for High Fidelity Natural Image Synthesis | ICLR 2019  | [1809.11096](https://arxiv.org/abs/1809.11096) | [tfhub](https://tfhub.dev/s?module-type=image-generator&q=biggan), [ajbrock/BigGAN-PyTorch](https://github.com/ajbrock/BigGAN-PyTorch) |
|      | SAGAN    |                                                              |            |                                                |                                                              |
|      | PGGAN    |                                                              |            |                                                |                                                              |
|      | WGAN-GP  |                                                              |            |                                                |                                                              |
|      | WGAN     |                                                              |            |                                                |                                                              |
|      | DCGAN    |                                                              |            |                                                |                                                              |
|      | GAN      |                                                              |            |                                                |                                                              |



## Conditional GANs

Note: See [[lzhbrian/image-to-image-papers]](https://github.com/lzhbrian/image-to-image-papers/) for GANs condition on image.

| Note | Model | Paper | Conference | paper link | code link |
| ---- | ----- | ----- | ---------- | ---------- | --------- |
|      | MSGAN |       |            |            |           |
|      | ACGAN |       |            |            |           |
|      | cGAN  |       |            |            |           |




## GANs with Encoder

Normally GAN handles latent code -> image, these papers simultaneously handle image -> latent code.

| Note | Model           | Paper                                                        | Conference   | paper link                                     | code link                                                    |
| ---- | --------------- | ------------------------------------------------------------ | ------------ | ---------------------------------------------- | ------------------------------------------------------------ |
|      | BigBiGAN        | Large Scale Adversarial Representation Learning              | NeurIPS 2019 | [1907.02544](https://arxiv.org/abs/1907.02544) | [tfhub](https://tfhub.dev/s?publisher=deepmind&q=bigbigan)   |
|      | O-GAN           | O-GAN: Extremely Concise Approach for Auto-Encoding Generative Adversarial Networks |              | [1903.01931](https://arxiv.org/abs/1903.01931) | [bojone/o-gan](https://github.com/bojone/o-gan)              |
|      | AET             | AET vs. AED: Unsupervised Representation Learning by Auto-Encoding Transformations rather than Data | CVPR 2019    | [1901.04596](https://arxiv.org/abs/1901.04596) |                                                              |
|      | Texture Mixer   | Texture Mixer: A Network for Controllable Synthesis and Interpolation of Texture | CVPR 2019    | [1901.03447](https://arxiv.org/abs/1901.03447) |                                                              |
|      | GAIA            | Generative adversarial interpolative autoencoding: adversarial training on latent space interpolations encourage convex latent distributions. |              | [1807.06650](https://arxiv.org/abs/1807.06650) |                                                              |
|      | IntroVAE        | IntroVAE: Introspective Variational Autoencoders for Photographic Image Synthesis | NIPS 2018    | [1807.06358](https://arxiv.org/abs/1807.06358) |                                                              |
|      | Pioneer Network | Pioneer Networks: Progressively Growing Generative Autoencoder | ACCV 2018    | [1807.03026](https://arxiv.org/abs/1807.03026) | [AaltoVision/pioneer](https://github.com/AaltoVision/pioneer) |
|      | AGE             | It Takes (Only) Two: Adversarial Generator-Encoder Networks  | AAAI 2018    | [1704.02304](https://arxiv.org/abs/1704.02304) | [DmitryUlyanov/AGE](https://github.com/DmitryUlyanov/AGE)    |
|      | ALI             | Adversarially Learned Inference                              | ICLR 2017    | [1606.00704](https://arxiv.org/abs/1606.00704) |                                                              |
|      | BiGAN           | Adversarially Feature Learning                               | ICLR 2017    | [1605.09782](https://arxiv.org/abs/1605.09782) |                                                              |



## Metrics

* FID Score
* Inception Score



## Datasets

* MNIST
* Fashion-MNIST
* ImageNet
* LSUN
* CelebA-HQ
* FFHQ

