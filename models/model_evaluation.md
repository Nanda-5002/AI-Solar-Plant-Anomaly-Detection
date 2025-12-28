## Model Evaluation Summary

This section summarizes the performance of different machine learning
models applied to solar plant anomaly detection and fault classification.

---

## 1. Isolation Forest

**Approach:** Unsupervised anomaly detection  
**Objective:** Identify abnormal operational patterns

### Observations
- Successfully detected abnormal behavior in solar performance data
- Effective for distinguishing normal vs anomalous conditions
- Limited in multi-class fault discrimination

**Use Case:** Early anomaly detection and system monitoring

---

## 2. Random Forest

**Approach:** Supervised multi-class classification

### Observations
- Demonstrated superior accuracy and robustness
- Effectively classified multiple fault types
- Reduced overfitting and improved generalization

**Strengths**
- High classification accuracy
- Stable performance across validation and test sets

---

## 3. Decision Tree

**Approach:** Supervised classification

### Observations
- Achieved high accuracy in identifying major fault categories
- Simple and interpretable model
- Slightly lower generalization compared to Random Forest

---

## Conclusion
Among the evaluated models, **Random Forest** showed the best overall
performance in terms of accuracy and robustness, while **Isolation Forest**
was effective for unsupervised anomaly detection.
