# Movie Quality Classification

## Business Problem

Streaming platforms evaluate large numbers of potential
content acquisitions. This project develops a machine-learning
screening system that ranks movies according to their probability
of meeting a predefined critical-quality threshold.

## Objective

Predict whether a movie achieves a Metacritic score >= 70.

## Approach

- Data cleaning
- Exploratory analysis
- Feature engineering
- Leakage prevention
- Multiple classification models
- Probability-based ranking
- Precision/Recall analysis
- PR-AUC
- Top-K analysis
- Lift analysis

## Results

Baseline positive rate: 6.0%

Top 10%:
- Precision: 28.0%
- Recall: 46.5%
- Lift: 4.66×

Top 15%:
- Precision: 23.8%
- Recall: 59.4%
- Lift: 3.97×

## Business Interpretation

The model is intended as a screening tool rather than
an autonomous acquisition decision system.

## Limitations

...
