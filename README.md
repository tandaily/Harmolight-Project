# [ACMMM 2026] HarmoLight: Multimodal-Guided Diffusion Model for Composite Image Lighting Adaptation via Curriculum Lighting Learning

[![Project Page](https://img.shields.io/badge/Project-Page-green)](https://tandaily.github.io/Harmolight-Project/)

## Introduction

Composite image lighting adaptation aims to adjust the lighting of a composited foreground so that it harmonizes with the illumination of a target background.
Existing diffusion-based relighting methods often struggle to maintain both **content consistency** and **lighting consistency**, and the construction of relighting datasets together with effective training paradigms remains underexplored.

We propose **HarmoLight**, a multimodal-guided diffusion model for composite image lighting adaptation. Our method:

- Guides the diffusion model with **decoupled content and lighting prompts** via a **decoupled cross-attention** mechanism
- Introduces a **lighting representation distillation** strategy that transfers lighting encoding knowledge from a large pre-trained model to a lightweight encoder
- Employs a **curriculum lighting learning** strategy on specially designed datasets, organizing training samples by lighting adaptation difficulty

Extensive experiments on synthetic datasets and real-world images show that HarmoLight consistently outperforms existing state-of-the-art relighting and harmonization approaches.


## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{Liu2026HarmoLight,
  title     = {Multimodal-Guided Diffusion Model for Composite Image Lighting Adaptation via Curriculum Lighting Learning},
  author    = {Liu, Zhirui and Sun, Shang-Quan and Pei, Renjing and Li, Chaopeng and Cui, Zhigao and Song, Fenglong and Zheng, Hao and Ren, Wenqi},
  booktitle = {Proceedings of the 34th ACM International Conference on Multimedia (MM '26)},
  year      = {2026}
}
```

## Acknowledgments

The project page is built upon the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), adapted from [Nerfies](https://nerfies.github.io/).

## License

The project page website is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
