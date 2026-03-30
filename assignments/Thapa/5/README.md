# Assignment 5: Literature Review, Part 2
## CS 800 Research Methods, Spring 2026
### Name : Bikash Thapa


This submission contains a summary of relationship between two close papers in my research area (applied cryptography, data security and privacy), and a google slides presentation describing this relationship.

## Directory structure

* **README.md** - This file (description, links).
* **research_papers/** - PDFs of the two papers which relationship summary is written.
* **slides** - google slides presentation file(.pdf).

## BibTeX

### Paper 1: PSMT: Private Segmented Membership Test for Distributed Record Linkage
```bibtex
@techreport{koirala2025psmt,
    title={{PSMT}: Private Segmented Membership Test for Distributed Record Linkage},
    author={Koirala, Nirajan and Takeshita, Jonathan and Stevens, Jeremy and Martin, Sam and Jung, Taeho},
    institution={Cryptology ePrint Archive},
    year={2025},
    number={2025/072}
}
```
### Paper 2: Select-Then-Compute: Encrypted Label Selection and Analytics over Distributed Datasets using FHE
```bibtex
@inproceedings{koirala2025select,
    author = {Koirala, Nirajan and Paik, Seunghun and Martin, Sam and Berens, Helena and Januszewicz, Tasha and Takeshita, Jonathan and Seo, Jae Hong and Jung, Taeho},
    title = {Select-Then-Compute: Encrypted Label Selection and Analytics over Distributed Datasets using {FHE}},
    year = {2026},
    isbn = {9798991927680},
    url = {https://dx.doi.org/10.14722/ndss.2026.240207},
    doi = {10.14722/ndss.2026.240207},
    booktitle = {Proceedings of the Symposium on Network and Distributed System Security}
}
```

## Summary of relationship between two papers

The relationship between these two papers is one of functional evolution, where the Paper 2 transforms the detection capabilities of the paper 1 into a comprehensive platform for data analytics. Paper 1 establishes the foundational architecture by introducing a scalable, summation-based protocol that allows a client to verify if a query exists within a set distributed across thousands of data holders without revealing the identities of the parties involved. Building directly upon this, Paper 2 addresses the limitation of Paper 1 only providing a "yes/no" result by enabling the secure retrieval of encrypted "labels" associated data points like transaction histories and the execution of complex, real-valued downstream computations such as machine learning inference on those labels. To make this practical for real-world use, Paper 2 introduces technical refinements like slot-wise windowing and improved Value Annihilating Function (VAF) approximations, which allow the system to handle massive 64-bit or 128-bit identifier domains that the previous Paper 1 could not handle efficiently.


**Google Slides Link:** [Google Slides](https://docs.google.com/presentation/d/12pmhEGRa5UfQ9sYx9a71QgPejaOSuQUAufrp1M_RXIY/edit?usp=sharing)
