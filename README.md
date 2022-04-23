# Transform-Day-time-to-night-time-images-for-Autonomous-Drive
To develop new software around automated detection of cars, pedestrians at all conditions for autonomous drive. One major bottleneck is data collection under severe weather conditions, especially capturing night-time images. So this project is to generate night time equivalent images from daytime images, such that we have access to some outdoor images acquired at night and some at day, but no pairwise images are available.

In this project we implement CycleGAN using Keras with the intention to transform Day time to night time images for Autonomous Drive like in:
https://github.com/simontomaskarlsson/CycleGAN-Keras.

* This project is to generate night time equivalent images from daytime images, such that had access to some outdoor images acquired at night and some at day, but no pairwise images are available.

* CycleGAN model architecture used as it comprised of two generator models and each generator has a corresponding discriminator model.

* The discriminator and generator models are trained in an adversarial zero-sum process, like normal GAN models.

* The project goal is to train such a 2 set Generator-Discriminator pair, to finally generate night-time images from day-time ones and quantify performance.
