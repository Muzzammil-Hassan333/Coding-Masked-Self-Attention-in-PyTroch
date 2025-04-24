🛡️ Coding Masked Self-Attention in PyTorch
This repository contains a minimal and educational implementation of Masked Self-Attention using PyTorch. Masked attention is a crucial concept in Transformer models like GPT, enabling them to "look only at the past" during sequence generation.

🧠 What You’ll Learn
How to implement self-attention with masking from scratch in PyTorch.

How masking works to prevent a token from attending to future tokens (causality).

How scaled dot-product attention operates under the hood, step by step.

How to manually verify and visualize attention weights and outputs.

🧱 Key Features
Custom MaskedSelfAttention class using PyTorch's nn.Module.

Manual masking implementation using masked_fill and lower-triangular matrices (torch.tril).

A simple example with small input data (d_model=2) to help you trace computations by hand.

Printout of intermediate tensors such as weights, queries, keys, values, scores, and attention probabilities for full transparency.

👀 Ideal For:
Anyone learning how GPT-like architectures work internally.

Students and enthusiasts wanting to grasp sequence masking and autoregressive attention.

Developers who prefer to build their intuition through low-level implementations.
