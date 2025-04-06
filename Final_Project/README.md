## Efficient ViT's with Dynamic Tanh

This repository contains my ongoing final project for the **Experimentation with PyTorch (ECE-491)** course, focusing on exploring model compression (pruning and quantization) techniques applied to normalization-free neural networks using Dynamic Tanh (DyT). Standard compression methods are usually tailored for networks employing normalization layers such as Batch Normalization or Layer Normalization. This project investigates whether the removal of these normalization layers influences the effectiveness of pruning and quantization, and evaluates if DyT can effectively adapt under compression.

### Objective  
Our goal is to explore how different normalization strategies affect vision transformers on CIFAR‑100. We will compare traditional Layer Normalization (LN) against a normalization‑free approach using Dynamic Tanh (DyT) to assess training stability, accuracy, and inference efficiency—both before and after applying compression techniques like iterative pruning and integer quantization.

### Approach
We begin by training a standard ViT‑Base model on CIFAR‑100, creating two variants: one with conventional Layer Normalization and another that replaces all normalization layers with Dynamic Tanh (DyT). After establishing these baseline models, we apply structured pruning and integer quantization using PyTorch’s native utilities, carefully monitoring how the DyT variant adapts during compression. Finally, we perform ablation studies to compare the training stability, accuracy, and inference efficiency of the two approaches under the same compression conditions.traditional LayerNorm-based model under identical compression regimes.

### Repository Structure

```
```