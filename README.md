# Monet Generator

The goal of this project is to generate 7000+ **monet-style paintings from photos**. <br />
(Kaggle challenge: https://www.kaggle.com/competitions/gan-getting-started/). <br />
Here are some example images I generated:

![example1](./examples/1.png)
![example2](./examples/2.png)
![example3](./examples/3.png)
![example4](./examples/4.png)
![example5](./examples/5.png)

## Introduction

The backbone of this project is a Generative Adversarial Network (GAN). A GAN consists of a generator and a discriminator who work against each other. The generator attempts to trick the discriminator, while the discriminator tries to accurately classify the real vs. generated images.

## How to Use

1. Make sure you've installed necessary packages in the **Setup** section of painter.ipynb. Running this notebook doesn't require GPU or TPU.
2. Code for saving and restoring checkpoints are provided in the notebook to help training the model over a large number of epochs.




