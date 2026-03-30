# Assignment 5, Literature Review, Part 2

**CS 800 Research Methods, Spring 2026**
**Student:** Ashish Acharya

## Description

This assignment explores the relationship between two research papers in the field of single-cell genomics and machine learning. The goal is to understand how a newer paper builds upon an existing foundational work.

- **Base Paper:** scGPT
- **Second Paper:** Path-GPTOmic

The focus is on identifying how the second paper **extends and applies** the ideas introduced in the first paper.

## Directory and File Structure

The files for this assignment are organized as follows:

- [slides](./slides/): Directory containing the Presentation slides used in class.
- `ReadMe.md`: This file the very file you are reading right now, documenting the assignment submission.
- [papers](./papers/): Directory containing the PDF copies of the two research papers that are presented in this literature review, Part 2.

## BibTeX Entries

- [Paper 1](./papers/paper1.pdf): scGPT: toward building a foundation model for single-cell multi-omics using generative AI

```bibtex
@article{cui2024scgpt,
  title={{scGPT}: toward building a foundation model for single-cell multi-omics using generative {AI}},
  author={Cui, Haotian and Wang, Chloe and Maan, Hassaan and Pang, Kuan and Luo, Fengning and Duan, Nan and Wang, Bo},
  journal={Nature Methods},
  volume={21},
  number={8},
  pages={1470--1480},
  year={2024},
  publisher={Nature Publishing Group},
  doi="10.1038/s41592-024-02201-0"
}
```

- [paper 2](./papers/paper2.pdf): Path-Gptomic: A Balanced Multi-Modal Learning Framework For Survival Outcome Prediction

```bibtex
@inproceedings{wang2024pathgptomic,
  title={{Path-GPTOmic}: {A} {B}alanced {Multi-Modal} {L}earning {F}ramework for {S}urvival {O}utcome {P}rediction},
  author={Wang, Hongxiao and Yang, Yang and Zhao, Zhuo and Gu, Pengfei and Sapkota, Nishchal and Chen, Danny Z.},
  booktitle={Proceedings of the IEEE International Symposium on Biomedical Imaging (ISBI)},
  year={2024},
  pages={1--5},
  publisher={IEEE},
  doi={10.1109/ISBI56570.2024.10635171}
}
```

## Relationship Between the Two papers

### ScGPT ( Base Paper)

- Introduces a foundation model for single-cell RNA-seq data.
- Uses a transformer-based architecture similar to GPT models.
- Learns general biological representations from large-scale datasets.
- Designed for tasks like:
  - Cell type annotation
  - Batch correction
  - Multi-omics integration

### Path-GPTOmic (Second Paper)

- Builds directly on scGPT by using its pretrained embeddings.
- Extends scGPT to:
  - Bulk RNA-seq data
  - Multi-modal learning (gene expression + pathology images)
  - Applies the model to clinical survival prediction tasks.
- Introduces:
  - A balanced learning framework
  - Gradient modulation techniques

### Key Relationship

- Reuse of Pretrained Knowledge
  - Uses scGPT embeddings as a foundation
- Extension to New Domains
  - Moves from single-cell RNA-seq data → Bulk RNA-seq data
- Multi-modal Integration
  - Combines genomics with imaging data
- Task-Specific Adaptation
  - Applies the model to survival prediction

## Slides Presentation

**Google Slides Link:** [https://docs.google.com/presentation/d/1FZDi8yLkLrPeSA7dC98RAXi4uJR7z6k_jkjhGX7SsCo/edit?usp=sharing](https://docs.google.com/presentation/d/1FZDi8yLkLrPeSA7dC98RAXi4uJR7z6k_jkjhGX7SsCo/edit?usp=sharing)
