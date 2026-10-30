# Lab 9: Autoencoders and Representation Learning

In this lab, I did two main tasks to build and evaluate autoencoders using **PyTorch**:

### 1. Autoencoder Building and Training
- Built an autoencoder using an **Encoder**, **Bottleneck**, and **Decoder**.
- Trained the model using the **Adam optimizer** and **Mean Squared Error (MSE)** loss.
- Tested different **bottleneck sizes** and compared their reconstruction errors.

### 2. Representation Learning and Denoising
- Visualized the learned features using a **2D latent space**.
- Evaluated the learned representations using **Logistic Regression** for digit classification.
- Trained a **Denoising Autoencoder** to reconstruct clean images from noisy inputs.
- Compared the performance of the regular and denoising autoencoders.
