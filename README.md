#  Bias–Variance Tradeoff in Financial Forecasting

This project investigates the bias–variance tradeoff in supervised learning models applied to low signal-to-noise time series. Using financial return data as a challenging real-world benchmark, we show that increasing model complexity reduces bias but amplifies variance, severely limiting out-of-sample generalization. 

## Research Objective
To investigate why traditional forecasting models fail in financial time series and analyze this failure through the bias–variance tradeoff.

## Models Evaluated
- Mean return model
- AR(1)
- ARIMA(5,0,0)

## Key Findings
- All models perform poorly out-of-sample
- Increased complexity reduces bias but increases variance
- Financial returns exhibit low signal-to-noise ratios
- Predictability is structurally limited


## Relation to Other Work
This project is part of a broader study on financial time series behavior.
A complementary project analyzes the limitations of forecasting models and the bias–variance tradeoff.

##Published Paper https://doi.org/10.5281/zenodo.18180884
