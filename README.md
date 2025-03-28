

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

This project, *Pruning and Quantizing a Normalization-Free Network With Dynamic Tanh*, investigates how compression techniques like pruning and quantization work on networks that skip traditional normalization layers by using Dynamic Tanh (DyT) instead. Inspired by the paper [Transformers without Normalization](https://arxiv.org/pdf/2503.10622), the goal is to see how removing normalization affects accuracy and stability after compression, and to understand how well DyT adapts to different levels of precision. By comparing these normalization-free models with standard ones, the project seeks to discover innovative strategies for deploying efficient deep learning models on devices with limited resources.