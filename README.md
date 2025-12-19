<div align="center">



<h1>✨ Factorized Video Generation (FVG) </h1>
<h3>Decoupling Scene Construction and Temporal Synthesis in Text-to-Video Diffusion Models</h3>

Mariam Hassan* · Bastien Van Delft* · Wuyang Li · Alexandre Alahi  
VITA @ EPFL  
*Equal contribution

<a href="https://arxiv.org/abs/2512.16371"><img src="https://img.shields.io/badge/arXiv-2512.16371-b31b1b"></a>
<a href="#"><img src="https://img.shields.io/badge/Project-Page-green"></a>

</div>

---
## 📌 Overview
https://github.com/user-attachments/assets/f8d6371c-ecc9-4bcb-a862-5dd6e9838dc8

State-of-the-art Text-to-Video (T2V) diffusion models can generate visually impressive results, yet they still frequently fail to compose complex scenes or follow logical temporal instructions. We introduce Factorized Video Generation (FVG), a pipeline that decouples T2V generation into three specialized stages:

1) **Reasoning** (LLM rewrites prompt to an initial-scene description),  
2) **Composition** (T2I generates a high-quality anchor frame),  
3) **Temporal Synthesis** (video model animates the anchored scene).

FVG improves performance on T2V benchmarks and enables faster sampling via visual anchoring.

## 🚧 Code
Code is **coming soon**. We’ll release training + inference and evaluation scripts.


## Citation
```bibtex
@misc{hassan2025factorized,
  title        = {Factorized Video Generation: Decoupling Scene Construction and Temporal Synthesis in Text-to-Video Diffusion Models},
  author       = {Hassan, Mariam and Van Delft, Bastien and Li, Wuyang and Alahi, Alexandre},
  year         = {2025},
  eprint       = {2512.16371},
  archivePrefix= {arXiv},
  primaryClass = {cs.CV},
  doi          = {10.48550/arXiv.2512.16371}
}
