### Assignment 5: Literature Review, Part 2
CS 800 Research Methods, Spring 2026 \
Submitted by: Md Habibur Rahman 

### Description
There are two papers I have chosen  `PentestGPT`, published in USENIX 2024 and `PentestAgent`, published in ASIA CCS 2025. In this assignment I am going to show the relationship and reason behind citing. Additionally, I am going to prepare for a presentation slide for presenting it in the class.

### Directory
As submitting the google slides links so there is only README.md file available here.

```text
Rahman
└── 5
    └── README.md
 

```

### Papers Detail
1. PentestGPT: Evaluating and Harnessing Large Language Models for Automated Penetration Testing
Link: [https://www.usenix.org/conference/usenixsecurity24/presentation/deng](https://www.usenix.org/conference/usenixsecurity24/presentation/deng)
```
@inproceedings {299699,​
author = {Gelei, Deng and Yi, Liu and V{\'\i}ctor, Mayoral-Vilches and Peng, Liu and Yuekang, Li and Yuan, Xu and Tianwei, Zhang and Yang, Liu and Martin, Pinzger and Stefan, Rass},​
title = {{PentestGPT:} Evaluating and Harnessing Large Language Models for Automated Penetration Testing},​
booktitle = {33rd USENIX Security Symposium (USENIX Security 24)},​
year = {2024},​
isbn = {978-1-939133-44-1},​
address = {Philadelphia, PA},​
pages = {847--864},​
url = {https://www.usenix.org/conference/usenixsecurity24/presentation/deng},​
publisher = {USENIX Association},​
month = aug​
}​
```



2. PentestAgent: Incorporating LLM Agents to Automated Penetration Testing

Link: [https://dl.acm.org/doi/full/10.1145/3708821.3733882](https://dl.acm.org/doi/full/10.1145/3708821.3733882)

```
@inproceedings{10.1145/3708821.3733882,​
author = {Shen, Xiangmin and Wang, Lingzhi and Li, Zhenyuan and Chen, Yan and Zhao, Wencheng and
Sun, Dawei and Wang, Jiashui and Ruan, Wei},​
title = {{PentestAgent:} Incorporating {LLM} Agents to Automated Penetration Testing},​
year = {2025},​
isbn = {9798400714108},​
publisher = {Association for Computing Machinery},​
address = {New York, NY, USA},​
url = {https://doi.org/10.1145/3708821.3733882},​
doi = {10.1145/3708821.3733882},​
booktitle = {Proceedings of the 20th ACM Asia Conference on Computer and Communications Security},​
pages = {375–391},​
numpages = {17},​
keywords = {Penetration Testing, Large Language Model, Agent},​
series = {ASIA CCS '25}​
}
```


### Summary of the relationship of the two papers
`PentestGPT` is the foundational paper that identified major LLM limitations in penetration testing such as context loss, and hallucination. To solve this problem a three module framework with task tree was introduced here. But still required human involvement. On the other hand, `PentestAgent` directly built on `PentestGPT` and it solved two weaknesses, i) knowledge gap, and ii)human in the loop, by introducing RAG and web search agent inside the agent loop. Overall, `PentestAgent` outperformed `PentestGPT` in both speed and task completion.


### Google Slide Link
Here is the Google Slide Link: [Google Slides](https://docs.google.com/presentation/d/13o1HvTX8au4JlMpZsoCrz69-RQ4vWOlVUVYTa8lwR8w/edit?usp=sharing)
