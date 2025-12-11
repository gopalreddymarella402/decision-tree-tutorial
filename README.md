# Decision Trees: Mastering the Bias-Variance Trade-Off with max_depth

A practical tutorial exploring how the `max_depth` hyperparameter controls complexity in Decision Trees through visual demonstrations of the bias-variance trade-off.

## 📚 Overview

This repository contains a complete machine learning tutorial that teaches:
- How Decision Trees work
- The critical role of the `max_depth` hyperparameter
- The bias-variance trade-off concept
- Practical hyperparameter tuning strategies
- Ethical considerations in model complexity

## 🎯 Quick Start

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Installation
pip install -r requirements.txt
### Run the Tutorial
jupyter notebook code_decision_tree.ipynb


## 📁 Repository Contents

- **decision_tree_tutorial.pdf** - Complete tutorial document (~1,400 words)
- **code_decision_tree.ipynb** - Executable Jupyter notebook with full code
- **figures/** - Generated decision boundary visualizations
  - figure_1_high_bias.png (Underfitting example)
  - figure_2_optimal.png (Optimal complexity)
  - figure_3_high_variance.png (Overfitting example)
  - figure_4_trade_off_curve.png (Bias-variance analysis)
- **results/** - Experiment outputs
  - bias_variance_scores.csv (Accuracy metrics)
- **requirements.txt** - Python dependencies


## 🎓 Learning Outcomes

After completing this tutorial, you'll understand:
- ✅ How to control Decision Tree complexity
- ✅ The bias-variance trade-off in practice
- ✅ How to select optimal hyperparameters
- ✅ Why model complexity matters for fairness


## 📦 Dependencies


numpy>=1.23
pandas>=1.3
matplotlib>=3.4
scikit-learn>=1.0
jupyter>=1.0


## 📖 References

- Hastie, T., Tibshirani, R., Friedman, J. (2009). The Elements of Statistical Learning
- Scikit-learn Decision Tree Documentation
- Towards Data Science: Understanding Bias-Variance Trade-off

## ⚖️ License
MIT License - See LICENSE file for details
