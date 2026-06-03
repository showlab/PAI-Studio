# PAI-Studio: Cinematic Video Background Replacement with Camera-Aware Motion

[![Project Page](https://img.shields.io/badge/Project-Page-blue)](https://gaohy63601-droid.github.io/promising/)

🔗 **Project page:** https://gaohy63601-droid.github.io/promising/

## Authors

Heyuan Gao<sup>1,2,*</sup>, Bangxun Tang<sup>1,3,*</sup>, Yiren Song<sup>1,4,*,‡</sup>, Guian Fang<sup>1,4</sup>, Zijian He<sup>1</sup>, Jie Yang<sup>1</sup>, Mike Zheng Shou<sup>4,†</sup>

<sup>1</sup>Utopai Studios &nbsp;&nbsp; <sup>2</sup>Nanyang Technological University &nbsp;&nbsp; <sup>3</sup>University of California, Irvine &nbsp;&nbsp; <sup>4</sup>Show Lab, National University of Singapore

<sup>*</sup>Equal contribution &nbsp;&nbsp; <sup>‡</sup>Project leader &nbsp;&nbsp; <sup>†</sup>Corresponding author

## Abstract

We present PAI-Studio, a new reference-conditioned video synthesis task that addresses a long-standing challenge in cinematic background replacement: generating dynamic backgrounds aligned with foreground motion while preserving foreground identity, matching reference scene appearance, and achieving globally consistent illumination with realistic foreground relighting. Existing open-source systems and commercial APIs cannot simultaneously ensure motion-consistent background generation, high-fidelity foreground relighting and foreground identity preservation, often resulting in static backgrounds, inconsistent boundaries, and noticeable compositing artifacts. To bridge this gap, we build upon a Diffusion Transformer video backbone and reformulate the problem as an in-context conditional generation task. Through bidirectional attention, our model jointly captures foreground dynamics and background reference information within a unified architecture. We further construct a 30K-scale dataset sourced from high-quality films and online videos to support this task. Extensive evaluations demonstrate that our method significantly outperforms existing open-source and commercial API solutions.

## Project Page

The project page (HTML + assets) lives in [`docs/`](docs/). It is the same site served at
https://gaohy63601-droid.github.io/promising/ . If this repository is made public, GitHub Pages
can be served directly from the `docs/` folder (Settings → Pages → Source: `main` / `/docs`).

## Code

Code release is coming soon.
