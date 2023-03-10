# Multimodal-Unsupervised-Image-to-Image-Translation

based on: https://arxiv.org/abs/1804.04732v2

The MUNIT framework is an extension of the UNIT (Unsupervised-Image-to-Image-translation) framework. MUNIT uses a combination of a VAE and a GAN but adds an additional constraint to the training process to enforce disentanglement in the learned latent space, where each dimension corresponds to a specific generative factor, such as the pose of an object or the color of an image.

This is achieved by using a shared content latent space for the VAE and GAN, but with different encoders and decoders for each modality (i.e., each domain of the input and output images).
