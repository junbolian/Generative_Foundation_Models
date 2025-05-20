# Generative Foundation Models : A Comprehensive Beginner’s Handbook 📚✨

[![arXiv](https://img.shields.io/badge/arXiv-2404.<arxiv-id>-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2404.<arxiv-id>)
[![Stars](https://img.shields.io/github/stars/junbolian/Generative_Foundation_Models?style=social)](https://github.com/junbolian/Generative_Foundation_Models/stargazers)

Welcome to the official repository for **“Generative Foundation Models – A Comprehensive Beginner’s Handbook.”**  
This handbook distills the theory _and_ practice behind the most influential generative model families released in the last five years—Transformers, Diffusion models, latent-space approaches, and recent linear-time SSMs such as **Mamba** and **Retentive Networks**.

> **Why star & fork?**  
> - **Stars** keep the project visible and motivate continuous improvements.  
> - **Forks** let you annotate, localize, or extend the book for your own courses or research.  
> - Every new star signals that the next chapter or tutorial is worth shipping sooner 🚀

---

## Table of Contents

| Chapter | Title | Key Topics |
| ------- | ------------------------- | ------------------------------------------------------------ |
| 1 | **Introduction** | Foundation-model landscape, notation |
| 2 | **Transformers for Sequence Modeling** | Self-attention, scaling laws |
| 3 | **Vision Transformer (ViT)** | Patch tokenization, image generation variants |
| 4 | **Mamba** | Selective State-Space Models, linear-time inference |
| 5 | **U-Net Architecture** | Encoder-decoder with skip connections |
| 6 | **Denoising Diffusion Probabilistic Models (DDPM)** | Forward/reverse processes, training objectives |
| 7 | **Diffusion Transformer (DiT)** | Pure-transformer denoisers, AdaLN conditioning |
| 8 | **Retentive Networks (RetNet)** | Multi-scale retention, recurrent decoding |
| 9 | **Latent Diffusion Models (LDM)** | VAE compression, Stable Diffusion paradigm |
|10 | **Text-to-3D Generation** | DreamFusion, Magic3D pipelines |
|11 | **Conclusions & Outlook** | Research frontiers, open problems |

---


## Cite it!
```bibtex
@misc{lian2025generative,
  author       = {Lian, Junbo Jacob},
  title        = {Generative Foundation Models: A Comprehensive Beginner’s Handbook},
  year         = {2025},
  month        = {April},
  note         = {Available at SSRN: \url{https://ssrn.com/abstract=5259947} or \url{http://dx.doi.org/10.2139/ssrn.5259947}},
  howpublished = {SSRN},
  url          = {https://ssrn.com/abstract=5259947},
}
```

## Quick Start

```bash
# 1 Clone
git clone https://github.com/<user>/generative-foundation-models.git
cd generative-foundation-models

# 2 Browse the handbook (LaTeX sources)
code .

# 3 Compile (requires LaTeX + make)
make pdf

# 4 Enjoy the latest PDF
open dist/Generative_Foundation_Models.pdf
