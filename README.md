# Cycle-GAN-Monet
This repository contains the code and final report for my deep learning final project. The project focuses on generating Claude Monet-style images using CycleGAN and Neural Style Transfer techniques. Additionally, it tackles the challenge of using only 10% of the Monet dataset.
## Introduction
In this project, I explore the fascinating field of image generation and artistic style transfer using deep learning techniques. The primary objective is to generate images that mimic the distinct artistic style of Claude Monet. Two approaches are employed: CycleGAN and Neural Style Transfer.

1. CycleGAN: CycleGAN is an unsupervised learning algorithm that can learn to translate images from one domain to another. In this project, CycleGAN is trained to transform images from a source domain (e.g., photographs) into images that resemble Monet paintings. The network is trained in a cyclic manner, ensuring that the translated images can be accurately converted back to the original domain.

2. Neural Style Transfer: Neural Style Transfer is a technique that allows the transfer of style from one image to another, effectively merging the content of one image with the style of another. In this project, the content images are selected from the Monet dataset, and the style images are chosen from a wide range of Monet paintings. The neural network then combines the content and style to generate Monet-style images.

The project also tackles the challenge of using only 10% of the Monet dataset, making it computationally efficient while maintaining impressive results.
