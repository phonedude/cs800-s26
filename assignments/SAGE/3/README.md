Papers
--------
[Elucidated Rolling Diffusion Model](papers/Elucidated_Rolling_diffusion_models.pdf)
[diffda](papers/diffda.pdf)
[aerosol ocean retrieval](papers/areosol_ocean_retrieval.pdf)
[Transformers](papers/transformer_paper)
[Generative data assimiliation](papers/NVIDIA_Paper)

------
Paper 1 Elucidated Rolling Diffusion Models

First Page

<img src="screenshots/Paper_1.png" alt="Paper 1" width="400" />
Reference

Cachay, S. R., Aittala, M., Kreis, K., Brenowitz, N., Vahdat, A., Mardani, M., & Yu, R. (2025). Elucidated Rolling Diffusion Models for Probabilistic Forecasting of Complex Dynamics. {ArXiv}.

DOI

https://doi.org/10.48550/arXiv.2506.20024

BibTeX

@article{cachay2025elucidated,
  title={Elucidated Rolling Diffusion Models for Probabilistic Forecasting of Complex Dynamics},
  author={Cachay, Salva R{\"u}hling and Aittala, Miika and Kreis, Karsten and Brenowitz, Noah and Vahdat, Arash and Mardani, Morteza and Yu, Rose},
  journal={{ArXiv} preprint {ArXiv}:2506.20024},
  year={2025},
  doi={10.48550/arXiv.2506.20024}
}


Problem:

Traditional diffusion models are powerful for generative tasks but are not well-suited for probabilistic forecasting of complex time-evolving systems such as weather or climate dynamics. Existing forecasting models often struggle with uncertainty estimation and long-range temporal dependencies.

Approach:

The authors introduce Rolling Diffusion Models (RDMs) combined with the Elucidated Diffusion Model (EDM) framework. The model generates forecasts step-by-step over time by rolling the diffusion process forward while maintaining stable training and sampling procedures.

Contributions:

Introduces Elucidated Rolling Diffusion Models for probabilistic forecasting.

Improves stability and performance of diffusion-based forecasting methods.

Demonstrates strong results on complex dynamical systems and long-horizon predictions.

-------
Paper 2 DiffDA

First Page

<img src="screenshots/Paper_2.png" alt="Paper 2" width="400" />

Reference

Huang, L., Gianinazzi, L., Yu, Y., Düben, P. D., & Hoefler, T. (2024). DiffDA: A Diffusion Model for Weather-scale Data Assimilation. {ArXiv}.

DOI
https://doi.org/10.48550/arXiv.2401.05932

BibTeX

@article{huang2024diffda,
  title={{DiffDA}: A Diffusion Model for Weather-scale Data Assimilation},
  author={Huang, Langwen and Gianinazzi, Lukas and Yu, Yuejiang and D{\"u}ben, Peter D. and Hoefler, Torsten},
  journal={{ArXiv} preprint {ArXiv}:2401.05932},
  year={2024},
  doi={10.48550/arXiv.2401.05932}
}

Problem

Weather data assimilation is computationally expensive and difficult at large spatial scales. Traditional assimilation methods (e.g., variational or ensemble methods) can struggle with scalability and uncertainty modeling.

Approach

The authors propose DiffDA, a diffusion-model-based approach for data assimilation that learns the distribution of atmospheric states and incorporates observational data into the generative process.

Contributions

Introduces a diffusion-based data assimilation framework.

Demonstrates the ability to handle weather-scale systems efficiently.

Shows improved reconstruction of atmospheric states from sparse observations.

----
Paper 3 Deep Learning-Based Aerosol and Ocean Data Retrieval

First Page

<img src="screenshots/Paper_3.png" alt="Paper 3" width="400" />
Reference

Wang, L., Stamnes, S., Hassan, S., Isiani, A., Sturdivant, C., Le, H. M., & Mahmud, K. R. (2025). Deep Learning-Based Aerosol and Ocean Data Retrieval from Satellite Polarimeter Measurements. IEEE SoutheastCon 2025.

DOI
https://doi.org/10.1109/SoutheastCon56624.2025.10971488

BibTeX

@inproceedings{wang2025aerosol,
  title={Deep Learning-Based Aerosol and Ocean Data Retrieval from Satellite Polarimeter Measurements},
  author={Wang, Lingxiao and Stamnes, Snorre and Hassan, Sunzid and Isiani, Alexander and Sturdivant, Cheston and Le, Hoang My and Mahmud, Khan Raqib},
  booktitle={{IEEE} SoutheastCon},
  year={2025},
  pages={1542--1547},
  doi={10.1109/SoutheastCon56624.2025.10971488}
}

Problem

Retrieving aerosol and ocean properties from satellite polarimeter measurements is complex due to nonlinear relationships between measurements and environmental variables. Traditional retrieval algorithms are often slow and limited.

Approach

The paper applies deep learning models to estimate aerosol and ocean parameters directly from satellite polarimeter data. The model learns the mapping between observed measurements and geophysical properties.

Contributions

Develops a deep learning-based retrieval method for satellite polarimeter data.

Improves accuracy and efficiency compared to traditional retrieval methods.

Demonstrates the feasibility of AI-driven remote sensing data analysis.

----
Paper 4 Attention Is All You Need

First Page

<img src="screenshots/Paper_4.png" alt="Paper 4" width="400" />
Reference

Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., Kaiser, Ł., & Polosukhin, I. (2017). Attention Is All You Need. {ArXiv} / NeurIPS 2017.

DOI

https://doi.org/10.48550/arXiv.1706.03762

BibTeX
@article{vaswani2017attention,
  title={Attention Is All You Need},
  author={Vaswani, Ashish and Shazeer, Noam and Parmar, Niki and Uszkoreit, Jakob and Jones, Llion and Gomez, Aidan N. and Kaiser, {\L}ukasz and Polosukhin, Illia},
  journal={{ArXiv} preprint {ArXiv}:1706.03762},
  year={2017},
  doi={10.48550/arXiv.1706.03762}
}

Problem

Sequence modeling methods such as recurrent neural networks (RNNs) and convolutional models have limitations in capturing long-range dependencies and are computationally inefficient for large datasets.

Approach

The authors introduce the Transformer architecture, which relies entirely on self-attention mechanisms instead of recurrence or convolution to model relationships between tokens in a sequence.

Contributions

Proposes the Transformer, a new neural network architecture.

Introduces self-attention as the core mechanism for sequence modeling.

Significantly improves performance and training efficiency in machine translation and other NLP tasks.

-----
Paper 5 Generative Data Assimilation of Sparse Weather Station Observations at Kilometer Scales

First Page

<img src="screenshots/Paper_5.png" alt="Paper 5" width="400" />

Reference

Manshausen, P., Cohen, Y., Harrington, P., Pathak, J., Pritchard, M., Garg, P., Mardani, M., Kashinath, K., Byrne, S., & Brenowitz, N. (2025). Generative Data Assimilation of Sparse Weather Station Observations at Kilometer Scales. Journal of Advances in Modeling Earth Systems.

DOI

https://doi.org/10.1029/2024MS004505

BibTeX

@article{manshausen2025generative,
  title={Generative Data Assimilation of Sparse Weather Station Observations at Kilometer Scales},
  author={Manshausen, Peter and Cohen, Yair and Harrington, Peter and Pathak, Jaideep and Pritchard, Mike S. and Garg, Piyush and Mardani, Morteza and Kashinath, Karthik and Byrne, Simon and Brenowitz, Noah D.},
  journal={Journal of Advances in Modeling Earth Systems},
  volume={17},
  number={10},
  pages={e2024MS004505},
  year={2025},
  doi={10.1029/2024MS004505}
}

Problem

Weather prediction systems often rely on dense observation networks, but many regions only have sparse weather station data, making high-resolution forecasting difficult.

Approach

The authors propose a generative data assimilation framework that uses machine learning to combine sparse observations with atmospheric models to reconstruct high-resolution weather fields.

Contributions

Introduces a generative approach to data assimilation for sparse observations.

Enables kilometer-scale weather reconstruction from limited data.

Demonstrates improved forecasting capability in data-sparse regions.

----

Youtube


