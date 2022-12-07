# Image-Super-Resolution
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/GeorgiosKalantzis/Image-Super-Resolution/blob/main/Notebooks/Load_data.ipynb "Open in Colab")
#### Overview
Our approach to the SR problem by building upon the work of the following papers and by providing our model with extra loss functions and a diverse set of weight parameters.
* [ Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network](https://arxiv.org/abs/1609.04802)
* [A U-Net Based Discriminator for Generative Adversarial Networks](https://arxiv.org/abs/2002.12655 

#### Dataset
You can download DIV2K dataset, from the following links : [train_HR](https://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_HR.zip), [train\_LR\_bicubic_X4](https://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_LR_bicubic_X4.zip), [valid_HR](https://data.vision.ee.ethz.ch/cvl/DIV2K/validation_release/DIV2K_valid_HR.zip), [valid\_LR\_bicubic_X4](https://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_LR_bicubic_X4.zip).

Your directory structure for the dataset should look like this:
```
  DIV2K
      └── DIV2K_train_HR
      ├── DIV2K_train_LR_bicubic
      ├── DIV2K_valid_HR
      └── DIV2K_valid_LR_bicubic
```
#### Qualitative Results 
![alt text](https://github.com/GeorgiosKalantzis/Image-Super-Resolution/blob/main/result.png?raw=true)
