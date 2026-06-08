# Netflix Recommendation System
Cult Open Projects 2026 — Team of 2

## Setup
pip install -r requirements.txt

## How to run
1. Download Netflix Prize dataset from Kaggle and place in /data
2. Run notebooks in order: 01_eda → 02_model_svd → 03_model_knn

## Models
- SVD (Matrix Factorization) via scikit-surprise
- KNN Collaborative Filtering via scikit-surprise

## Evaluation
- RMSE on test set
- MAP@10 (relevance threshold = 3.5 stars)
