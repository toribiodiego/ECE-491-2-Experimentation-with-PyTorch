# Pruning and Quantizing a Normalization-Free Network With Dynamic Tanh

This repository contains my ongoing final project for the **Experimentation with PyTorch (ECE-491)** course, focusing on exploring model compression (pruning and quantization) techniques applied to normalization-free neural networks using Dynamic Tanh (DyT). Standard compression methods are usually tailored for networks employing normalization layers such as Batch Normalization or Layer Normalization. This project investigates whether the removal of these normalization layers influences the effectiveness of pruning and quantization, and evaluates if DyT can effectively adapt under compression.

## Project Overview

**Objective:**  
To analyze how normalization-free neural network architectures, specifically those utilizing Dynamic Tanh (DyT) activations instead of traditional normalization methods, respond to model compression techniques like structured pruning and integer quantization. The goal is to determine DyT's adaptability and robustness under aggressive compression scenarios.

**Key Research Questions:**
- How does removing normalization layers affect accuracy and representational power after compression?
- Can Dynamic Tanh activations successfully adapt their parameters to maintain performance under pruning and quantization?
- Is there a viable pathway to deploying compressed, normalization-free models on edge or constrained hardware?

**Approach:**
- **Baseline Model:** Start from a moderately-sized Transformer or vision model, replace normalization layers (BatchNorm or LayerNorm) with DyT.
- **Model Compression:** Apply structured pruning (weight or attention-head pruning) and quantization (integer/fixed-point, int8, etc.) through PyTorch's native utilities, monitoring DyT parameter adaptation throughout.
- **Comparative Analysis:** Conduct ablation studies comparing DyT-based models against standard LayerNorm-based models under identical compression regimes.

Further updates on experiments, results, and deployment scenarios will be documented as the project progresses.

