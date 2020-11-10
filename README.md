# London-Housing

---Work in Progress---

Multivariate Time Series Predictions of London House Prices

## Data
- 34753 LSOA (Lower Super Output Area) of London,
- Quarterly Prices 1995-2019

## Pre-processing
- Format time stamps.
- Clean up numbers, replace NANs etc.
- Interpolate missing values.

<img src = "/download1.png" width="700">


## Modelling
- Test stationarity.
- Scale.
- Difference.

<img src = "/download2.png" width="700">


- Vector Auto Regression (VAR)
- Keras NN model
