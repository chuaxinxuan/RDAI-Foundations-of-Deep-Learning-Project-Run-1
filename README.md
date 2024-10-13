## RDAI: Foundations of Deep Learning Project Run 1

For the RDAI: Foundations of Deep Learning Project, I would like to explore how well deep learning models can differentiate between real and AI-Generated Synthetic Images.

The dataset was obtained from Kaggle: https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images/data

The dataset contains 60,000 synthetically-generated images and 60,000 real images (collected from CIFAR-10). The CIFAR-10 is a dataset consisting of 60,000 32x32 colour images, in 10 classes (6000 images per class). In the CIFAR-10 dataset, there are 50,000 training images and 10,000 testing images.


The two classes in this dataset are - REAL and FAKE:
* The REAL images are obtained from the CIFAR-10 dataset.
* The FAKE images are generated from the equivalent images of CIFAR-10 with Stable Diffusion version 1.4
  
Hence, there are a total of 100,000 images for training and 20,000 images for testing.
