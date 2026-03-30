# CS 800, Spring 2026 - HW5: Literature Review, Part 2

**Mehrdad Rostamzadeh**
## Assignment 5
This assignment for Research Methods (CS800) focuses on analyzing the substantive academic relationship between a pair of research papers. The primary goal is to select a foundational paper and a secondary paper that builds upon, extends, or refutes the original work, followed by a 10-minute presentation explaining the rationale behind the citation.

For this project, the following papers were selected to demonstrate the evolution from AI capability to AI safety:


- Foundational Paper: MCP-Universe: Benchmarking Large Language Models with Real-World Model Context Protocol Servers.


- Substantive Extension: MCP-SafetyBench: A Benchmark for Safety Evaluation of Large Language Models with Real-World MCP Server



## Assginment 5 Structure

```
├── 1/
├── 2/
├── 3/
├── 4/
└── 5/
├── papers/
│ ├── paper1.pdf
│ └── paper2.pdf
└── README.md
```


## Paper 1  MCP Universe

### MCP-Universe: Benchmarking Large Language Models with Real-World Model Context Protocol Servers
- **Foundational Paper**: [MCP-Universe Project Page](https://mcp-universe.github.io)
### BibTex

```
@misc{luo2025mcp,
  author  = {Luo, Ziyu and Shen, Zehui and Yang, Wenhao and Zhao, Zheng and Jwalapuram, Prathyusha and Saha, Ankit and Sahoo, Doyen and Savarese, Silvio and Xiong, Caiming and Li, Juan},
  title   = {{MCP-Universe}: Benchmarking Large Language Models with Real-World Model Context Protocol Servers},
  journal = {arXiv preprint arXiv:2508.14704},
  year    = {2025},
  url     = {https://arxiv.org/abs/2508.14704}
}
```

## Paper2 MCP-SafetyBench

### MCP-SafetyBench: A Benchmark for Safety Evaluation of Large Language Models with Real-World MCP Servers
- **Substantive Extension**: [MCP-SafetyBench Repository](https://anonymous.4open.science/r/MCP-SafetyBench-5738)
### BibTex Entry

```
@misc{zong2025mcp,
  author  = {Zong, Xuanjun and Shen, Zhiqi and Wang, Lei and Lan, Yunshi and Yang, Chao},
  title   = {{MCP-SafetyBench}: A Benchmark for Safety Evaluation of Large Language Models with Real-World {MCP} Servers},
  journal = {arXiv preprint arXiv:2512.15163},
  year    = {2025}
}

```

## MCP-Universe & MCP-SafetyBench

### Overview

The relationship between these two works is defined by a progression from establishing baseline capabilities to
evaluating adversarial robustness.

#### 1. Foundation vs. Extension

- **MCP-Universe (Paper 1)**: Establishes the capability baseline for real-world tool use[cite: 11, 15].
- **MCP-SafetyBench (Paper 2)**: Serves as an adversarial extension focusing on security risks introduced by MCP’s
  openness and multi-server workflows.

#### 2. Infrastructure & Methodology Reuse

- **Shared Ecosystem**: *SafetyBench* is built directly upon the *MCP-Universe* framework, utilizing the same 11
  real-world servers (e.g., GitHub, Google Maps, Yahoo Finance) and communication protocols.
- **Task Instrumentation**: *SafetyBench* transforms "clean" tasks from *Universe* into security testbeds by
  instrumenting them with a taxonomy of 20 attack types.
- **Evaluation Synergy**: Both papers utilize a shared execution-based evaluation methodology, allowing for a direct
  comparison between "clean" utility and compromised robustness.

#### 3. The Capability-Safety Paradox

- **Inverse Correlation**: Research reveals a clear negative trend where models optimized for high task performance (
  Utility) often exhibit weaker resistance to attacks (Robustness).
- **Critical Insight**: While *MCP-Universe* established that agents can perform complex tasks, *MCP-SafetyBench* proves
  that this very utility is a primary attack vector.

### Presentation URL

https://olddominion-my.sharepoint.com/:p:/g/personal/mrost004_odu_edu/IQAFpxRDAkSsQ4FJYApErsQKAVSCXa3glbKdpx2C_PthGxU?e=DQli83

Link with editable access

https://olddominion-my.sharepoint.com/:p:/g/personal/mrost004_odu_edu/IQAFpxRDAkSsQ4FJYApErsQKAWZ14A4WDxVQpr7qHjTQdhM?e=6pmb0y