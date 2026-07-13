# Machine-Learning-Comparison-Experiments-Repository
# Machine Learning Comparison Experiments Repository
This repository stores a series of comparative machine learning experiments, including two core research directions:
1. Traditional tabular machine learning performance comparison on tiny & imbalanced datasets
2. Performance benchmark of PDE-solving models: standard PINN and optimized PINN variants

## Experiment Contents
### Part 1: Tiny Imbalanced Dataset Benchmark
- Classical ML models: Logistic Regression, XGBoost, LightGBM, Random Forest, SVM
- Evaluation metrics: F1-score, AUC-ROC, Recall, Precision under extreme class imbalance
- Data setting: limited small sample size, class distribution skew

### Part 2: PINN Optimization Comparison
- Baseline: Original deterministic Physics-Informed Neural Networks with SGD optimizer
- Optimized variants1: PINN with Adam optimizer
- Optimized variants2: PINN with AdamW+Gradients Clipping +cosine annealing+smoothing
## Repository Folder Structure
```├── notebooks/
   │ ├── kaggle-experiments/ # All raw notebooks exported from Kaggle
   │ ├── tabular-imbalance/ # Tiny imbalanced dataset ML comparison codes
   │ └── pinn-optimization/ # PINN optimizer & regularization contrast experiments
   ├── src/ # Reusable model functions, metrics, PDE residual tools
   ├── configs/ # Hyperparameter yaml configs for each experiment group
   ├── scripts/ # Standalone training & evaluation scripts
   ├── .gitignore # Predefined filter for cache, datasets and model weights
   ├── LICENSE # MIT open-source license
   ├── requirements.txt # Full Python environment dependencies
   └── README.md

