
# Capstone Report — Content Action Playbook

## 0. Abstract
This project studies whether historical content performance signals can help prioritize pages for review.
A baseline scoring method and Random Forest model were evaluated using anonymized content signals.
The output is a ranked queue for human review.

## 1. Problem framing
The goal is to help content teams decide which pages should be reviewed first.

## 2. Data safety
The project uses anonymized content performance signals.
Target-derived fields and identifiers were excluded to reduce leakage risk.

## 3. Baseline
A transparent score was created using CTR, ranking position, content age, and impressions.

## 4. Model
A Random Forest model was evaluated using historical content signals.

## 5. Evaluation
Random split and time-aware validation were compared.

## 6. Interpretation
Feature signals show relationships between historical content performance and review priority.

## 7. Recommendation
The ranked queue supports human content review decisions.

## 8. Reproducibility
Code, notebooks, and output files are stored in the repository.

## 9. Acknowledgments
Built on the FlyRank ML Internship dataset.
https://flyrank.ai
