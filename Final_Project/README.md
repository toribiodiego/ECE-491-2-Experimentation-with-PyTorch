> This directory contains the final project for **Experimentation with PyTorch (ECE‑491)**, focusing on model compression techniques—pruning and quantization—applied to normalization‑free neural networks using Dynamic Tanh (DyT).

## Efficient ViT's with Dynamic Tanh

### Objective  
Our goal is to explore how different normalization strategies affect vision transformers on CIFAR‑100. We will compare traditional Layer Normalization (LN) against a normalization‑free approach using  Tanh (DyT) to assess training stability, accuracy, and inference efficiency—bDynamicoth before and after applying compression techniques like iterative pruning and integer quantization.

### Approach
We begin by training a standard ViT‑Base model on CIFAR‑100, creating two variants: one with conventional Layer Normalization and another that replaces all normalization layers with Dynamic Tanh (DyT). After establishing these baseline models, we apply structured pruning and integer quantization using PyTorch’s native utilities, carefully monitoring how the DyT variant adapts during compression. Finally, we perform ablation studies to compare the training stability, accuracy, and inference efficiency of the two approaches under the same compression conditions.traditional LayerNorm-based model under identical compression regimes.

### Directory Structure

```
.
├── README.md
└── fine_tune.ipynb
```


### Results



<br>


### References



<br>
