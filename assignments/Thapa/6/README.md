# Assignment 6: Student Dissertation Presentation
## CS 800 Research Methods, Spring 2026
### Name : Bikash Thapa
---

## Assignment description

This folder contains materials for **CS 800 – Research Methods (Assignment 6)**. The task is to **read a PhD dissertation**, then **prepare and deliver a 20 minute presentation** (about **25 minutes** total including questions and discussion). The emphasis is on **research questions**, **technical highlights**, **results and evaluation**, and **contributions**—not a full walkthrough of the thesis.

---

## Repository structure

```
.
└── README.md
```


## Dissertation presented

**Title:** Privacy-Preserving Deep Learning Framework for IoT Malware Detection 

**Author:** Sabbir Ahmed Khan  
**Institution:** Old Dominion University  
**Department / degree:** Computer Science; Doctor of Philosophy (PhD)  
**Document type:** Dissertation  
**Date of award:** Summer 2024   

**Committee:** Danella Zhao (Director); Ravi Mukkamala (Director); Stephan Olariu; Chunsheng Xin

**Abstract:** Cyberattacks on IoT devices are accelerating at an unprecedented rate, largely driven by IoT malware activities. The IoT malware attacks typically comprise three stages: intrusion, infection, and monetization. Existing IoT malware detection methods fail to identify malicious activities at the intrusion and infection stages and thus cannot stop potential attacks timely. In our research, we have leveraged power side-channel information as input to our deep learning model to identify malware at early stages of intrusion on IoT devices. But, deploying a resource-intensive deep learning model on highly resource-constrained IoT devices is a significant challenge. Consequently, utilizing a Machine Learning as a Service (MLaaS) engine to offload computation tasks to edge servers in the cloud becomes an attractive solution. However, edge computing introduces significant privacy concerns since client data from IoT devices is sensitive, and the model parameters at the edge server are regarded as proprietary information. Therefore, we propose three privacy-preserved deep learning frameworks to monitor side-channel power consumption in real-time and identify its correlation to various malware infection activities without leaking client or server information. Our first framework, DeepShield, is a secure inference-based IoT malware detection system characterized by a novel hybrid cryptographic protocol. This protocol offloads most computation to the edge and enables secret-sharing collaboration between the client and edge server. It takes the most expensive computation of homomorphic operations offline, lightening online secure interaction. However, its detection strategy must catch up with the rapid pace of malware evolution. Hence, we introduce our second framework, BoTShield, a novel privacy-preserved online training method capable of detecting malware variants. We use a combination of homomorphic encryption, secret sharing, and differential privacy approach to preserve the privacy of BoTShield. Though BoTShield represents an advancement over DeepShield, it isn’t fully equipped to detect zeroday malware attacks. Thus, we introduce MalwareShield, a privacy-preserved federated learning framework based on a novel differential privacy approach equipped with an encoder-based unsupervised model to detect zero-day malware attacks. Moreover, MalwareShiedl reduces the amount of data communication between the client and the server. Our empirical experiments demonstrate that these frameworks enable secure, accurate, real-time, and scalable malware detection.

**DOI:** [10.25777/vpxr-9x83](https://doi.org/10.25777/vpxr-9x83)  
**ODU Digital Commons:** [computerscience_etds/180](https://digitalcommons.odu.edu/computerscience_etds/180)  
**Google Scholar (author):** [Google Scholar Profile](https://scholar.google.com/citations?user=mJNY8gIAAAAJ&hl=en)  

---

## Google Slides presentation

[Bikash Thapa – Assignment 6 – Presentation](https://docs.google.com/presentation/d/1qNR5Tp2z_7WUHWmjQsUM8gQyrv9aXtPMgWiKt5sxv0c/edit?usp=sharing)

---

## Recommended citation (dissertation)

Khan, Sabbir A.. "Privacy-Preserving Deep Learning Framework for IoT Malware Detection" (2024). Doctor of Philosophy (PhD), Dissertation, Computer Science, Old Dominion University, DOI: 10.25777/vpxr-9x83 https://digitalcommons.odu.edu/computerscience_etds/180
