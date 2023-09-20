# GAN_MNIST
Generating GAN images by training on MNIST dataset
In this project, we provide Python code for training a GAN on the MNIST dataset. The GAN is composed of a generator network that creates synthetic MNIST digits and a discriminator network that learns to distinguish between real and fake images. The GAN is trained iteratively, with the generator aiming to produce more convincing fake images, while the discriminator gets better at telling real from fake.

![Generated Images](https://github.com/ashinbabu/GAN_MNIST/assets/90083801/3e35f18a-6153-4185-8048-aaf6de52b0ad)

# Saving the Trained Generator Model

The trained generator model can be saved for later use. It is saved as 'generator.pth' in the project directory. You can load this model to generate MNIST-style images without retraining the GAN.
