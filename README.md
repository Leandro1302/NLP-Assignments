# NLP Assignments (2025‑2026)

## Authors
- Leandro Battistoni — ID 0001157160 — leandro.battistoni@studio.unibo.it  
- Giacomo Ponzuoli — ID 0001189368 — giacomo.ponzuoli@studio.unibo.it  
- Federico Rimondi — ID 0001205612 — federico.rimondi@studio.unibo.it

## Assignment 1 — Sexism Detection (EXIST 2023 Task 2)
Goal: build and analyze classifiers for sexist content on social media.  
Main steps implemented in the notebook:
- Download and unpack the provided dataset (`A1/data`) via the embedded `wget` cell.
- Clean and normalize text; filter to English; encode labels and splits.
- Explore the corpus (length distributions, annotator agreement, bias inspection).
- Train and evaluate three model families: CNN/LSTM baselines with GloVe embeddings, stacked variants, and a transformer baseline (`twitter-roberta-base`).
- Perform extensive error analysis (class-wise errors, OOV impact, ensemble comparison).

## Assignment 2 — Prompt Engineering with LLMs
Goal: compare LLaMA‑v3.1 and Mistral‑v0.3 on intent classification using zero‑shot and few‑shot prompting strategies.  
Main steps implemented in the notebook:
- Configure a Hugging Face access token (replace the placeholder `A2-TOKEN` cell).
- Load the provided data (`Assignment 2/data/a2_test.csv` and `demonstrations.csv`).
- Define instruction prompts and chat templates for zero‑shot and few‑shot setups.
- Generate model responses and compute F1, precision, recall, confusion matrices, and failure ratios.
- Analyze prompt variants: mixed demonstrations, length‑constrained examples, chain‑of‑thought prompts, and template length ablations.