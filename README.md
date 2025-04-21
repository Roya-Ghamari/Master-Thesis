# Master-Thesis
Forecast reconciliation is a post forecasting process that ensures coherence when dealing with
linear constraints time series, aligning predictions at different levels of aggregation. Exploring
the cross-temporal framework, this thesis compares different linear and machine learning-based
solutions with two empirical applications: Citi Bike rental demand and Energy Load. While
both datasets share the same temporal structure, they differ in cross-sectional hierarchy and
industry context, allowing for a broader evaluation of reconciliation methods.
Key concepts in this study include evaluating different reconciliation strategies by exploring
various covariance matrice structures, refining residual handling in linear and machine learningbased
models, and ensuring consistency in non-negativity constraints across all reconciliation
methods. The results indicate that, in contrast to prior findings, linear reconciliation methods
consistently outperformed ML-based approaches. Among the linear models, heuristic and
optimal linear reconciliation approaches demonstrated the highest forecast accuracy. On the
other hand, Random Forest remained the strongest ML-based reconciliation method.
Sensitivity analyses revealed that including a wide range of temporal aggregation levels generally
improves accuracy, reinforcing the value of comprehensive reconciliation structures. The
choice between compact and complete feature matrices had a notable impact on ML reconciliation
performance, with its effects varying across hierarchical levels. These findings highlight
the importance of methodological choices in reconciliation and their influence on forecast accuracy.
