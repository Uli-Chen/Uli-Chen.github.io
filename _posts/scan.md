---
layout: post
title: "Parallel Prefix Sum (Scan) in CUDA"
date: 2025-10-16
permalink: /posts/scan/
tags:
  - CUDA
  - GPU
  - Parallel Algorithms
---

## Scan

![Algorithm for performing a sum scan on a large array of values.](framework.png)
*Figure: Algorithm for performing a sum scan on a large array of values.*

---

## Header and Definitions

```cpp
#include <cuda_runtime.h> 
#include <iostream>
#include <vector>
#include <chrono>
using namespace std;

#define MAX_THREADS_PER_BLOCK 1024
#define MAX_ELEMENTS_PER_BLOCK (MAX_THREADS_PER_BLOCK * 2)
```
