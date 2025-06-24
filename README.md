# Meta ML Experiment Outcome Predictor

Simulate hundreds of ML experiments with different hyperparameters and predict:
- Whether the experiment will **succeed**
- What its **final accuracy** will be

---

## 📌 Overview

This project mimics how machine learning researchers:
- Design experiments with varied hyperparameters
- Analyze patterns behind which ones succeed
- Use predictive models to guide future experiments

---

## 🛠 Features

- Simulated dataset of 1000 synthetic ML experiments
- Features: `learning_rate`, `num_layers`, `batch_size`, `dropout`
- Target 1: **Binary classification** — did the experiment succeed?
- Target 2: **Regression** — what was the final accuracy?
- Models: Logistic Regression and Random Forest Modeling
- Visual EDA: distributions, boxplots, trends, barplots
- Feature importance & model evaluation

---

## 📊 Example Results

- **Success Prediction Accuracy**: `0.745`
- **Accuracy (Classification)**: `0.790`
- **Mean Squared Error (Accuracy Prediction)**: `0.0005`
- **R² Score**: `0.803`

---

## 📚 Key ML Concepts

- Meta-learning (learning about learning)
- Synthetic data simulation
- Feature-target relationships
- Classification and regression modeling

---

## 🔧 Requirements

Install dependencies:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn