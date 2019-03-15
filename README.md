# CV papers



### Image Transfer

* [image style transfer using convolutional neural networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)：使用预训练CNN提取特征，反向传播优化输入图片。
* [Deep Photo Style Transfer](https://arxiv.org/abs/1703.07511)：在进行风格转换的基础上更多保留细节。



### Image to Image GAN

* [BicycleGAN](https://arxiv.org/pdf/1711.11586.pdf)：解决multimodal图像转换问题，即一张图片可转换成多张不同的图片，使用pair数据。
* [CycleGAN](https://arxiv.org/pdf/1703.10593.pdf)：解决不同领域图像转换问题。使用非Pair 数据，提出cycle consistency loss、identity loss。
* [StarGAN](https://arxiv.org/pdf/1711.09020.pdf)：解决多领域间的图像转换问题。使用了label信息。Conditional + CycleGAN。
* [Unsupervised Image-to-Image Translation Networks](https://arxiv.org/pdf/1703.00848.pdf)：UNIT，使用相同的latent code和不同的Generator来生成不同领域的图片。
* [MUNIT](https://arxiv.org/pdf/1804.04732.pdf)：解决Multimodal图像转换问题，使用非pair数据，将图片encode成content和style两个code。