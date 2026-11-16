# Michigan Fatal Crash Time-Series Analysis (2008–2023)

Course research report analyzing **192 months** of Michigan fatal-crash data from NHTSA FARS, including exploratory time-series and spectral diagnostics, seasonal ARIMA modeling, residual checks, and 12-month forecasts.

## Reported model

The available report specifies **SARIMA(1,1,1)(1,1,1)[12]**, selected using time-series diagnostics and parsimony. It reports a lag-12 Ljung–Box p-value of approximately **0.421**. The report does **not** establish held-out forecast accuracy.

An older resume describes a different specification and a 35-model search; until the corresponding source code is found, these are treated as distinct descriptions and not silently combined.

## Reproducibility

The original analysis notebook / Quarto or Python source was not provided. This is a **report-only portfolio entry** until source code, data preparation and final model settings are recovered. See `report.pdf` when uploaded.
