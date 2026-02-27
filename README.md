# Fraud Risk Analytics: Threshold Optimization & Review Cost Modeling

## Business Problem

Fraud detection systems generate high volumes of alerts. Reviewing every alert increases operational cost and investigator workload, while ignoring alerts increases fraud losses.

Fraud teams must balance:

- Fraud loss (false negatives)
- False positive workload and customer friction
- Investigator review cost
- Alert volume and operational capacity

This project evaluates how threshold optimization and selective review policies impact total operational cost in fraud monitoring systems.

---

## Objective

Minimize total operational cost by modeling trade-offs between:

- Fraud loss (false negatives)
- False positive cost
- Human review cost

Total Operational Cost = Fraud Loss + False Positive Cost + Review Cost

This project demonstrates how decision thresholds and review allocation strategies influence investigation workload and fraud capture efficiency.

---

## Approach

This project simulates a fraud monitoring pipeline and evaluates how operational decisions affect total cost.

The framework includes:

1. A probabilistic fraud detection model (e.g., Logistic Regression).
2. Threshold tuning to control alert volume.
3. Selective human review allocation based on model confidence.
4. Cost-sensitive evaluation using asymmetric false-positive and false-negative costs.

The analysis isolates decision-layer effects to understand how:

- Threshold adjustments impact false positives and fraud capture.
- Review allocation policies affect investigation workload.
- Cost trade-offs influence optimal alert strategies.

No model retraining is performed. The focus is on operational optimization through decision policy design.
