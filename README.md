# CV papers



### Content

* [Image Transfer](#Image-Transfer)
* [Image to Image GAN](#Image-to-Image-GAN)
* [Image Inpainting](#Image-Inpainting)
* [Noise/Latent GAN](#Noise/Latent-GAN)
* [Text to Image](#Text-to-Image)
* [Training Trick](#Training-Trick)
* [Others](#Others)





## Image Transfer

| nickname              | paper title                                          | paper link                                                  | note                                          | conference | code |
| --------------------- | -------------------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------- | ---------- | ---------- |
| Color Transfer | Color Transfer between Images | [IEEE](https://ieeexplore.ieee.org/document/946629) | mean, std |  |  |
| Neural Style Transfer | image style transfer using convolutional neural networks | [cv_foundation](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) | CNN + back propagation | CVPR 2016  ||
|                       | Deep Photo Style Transfer                                | [1703.07511](https://arxiv.org/abs/1703.07511)          | based on Neural Style Transfer |            ||
| | Deep Image Harmonization | [1703.00069](https://arxiv.org/abs/1703.00069) |  | ||
|                       | Deep Painterly Harmonization                             | [1804.03189](https://arxiv.org/abs/1804.03189)          | Neural Style Transfer + Gram matrix + mapping |            ||
| | Smart, Deep Copy-Paste | [1903.66763](https://arxiv.org/abs/1903.06763) | data augmentation | ||





## Image to Image GAN

| nickname   | paper title                                              | paper link                                   | note                           | conference | code |
| ---------- | ------------------------------------------------------------ | --------------------------------------------- | ------------------------------ | ---------- | ---------- |
|            | Image Generation from Sketch Constraint Using Contextual GAN | [1711.08972](https://arxiv.org/pdf/1711.08972.pdf) |                                |            ||
| pix2pix | Image-to-Image Translation with Conditional Adversarial Networks | [1611.07004](https://arxiv.org/abs/1611.07004) | | CVPR 2017 |[github](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)|
| BicycleGAN | Toward Multimodal Image-to-Image Translation                 | [1711.11586](https://arxiv.org/pdf/1711.11586.pdf) | multimodal, pair data          | NIPS 2017  |[github](https://github.com/junyanz/BicycleGAN)|
| DiscoGAN   | Learning to Discover Cross-Domain Relations with Generative Adversarial Networks | [1703.05192](https://arxiv.org/abs/1703.05192) |                                | ICML 2017  ||
| DualGAN | DualGAN: Unsupervised Dual Learning for Image-to-Image Translation | [1704.02510](https://arxiv.org/abs/1704.02510) | | ICCV 2017 |[github](https://github.com/duxingren14/DualGAN)|
| CycleGAN   | Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks | [1703.10593](https://arxiv.org/pdf/1703.10593.pdf) | unpaired data                  | ICCV 2017  |[github](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)|
| StarGAN    | StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | [1711.09020](https://arxiv.org/pdf/1711.09020.pdf) | Conditional + CycleGAN, label  | CVPR 2018 oral |[github](https://github.com/yunjey/stargan)|
| SketchyGAN | SketchyGAN: Towards Diverse and Realistic Sketch to Image Synthesis | [1801.02753](https://arxiv.org/abs/1801.02753) |  | CVPR 2018 |[github](https://github.com/wchen342/SketchyGAN)|
| GANimation | GANimation: Anatomically-aware Facial Animation from a Single Image | [1807.09251](https://arxiv.org/abs/1807.09251) |                                | ECCV 2018  |[github](https://github.com/brownvc/ganimorph)|
| UNIT       | Unsupervised Image-to-Image Translation Networks             | [1703.00848](https://arxiv.org/pdf/1703.00848.pdf) | Encoder + Generator            |            ||
| MUNIT      | Multimodal Unsupervised Image-to-Image Translation           | [1804.04732](https://arxiv.org/abs/1804.04732) | UNIT + CycleGAN, unpaired data | ECCV 2018  |[github](https://github.com/NVlabs/MUNIT)|
| DRIT | Diverse Image-to-Image Translation via Disentangled Representations | [1808.00948](https://arxiv.org/abs/1808.00948) |  | ECCV 2018 oral |[github](https://github.com/HsinYingLee/DRIT) & [High resolution version](https://github.com/hytseng0509/DRIT_hr)|
|  | Compatible and Diverse Fashion Image Inpainting | [1902.01096](https://arxiv.org/abs/1902.01096) | |  ||






## Image Inpainting

| nickname    | paper title                                       | paper link                                   | note | conference |code|
| ----------- | ----------------------------------------------------- | --------------------------------------------- | ---- | ----------- | ----------- |
|  | Globally and Locally Consistent Image Completion | [ACM](https://dl.acm.org/citation.cfm?id=3073659) |  | SIGGRAPH 2017 |[github](https://github.com/satoshiiizuka/siggraph2017_inpainting)|
| | High-Resolution Image Inpainting using **Multi-Scale** Neural Patch Synthesis | [1611.09969](https://arxiv.org/abs/1611.09969) |  |  ||
| Shift-Net | Shift-Net: Image Inpainting via Deep Feature Rearrangement | [1801.09392](https://arxiv.org/abs/1801.09392) |  |  ||
| Deepfill v1 | Generative Image Inpainting with **Contextual Attention** | [1801.07892](https://arxiv.org/pdf/1801.07892.pdf) |      |CVPR 2018|[github](https://github.com/JiahuiYu/generative_inpainting)|
| FaceShop | FaceShop: Deep Sketch-based Face Image Editing | [1804.08972](https://arxiv.org/abs/1804.08972) | |||
| Deepfill v2 | Free-Form Image Inpainting with **Gated Convolution** | [1806.03589](https://arxiv.org/pdf/1806.03589.pdf) | |||
| Edge-Connect | EdgeConnect: Generative Image Inpainting with Adversarial Edge Learning | [1901.00212](https://arxiv.org/abs/1901.00212) | ||[github](https://github.com/knazeri/edge-connect)|
| SC-FEGAN | SC-FEGAN: Face Editing Generative Adversarial Network with **User’s Sketch and Color** | [1902.06838](https://arxiv.org/abs/1902.06838) | |||
| PICNet | Pluralistic Image Completion | [1903.04227](https://arxiv.org/abs/1903.04227) | multimodal |CVPR 2019|[github](https://github.com/lyndonzheng/Pluralistic-Inpainting)|





## Noise/Latent GAN
| nickname | paper title                                              | paper link                                   | note | conference | code |
| -------- | ------------------------------------------------------------ | --------------------------------------------- | ---- | ---------- | ---------- |
| DCGAN    | Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks | [1511.06434](https://arxiv.org/pdf/1511.06434.pdf) |      |            ||
| PGGAN    | **Progressive Growing** of GANs for Improved Quality, Stability, and Variation | [1710.10196](<https://arxiv.org/abs/1710.10196>) |      | ICLR 2018  ||
| BigGAN | **Large Scale** GAN Training for High Fidelity Natural Image Synthesis | [1809.11096](https://arxiv.org/abs/1809.11096) | |  ||
| StyleGAN | A Style-Based Generator Architecture for Generative Adversarial Networks | [1812.04948](https://arxiv.org/abs/1812.04948) | |  |[github](https://github.com/NVlabs/stylegan)|





## Text to Image

| nickname | paper title                                              | paper link                                   | note | conference | code |
| -------- | ------------------------------------------------------------ | --------------------------------------------- | ---- | ---------- | ---------- |
| StackGAN | StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks | [1612.03242](https://arxiv.org/abs/1612.03242) |      | ICCV 2017 oral |[github](https://github.com/hanzhanggit/StackGAN), [v2](https://github.com/hanzhanggit/StackGAN-v2)|
| AttnGAN | AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks | [1711.10485](https://arxiv.org/abs/1711.10485) | attention |  ||





## Training Trick
| nickname | paper title | paper link | note | conference | code |
| -------- | ---------- | ----------- | ---- | ---------- | ---- |
| Conditional GAN | Conditional Generative Adversarial Nets | [1411.1784](https://arxiv.org/abs/1411.1784) |  |  |  |
| WGAN | Wasserstein GAN | [1701.07875](https://arxiv.org/abs/1701.07875) |  |  |  |
| WGAN-GP | Improved Training of Wasserstein GANs | [1704.00028](https://arxiv.org/abs/1704.00028) |  |  | [github](https://github.com/igul222/improved_wgan_training) |
| MSGAN | Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis | [1903.05628](https://arxiv.org/abs/1903.05628) | solved Condition GAN's model collapse | CVPR 2019 |[github](https://github.com/HelenMao/MSGAN)|





## Others

| nickname | paper name                      | paper links                               | note | conference | code |
| -------- | ------------------------------- | ----------------------------------------- | ---- | ---------- | ---------- |
| SIMS     | Semi-parametric Image Synthesis | [1804.10992](https://arxiv.org/abs/1804.10992) |      | CVPR 2018  ||
|  |  |  | |  ||

