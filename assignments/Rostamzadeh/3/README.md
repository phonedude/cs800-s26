
# Project Structure

## Files

### Marked_up pdf files
- [MCP-Ssafetybench.pdf](3/Marked-up_pdfs/MCP-Safetybench.pdf)
- [mcp-universe.pdf](3/Marked-up_pdfs/mcp-universe.pdf)
- [MCPTox: A Benchmark for Tool Poisoning.pdf](3/Marked-up_pdfs/MCPTox:%20A%20Benchmark%20for%20Tool%20Poisoning.pdf)
- [ReAct.pdf](3/Marked-up_pdfs/ReAct.pdf)
- [Security foundation.pdf](3/Marked-up_pdfs/Security%20foundation.pdf)

### Screenshots
- [MCP-Safetybench.png](3/Screenshots/MCP-Safetybench.png)
- [MCP-Universe.png](3/Screenshots/MCP-Universe.png)
- [MCPTOX.png](3/Screenshots/MCPTOX.png)
- [ReAct.png](3/Screenshots/ReAct.png)
- [SecurityAgentic.png](3/Screenshots/Security_Foundation.png)

### README
- [README.md](README.md)




## Paper 1 — MCP-SafetyBench
### MCP Safety Bench

![MCP Safety Bench](3/Screenshots/MCP-Safetybench.png)

### Reference
Zong, X., Shen, Z., Wang, L., Lan, Y. and Yang, C., 2025. MCP-SafetyBench:
A Benchmark for Safety Evaluation of Large Language Models with Real-World MCP Servers.
arXiv preprint arXiv:2512.15163.
### DOI
https://doi.org/10.48550/arXiv.2512.15163

### BibTex Entry 

```
@article{zong2025mcpsafetybench,
  author={Zong, X. and Shen, Z. and Wang, L. and Lan, Y. and Yang, C.},
  title={{MCP-SafetyBench: A Benchmark for Safety Evaluation of Large Language Models with Real-World MCP Servers}},
  journal={arXiv preprint arXiv:2512.15163},
  year={2025},
  url={https://arxiv.org/abs/2512.15163}
}
```


### Problem
MCP’s openness and multi-server workflows introduce new safety risks
that existing benchmarks fail to capture, as they focus on isolated attacks or lack real-world
coverage.


### Approach
The authors propose MCP-SafetyBench, a benchmark built on real MCP servers with 20
attack types across five domains.

### Contributions

1. A unified taxonomy of 20 MCP attack types is introduced.
2. MCP-SafetyBench, a benchmarkbased on this taxonomy and real-world MCP servers is developed 
3. Evaluation of state-of-the-art LLMs showing vulnerabilities



## Paper 2 -- Systems Security Foundations for Agentic Computing

### Reference
Christodorescu, M., Fernandes, E., Hooda, A., Jha, S., Rehberger, J. and Shams, K., 2025. Systems Security Foundations for Agentic Computing.
arXiv preprint arXiv:2512.01295.

### DOI
https://doi.org/10.48550/arXiv.2512.01295

### BibTex
```
@article{christodorescu2025systems,
  author={Christodorescu, Mihai and Fernandes, Earlence and Hooda, Ashish and Jha, Somesh and Rehberger, Johann and Shams, Kayhan},
  journal={arXiv preprint arXiv:2512.01295}, 
  title={Systems Security Foundations for {Agentic Computing}}, 
  year={2025},
  eprint={2512.01295},
  archivePrefix={arXiv},
  primaryClass={cs.CR}
}

```
### **1. Problem: Security Frameworks Outpaced**

**Interaction Risks**: Frequent connections to third-party servers invite data exfiltration
and prompt injection.
**Narrow Focus**: Research often ignores end-to-end system properties in favor of
isolated model alignment.
**Principle Friction**: Standard security fails against probabilistic TCBs,
task-specific policies, and "fuzzy" semantic boundaries.


### **2. Approach: Systems Security Lens**

**Knowledge Adaptation**: Adapts established concepts like isolation and mediation to agentic loops.
**Attack-Driven Analysis**: Uses 11 case studies to map real-world exploits to violated
security principles.
**Defense-in-Depth**: Combines model robustness with system-level
and user-level guardrails.

### **3. Contributions**

**Technical Framework**: Formalizes challenges like managing non-deterministic TCBs and defining harmful vs. useful instructions.
**Exploit Taxonomy**: Details 11 major attacks (e.g., ChatGPT "SpAIware," Devin AI exposed ports) and their specific failures.
**State-of-the-Field Review**: Compares 28 current safety systems,
such as FIDES,
ACE, and Progent.

**Future Roadmap**: Sets a research agenda for instruction-data separation,
least-privilege control, and information-flow arithmetic.



## Paper 3 -- MCP-Universe: Benchmarking Large Language Models with Real-World Model Context Protocol Servers

### Reference
Luo, Z., Shen, Z., Yang, W., Zhao, Z., Jwalapuram, P., Saha, A., Sahoo, D., Savarese, S., Xiong,
C. and Li, J., 2025. Mcp-universe: Benchmarking large language models with real-world model
context protocol servers. arXiv preprint arXiv:2508.14704.


