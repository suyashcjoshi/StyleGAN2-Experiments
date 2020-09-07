# StyleGAN2-Experiments
Google Colab Notebook to play with StyleGAN for generating images and videos. Provide your own image and experiment with code in the notebook.

### How to Run: Download and run locally or click below to run on Google Colab using your Google Account
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/weiji14/deepbedmap/]


### Example Input : Suyash Joshi's Portrait Image experimentation with StyleGAN2
![Suyash Joshi - Portrait Image](https://github.com/suyashjoshi/StyleGAN2-Experiments/blob/master/sj-portrait.png?raw=true)

### Outputs : Aligns the face and generated from the Latent Space

<img src="https://github.com/suyashjoshi/StyleGAN2-Experiments/blob/master/sj-StyleGAN_Generated.png?raw=true" width="460">

### Outputs : Interpolates between my generated image with Trump's

<img src="https://github.com/suyashjoshi/StyleGAN2-Experiments/blob/master/sj-trump-interpolation.gif" width="460">

### Additional Resources

- [GAN Tutorial](https://machinelearningmastery.com/what-are-generative-adversarial-networks-gans/)

- [Ian Goodfellow's Tutorial on GAN from 2016 NIPS on YouTube](https://www.youtube.com/watch?v=HGYYEUSm-0Q)

- [Original StyleGAN paper](https://arxiv.org/abs/1812.04948), [StyleGAN2 paper](https://arxiv.org/abs/1912.04958), [StyleGAN2 official TensorFlow implementation](https://github.com/NVlabs/stylegan2).

- Sampling Generative Networks: [paper](https://arxiv.org/abs/1609.04468)

- StyleGAN2 Distillation for Feedforward image manipulation: [paper](https://arxiv.org/abs/2004.02546), [github repo](https://github.com/EvgenyKashin/stylegan2-distillation)

- GANSpace: Discovering Interpretable GAN Controls: [paper](https://arxiv.org/abs/2004.02546), [code](https://github.com/harskish/ganspace), [colab notebook](https://colab.research.google.com/github/harskish/ganspace/blob/master/notebooks/Ganspace_colab.ipynb)

- Berns and Colton. 2020. Bridging Generative Deep Learning and Computational Creativity. Proceedings of the 11th International Conference on Computational Creativity. [Paper](http://sebastianberns.com/iccc2020bridging/)

- Network Bending: Manipulating The Inner Representations of Deep Generative Models: [paper](https://arxiv.org/abs/2005.12420), [code](https://github.com/terrybroad/network-bending), [colab notebook](https://colab.research.google.com/github/dvschultz/ml-art-colabs/blob/master/Network_Bending_Static_Images.ipynb)

### Acknowledgements

Thanks to [Sebastian Berns](http://sebastianberns.com/), Queen Mary, University of London ([@sebastianberns](https://twitter.com/sebastianberns)) and [Terence Broad](https://terencebroad.com/), Goldsmiths, University of London ([@Terrybroad](https://twitter.com/Terrybroad)) for conducting this tutorial at ICCC 20 Conference. Also thanks to the original StyleGAN & StyleGAN2 authors Tero Karras, Samuli Laine, Timo Aila, Miika Aittala, Janne Hellsten and Jaakko Lehtinen for their excellent work in advancing the state of the art of generative models. Also thanks to Kim Seonghyeon for providing an open source [PyTorch implementation](https://github.com/rosinality/stylegan2-pytorch) used in this notebook. Also thanks to Dmitry Nikitko for providing the [code we have used here for aligning images](https://github.com/Puzer/stylegan-encoder) before projection into StyleGAN and the figure that we have used to demonstrate the vector arithmetic.

