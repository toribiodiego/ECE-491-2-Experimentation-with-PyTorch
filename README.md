

> This repository contains the code for **ECE 491: Experimentation with PyTorch**, a 3-credit graduate-level course at The Cooper Union for the Advancement of Science and Art, offering hands-on experience with deep learning using PyTorch.


## Experimentation with PyTorch
**Spring 2025 Independent Study**  
**Instructor:** Professor Carl Sable

## Course Overview
The *independent study* is designed to build true proficiency in PyTorch by working at a low level with the framework, beyond relying on high-level abstractions. Through hands-on practice and guided exploration, students gain the skills needed to develop original deep learning projects that go beyond standard, boilerplate implementations.

- Core PyTorch operations and custom model development  
- Loss functions, optimizers, and training loops  
- Transfer learning with pretrained models from Hugging Face  
- Applications in NLP, computer vision, audio, and video processing  
- Weekly activities based on *Machine Learning with PyTorch and Scikit-Learn* and Hugging Face tutorials  
- Final projects showcasing innovative applications beyond conventional deep learning approaches  


## Repository Structure

- **some-file**


## Final Project Description

This project, *Pruning and Quantizing a Normalization-Free Network With Dynamic Tanh*, investigates how compression techniques like pruning and quantization work on networks that skip traditional normalization layers by using Dynamic Tanh (DyT) instead. Inspired by the paper [Transformers without Normalization](https://arxiv.org/pdf/2503.10622), the goal is to see how removing normalization affects accuracy and stability after compression, and to understand how well DyT adapts to different levels of precision. By comparing these normalization-free models with standard ones, the project seeks to discover innovative strategies for deploying efficient deep learning models on devices with limited resources.