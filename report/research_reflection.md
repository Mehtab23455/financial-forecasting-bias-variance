# Research Reflection

## Motivation
The motivation for this project stemmed from a fundamental question in financial modeling: if markets exhibit complex dynamics, why do many forecasting models still fail in practice? This project explores the inherent limitations of traditional time series forecasting models through the lens of the bias–variance tradeoff.

## Key Learnings
A central takeaway was that increased model complexity does not necessarily lead to better predictive performance. Simpler models often generalize better, while more flexible models may overfit historical noise rather than capture meaningful structure.

This project clarified the practical implications of bias and variance beyond theoretical definitions, especially in noisy and non-stationary financial environments.

## Methodological Challenges
Selecting appropriate evaluation metrics and avoiding data leakage were critical challenges. Ensuring that models were compared fairly required careful train-test splits and consistent forecasting horizons.

Understanding why certain models performed well in-sample but poorly out-of-sample was a valuable learning experience.

## Interpretation of Results
The results demonstrated that forecasting financial time series is fundamentally constrained by noise and regime changes. Even well-specified models struggle to maintain stable predictive accuracy across time, reinforcing the idea that markets are difficult to forecast reliably.

## Reflection on Limitations
This project does not attempt to propose a superior forecasting model. Instead, it emphasizes understanding why forecasting is difficult and why performance degradation occurs. The findings highlight the importance of model humility and risk-aware decision-making.

## Academic Growth
This work deepened my understanding of statistical learning theory in applied settings. It improved my ability to evaluate models critically and reinforced the importance of robustness, generalization, and theoretical grounding in financial data science.
