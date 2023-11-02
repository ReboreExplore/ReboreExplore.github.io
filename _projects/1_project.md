---
layout: page
title: JPEG Encoder
description: A JPEG Encoder using OpenCL
img: assets/img/12.jpg
importance: 1
category: work
---

A Joint Photographic Experts Group (JPEG) encoder is a crucial component in digital image processing, designed
to efficiently compress and encode images in the JPEG standard. This project aims to implement the JPEG encoding process in the
C++ programming language, comparing how the various stages can be accelerated on a Graphics Processing Unit (GPU). The various stages of the JPEG encoding process, color space conversion, downsampling or chroma subsampling, level shifting, discrete
cosine transform, quantization, zigzag scan, run length encoding and Huffman encoding are implemented as C++ functions as
well as Open Computing Language (OpenCL) kernels. Both the CPU and GPU implementations are compared and the speedup
are evaluated which justifies the parallel processing capabilities of modern GPUs. As per our results, speedups in the range 35-
200 are recorded for various stages. The results also support the presumption that the stages of the JPEG encoding process are
highly parallelizable.

The code for this project can be found [here](https://github.com/ReboreExplore/jpeg-encoder).

Read the full report [here](https://drive.google.com/file/d/1BdacI2S6JgnBgMHemFvCgDaKXZq6Jpre/view?usp=sharing).

