# Quantifying cross-site effect in AI-based dental age estimation: evidence from Brazilian panoramic radiographs - Code

This repository contains the source code for machine learning models developed to estimate human age based on panoramic radiographs of Brazilian patients. It includes scripts for both training and evaluation.

> **Note**
>
> The code is provided **AS IS**. If you have any questions or encounter issues, please open an issue and the author will respond.

To access the training data, follow the steps outlined in the README of this repository:
- [cross-site-age-estimation-brazilians-dataset](https://github.com/willianfco/cross-site-age-estimation-brazilians-dataset)

## Citing our work

If you use this code in your research, please cite our work using the following BibTeX entry:

```bibtex
@article{10.1093/dmfr/twag014,
    author = {Oliveira, Willian and Oliveira, Matheus L and Haiter Neto, Francisco and Albuquerque Santos, Mariana and dos Anjos Pontual, Maria Luiza and Beltrão, Ricardo V and Pontual, Andrea A and Ramos-Perez, Flávia Maria M and Freitas, Deborah Queiroz and Zanchettin, Cleber},
    title = {Quantifying cross-site effect in AI-based dental age estimation: evidence from Brazilian panoramic radiographs},
    journal = {Dentomaxillofacial Radiology},
    pages = {twag014},
    year = {2026},
    month = {02},
    abstract = {To quantify cross-regional generalization of dental age-estimation models, identify practical strategies to improve their performance, and report uncertainty in a transparent manner.A total of 21,722 panoramic radiographs from two Brazilian regions were acquired using distinct equipment. A robust Inception-v4 model was evaluated under four scenarios: (1) training on Northeast data and testing on Southeast data; (2) fine-tuning using Southeast data only or both regions; (3) training from scratch on pooled data; (4) pooled training with augmentation. Model performance was assessed using mean absolute error (MAE), mean signed error (bias), R2, Bland–Altman analysis, and calibration metrics.A marked performance drop was observed when the model trained on Northeast data was applied to Southeast radiographs (MAE 4.97 years vs 3.10 years in-region), with negative bias and wider Bland–Altman limits at older ages. Training with pooled regions and modest fine-tuning improved accuracy and calibration across both cohorts (MAE 3.24–3.69; R2 0.93–0.95). Data augmentation yielded only small additional improvements and did not eliminate large residual errors. Heatmaps highlighted clinically relevant anatomical structures commonly used by dental experts for age estimation.Cross-site and domain shifts significantly impact the performance of AI models for dental age estimation. Multi-regional training combined with light model adaptation provides robust, well-calibrated, and interpretable results across regions, whereas data augmentation alone has limited effectiveness. This study offers a two-region benchmark, code, and data-access protocols to support reproducible evaluation and guide clinical deployment.},
    issn = {0250-832X},
    doi = {10.1093/dmfr/twag014},
    url = {https://doi.org/10.1093/dmfr/twag014},
    eprint = {https://academic.oup.com/dmfr/advance-article-pdf/doi/10.1093/dmfr/twag014/66992588/twag014.pdf},
}
```
