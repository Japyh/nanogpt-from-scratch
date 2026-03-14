# nanoGPT From Scratch

Rebuilding a GPT-style Transformer model from the ground up to understand modern Large Language Models (LLMs) at an implementation level.

This repository documents a hands-on learning journey through core GPT components, training dynamics, and text generation. The focus is on clarity, experimentation, and understanding how each part of the model contributes to final behavior.

## Why This Repository Exists

Reading about Transformers is useful, but implementing them from scratch makes the ideas stick.

This project is inspired by Andrej Karpathy's excellent [nanoGPT](https://github.com/karpathy/nanoGPT), a minimal and elegant PyTorch codebase for GPT training and fine-tuning. Here, I recreate those ideas step-by-step in my own way to build intuition and practical understanding.

## What I Am Building

The repository covers the major building blocks of a decoder-only GPT architecture:

- Tokenization and dataset preparation
- Transformer architecture (decoder-only)
- Self-attention and multi-head attention
- Positional encodings
- Feed-forward networks (MLP blocks)
- Training loops and optimization
- Text generation (sampling / inference)

## Project Goals

- Build a working GPT-style language model end-to-end
- Understand each component deeply, not just use it
- Keep the implementation readable and easy to experiment with
- Document lessons and insights during development

## Learning-First Principles

- Keep code simple before making it fast
- Prefer explicit implementations over hidden abstractions
- Validate understanding with small experiments
- Iterate in small, testable steps

## Acknowledgments

- Andrej Karpathy for the original [nanoGPT](https://github.com/karpathy/nanoGPT) and educational resources

---

If you are learning Transformers too, feel free to follow along, fork the repo, and experiment.
