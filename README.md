# Zipf's Law Hackathon Solutions

This repository contains my independent solutions to the remaining prompt cards from a hackathon in **LING 498 – Computational Methods in Linguistics** at **Concordia University**, winter 2026.

The hackathon challenged students to investigate whether **Zipf-like rank–frequency patterns** emerge across different kinds of linguistic evidence—including words, morpheme proxies, constructions, phoneme sequences, and semantic domains—while considering how preprocessing and annotation choices influence the results. 

While one analysis was completed during the course (Prompt 9), this repository extends the project through self-study by exploring the remaining prompt cards.

## Objectives

- Investigate Zipf-like rank–frequency distributions across multiple linguistic units.
- Compare how different linguistic representations influence rank–frequency distributions.
- Practice computational linguistic analysis using Python, Jupyter Notebooks, and NLTK.

## Repository Structure

The repository is organized by linguistic subfield. Each folder contains one or more prompt-based analyses from the LING 498 Zipf Hackathon.

```text
zipf-hackathon-analysis/
│
├── baseline/
│   └── Prompt 1 – Zipf in Words (Wordforms)
│
├── register/
│   └── Prompt 2 – Register Shift: Zipf by Genre
│
├── morphology/
│   ├── Prompt 3 – Suffixes as Morpheme Proxies
│   ├── Prompt 4 – Prefix Distributions
│   └── Prompt 5 – Hyphenated & Clitic-like Pieces
│
├── syntax/
│   ├── Prompt 6 – POS Tags
│   ├── Prompt 7 – POS Bigrams
│   └── Prompt 8 – Grammar Rules
│
├── phonetics_phonology/
│   ├── Prompt 9 – Phoneme Token Frequencies
│   ├── Prompt 10 – Onset Clusters
│   └── Prompt 11 – Stress Templates
│
└── semantics/
    └── Prompt 12 – WordNet Semantic Domains
```

Each notebook follows a consistent structure and includes:

- Research question
- Dataset and methodology
- Python implementation
- Results and interpretation
- Visualizations (when applicable)
- Discussion of limitations

## Tools

- Python
- Jupyter Notebook
- NLTK
- Regular Expressions (`re`)
- FreqDist
- NLTK corpora (Brown, Gutenberg, CMUdict, WordNet, etc.)
- matplotlib (when applicable)

## Course

**LING 498 – Computational Methods in Linguistics**  
Concordia University
