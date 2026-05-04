# Assignment 6: Student Dissertation Presentation

**CS 800 Research Methods, Spring 2026**

## Mehrdad Rostamzadeh

## Description

This assignment requires selecting, analyzing, and presenting a doctoral dissertation from the Electrical and Computer
Engineering (ECE) or Computer Science (CS) departments at Old Dominion University (ODU). The objective is to critically
evaluate the research and clearly communicate its main contributions within a 20-minute presentation.

## Directory and File Structure

The files for this assignment are organized as follows:

- `ReadMe.md`: This file the very file you are reading right now, documenting the assignment submission.

## Dissertation

```bibtex
@phdthesis{ferguson2025anomaly,
  author       = {Hal Ferguson},
  title        = {Machine Learning for Anomaly Detection in Neural Network Security and SRF Cavities},
  school       = {Old Dominion University},
  year         = {2025},
  type         = {Doctor of Philosophy (PhD) Dissertation},
  address      = {Norfolk, Virginia, USA},
  month        = {December},
  doi          = {10.25777/2pjk-8q69},
  url          = {https://digitalcommons.odu.edu/ece_etds/614},
  isbn         = {9798276040028},
  note         = {Department of Electrical \& Computer Engineering}
}   
```

## Abstract

This dissertation explores the development and deployment of machine learning approaches to address critical challenges
in anomaly detection across two distinct domains: neural network security in federated learning settings and cavity
behavior analysis in particle accelerator operations at Jefferson Lab in Newport News, Virginia. Anomaly detection
identifies deviations from expected patterns, safeguarding systems in cybersecurity, industry, and research against
malicious activities and failures. This dissertation demonstrates how our machine learning approaches enhance detection
accuracy and efficiency in both neural network security and industrial applications.

First, we investigate vulnerabilities in deep neural networks deployed in federated learning. Although federated
learning preserves user privacy by training models locally, it remains vulnerable to backdoor attacks, in which
malicious participants embed hidden triggers that induce targeted misbehavior. We propose a self-supervised contrastive
learning framework to detect and mitigate such backdoor attacks. In our experiments, this method achieves higher
detection accuracy and lower false positive rates than existing defenses, while operating without access to local model
updates or original training data and thus preserving the privacy guarantees of the federated setting. Second, we
address the operational reliability of superconducting radio-frequency (SRF) cavities at the Continuous Electron Beam
Accelerator Facility (CEBAF). Our research leverages an unsupervised learning approach, combined with Principal
Component Analysis (PCA) and k-means clustering, to identify anomalous behaviors in SRF cavities. Our method detects
subtle anomalous behavior by analyzing SRF signal data. This knowledge allows for the early detection and resolution of
potential faults, significantly improving the efficiency and reliability of operations. Third, we extend these insights
to time-series anomaly detection more broadly. We design a contrastive-learning based model tailored to increasingly
dynamic environments and academic research. This model improves detection accuracy in settings that require real-time
monitoring and predictive maintenance.

Our research underscores the broader applicability and impact of advanced machine learning techniques in anomaly
detection. By extracting meaningful patterns from complex data, machine learning can significantly enhance security in
distributed neural networks and improve the efficiency of particle accelerator operations. This dissertation serves as a
stepping stone for future investigations into the vast possibilities of anomaly detection, inspiring further exploration
and development of machine learning techniques in this field.


---

## Slides Presentation

**Google Slides Link:
** [https://docs.google.com/presentation/d/1DjQmNlMvEce8bgZTe_8j2FA46tHij2C-3FQxS9FKMYs/edit?usp=sharing](https://docs.google.com/presentation/d/1DjQmNlMvEce8bgZTe_8j2FA46tHij2C-3FQxS9FKMYs/edit?usp=sharing)
