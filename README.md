# Task 4: Loan Default Risk + Cost Optimization

##  Objective
Predict credit card default and optimize approval threshold to minimize business cost.

## 🛠 Approach
- Used UCI Credit Card Default dataset (30K clients).
- Trained CatBoost classifier (handles imbalanced data well).
- Defined FP cost ($200) and FN cost ($5000).
- Optimized decision threshold (0.1–0.9) to minimize total cost.

##  Results
- Default threshold (0.5) → High cost from rejecting good customers.
- Optimized threshold (0.30) → Saved **$XX,XXX**.
- Model prioritized reducing costly false negatives.

##  Insight
Lowering threshold increased approvals — reduced losses from missed good customers.

##  Business Use
Maximize profit by balancing risk — not just predicting defaults. Real-world cost-sensitive ML.
