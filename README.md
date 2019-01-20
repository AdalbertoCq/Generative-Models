# Generative-Models
This is a repository papers and code on different generative models.

## GANs.
* Original GAN: 'Generative Adversarial Networks' Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio. 2014. [[Arxiv]](https://arxiv.org/pdf/1406.2661.pdf).
* DCGAN: 'Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks' Alec Radford, Luke Metz, Soumith Chintala. 2016. [[Arxiv]](https://arxiv.org/abs/1511.06434). [[Code]](https://github.com/AdalbertoCq/Generative-Models/blob/master/GANs/DCGAN.py).

* __Cost function improvement proposals__:
  * CGAN: 'Conditional Generative Nets' Mehdi Mirza, Simon Osindero. 2014. [[Arxiv]](https://arxiv.org/abs/1411.1784). [[Code]]().
  * ACGAN: 'Conditional Image Synthesis With Auxiliary Classifier GANs' Augustus Odena, Christopher Olah, Jonathon Shlens. 2016. [[Arxiv]](https://arxiv.org/abs/1610.09585). [[Code]]().
  * InfoGAN: 'InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets' Xi Chen, Yan Duan, Rein Houthooft, John Schulman, Ilya Sutskever, Pieter Abbeel. 2016. [[Arxiv]](https://arxiv.org/abs/1606.03657). [[Code]]().
  * LSGAN: 'Least Squares Generative Adversarial Networks' Xudong Mao, Qing Li, Haoran Xie, Raymond Y.K. Lau, Zhen Wang, Stephen Paul Smolley. 2017. [[Arxiv]](https://arxiv.org/abs/1611.04076). [[Code]](https://github.com/AdalbertoCq/Generative-Models/blob/master/GANs/LSGAN.py).
  * WGAN: 'Wassertein GAN' Martin Arjovsky, Soumith Chintala, Léon Bottou. 2017. [[Arxiv]](https://arxiv.org/abs/1701.07875). [[Code]](https://github.com/AdalbertoCq/Generative-Models/blob/master/GANs/WGAN.py).
  * WGAN-GP: 'Improved Training of Wasserstein GANs' Ishaan Gulrajani, Faruk Ahmed, Martin Arjovsky, Vincent Dumoulin, Aaron Courville. 2017. [[Arxiv]](https://arxiv.org/abs/1704.00028). [[Code]](https://github.com/AdalbertoCq/Generative-Models/blob/master/GANs/WGAN_GP.py).
  * EBGAN: 'Energy-based Generative Adversarial Network' Junbo Zhao, Michael Mathieu, Yann LeCun. 2016. [[Arxiv]](https://arxiv.org/abs/1609.03126). [[Code]]().
  * BEGAN: 'BEGAN: Boundary Equilibrium Generative Adversarial Networks' David Berthelot, Thomas Schumm, Luke Metz
. 2017. [[Arxiv]](https://arxiv.org/abs/1703.10717). [[Code]]().
  * RSGAN & RaSGAN: 'The relativistic discriminator: a key element missing from standard GAN' Alexia Jolicoeur-Martineau. 2018. [[Arxiv]](https://arxiv.org/abs/1807.00734). [RaSGAN Code](https://github.com/AdalbertoCq/Generative-Models/blob/master/GANs/RaSGAN.py). [RaLSGAN Code](https://github.com/AdalbertoCq/Generative-Models/blob/master/GANs/RaLSGAN.py). [RaSGAN-GP Code](https://github.com/AdalbertoCq/Generative-Models/blob/master/GANs/RaSGAN_FP.py).
  * DRAGAN: 'On Convergence and Stability of GANs' Naveen Kodali, Jacob Abernethy, James Hays, Zsolt Kira
. 2017. [[Arxiv]](https://arxiv.org/abs/1705.07215). [[Code]]().
  * Spectral GAN: 'Spectral Normalization for Generative Adversarial Networks' Takeru Miyato, Toshiki Kataoka, Masanori Koyama, Yuichi Yoshida. 2018. [OpenReview](https://openreview.net/forum?id=B1QRgziT-). [[Code]]().
  * BigGAN: 'Large Scale GAN Training for High Fidelity Natural Image Synthesis' Andrew Brock, Jeff Donahue, Karen Simonyan
. 2018. [[Arxiv]](https://arxiv.org/abs/1809.11096). [[Code]]().
  
* __Network changes proposals__:
  * StackGAN: 'StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks' Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas. 2016. [[Arxiv]](https://arxiv.org/abs/1612.03242). [[Code]]().
  * SaGAN: 'Self-Attention Generative Adversarial Networks' Han Zhang, Ian Goodfellow, Dimitris Metaxas, Augustus Odena
. 2018. [[Arxiv]](https://arxiv.org/abs/1805.08318). [[Code]]().
  * ProGAN: 'Progressive Growing of GANs for Improved Quality, Stability, and Variation' Tero Karras, Timo Aila, Samuli Laine, Jaakko Lehtinen. 2018. [[Arxiv]](https://arxiv.org/abs/1710.10196). [[Code]]().
  * Style-GAN: 'A Style-Based Generator Architecture for Generative Adversarial Networks' Tero Karras, Samuli Laine, Timo Aila. 2018. [[Arxiv]](https://arxiv.org/abs/1812.04948). [[Code]]().
  
* __Applications__:
  * Cycle-GANs: 'Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks' Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros. 2017. [[Arxiv]](https://arxiv.org/abs/1703.10593). [[Code]]().
  * SRGANs: 'Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network' Christian Ledig, Lucas Theis, Ferenc Huszar, Jose Caballero, Andrew Cunningham, Alejandro Acosta, Andrew Aitken, Alykhan Tejani, Johannes Totz, Zehan Wang, Wenzhe Shi. 2016. [[Arxiv]](https://arxiv.org/abs/1609.04802). [[Code]]().
  * ESRGAN: 'ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks' Xintao Wang, Ke Yu, Shixiang Wu, Jinjin Gu, Yihao Liu, Chao Dong, Chen Change Loy, Yu Qiao, Xiaoou Tang. 2018. [[Arxiv]](https://arxiv.org/abs/1809.00219). [[Code]]().
  * GAWWN: 'Learning What and Where to Draw' Scott Reed, Zeynep Akata, Santosh Mohan, Samuel Tenka, Bernt Schiele, Honglak Lee. 2016 [[Arxiv]](https://arxiv.org/abs/1610.02454). [[Code]]().

* GAN Training & Studies:
  * 'Improved Techniques for Training GANs' Tim Salimans, Ian Goodfellow, Wojciech Zaremba, Vicki Cheung, Alec Radford, Xi Chen. 2016. [[Arxiv]](https://arxiv.org/abs/1606.03498).
  * 'Are GANs Created Equal? A Large-Scale Study' Mario Lucic, Karol Kurach, Marcin Michalski, Sylvain Gelly, Olivier Bousquet
. 2017. [[Arxiv]](https://arxiv.org/abs/1711.10337).
  * 'Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning' Takeru Miyato, Shin-ichi Maeda, Masanori Koyama, Shin Ishii. 2017. [[Arxiv]](https://arxiv.org/abs/1704.03976).
   

## VAEs.
* VAE: 'Auto-Encoding Variational Bayes' Diederik P Kingma, Max Welling. 2013. [[Arvix]](arxiv.org/abs/1312.6114). [[Code]]().
* Wassertein VAE: 'Wasserstein Auto-Encoders' Ilya Tolstikhin, Olivier Bousquet, Sylvain Gelly, Bernhard Schoelkopf. 2018. [[Arvix]](https://arxiv.org/pdf/1711.01558.pdf). [[Code]]().
* ['Tutorial on Variational Autoencoders' Doersch C, et al. 2016](https://arxiv.org/abs/1606.05908)
* ['Learning Structured Output Representation using Deep Conditional Generative Models' Sohn K, Yan X, Lee H, et al. 2014](https://papers.nips.cc/paper/5775-learning-structured-output-representation-using-deep-conditional-generative-models)
* ['Autoencoding beyond pixels using a learned similarity metric' Anders Boesen Lindbo Larsen, Søren Kaae Sønderby, Hugo Larochelle, Ole Winther. 2015](https://arxiv.org/abs/1512.09300)
 

## Autoregressive Models.
* ['Neural Autoregressive Distribution Estimation' Benigno Uria, Marc-Alexandre Côté, Karol Gregor, Iain Murray, Hugo Larochelle. 2016](https://arxiv.org/abs/1605.02226)
* ['RNADE: The real-valued neural autoregressive density-estimator' Benigno Uria, Iain Murray, Hugo Larochelle. 2014](https://arxiv.org/abs/1306.0186)
* ['MADE: Masked Autoencoder for Distribution Estimation' Mathieu Germain, Karol Gregor, Iain Murray, Hugo Larochelle. 2015](https://arxiv.org/abs/1502.03509)
* ['Pixel Recurrent Neural Networks' Aaron van den Oord, Nal Kalchbrenner, Koray Kavukcuoglu. 2016](https://arxiv.org/abs/1601.06759)
* ['Conditional Image Generation with PixelCNN Decoders' Aaron van den Oord, Nal Kalchbrenner, Koray Kavukcuoglu. 2016](https://arxiv.org/abs/1606.05328)
* ['PixelCNN++: Improving the PixelCNN with Discretized Logistic Mixture Likelihood and Other Modifications' Tim Salimans, Andrej Karpathy, Xi Chen, Diederik P. Kingma. 2017](https://arxiv.org/abs/1701.05517)
* ['WaveNet: A Generative Model for Raw Audio' Aaron van den Oord, Sander Dieleman, Heiga Zen, Karen Simonyan, Oriol Vinyals, Alex Graves, Nal Kalchbrenner, Andrew Senior, Koray Kavukcuoglu. 2016](https://arxiv.org/pdf/1609.03499.pdf)

## Normalizing Flows.
* ['Glow: Generative Flow with Invertible 1x1 Convolutions' Kingma D Dhariwal P. 2018](https://arxiv.org/abs/1807.03039)
* ['NICE: Non-linear Independent Components Estimation' Dinh L Krueger D Bengio Y. 2014](https://arxiv.org/abs/1410.8516)
* ['Density estimation using Real NVP' Dinh L Sohl-Dickstein J Bengio S. 2016](https://arxiv.org/abs/1605.08803)

* VAE and Normalizing Flows:
  * ['Improving Variational Auto-Encoders using Householder Flow' Tomczak J Welling M. 2016](https://arxiv.org/abs/1611.09630)
  * ['Flow-GAN: Combining Maximum Likelihood and Adversarial Learning in Generative Models' Grover A Dhar M Ermon S. 2017](https://arxiv.org/abs/1505.05770)

* GAN and Normalizing Flows:
  * ['Variational Inference with Normalizing Flows' Rezende D Mohamed S. 2015](https://arxiv.org/abs/1705.08868)

## Evaluation of Generative Models.
* ['A note on the evaluation of generative models' Theis L Oord A Bethge M. 2015](https://arxiv.org/abs/1511.01844)
* ['Pros and Cons of GAN Evaluation Measures' Borji A. 2018](https://http://arxiv.org/abs/1802.03446)
* [Stanford CS236: Deep Generative Models: Evaluating Generative Models](http://cs236.stanford.edu/assets/slides/cs236_lecture11.pdf)





