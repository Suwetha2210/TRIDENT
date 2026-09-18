# TRIDENT
## Live Demo
https://suwetha2210.github.io/TRIDENT/
# Trident — Adversarial Prompt Detection System

Three-layer ML pipeline detecting prompt injection, jailbreak, 
and data exfiltration attacks against LLMs.

## Live Demo
https://suwetha2210.github.io/TRIDENT/

## Stack
Python | DistilBERT | TF-IDF | Random Forest | Scikit-learn | HuggingFace

## Dataset
deepset/prompt-injections — 546 samples (343 benign, 203 malicious)

## Results
- Layer 1 (Heuristic): 63.4% accuracy, 100% precision, 0 false positives
- Layer 2 (Random Forest): 93.6% accuracy
- Layer 3 (DistilBERT): ~96.8% accuracy

## Progress
- [x] R1: Dataset + EDA + Layer 1
- [x] R2: TF-IDF + Random Forest + LIME + SORT
- [x] R3: DistilBERT fine-tuned
- [x] R4: Full pipeline integration + Frontend deployed
