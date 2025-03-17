


> This repository contains the code for **ECE 491: Experimentation with PyTorch**, a graduate-level, 3-credit course offering hands-on deep learning experience with PyTorch. Under **Professor Carl Sable**'s guidance, it includes exercises from *Machine Learning with PyTorch and Scikit-Learn* by Raschka, Liu, and Mirjalili, the Hugging Face NLP Tutorial, and our final project work. The course is designed to deepen our PyTorch proficiency and inspire innovative final projects that transcend conventional deep learning approaches.



## Course Overview

In *Experimentation with PyTorch*, students gain practical experience with the PyTorch framework through weekly discussions, readings, and hands-on tutorials. The course covers a wide range of topics that deepen understanding of PyTorch, including the use of pre-built and pretrained models from the Hugging Face Hub as well as the development of custom layers, loss functions, and architectures. 

 While the primary focus is on NLP, the curriculum also touches on other machine learning domains such as computer vision, audio, and video processing. Ultimately, the course is designed to build proficiency in PyTorch and guide students toward conceptualizing and implementing a final project that transcends conventional deep learning approaches.



## Codebase Structure



## Final Project Description

This project, *Pruning and Quantizing a Normalization-Free Network With Dynamic Tanh*, investigates how compression techniques like pruning and quantization work on networks that skip traditional normalization layers by using Dynamic Tanh (DyT) instead. Inspired by the paper [Transformers without Normalization](https://arxiv.org/pdf/2503.10622), the goal is to see how removing normalization affects accuracy and stability after compression, and to understand how well DyT adapts to different levels of precision. By comparing these normalization-free models with standard ones, the project seeks to discover innovative strategies for deploying efficient deep learning models on devices with limited resources.