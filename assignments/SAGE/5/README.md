## Assignment 5

## Papers

[Diffda](Papers/diffda.pdf)
[SLAMS](Papers/SLAMS.pdf)

## BibTeX

```
@article{huang2024diffda,
  title={Diffda: a diffusion model for weather-scale data assimilation},
  author={Huang, Langwen and Gianinazzi, Lukas and Yu, Yuejiang and Dueben, Peter D and Hoefler, Torsten},
  journal={{arXiv} preprint arXiv:2401.05932},
  year={2024}
}
```
```
@inproceedings{qu2024deep,
  title={Deep generative data assimilation in multimodal setting},
  author={Qu, Yongquan and Nathaniel, Juan and Li, Shuolin and Gentine, Pierre},
  booktitle={Proceedings of the {IEEE/CVF} conference on computer vision and pattern recognition},
  pages={449--459},
  year={2024}
}
```
## Paper Description

# DiffDA (Diffusion Data Assimilation)

DiffDA introduces a method for applying diffusion models directly to weather data assimilation. It treats the problem as a conditional generation task, where the model reconstructs the full atmospheric state. It uses prior forecast from a numerical or learned weather model and sparse observational data.  This allows Diffda to operate directly on gridded weather data and demonstrates that diffusion models can scale to high-resolution global weather systems.

# SLAMS (Score-based Latent Assimilation in Multimodal Setting)

SLAMS expands on DiffDA by introducing a more general and flexible framework. Instead of operating directly on physical grids, it learns a latent representation of the system, uses score based diffusion for probabilistic inference and supports the use of multimodal data sources like satellites and ground stations. This allows SLAMS to handle noisy, sparse, and heterogeneous observations more effectively.

# Relationship

SLAMS builds directly on the ideas introduced in DiffDA. While DiffDA shows that diffusion models can be successfully applied to weather data assimilation, it is limited to structured grid data and a single modality. SLAMS generalizes this approach by moving from grid space to latent space modeling, enabling multimodal data fusion and using a more principled probabilistic framework such as score based diffusion.

## Presentation Link

Link to Slides: https://docs.google.com/presentation/d/1Q_pFopBVR9awfXePr02S9UKUDacHI3UFywaoGFHb5_Q/edit?slide=id.p#slide=id.p
