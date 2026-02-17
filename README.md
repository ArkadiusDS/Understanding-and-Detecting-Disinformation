# Understanding and Detecting Disinformation

This repository accompanies my PhD dissertation:

> **Leveraging Persuasion and Intent for Analysis and Reasoning-based Detection of Disinformation with Large Language Models**
> Arkadiusz Modzelewski

It serves as the **central index repository** for all software artifacts, datasets, and experimental frameworks developed as part of the dissertation.

Following reproducibility standards emphasized in major NLP conferences (ACL, EMNLP, EACL), all code used to obtain the results in this dissertation has been made publicly available.

---

## Dissertation Structure and Corresponding Repositories

The dissertation consists of four main research chapters.
Each chapter corresponds to a published paper and has its own dedicated repository.

---

## Chapter 4 — Benchmarking Models on Polish Disinformation Detection

📄 Paper:
**MIPD: Exploring Manipulation and Intention In a Novel Corpus of Polish Disinformation**
EMNLP Main 2024

BibTeX:

```bibtex
@inproceedings{modzelewski2024mipd,
  title={MIPD: Exploring Manipulation and Intention In a Novel Corpus of Polish Disinformation},
  author={Modzelewski, Arkadiusz and Da San Martino, Giovanni and Savov, Pavel and Wilczy{\'n}ska, Magdalena and Wierzbicki, Adam},
  booktitle={Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing},
  pages={19769--19785},
  year={2024}
}
```

💻 Repository:
👉 [https://github.com/ArkadiusDS/MIPD](https://github.com/ArkadiusDS/MIPD)

**What you will find there:**

* The MIPD dataset
* Annotation schema and guidelines
* Baseline benchmarking experiments
* Model training and evaluation scripts

---

## Chapter 5 — Persuasion-Augmented Reasoning for Disinformation Detection

📄 Paper:
**PCoT: Persuasion-Augmented Chain of Thought for Detecting Fake News and Social Media Disinformation**
ACL Main 2025 (Long Papers)

ACL Anthology:
[https://aclanthology.org/2025.acl-long.1215/](https://aclanthology.org/2025.acl-long.1215/)

BibTeX:

```bibtex
@inproceedings{modzelewski-etal-2025-pcot,
    title = "{PC}o{T}: Persuasion-Augmented Chain of Thought for Detecting Fake News and Social Media Disinformation",
    author = "Modzelewski, Arkadiusz  and
      Sosnowski, Witold  and
      Labruna, Tiziano  and
      Wierzbicki, Adam  and
      Da San Martino, Giovanni",
    booktitle = "Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics"
}
```

💻 Repository:
👉 [https://github.com/ArkadiusDS/PCoT](https://github.com/ArkadiusDS/PCoT)

**What you will find there:**

* Persuasion-augmented reasoning framework
* Prompts
* Experimental evaluation scripts
* Datasets

---

## Chapter 6 — Intent-Augmented Reasoning for Disinformation Detection

📄 Paper:
**MALicious INTent Dataset and Inoculating LLMs for Enhanced Disinformation Detection**
EACL Main 2026 (Long Papers, accepted)

Citation:

```
Arkadiusz Modzelewski, Witold Sosnowski, Eleni Papadopulos,
Elisa Sartori, Tiziano Labruna, Giovanni Da San Martino,
and Adam Wierzbicki. 2026.
MALicious INTent Dataset and Inoculating LLMs for Enhanced Disinformation Detection.
In Proceedings of the 19th Conference of the European Chapter of the
Association for Computational Linguistics (Volume 1: Long Papers),
Rabat, Morocco. Association for Computational Linguistics.
```

💻 Repository:
👉 [https://github.com/ArkadiusDS/MALINT](https://github.com/ArkadiusDS/MALINT)

**What you will find there:**

* MALINT dataset
* Intent-augmented reasoning framework
* Fine-tuning and evaluation scripts

---

## Chapter 7 — Human and Machine - Generated Persuasive Text

📄 Paper (arXiv preprint):

**Can AI-Generated Persuasion Be Detected? Persuaficial Benchmark and AI vs. Human Linguistic Differences**

Authors:
Arkadiusz Modzelewski, Paweł Golik, Anna Kołos, Giovanni Da San Martino

💻 Repository:
👉 [https://anonymous.4open.science/r/Persuaficial-26EC/README.md](https://anonymous.4open.science/r/Persuaficial-26EC/README.md)

**What you will find there:**

* Persuaficial benchmark
* Human vs. AI persuasion experiments
* Linguistic feature analysis
* Detection scripts

---

## How This Repository Relates to the Others

This repository acts as:

* 📌 The **main dissertation resource entry point**
* 📚 A structured overview of all contributions
* 🔗 A directory pointing to chapter-specific repositories

Each chapter repository is self-contained and includes:

* Installation instructions
* Dataset access information
* Training and evaluation scripts

---

## Reproducibility Commitment

All experiments reported in the dissertation were conducted using the publicly available code in the linked repositories.

---

## Contact

Arkadiusz Modzelewski

For questions regarding the dissertation or repositories, please open an issue in the relevant repository or write email to arcadius.modzelewski@gmail.com
