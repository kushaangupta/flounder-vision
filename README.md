# flounder-vision

Neuromatch Academy - Deep Learning 2021 project for group `Flounder Vision` of
pod `Nice Flounders`.

---
## Abstract

There is a lot of recent interest in comparing the learned representations in
deep neural networks to the representations in the human brain. Most of the
research along these lines use task-optimized neural networks, trained to
perform a specific task (like image classification). The learned
representations in these networks are influenced by two factors, (i) the visual
features of the input stimulus, and (ii) the semantic requirements of the
specific task. However, assessing the individual influence of these two
components is difficult and largely unexplored. To address this we attempt a
comparison between task-optimized neural network and a task-agnostic neural
network. Thus, we propose using a variational autoencoder (VAE), a generative
model trained to represent images using a low-dimensional latent space. Since a
VAE is not trained for a specific task, the latent representations of the VAE
are governed only by visual features of the presented stimulus. We compare the
representations of a VAE (task-agnostic) to the layer-wise representations of a
neural network trained to classify images (task-optimized). Next, to examine
the correspondence of the VAE latent space to the representational spaces of
different visual regions, we train a network model that maps fMRI responses
from these regions to their corresponding latent representations. We also probe
the representational space in the fMRI responses and the latent space using
representational similarity analysis (RSA) to find similarities and
differences. In summary, our work aims to understand the learned
representations in task-agnostic deep-learning models, and to compare them with
representations in the visual cortex.
