# Assignment 3: Reading Papers  
**CS 800 Research Methods, Spring 2026**  
**Name : Anurudh Singh**

This submission contains five papers from my research area (**Honeypots, Honeynets, and Deception-Based Defense**).   
Each paper includes:

- Keshav's 1st-pass summary (Problem, Approach, Contributions)  
- Full reference  
- DOI link  
- BibTeX entry  
- Screenshot of Page 1  
- Marked-up PDF with highlighted sections  

---
# Selected Papers
My research focuses on Honeypots, honeynets, and deception-based defense mechanisms. The following papers were selected because they provide foundational and practical insights into these areas.

## Paper 1: *Implementation of Honeynet and Honeypot in Network Infrastructure in Production Network*

**Reference:**  

- S. Rathore, P. K. Sharma, V. Loia, Y.-S. Jeong, and J. H. Park, “Social network security: Issues, challenges, threats, and solutions,” Information sciences, vol. 421, pp. 43–69, 2017.
- H. Lin, Z. Yan, Y. Chen, and L. Zhang, “A survey on network securityrelated data collection technologies,” IEEe Access, vol. 6, pp. 18 34518 365, 2018.

**Link:** http://arxiv.org/abs/2512.07180  
**DOI:** 10.48550/arXiv.2512.07180

```bibtex
@misc{evan2025implementationhoneynethoneypotnetwork,
      title={Implementation of Honeynet and Honeypot in Network Infrastructure in Production Network}, 
      author={Nawshad Ahmed Evan and Md Raihan Uddin},
      year={2025},
      eprint={2512.07180},
      archivePrefix={arXiv},
      primaryClass={cs.NI},
      url={https://arxiv.org/abs/2512.07180}, 
}
```

# 1st Pass (Keshav)

## Problem
- The paper addresses the increasing security challenges faced by network infrastructure in production environments due to the growing reliance on the internet and the expansion of the attack surface, particularly with the rise of IoT devices. 
- Traditional security measures like firewalls and intrusion detection systems are insufficient to counter modern cyber threats, such as unauthorized access, data theft, and Distributed Denial of Service (DDoS) attacks. 
- The study highlights the need for proactive security measures to detect, divert, and analyze attacker behavior to protect critical network resources. 


## Approach
- The paper proposes a hybrid network security model that integrates honeypots and honeynets with firewalls to enhance network security.
  The methodology involves:
### 1.	Honeypot and Honeynet Implementation:
- A honeynet is set up as a decoy network with devices mimicking real resources. 
- Two honeypots are deployed: one in front of the honeynet router to act as a fake web server and mislead attackers, and another behind the router to analyze attacker behavior and collect logs. 
### 2.	Simulation and Testing:
- The network topology is designed using the GNS3 open-source simulator, incorporating routers, switches, firewalls, and honeypots.
- Attacker behavior is simulated using tools like Kali Linux and Slowloris to generate random attacks and DDoS scenarios.
- Data is collected and analyzed using tools like Wireshark and KFSensor to understand attack patterns and trace attacker origins. 

## Contributions:
### 1. Hybrid Security Model: 
- The study introduces a three-layer security system combining honeypots, honeynets, and firewalls to provide advanced protection for production networks.
### 2. Proactive Threat Analysis: 
- The honeypots and honeynets are used to mislead attackers, collect their footprints, and analyze their behavior, providing valuable insights into attack patterns and vulnerabilities.
### 3. Real-Time Simulation: 
- The paper demonstrates the effectiveness of the proposed model through a virtual lab setup using GNS3 and VMWare, simulating real-world attack scenarios.
### 4. Enhanced Security Measures: 
- The study highlights the importance of integrating honeypots and honeynets with firewalls to provide additional layers of security, allowing security engineers to prepare for potential attacks.
### 5. Future Work: 
- The paper outlines plans to improve honeypot functionality, implement intrusion protection systems, and automate the integration of honeynets with production networks for enhanced security. 
   

## Screenshot (Page 1)
![Paper 1 Page 1](screenshots/paper1_page1.png)

## Marked-up PDF : [View Marked-up PDF](papers/paper1_implementation_honeynet.pdf)

## Paper 2: *A comprehensive survey on cyber deception techniques to improve honeypot performance*

**Reference:**  

- N.C. Abay, C.G. Akcora, Y. Zhou, M. Kantarcioglu, B. Thuraisingham
Using deep learning to generate relational honeydata
Autonomous Cyber Deception, Springer (2019), pp. 3-19

**Link:** https://doi.org/10.1016/j.cose.2024.103792  

```bibtex
@article{javadpour2024comprehensive,
  title={A comprehensive survey on cyber deception techniques to improve honeypot performance},
  author={Javadpour, Amir and Ja'fari, Forough and Taleb, Tarik and Shojafar, Mohammad and Benza{\"\i}d, Chafika},
  journal={Computers \& Security},
  volume={140},
  pages={103792},
  year={2024},
  publisher={Elsevier}
}
```

# 1st Pass (Keshav)

## Problem
The document identifies several challenges in the field of honeypots and honeynets:
### 1. Evolving Cyber Threats: 
- Attackers are constantly developing new techniques to detect and bypass honeypots, making it difficult to maintain their effectiveness. 
### 2. Lack of Comprehensive Evaluation: 
- Existing research lacks a standardized framework for evaluating honeypot performance and deception techniques. 
### 3. Limited Focus on Emerging Technologies: 
- Current honeypot research often overlooks specific vulnerabilities and services in modern environments like Software-Defined Networking (SDN), cloud computing, and 5G networks. 
### Research Gaps: 
- There is insufficient exploration of advanced deception techniques, botnet-specific honeypots, distributed honeypots, and the impact of vulnerability types on honeynet effectiveness. 

