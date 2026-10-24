# Generative Adversarial Networks (GANs)

A hands-on implementation of **Vanilla GAN and Deep Convolutional GAN (DCGAN)** to understand how Generative Adversarial Networks learn data distributions and generate new, realistic samples.

## 📌 Overview

Generative Adversarial Networks (GANs) are deep learning models consisting of two neural networks — a **Generator** and a **Discriminator** — trained adversarially against each other.

The Generator learns to create realistic synthetic data, while the Discriminator learns to distinguish real samples from generated ones.

This project focuses on understanding the fundamentals of GANs and implementing two popular architectures: Vanilla GAN and DCGAN.

## 🧠 Concepts Covered

- Fundamentals of Generative Adversarial Networks
- Generator and Discriminator architectures
- Adversarial training and loss functions
- Binary Cross-Entropy loss
- Training loop and backpropagation
- Synthetic data generation
- Differences between fully connected and convolutional GAN architectures

## 🚀 Implementations

### 1. Vanilla GAN

Vanilla GAN is a basic GAN architecture that uses fully connected neural network layers.

**Generator**
- Takes random noise as input.
- Transforms the noise into synthetic samples using neural network layers.

**Discriminator**
- Takes real or generated samples as input.
- Predicts whether a sample is real or fake.

**Objective:** Learn the underlying data distribution and generate realistic samples through adversarial training.

### 2. Deep Convolutional GAN (DCGAN)

DCGAN extends the GAN architecture using convolutional neural network layers, making it suitable for image generation tasks.

**Generator**
- Uses transposed convolutional layers to generate images from random noise.
- Uses activation functions to learn meaningful image features.

**Discriminator**
- Uses convolutional layers to extract image features.
- Classifies input images as real or generated.

**Objective:** Generate image samples by learning spatial features through convolutional architectures.

## ⚖️ Vanilla GAN vs DCGAN

| Feature | Vanilla GAN | DCGAN |
|---|---|---|
| Architecture | Fully connected layers | Convolutional layers |
| Input | Flattened data or vectors | Image-shaped tensors |
| Feature learning | Dense representations | Spatial image features |
| Image generation | Basic | Better suited for images |
| Main purpose | Understand GAN fundamentals | Deep learning-based image generation |

## 🛠️ Tech Stack

- Python
- PyTorch or TensorFlow/Keras *(depending on the implementation)*
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## ⚙️ Workflow

1. Prepare and preprocess the dataset.
2. Initialize random noise for the Generator.
3. Generate synthetic samples.
4. Train the Discriminator using real and generated samples.
5. Train the Generator to fool the Discriminator.
6. Repeat adversarial training over multiple epochs.
7. Visualize generated samples and observe training progress.

## 📚 Learning Outcomes

- Developed an understanding of adversarial learning.
- Implemented Generator and Discriminator networks.
- Explored the differences between Vanilla GAN and DCGAN.
- Learned how neural networks can generate synthetic data.
- Practiced deep learning model training and visualization.

## 🔮 Future Improvements

- Experiment with different network architectures and hyperparameters.
- Improve generated sample quality and training stability.
- Explore Conditional GANs (CGANs) and Wasserstein GANs (WGANs).

## 👩‍💻 Author

**Khushi Pandey**

- GitHub: [khushi123438](https://github.com/khushi123438)

---

*Built as a hands-on deep learning project to explore Generative Adversarial Networks and image generation.*