### DOI
https://doi.org/10.48550/arXiv.2508.14704

### BibTex
```
@article{luo2025mcp,
  author={Luo, Ziyu and Shen, Zehui and Yang, Wenhao and Zhao, Zheng and Jwalapuram, Prathyusha and Saha, Ankit and Sahoo, Doyen and Savarese, Silvio and Xiong, Caiming and Li, Juan},
  journal={arXiv preprint arXiv:2508.14704}, 
  title={{MCP-Universe}: Benchmarking Large Language Models with Real-World {Model Context Protocol} Servers}, 
  year={2025},
  eprint={2508.14704},
  archivePrefix={arXiv},
  primaryClass={cs.AI}
}
```

### Problem

Existing benchmarks do not evaluate LLM agents in realistic MCP environments with real servers,
dynamic data, and large tool spaces.

### Approach

The authors propose MCP-Universe, a benchmark with:

- 11 real MCP servers across multiple domains
- 231 tasks with real-world scenarios
- Execution-based evaluators (format, static, dynamic)
- Evaluation of several LLM agents and frameworks.

### Contributions

- A comprehensive benchmark for MCP-based LLM agents.
- An execution-based evaluation framework using real environments.
- Empirical analysis showing limitations of current agents.
- An extensible open-source platform.


## Paper 4 -- ReAct: Synergizing and acting in language models

### Reference
Yao, S., Zhao, J., Yu, D., Du, N., Shafran, I., Narasimhan, K.R. and Cao, Y., 2022, October.
React: Synergizing reasoning and acting in language models. 
In The eleventh international conference on learning representations.


### DOI
https://doi.org/10.48550/arXiv.2210.03629

## BibTex 
```
@inproceedings{yao2022react,
  author={Yao, S. and Zhao, J. and Yu, D. and Du, N. and Shafran, I. and Narasimhan, K.R. and Cao, Y.},
  title={{REACT: Synergizing Reasoning and Acting in Language Models}},
  booktitle={The Eleventh International Conference on Learning Representations (ICLR)},
  month={Oct.},
  year={2022},
  url={https://arxiv.org/pdf/2210.03629 }
```


### Problem
While large language models (LLMs) have demonstrated impressive performance
across tasks in language understanding and interactive decision making. Their
abilities for reasoning (e.g. chain-of-thought prompting) and acting (e.g. action
plan generation) have primarily been studied as separate topics.


### Approach
1. **ReAct Paradigm**: A novel prompt-based framework is introduced to synergize reasoning and acting within language models for general task solving.
2. **Empirical Validation**: Extensive benchmarking demonstrates the superiority of ReAct in few-shot learning compared to models using reasoning or acting in isolation.
3. **Ablation Studies**: Systematic analyses are performed to evaluate the critical interdependence between acting in reasoning tasks and reasoning in interactive tasks.
4. **Scalability & Fine-tuning**: Limitations within prompting setups are identified, and initial fine-tuning experiments are conducted to showcase ReAct's potential for improvement with additional training data.

## Paper 5 -- MCPTox: A Benchmark for Tool Poisoning Attack on Real-World MCP Servers

### MCPTOX
![MCPTOX](./3/Screenshots/MCPTOX.png)

### Reference
Wang, Z., Gao, Y., Wang, Y., Liu, S., Sun, H., Cheng, H., Shi, G., Du, H. and Li, X., 2025. 
MCPTox: A benchmark for tool poisoning attack on real-world MCP servers. 
arXiv preprint arXiv:2508.14925.
### DOI
https://doi.org/10.48550/arXiv.2508.14925


### BibTex entry
```
@article{wang2025mcptox,
  author={Wang, Z. and Gao, Y. and Wang, Y. and Liu, S. and Sun, H. and Cheng, H. and Shi, G. and Du, H. and Li, X.},
  title={{MCPTox: A Benchmark for Tool Poisoning Attack on Real-World MCP Servers}},
  journal={arXiv preprint arXiv:2508.14925},
  year={2025},
  url={https://arxiv.org/abs/2508.14925}
}
```

### Problem
- Novel attack surface due to connection to external tools
- A lack of systematic evaluation of tool poisoning attack in MCP servers
- 
### Approach
MCPTox is introduced as the first benchmark for systematically evaluating
agent robustness against Tool Poisoning in realistic MCP settings. It is built from 353
tools across 45 real-world MCP servers, 
with 1,312 malicious test cases generated using three attack templates covering 10 risk categories. 

### Contributions
- The first large-scale empirical study demonstrating that Tool Poisoning is a practical and widespread threat in real-world MCP servers.
- MCPTox, the first benchmark for MCP Tool Poisoning, with 1,312 malicious cases from 353 tools across 45 MCP servers, enabling standardized robustness evaluation.
- Evaluation shows MCP-based LLM agents are highly vulnerable to Tool Poisoning, with attack success over 72% and safety refusal below 3%.


## YouTube Link