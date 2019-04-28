# This Gemstone Does Not Exist
Deep Convolutional Generative Adversarial Network (DCGAN) for generating gemstones.

# Dependencies
* pandas
* numpy
* matplotlib
* keras
* tqdm
* [Gemstone Dataset](https://github.com/loliverhennigh/Crystal-Gems)
* [DCGAN](https://github.com/eriklindernoren/Keras-GAN)

# Experimental Settings
* Image resolution: 110x110x3 (Padded to 112x112x3)
* No. of training images: 2937
* Total training epochs: 15000

# Examples of Generated Gemstones
### Epoch 50
![gem_50](https://user-images.githubusercontent.com/27071473/56861874-da212080-69d7-11e9-9980-8f875bf27367.png)
### Epoch 500
![gem_500](https://user-images.githubusercontent.com/27071473/56861898-10f73680-69d8-11e9-8ed8-7c01afbcf48a.png)
### Epoch 5000
![gem_5000](https://user-images.githubusercontent.com/27071473/56861917-2e2c0500-69d8-11e9-91cb-b0afc3ca5723.png)
### Epoch 15000
![gem_15000](https://user-images.githubusercontent.com/27071473/56861907-20767f80-69d8-11e9-9cae-bfdb33d9e9d7.png)

# References
* [Original paper](https://arxiv.org/abs/1511.06434)
* [Gemstone dataset](https://github.com/loliverhennigh/Crystal-Gems)
* [DCGAN](https://github.com/eriklindernoren/Keras-GAN)
