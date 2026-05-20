# Simplified MPEG-4 Video Encoder Pipeline

A complete implementation of a simplified MPEG-4-like video encoder pipeline in Python, from raw image frames to a compressed binary file that can be decoded back into images.

## Overview

This project implements the five key stages of a video codec:

1. **Pre-processing** — Color space conversion (BGR → YCbCr) and chroma subsampling
2. **Intra-frame coding (I-frames)** — DCT-based spatial compression
3. **Inter-frame coding (P-frames)** — Motion estimation and residual coding
4. **Entropy coding** — Lossless compression of the bitstream
5. **Evaluation & Visualisation** — Quality metrics and pipeline visualisation

## Features

- Configurable GOP size and quantisation factor
- Motion estimation with adjustable search window
- Full encode/decode pipeline
- PSNR calculation for quality assessment
- Pipeline visualisation with matplotlib


## 🔧 Requirements

```bash
pip install numpy opencv-python scipy matplotlib
```




