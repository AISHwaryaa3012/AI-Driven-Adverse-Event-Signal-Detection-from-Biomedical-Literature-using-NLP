# Mini-Project Assignment 3: Drug–ADR Signal Detection

Student: Aishwarya Adepu  

## Overview
This project implements an end-to-end pharmacovigilance pipeline using FAERS data and PubMed text.
The goal is to detect, prioritize, and analyze drug–adverse drug reaction (ADR) signals.

## Pipeline Steps
1. Merge FAERS PRR / ROR signals with EBGM statistics
2. Load and clean PubMed text corpus
3. Extract biomedical entities using spaCy / scispaCy
4. Generate drug–ADR sentence-level candidates
5. Rank signals using rule-based + TF-IDF scoring
6. Visualize top drug–ADR relationships
7. Generate summary and report files

## Repository Structure
- `Assignment-3.ipynb` — Full working notebook
- `data/` — Input datasets (FAERS + PubMed)
- `results/` — Generated CSV outputs
- `figures/` — Visualizations

## How to Run
Open the notebook and run all cells sequentially.
All outputs are saved automatically.

## Notes
- No manual labeling was performed
- Rule-based ranking used when DL sample size was insufficient
