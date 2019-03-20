# CV papers



### Content

* [Image Transfer](#{Image Transfer})
* [Image to Image GAN](#Image to Image GAN)
* [Image Inpainting](#Image Inpainting)
* [Noise/Latent GAN](#Noise/Latent GAN)
* [Text to Image](#Text to Image)
* [Training Trick](#Training Trick)
* [Others](#Others)





### Image Transfer

| nickname              | paper name                                               | paper links                                                  | note                                          | conference | code |
| --------------------- | -------------------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------- | ---------- | ---------- |
| Color Transfer | Color Transfer between Images | [IEEE](https://ieeexplore.ieee.org/document/946629) | mean, std |  |  |
| Neural Style Transfer | image style transfer using convolutional neural networks | [cv_foundation](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) | CNN + back propagation | CVPR 2016  ||
|                       | Deep Photo Style Transfer                                | [arxiv](https://arxiv.org/abs/1703.07511)                    | based on Neural Style Transfer |            ||
| | Deep Image Harmonization | [arxiv](https://arxiv.org/abs/1703.00069) |  | ||
|                       | Deep Painterly Harmonization                             | [arxiv](https://arxiv.org/abs/1804.03189)                    | Neural Style Transfer + Gram matrix + mapping |            ||



### Image to Image GAN

| nickname   | paper name                                                   | paper links                                   | note                           | conference | code |
| ---------- | ------------------------------------------------------------ | --------------------------------------------- | ------------------------------ | ---------- | ---------- |
|            | Image Generation from Sketch Constraint Using Contextual GAN | [arxiv](https://arxiv.org/pdf/1711.08972.pdf) |                                |            ||
| pix2pix | Image-to-Image Translation with Conditional Adversarial Networks | [arxiv](https://arxiv.org/abs/1611.07004) | | CVPR 2017 ||
| BicycleGAN | Toward Multimodal Image-to-Image Translation                 | [arxiv](https://arxiv.org/pdf/1711.11586.pdf) | multimodal, pair data          | NIPS 2017  ||
| DiscoGAN   | Learning to Discover Cross-Domain Relations with Generative Adversarial Networks | [arxiv](https://arxiv.org/abs/1703.05192)     |                                | ICML 2017  ||
| CycleGAN   | Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks | [arxiv](https://arxiv.org/pdf/1703.10593.pdf) | unpaired data                  | ICCV 2017  ||
| StarGAN    | StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | [arxiv](https://arxiv.org/pdf/1711.09020.pdf) | Conditional + CycleGAN, label  |            ||
| GANimation | GANimation: Anatomically-aware Facial Animation from a Single Image | [arxiv](https://arxiv.org/abs/1807.09251)     |                                | ECCV 2018  ||
| UNIT       | Unsupervised Image-to-Image Translation Networks             | [arxiv](https://arxiv.org/pdf/1703.00848.pdf) | Encoder + Generator            |            ||
| MUNIT      | Multimodal Unsupervised Image-to-Image Translation           | arxiv                                         | UNIT + CycleGAN, unpaired data | ECCV 2018  |[github](https://github.com/NVlabs/MUNIT)|
| DRIT | Diverse Image-to-Image Translation via Disentangled Representations | [arxiv](https://arxiv.org/abs/1808.00948) |  | ECCV 2018 oral |[original version](https://github.com/HsinYingLee/DRIT) & [High resolution version](https://github.com/hytseng0509/DRIT_hr)|




### Image Inpainting

| nickname    | paper name                                            | paper links                                   | note | conference |code|
| ----------- | ----------------------------------------------------- | --------------------------------------------- | ---- | ----------- | ----------- |
|  | Globally and Locally Consistent Image Completion | [ACM](https://dl.acm.org/citation.cfm?id=3073659) |  | SIGGRAPH 2017 ||
| | High-Resolution Image Inpainting using **Multi-Scale** Neural Patch Synthesis | [arxiv](https://arxiv.org/abs/1611.09969) |  |  ||
| Shift-Net | Shift-Net: Image Inpainting via Deep Feature Rearrangement | [arxiv](https://arxiv.org/abs/1801.09392) |  |  ||
| Deepfill v1 | Generative Image Inpainting with **Contextual Attention** | [arxiv](https://arxiv.org/pdf/1801.07892.pdf) |      |CVPR 2018||
| Deepfill v2 | Free-Form Image Inpainting with **Gated Convolution** | [arxiv](https://arxiv.org/pdf/1806.03589.pdf) | |||
| SC-FEGAN | SC-FEGAN: Face Editing Generative Adversarial Network with **User’s Sketch and Color** | arxiv | |||
| PICNet | Pluralistic Image Completion | [arxiv](https://arxiv.org/abs/1903.04227) | |CVPR 2019|[github](https://github.com/lyndonzheng/Pluralistic-Inpainting)|



### Noise/Latent GAN
| nickname | paper name                                                   | paper links                                   | note | conference | code |
| -------- | ------------------------------------------------------------ | --------------------------------------------- | ---- | ---------- | ---------- |
| DCGAN    | Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks | [arxiv](https://arxiv.org/pdf/1511.06434.pdf) |      |            ||
| PGGAN    | Progressive Growing of GANs for Improved Quality, Stability, and Variation | [arxiv](<https://arxiv.org/abs/1710.10196>)   |      | ICLR 2018  ||



### Text to Image

| nickname | paper name                                                   | paper links                                   | note | conference | code |
| -------- | ------------------------------------------------------------ | --------------------------------------------- | ---- | ---------- | ---------- |
| StackGAN | StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks | [arxiv](https://arxiv.org/abs/1612.03242)     |      | ICCV 2017 oral |[github](https://github.com/hanzhanggit/StackGAN)|



### Training Trick
| nickname | paper name | paper links | note | conference | code |
| -------- | ---------- | ----------- | ---- | ---------- | ---- |
| MSGAN | Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis | [arxiv](https://arxiv.org/abs/1903.05628) | Condition GAN | CVPR 2019 |[github](https://github.com/HelenMao/MSGAN)|



### Others

| nickname | paper name                      | paper links                               | note | conference | code |
| -------- | ------------------------------- | ----------------------------------------- | ---- | ---------- | ---------- |
| SIMS     | Semi-parametric Image Synthesis | [arxiv](https://arxiv.org/abs/1804.10992) |      | CVPR 2018  |

