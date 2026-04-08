# Assignment 5 - Literature Review Part 2
**CS 800 Research Methods, Spring 2026 | Due: 2026-03-23**

## Description

10-minute paired paper presentation stressing the relationship between two papers. Paper 1 is selected from A3/A4. Paper 2 cites Paper 1 in a substantive way. The presentation explains why the second paper cited the first.

---

## BibTeX

```bibtex
@techreport{lecun2022path,
  author      = {LeCun, Yann},
  title       = {A Path Towards Autonomous Machine Intelligence},
  institution = {Meta FAIR / NYU},
  year        = {2022},
  note        = {Version 0.9.2}
}

@inproceedings{assran2023ijepa,
  author    = {Assran, Mahmoud and Duval, Quentin and Misra, Ishan and
               Bojanowski, Piotr and Vincent, Pascal and Rabbat, Michael
               and LeCun, Yann and Ballas, Nicolas},
  title     = {Self-Supervised Learning from Images with a
               Joint-Embedding Predictive Architecture},
  booktitle = {CVPR},
  pages     = {15619--15629},
  year      = {2023}
}
```

---

## Relationship

LeCun 2022 proposes JEPA as the theoretical basis for a world model encoder and makes four falsifiable claims about self-supervised learning. Nothing is built or tested, it's simply a blueprint. I-JEPA is the first implementation of that blueprint. It cites LeCun 2022 as the direct source of its architecture, operationalises all four claims, and confirms each one experimentally. The citation is substantive because LeCun 2022 is not background context, but is the reason I-JEPA exists.

---

## Presentation

**[Does the Blueprint Hold? LeCun's JEPA Theory Meets Its First Test](https://docs.google.com/presentation/d/1nXOzteYQA3iGXxwRondngFbeSm5G_HJIq2NHClvInDA/edit?usp=sharing)**