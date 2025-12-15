# Skill-Based Recipe Difficulty Classification (NLP)

This project applies Natural Language Processing (NLP) and supervised machine learning to classify baking recipes into three difficulty levels: **Beginner**, **Intermediate**, and **Advanced**, based solely on recipe instructions.

## Overview
Most recipe platforms categorise content by ingredients or cuisine, but not by skill level. This project explores whether linguistic patterns in recipe instructions can be used to infer recipe complexity automatically.

## Key Techniques
- Text preprocessing and token engineering
- TF-IDF vectorisation with n-grams
- Class imbalance handling (SMOTE, BorderlineSMOTE)
- Supervised models:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Cross-validation and hyperparameter tuning
- Feature importance and error analysis

## Data
Recipes were scraped from publicly available baking websites. Instruction text was cleaned, standardised, and used as the primary input feature.

## Outcome
The models demonstrate that recipe difficulty can be partially inferred from textual structure, technique references, and instruction complexity. Gradient Boosting achieved the most balanced performance across all difficulty levels.

## Tech Stack
Python, scikit-learn, NLTK, pandas, imbalanced-learn, matplotlib, seaborn

## Notes
This repository focuses on experimentation, model comparison, and interpretability rather than deployment.
