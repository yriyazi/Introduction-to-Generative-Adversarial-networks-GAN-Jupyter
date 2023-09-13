# Different GANs Project

![Image Description](Images/Train-Data%20Sample.png)
*Caption: Train-Data Sample.*


![Image Description](Images/Wasserstein%20GAN.gif)
*Caption: Neural networks evolution.*


Welcome to the **Different GANs** GitHub project! In this repository, you'll find a collection of Jupyter Notebook files showcasing various Generative Adversarial Networks (GANs) and their applications. Each notebook provides an interactive and informative environment to explore and experiment with different GAN architectures and techniques.

## Project Overview

The repository includes the following Jupyter Notebook files:

- `Q1_1_dcgan.ipynb`: A notebook that demonstrates a Deep Convolutional GAN (DCGAN) architecture for image generation.

- `Q1_1_dcgan_augmented.ipynb`: This notebook explores DCGAN with augmented training data, enhancing the diversity of generated images.

- `Q1_3_dcgan_smoothing.ipynb`: A notebook showcasing DCGAN with image smoothing techniques to improve image quality.

- `Q1_3_dcgan_noise.ipynb`: This notebook delves into DCGAN with added noise for generating diverse and realistic images.

- `Q1_3_dcgan_augmented_smoothing+noise.ipynb`: An integrated approach combining augmentation, smoothing, and noise in DCGAN.

- `2_2_wgan.ipynb`: A notebook introducing Wasserstein GAN (WGAN) as an alternative to traditional GANs.

- `2_2_wgan_noise+smoothing.ipynb`: WGAN with noise addition and image smoothing for improved image synthesis.

- `2_2_wgan_augmented_noise+smoothing.ipynb`: A comprehensive notebook exploring augmented training, noise, and smoothing in WGAN.

# Wasserstein GAN (WGAN) Explanation

In the 2_2_wgan.ipynb notebook, you'll encounter the concept of Wasserstein GAN (WGAN). WGAN is a variant of the traditional GAN that aims to improve training stability and address some of the challenges associated with training difficulties and mode collapse.

WGAN introduces a different metric, called the Wasserstein distance or Earth Mover's distance, to measure the distance between the distributions of real and generated data. This metric provides a smoother and more informative gradient signal during training, enabling better convergence and more stable learning dynamics.

One of the key differences of WGAN is the use of a Lipschitz constraint on the discriminator, which helps ensure that the gradients remain stable and don't explode. This constraint is enforced by weight clipping in the discriminator or by using gradient penalty techniques.

In the 2_2_wgan.ipynb notebook, you'll learn about:

    The Wasserstein distance and how it differs from traditional GAN loss.
    Weight clipping and gradient penalty techniques to enforce the Lipschitz constraint.
    Practical implementation of WGAN using popular deep learning frameworks.
    Observing the training stability and mode collapse mitigation benefits of WGAN.

Feel free to dive into the notebook to gain a deeper understanding of Wasserstein GAN and its advantages over traditional GANs.

## Usage

To get started, simply open the desired notebook(s) using Jupyter Notebook or JupyterLab. Each notebook provides explanations, code snippets, and visualizations to guide you through the GAN architectures and techniques being demonstrated.

Feel free to modify the code, experiment with parameters, and observe the results interactively. These notebooks are designed to encourage exploration and learning in the field of generative modeling and GANs.

## Acknowledgments

The **Different GANs** project aims to provide an educational resource for individuals interested in understanding and experimenting with various GAN architectures. It's built on insights from the field of deep learning, computer vision, and generative modeling.

For deeper insights and further context, explore the code and content within each notebook.
