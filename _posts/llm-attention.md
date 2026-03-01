---
title: "Attention"
date: 2026-3-1
permalink: /posts/llm/attention
tags:
  - Large Language Model
  - Embedding
---

In this post, I will introduce how to encode token into embeddings.

# One-hot encodings

Given vocabulary $V$, token i is encoded into a vector $x_{OHE}$ with $i$-th element equals to 1 and other elements 0.

Noticing that embeddings are all athogonal to one another, which indicates the limiation that we cannot compute the similarity between two tokens.

# Continuous encodings

## Word2vec

It is based ona shallow neural network with one hidden layer. It project one-hot embeddings $X_{OHE}$ into

![Test Image](../assets/fonts/academicons.svg)
