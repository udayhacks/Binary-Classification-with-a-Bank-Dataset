# 🏦 Kaggle Playground Series 2025 - Bank Term Deposit Prediction

Welcome to the **Kaggle Playground Series 2025**! This competition provides an approachable dataset for practicing machine learning skills. Your goal is to build a binary classification model to predict whether a client will subscribe to a bank term deposit.

---

## 🎯 Goal

Predict the probability that a client will subscribe to a bank term deposit.

---
## DATA 
```kaggle competitions download -c playground-series-s5e8```
---


## 🧪 Evaluation Metric

Submissions are evaluated using the **ROC AUC** score between the predicted probability and the actual target.

- You must submit **predicted probabilities** for the positive class (class 1).
- Do **not** submit hard class labels (0 or 1).
- ROC AUC measures how well your model ranks positives vs negatives.

---

## 📝 Submission Format

Your submission file should be a CSV with the following format:

```
id,y
750000,0.74231
750001,0.12001
750002,0.89765
...
```

- `id`: Unique ID from the test set
- `y`: Predicted probability of subscribing (class 1)

---


Happy modeling and good luck on the leaderboard! 🚀
