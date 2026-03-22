Assignment 3: Reading Papers

CS 800 Research Methods, Spring 2026
Name: Protiva Das

This submission contains five papers from my research area (LLM security, privacy, and adversarial robustness), each with Keshav’s 1st-pass summary (problem, approach, contributions), reference, DOI link, BibTeX entry, and a marked-up PDF highlighting the relevant sections.

Directory structure
assignments/Das/3/
├── README.md
├── A3_papers_marked/
│   ├── paper1_GuardAgent_marked.pdf
│   ├── paper2_HiddenNoMore_marked.pdf
│   ├── paper3_SecureCodeGen_marked.pdf
│   ├── paper4_BackdoorSurvey_marked.pdf
│   └── paper5_NEXUS_marked.pdf
└── paper_images/
    ├── paper 1.png
    ├── paper 2.png
    ├── paper 3.png
    ├── paper 4.png
    └── paper 5.png
Paper 1: GuardAgent – Safeguard LLM Agents via Knowledge-Enabled Reasoning

Reference:
Xiang, Z., Zheng, L., Li, Y., Hong, J., Li, Q., Xie, H., ... & Li, B. (2025, July). Guardagent: safeguard LLM agents via knowledge-enabled reasoning. In ICML 2025 workshop on computer use agents.

DOI:
https://arxiv.org/abs/2406.09187

BibTeX:

@inproceedings{xiang2025guardagent,
title={Guardagent: safeguard LLM agents via knowledge-enabled reasoning},
author={Xiang, Zhen and Zheng, Linzhi and Li, Yanjie and Hong, Junyuan and Li, Qinbin and Xie, Han and Zhang, Jiawei and Xiong, Zidi and Xie, Chulin and Bastian, Nathaniel D and others},
booktitle={ICML 2025 workshop on computer use agents},
year={2025}
}

1st pass (Keshav):

Problem:
LLM agents can autonomously execute actions using tools, but existing safety mechanisms are either hard-coded or limited to text moderation.

Approach:
GuardAgent introduces a separate LLM-based guard that converts policies into executable safety checks.

Contributions:

First guardrail agent for LLM agents
Code-based safety enforcement
Benchmark-based validation

Screenshot (Page 1):


Marked-up PDF:
A3_papers_marked/paper1_GuardAgent_marked.pdf

Paper 2: Hidden No More – Attacking and Defending Private Third-Party LLM Inference

Reference:
Pal, A., Thomas, R. K., Zahran, L., Choi, E., Potti, A., & Goldblum, M. (2025). Hidden no more: attacking and defending private third-party LLM inference.

DOI:
https://openreview.net/forum?id=QfD9P9IIoz

BibTeX:

@inproceedings{pal2025hidden,
title={Hidden no more: attacking and defending private third-party LLM inference},
author={Pal, Arka and Thomas, Rahul Krishna and Zahran, Louai and Choi, Erica and Potti, Akilesh and Goldblum, Micah},
booktitle={ICLR 2025 workshop on building trust in language models and applications},
year={2025}
}

1st pass (Keshav):

Problem:
Sensitive prompts can be reconstructed from hidden states.

Approach:
Designs reconstruction attacks and proposes Cascade defense.

Contributions:

Hidden-state attack
Defense evaluation
Cascade framework

Screenshot (Page 1):


Marked-up PDF:
A3_papers_marked/paper2_HiddenNoMore_marked.pdf

Paper 3: Secure Code Generation

Reference:
Tessa, M., Olatunji, I. E., War, A., Klein, J., & Bissyandé, T. F. (2026).

DOI:
https://arxiv.org/abs/2601.07084

BibTeX:

@article{tessa2026secure,
title={How Secure is Secure Code Generation? Adversarial Prompts Put LLM Defenses to the Test},
author={Tessa, Melissa and Olatunji, Iyiola E and War, Aicha and Klein, Jacques and Bissyand{\'e}, Tegawend{\'e} F},
journal={arXiv preprint arXiv:2601.07084},
year={2026}
}

1st pass (Keshav):

Problem:
Security claims of code LLMs are unreliable.

Approach:
Adversarial prompt evaluation.

Contributions:

Robustness testing
Security-functionality tradeoff

Screenshot (Page 1):


Marked-up PDF:
A3_papers_marked/paper3_SecureCodeGen_marked.pdf

Paper 4: Backdoor Survey

Reference:
Cheng, P., Wu, Z., Du, W., Zhao, H., Lu, W., & Liu, G. (2025).

DOI:
https://arxiv.org/abs/2309.06055

BibTeX:

@article{cheng2025backdoor,
title={Backdoor attacks and countermeasures in natural language processing models: A comprehensive security review},
author={Cheng, Pengzhou and Wu, Zongru and Du, Wei and Zhao, Haodong and Lu, Wei and Liu, Gongshen},
journal={IEEE Transactions on Neural Networks and Learning Systems},
year={2025},
publisher={IEEE}
}

1st pass (Keshav):

Problem:
Backdoor threats lack unified study.

Approach:
Survey-based taxonomy.

Contributions:

Unified taxonomy
Defense categorization

Screenshot (Page 1):


Marked-up PDF:
A3_papers_marked/paper4_BackdoorSurvey_marked.pdf

Paper 5: NEXUS

Reference:
Asl, J. R., Narula, S., Ghasemigol, M., Blanco, E., & Takabi, D. (2025).

DOI:
https://arxiv.org/abs/2510.03417

BibTeX:

@inproceedings{asl2025nexus,
title={NEXUS: Network Exploration for eXploiting Unsafe Sequences in Multi-Turn LLM Jailbreaks},
author={Asl, Javad Rafiei and Narula, Sidhant and Ghasemigol, Mohammad and Blanco, Eduardo and Takabi, Daniel},
booktitle={Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing},
pages={24278--24306},
year={2025}
}

1st pass (Keshav):

Problem:
Multi-turn jailbreak attacks evade safety.

Approach:
Network-based exploration + refinement.

Contributions:

ThoughtNet
Adaptive attack framework

Screenshot (Page 1):


Marked-up PDF:
A3_papers_marked/paper5_NEXUS_marked.pdf

Video walkthrough

Video Link: https://youtu.be/spAzK32RXmI