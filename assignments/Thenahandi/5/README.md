# Assignment 5: Citation Relationship Presentation
## CS 800 Research Methods, Spring 2026
### Name: Pasindu Thenahandi
### UIN: 01307992

## Assignment Description

For this assignment, I selected one paper from my earlier readings (A4) and then selected a second paper that cites it in a substantive way.

- Base paper: **WebGazer: Scalable Webcam Eye Tracking Using User Interactions**
- Citing paper: **SearchGazer: Webcam Eye Tracking for Remote Studies of Web Search**

The presentation focuses on why the second paper cites the first paper and how it builds on it.

## Directory
This directory contains:

```text
5/
├── README.md               # This file - assignment documentation
└── papers/
  ├── WebGazer.pdf          # Base paper
  └── SearchGazer.pdf       # Citing paper
```

## Paper Pair and Links

1. **WebGazer: Scalable Webcam Eye Tracking Using User Interactions**
	 - DOI: [https://dl.acm.org/doi/10.5555/3061053.3061156](https://dl.acm.org/doi/10.5555/3061053.3061156)
2. **SearchGazer: Webcam Eye Tracking for Remote Studies of Web Search**
	 - DOI: [https://doi.org/10.1145/3020165.3020170](https://doi.org/10.1145/3020165.3020170)

## BibTeX Entries

```bibtex
@inproceedings{papoutsaki2016webgazer,
  title={{WebGazer}: Scalable Webcam Eye Tracking Using User Interactions},
  author={Papoutsaki, Alexandra and Sangkloy, Patsorn and Laskey, James and Daskalova, Nediyana and Huang, Jeff and Hays, James},
  booktitle={Proceedings of the Twenty-Fifth International Joint Conference on Artificial Intelligence (IJCAI)},
  pages={3839--3845},
  year={2016},
  doi={10.5555/3061053.3061156},
  organization={AAAI Press}
}

@inproceedings{papoutsaki2017searchgazer,
  title={{SearchGazer}: Webcam eye tracking for remote studies of web search},
  author={Papoutsaki, Alexandra and Laskey, James and Huang, Jeff},
  booktitle={Proceedings of the 2017 conference on conference human information interaction and retrieval},
  pages={17--26},
  year={2017},
  doi={10.1145/3020165.3020170}
}
```

## Relationship Between the Two Papers

`SearchGazer` cites `WebGazer` because WebGazer established the core idea that commodity webcams and user interactions can support scalable eye tracking in real-world settings. SearchGazer then extends that foundation into a domain-specific research platform for web search behavior.

In particular, the citation is substantive because SearchGazer:

- Uses the webcam-based gaze estimation direction enabled by WebGazer.
- Adapts the interaction-driven calibration concept to web search tasks and SERP behavior.
- Moves from a general eye-tracking system to a specialized tool for remote information-retrieval experiments.
- Demonstrates that this approach can replicate findings from seminal web-search eye-tracking studies with lower cost and higher scalability.

So, SearchGazer does not cite WebGazer only as background; it cites it as a direct technical and methodological foundation that it builds on and operationalizes for a specific HCI/IR research setting.

## Google Slides Presentation

- Slide deck link: **https://docs.google.com/presentation/d/1eKcnbsTmJR92M9E5Z6-85A0mL5-WaohSoIvhdLfRNOk/edit?usp=sharing**