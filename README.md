# CV papers



### Image Transfer

| nickname              | paper name                                               | paper links                                                  | note                                          | conference |
| --------------------- | -------------------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------- | ---------- |
| Neural Style Transfer | image style transfer using convolutional neural networks | [cv_foundation](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) | 使用预训练CNN提取特征，反向传播优化输入图片。 | CVPR 2016  |
|                       | Deep Photo Style Transfer                                | [arxiv](https://arxiv.org/abs/1703.07511)                    | 在Neural Style Transfer的基础上更多保留细节。 |            |
|                       | Deep Painterly Harmonization                             | arxiv                                                        | Neural Style Transfer + Gram matrix + mapping |            |



### Image to Image GAN

| nickname   | paper name                                                   | paper links                                   | note                           | conference |
| ---------- | ------------------------------------------------------------ | --------------------------------------------- | ------------------------------ | ---------- |
|            | Image Generation from Sketch Constraint Using Contextual GAN | [arxiv](https://arxiv.org/pdf/1711.08972.pdf) |                                |            |
| BicycleGAN |                                                              | [arxiv](https://arxiv.org/pdf/1711.11586.pdf) | multimodal, pair data          |            |
| CycleGAN   |                                                              | [arxiv](https://arxiv.org/pdf/1703.10593.pdf) | non-pair data                  |            |
| StarGAN    | StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | [arxiv](https://arxiv.org/pdf/1711.09020.pdf) | Conditional + CycleGAN, label  |            |
| UNIT       | Unsupervised Image-to-Image Translation Networks             | [arxiv](https://arxiv.org/pdf/1703.00848.pdf) | Encoder + Generator            |            |
| MUNIT      | Multimodal Unsupervised Image-to-Image Translation           | arxiv                                         | UNIT + CycleGAN, non-pair data | ECCV 2018  |

* 
* [MUNIT](https://arxiv.org/pdf/1804.04732.pdf)：解决Multimodal图像转换问题，使用非pair数据，将图片encode成content和style两个code。



### Image Inpainting

| nickname    | paper name                                            | paper links                                   | note | conference |
| ----------- | ----------------------------------------------------- | --------------------------------------------- | ---- | ----------- |
|  | Globally and Locally Consistent Image Completion | [] |  | SIGGRAPH 2017 |
| Deepfill v1 | Generative Image Inpainting with Contextual Attention | [arxiv](https://arxiv.org/pdf/1801.07892.pdf) |      |CVPR 2018|
| Deepfill v2 | Free-Form Image Inpainting with Gated Convolution | [arxiv](https://arxiv.org/pdf/1806.03589.pdf) | ||
| SC-FEGAN | SC-FEGAN: Face Editing Generative Adversarial Network with User’s Sketch and Color | arxiv | ||



### Noise/Latent GAN
| nickname | paper name                                                   | paper links                                   | note | conference |
| -------- | ------------------------------------------------------------ | --------------------------------------------- | ---- | ---------- |
| DCGAN    | Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks | [arxiv](https://arxiv.org/pdf/1511.06434.pdf) |      |            |
| PGGAN    | Progressive Growing of GANs for Improved Quality, Stability, and Variation | [arxiv](<https://arxiv.org/abs/1710.10196>)   |      | ICLR 2018  |
### Others

| nickname | paper name                      | paper links | note | conference |
| -------- | ------------------------------- | ----------- | ---- | ---------- |
| SIMS     | Semi-parametric Image Synthesis |             |      |            |

