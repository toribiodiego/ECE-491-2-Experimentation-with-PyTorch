

> This repository contains the code for **ECE 491: Experimentation with PyTorch**, a 3-credit graduate-level course at The Cooper Union for the Advancement of Science and Art, offering hands-on experience with deep learning using PyTorch.


## Experimentation with PyTorch
**Independent Study, Spring 2025**  
**Instructor:** Professor Carl Sable

### Overview

This independent study provides a practical introduction to deep learning, emphasizing proficiency in the PyTorch framework and the Hugging Face ecosystem. Through focused study of key textbook chapters and interactive online tutorials, students gain both theoretical foundations and hands-on experience required to conduct original research or advanced projects.


### Material

The textbook [*Machine Learning with PyTorch and Scikit-Learn*](https://www.goodreads.com/en/book/show/60098440-machine-learning-with-pytorch-and-scikit-learn) by Sebastian Raschka, Yuxi (Hayden) Liu, and Vahid Mirjalili provides a solid foundation in PyTorch fundamentals and deep learning theory, including:

- Building and optimizing neural networks with PyTorch's torch.nn and torch.optim modules.
- Streamlining projects using PyTorch Lightning.
- Training and deploying language models with the *Hugging Face Trainer API*.

Complementing this, the [*Hugging Face NLP Course*](https://huggingface.co/learn/nlp-course/en/chapter1/1) offers practical training for modern research workflows, including:

- Working with pretrained transformer models and tokenizers
- Fine-tuning Hugging Face models for specific tasks
- Using Hugging Face datasets for efficient experimentation




### Repository Structure

- **Final_Project**


### Final Project

The Project, *Efficient ViT's with Dynamic Tanh*, explores how different normalization methods impact vision transformers for image classification. Inspired by the paper [Transformers without Normalization](https://arxiv.org/pdf/2503.10622), this study develops two versions of a ViT‑Base model—one using traditional Layer Normalization (LN) and another replacing it with Dynamic Tanh (DyT). By applying iterative pruning and integer quantization, we compare their training stability, accuracy, and inference efficiency to see if the normalization‑free DyT approach can match or exceed the performance of conventional LN, offering new insights for building efficient models in resource‑constrained environments.