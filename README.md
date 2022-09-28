# Auto-regression-Analysis
Analysis of female birth using auto regressive analysis with python
The Autoregressive Model, or AR model for short, relies only on past period values to predict current ones. It’s a linear model, where current period values are a sum of past outcomes multiplied by a numeric factor. We denote it as AR(p), where “p” is called the order of the model and represents the number of lagged values we want to include.

For instance, if we take X as time-series variable, then an AR(1), also known as a simple autoregressive model, would look something like this:

Xt = C + ϕ1Xt-1 + ϵt
