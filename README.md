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
- Baseline: Original deterministic Physics-Informed Neural Networks
- Optimized variants: Laurent series normalized PINN, BPINN (Bayesian PINN with VI / HMC)
- Task: Solve damped harmonic oscillator PDE, mitigate gradient blowup problem

## Repository Folder Structure
