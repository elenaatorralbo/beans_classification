# 📊 Project Summary: Imbalance & Macro F1

## 🎯 Objective
Analyze the impact of **class imbalance** on classification models and evaluate improvements using balancing techniques, optimizing the **Macro F1-score**.

---

## ⚙️ Methodology
- Train baseline classification models.
- Evaluate performance on imbalanced data.
- Apply balancing techniques:
  - Oversampling
  - Undersampling
  - Class weight adjustment
- Compare metrics before and after balancing.

---

## 📈 Key Results

- Class imbalance significantly affects performance on minority classes.
- **Accuracy** can be misleading in this context.
- **Macro F1-score** provides a more reliable evaluation.

### 🔍 Key Observations

- Without balancing:
  - Good performance on majority classes.
  - Low recall on minority classes.

- With balancing techniques:
  - Noticeable improvement in Macro F1.
  - Higher recall for minority classes.
  - Slight drop in overall precision in some cases.

---

## 🏆 Best Approach

The best performance is achieved by combining:
- Class weight adjustment  
- Oversampling  

This combination balances precision and recall effectively.

---

## 📌 Conclusions

- Choosing the right metric (Macro F1) is crucial for imbalanced datasets.
- Balancing techniques improve model fairness.
- There is a trade-off between overall performance and per-class performance.

---

## 🚀 Future Work

- Test more complex models (e.g., ensembles).
- Hyperparameter tuning.
- Evaluation on additional imbalanced datasets.