## Approach
The survey adopts a systematic approach to address these challenges:
### 1. Categorization of Honeypots: 
- Honeypots are classified based on their purpose, interaction level, implementation, activity, operation, and uniformity. 
### 2. Deception Techniques: 
- The paper explores and categorizes various deception techniques for single honeypots and honeynets, including advanced mimicking, fake cooperation, deceptive databases, subtle interruptions, honeytoken baiting, and traffic redirection. 
### 3. Mathematical Modeling: 
- A general mathematical model is proposed to analyze honeynets, enabling comparison of different deception techniques and strategies. 
### 4. Simulation Experiments: 
- Python-based simulations are conducted to evaluate the effectiveness of key deception techniques in various network scenarios. 
### 5. Evaluation Metrics: 
- A set of metrics is proposed to measure honeypot performance, including intrusion detection rate, engagement rate, time to compromise, and more.
### 6. Recommendations for Future Research: 
- The paper identifies open issues and suggests areas for further investigation, such as SDN-based honeypots, 5G-specific honeypots, and machine learning-based honeynet optimization.


## Contributions:
### 1. Comprehensive Survey: 
- The paper provides a detailed review of honeypot research over the past two decades, categorizing honeypots and honeynets based on various criteria.
### 2. Deception Techniques: 
- It introduces and categorizes six deception techniques for single honeypots and five for honeynets, offering insights into their implementation and effectiveness.
### 3. Mathematical Model:
- A novel general mathematical model is proposed to analyze honeynets and compare different deception techniques. 
### 4. Simulation Results:
- Empirical simulations are conducted to evaluate the performance of key deception techniques, providing actionable insights for researchers and practitioners. 
### 5. Evaluation Framework: 
- The paper suggests robust metrics and methodologies, including red-teaming experiments, to assess honeypot effectiveness comprehensively. 
### 6. Future Research Directions: 
- It identifies research gaps and provides recommendations for improving honeypot technologies, including the use of machine learning, addressing SDN and 5G vulnerabilities, and enhancing honeypot dynamization and topology shaping.


## Screenshot (Page 1)
![Paper 1 Page 1](screenshots/paper2_page1.png)

## Marked-up PDF : [View Marked-up PDF](papers/paper2_deception_techniques.pdf)

## Paper 3: *Honeypots: concepts, approaches, and challenges*

**Reference:**  

- Know Your Enemy: Honeynets. http://www.honeynet.org/papers/kye.html.
- SANS Institiute GIAC Certification GSEC Assignment#1.4: Honey Pots-Strategic Considerations, 2002.

**Link:** https://dl.acm.org/doi/10.1145/1233341.1233399   
**DOI** 10.1145/1233341.1233399

```bibtex
@inproceedings{10.1145/1233341.1233399,
author = {Mokube, Iyatiti and Adams, Michele},
title = {Honeypots: concepts, approaches, and challenges},
year = {2007},
isbn = {9781595936295},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/1233341.1233399},
doi = {10.1145/1233341.1233399},
abstract = {Information security is a growing concern today for organizations and individuals alike. This has led to growing interest in more aggressive forms of defense to supplement the existing methods. One of these methods involves the use of honeypots. A honeypot is a security resource whose value lies in being probed, attacked or compromised. In this paper we present an overview of honeypots and provide a starting point for persons who are interested in this technology. We examine different kinds of honeypots, honeypot concepts, and approaches to their implementation.},
booktitle = {Proceedings of the 45th Annual ACM Southeast Conference},
pages = {321–326},
numpages = {6},
keywords = {honeypots, legal issues, types of honeypots},
location = {Winston-Salem, North Carolina},
series = {ACMSE '07}
}
```

# 1st Pass (Keshav)

## Problem
The paper addresses the increasing concern of information security for organizations and individuals.  Traditional security methods are primarily defensive, which may not be sufficient to combat evolving cyber threats.  The problem lies in the need for more proactive and effective security measures to detect, prevent, and analyze cyberattacks.  Honeypots are proposed as a solution to address these challenges.

## Approach
The authors explore the concept of honeypots as a flexible security tool that can be used for prevention, detection, and information gathering. They classify honeypots based on their purpose (research, production, and honeytokens) and level of interaction (low, medium, and high).  The paper also discusses strategic considerations for implementing honeypots, such as data management, preventing liability, and deciding between building or purchasing honeypots. Additionally, it examines legal issues like entrapment, privacy concerns, and liability risks. 

## Contributions:
### 1.Comprehensive Overview: 
The paper provides a detailed survey of honeypots, serving as a starting point for individuals interested in the technology. 
### 2.Classification Framework: 
It categorizes honeypots by purpose and interaction level, offering a structured understanding of their types and applications. 
### 3.Implementation Insights:
Practical guidelines are provided for deploying honeypots, including considerations for data, location, and legal compliance.
### 4.Legal Analysis:
The paper highlights key legal challenges (entrapment, privacy, liability) and offers strategies to mitigate risks. 
### 5.Evaluation of Pros and Cons:
It identifies the advantages (e.g., simplicity, minimal resources, discovery of new tools) and disadvantages (e.g., limited vision, risk of takeover, fingerprinting) of honeypots.
### 6.Future Outlook:
The authors emphasize the potential of honeypots in cybersecurity and digital forensics, predicting their increased adoption as commercial solutions become more accessible. 


## Screenshot (Page 1)
![Paper 1 Page 1](screenshots/paper3_pag1.png)

## Marked-up PDF : [View Marked-up PDF](papers/paper3_honeypots.pdf)

