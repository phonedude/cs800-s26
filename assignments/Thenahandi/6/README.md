# Assignment 6: Dissertation Presentation
## CS 800 Research Methods, Spring 2026
### Name: Pasindu Thenahandi
### UIN: 01307992

## Assignment Description

For this assignment, I chose the dissertation "Multi-Eyes: Multi-User Eye Tracking Using Commodity Hardware" by Dr.Bhanuka Mahanama.

## Selected Dissertation

- Title: Multi-Eyes: Multi-User Eye Tracking Using Commodity Hardware
- Link: [ODU Digital Commons entry](https://digitalcommons.odu.edu/computerscience_etds/188/)
- Author: Bhanuka Mahanama, Old Dominion University
- Date of Award: Summer 8-2025
- Document Type: Dissertation
- Degree Name: Doctor of Philosophy (PhD)
- Department: Computer Science
- Program/Concentration: Computer Science
- Committee Director: Sampath Jayarathna
- Committee Members: Michael L. Nelson, Michele C. Weigle, Vikas G. Ashok, Yusuke Yamani

## Abstract

The human gaze provides informative cues for understanding behavior during multi-user interactions. However, eye-tracking in multi-user environments presents significant challenges, as conventional eye-tracking systems are typically limited to single-user setups and require a dedicated device for each participant. This results in costly, complex, and often restrictive experimental configurations due to the operational and hardware constraints of conventional eye trackers. In contrast, commodity hardware such as standard webcams offers a cost-efficient alternative for gaze estimation across multiple users in a co-located environment. Despite recent advances in computer vision, appearance-based gaze estimation, and the availability of large-scale gaze datasets, limited research exists on developing lightweight, cost-effective, commodity hardware-based eye-tracking systems capable of supporting multi-user environments.

To address the research gap, we propose Multi-Eyes, a real-time, multi-user eye-tracking framework designed for scalable and cost-efficient gaze estimation and analysis. Multi-Eyes integrates a three-stage pipeline encompassing user detection, appearance-based gaze estimation, and gazeto- surface mapping for gaze analytics. The system operates at 17 frames per second on standard hardware and achieves an average gaze accuracy of 319 mm (horizontal) and 219 mm (vertical) on a large-format display. Beyond raw gaze estimation, Multi-Eyes also enables the derivation of low-frequency fixation-based measures, demonstrating its potential utility in real-world interaction studies. At its core, the system features a parameter-efficient appearance-based gaze estimation model that achieves an in-domain gaze error of 4.95◦ using only 6.2 million parameters, 76% fewer parameters compared to ResNet-50 baselines while maintaining comparable performance. Additionally, the model incorporates an unsupervised domain adaptation strategy, enabling strong generalization and competitive performance across multiple unseen target domains. These contributions establish Multi-Eyes as a promising step toward scalable, low-cost multi-user eye-tracking systems.

## Directory

This directory contains:

```text
6/
└── README.md
```

## Presentation Link

- Google Slides presentation: [https://docs.google.com/presentation/d/15cp526ILoKiQFZaRDax1yYg2cJlf8tOIdLmVTDuMl5E/edit?usp=sharing](https://docs.google.com/presentation/d/15cp526ILoKiQFZaRDax1yYg2cJlf8tOIdLmVTDuMl5E/edit?usp=sharing)