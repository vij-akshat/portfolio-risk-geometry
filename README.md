# Portfolio Risk Surface and Correlation Geometry
This project visualizes the full risk surface of a two-asset portfolio and studies how correlation structure shapes portfolio volatility. It builds geometric intuition for covariance, diversification, and efficient frontiers.
Rather than focusing only on the optimal point, this notebook maps the entire volatility landscape.

# What It Does
Given two assets with:
- Volatilities $\sigma_{1}, \sigma_{2}$
- Correlation $\rho$
- Portfolio weights $w$

Portfolio variance is: $\sigma^{2}_{p} = w^{2}\sigma^{2}_{1} + (1 - w)^{2}\sigma^{2}_{2} + 2w(1-w)\rho \sigma_{1} \sigma_{2}$
