# Electromagnetic Inverse Scattering Problem Solved by DConvNet and Adapted Attention U-Net

This repository contains the concept and architecture for a two-stage Deep Learning strategy designed to resolve the **Electromagnetic Inverse Scattering Problem (ISP)**. 

Our proposed approach utilizes a **Deep Convolutional Neural Network (DConvNet)** alongside an **adapted version of an Attention U-Net** to significantly improve non-linear image reconstruction precision and quality from scattered field data.

---

## Citation & Paper Access

If you find this architecture or approach useful in your research, please cite our official IEEE publication:

*   **Title:** Electromagnetic inverse scattering problem solved by DConvNet and adapted attention U-Net
*   **Authors:** Pravallika Saladi, Yaswanth Kalepu
*   **Conference:** 2023 IEEE 12th International Conference on Communication Systems and Network Technologies (CSNT)
*   **Publisher:** IEEE
*   **DOI / Publisher Link:** [Read the full paper on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10134734/)

```bibtex
@INPROCEEDINGS{10134734,
  author={Saladi, Pravallika and Kalepu, Yaswanth},
  booktitle={2023 IEEE 12th International Conference on Communication Systems and Network Technologies (CSNT)}, 
  title={Electromagnetic inverse scattering problem solved by DConvNet and adapted attention U-Net}, 
  year={2023},
  pages={101-104},
  doi={10.1109/CSNT57126.2023.10134734}}
```

---

## Methodology Overview

The Inverse Scattering Problem (ISP) is inherently non-linear and ill-posed. This project solves it using a highly efficient **two-stage deep learning pipeline**:

1.  **Feature Extraction (DConvNet):** A Deep Convolutional Neural Network processes raw scattered field data to map and extract crucial structural and physical features.
2.  **Image Refinement (Adapted Attention U-Net):** An optimized Attention U-Net takes the extracted feature maps to perform high-precision image reconstruction, focusing specifically on localized target boundaries.

### Performance & Benchmarks
Our empirical results show that combining these frameworks yields superior performance compared to standalone architectures:
*   **Better Image Quality:** Enhanced structural sharpness and reduced artifacts.
*   **Reconstruction Precision:** Highly accurate mapping of permissive profiles.
*   **Comparative Baseline:** Outperformed standard **Attention U-Net**, standalone **DConvNet**, and Deep Residual Convolutional Neural Networks (**DRCNN**) in resolving complex ISPs.


`Electromagnetic Inverse Scattering Problem (ISP)` | `Deep Convolutional Neural Network (DConvNet)` | `Adapted Attention U-Net` | `Deep Residual Convolutional Neural Network (DRCNN)` | `Non-linear Image Reconstruction Precision` | `Scattered Field Data Feature Extraction` | `Computational Electromagnetics` | `Wave Propagation`
