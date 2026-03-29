# Essential AI/ML Curriculum for a Mathematically Advanced Reader

(As of 30 March 2026)

This repository contains a concise self-directed curriculum for studying machine learning and artificial intelligence from a mathematically serious perspective.

The aim is not to cover everything, but to identify a strong core: the books and papers that matter most for building real understanding without diffusing attention.

## Guiding Principle

This curriculum is designed around three ideas:

- **books are the backbone**
- **papers are landmarks**
- **depth matters more than breadth**

It is intended as a serious intellectual curriculum, not as a job-training checklist or a survey of every fashionable topic.

---

## Phase 1. Foundations

These are the core texts for the mathematical and conceptual foundations of machine learning.

### Books

- **Kevin P. Murphy**, *Probabilistic Machine Learning: An Introduction*
- **Shalev-Shwartz & Ben-David**, *Understanding Machine Learning: From Theory to Algorithms*
- **Goodfellow, Bengio, Courville**, *Deep Learning*
  Read selected chapters only.

### Main goals

- probabilistic modeling
- estimation and inference
- supervised and unsupervised learning
- regularization and generalization
- optimization basics
- core deep learning concepts

---

## Phase 2. Landmark Deep Learning and Language Model Papers

These papers mark the main architectural and conceptual turns in modern AI.

### Core papers

- **Krizhevsky, Sutskever, Hinton**, *ImageNet Classification with Deep Convolutional Neural Networks* (AlexNet)
- **He et al.**, *Deep Residual Learning for Image Recognition* (ResNet)
- **Vaswani et al.**, *Attention Is All You Need* (Transformer)
- **Devlin et al.**, *BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*
- **Brown et al.**, *Language Models are Few-Shot Learners* (GPT-3)
- **Kaplan et al.**, *Scaling Laws for Neural Language Models*

### Main goals

- understand why deep learning became dominant
- understand residual connections and attention
- understand pretraining and transfer
- understand the scaling paradigm behind modern LLMs

---

## Phase 3. Generative Modeling

This section gives the minimal serious path into modern generative models.

### Reading

- **Kevin P. Murphy**, *Probabilistic Machine Learning: Advanced Topics*
  Read the relevant chapters selectively.

### Core papers

- **Kingma & Welling**, *Auto-Encoding Variational Bayes* (VAE)
- **Goodfellow et al.**, *Generative Adversarial Nets* (GAN)
- **Ho, Jain, Abbeel**, *Denoising Diffusion Probabilistic Models* (DDPM)

### Main goals

- latent-variable modeling
- variational inference
- adversarial training
- diffusion-based generation

---

## Phase 4. LLM Post-Training and Adaptation

This section covers the minimum needed to understand how modern large language models are adapted after pretraining.

### Core papers

- **Ouyang et al.**, *Training language models to follow instructions with human feedback* (RLHF)
- **Hu et al.**, *LoRA: Low-Rank Adaptation of Large Language Models*

### Main goals

- instruction tuning
- human feedback and alignment
- parameter-efficient fine-tuning
- the distinction between pretraining and post-training

---

## Phase 5. Reinforcement Learning

This section provides the minimum serious route into reinforcement learning.

### Book

- **Sutton & Barto**, *Reinforcement Learning: An Introduction*

### Core papers

- **Mnih et al.**, *Playing Atari with Deep Reinforcement Learning* (DQN)
- **Schulman et al.**, *Proximal Policy Optimization Algorithms* (PPO)

### Main goals

- Markov decision processes
- value methods and policy methods
- exploration
- function approximation
- deep reinforcement learning

---

## Phase 6. Advanced Mathematical Expansion

These are important, but not part of the minimal first-pass core.
They should be added only after the main curriculum is reasonably secure.

### Possible directions

- **Hastie, Tibshirani, Friedman**, *The Elements of Statistical Learning*
- **Vershynin**, *High-Dimensional Probability*
- **Wainwright**, *High-Dimensional Statistics*
- **Peyré & Cuturi**, *Computational Optimal Transport*
- **Amari**, *Information Geometry and Its Applications*
- **Jacot, Gabriel, Hongler**, *Neural Tangent Kernel*
- **Grohs & Kutyniok (eds)**, *Mathematical Aspects of Deep Learning*
- **Jentzen et al.**, *Mathematical Introduction to Deep Learning*
- causality
- representation learning and self-supervision

### Purpose

This phase is for moving from learning the field to identifying possible research directions.

---

## Recommended Order

1. Murphy, *Probabilistic Machine Learning: An Introduction*
2. Shalev-Shwartz & Ben-David, *Understanding Machine Learning*
3. Goodfellow, Bengio, Courville, *Deep Learning* (selected chapters)
4. AlexNet
5. ResNet
6. Transformer
7. BERT
8. GPT-3
9. Scaling Laws
10. Murphy, *Probabilistic Machine Learning: Advanced Topics* (selected chapters)
11. VAE
12. GAN
13. DDPM
14. Ouyang et al. (RLHF)
15. Hu et al. (LoRA)
16. Sutton & Barto, *Reinforcement Learning*
17. DQN
18. PPO

---

## What This Curriculum Is

This curriculum is:

- mathematically serious
- selective rather than exhaustive
- oriented toward understanding rather than trend-chasing
- suitable for a self-learner preparing for research-level study

## What This Curriculum Is Not

This curriculum is not primarily:

- a coding bootcamp
- an MLOps roadmap
- a cloud/deployment guide
- a production engineering syllabus
- an industry interview checklist

Those things may be important in other settings, but they are not the central purpose of this repository.

---

## Suggested Use

A reasonable way to use this curriculum is:

- study the books carefully
- read the papers as conceptual landmarks
- take notes in your own words
- implement small toy examples in parallel if needed
- avoid expanding the list too quickly

The main danger is not reading too little.
It is reading too diffusely.

---

## Status

This is a living document and may be revised over time.
