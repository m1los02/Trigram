# Trigram Language Model — Counting & Neural Network Approach

This project implements a **Trigram Language Model** using two methods:

- A **basic statistical model** based on trigram frequency counting
- A **neural network model**

The project was inspired by Andrej Karpathy’s  **"Neural Networks: Zero to Hero"** series and serves as an introduction to how language models work under the hood.

## What is a Trigram Model?

A Trigram model predicts the next character (or word) based on the previous two. For example, given the sequence `"th"`, it estimates the likelihood of each possible third character.

## Methods Implemented

### 1. **Trigram Counting Model**

- Counts all trigrams in the training corpus
- Calculates conditional probabilities using frequency counts
- Generates new text character-by-character

### 2. **Neural Network Model**

- Embedding(One Hot Encoding) + Linear layers
- Trained using cross-entropy loss
- Learns from the same trigram data but generalizes better and can capture subtler patterns

## Skills Demonstrated

- Tokenization and dataset preparation
- Probability modeling with n-grams
- Building and training simple neural nets from scratch (no high-level abstractions)
- Sampling/generating text
- Working with PyTorch

## Motivation

The goal was to learn how language models work at a fundamental level and gain practical experience implementing everything from scratch, inspired by Karpathy's hands-on approach.
