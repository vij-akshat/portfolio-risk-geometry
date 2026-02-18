# Portfolio Risk Surface and Correlation Geometry
This project visualizes the full risk surface of a two-asset portfolio and studies how correlation structure shapes portfolio volatility. It builds geometric intuition for covariance, diversification, and efficient frontiers.
Rather than focusing only on the optimal point, this notebook maps the entire volatility landscape.

## What It Does
Given two assets with:
- Volatilities $\sigma_{1}, \sigma_{2}$
- Correlation $\rho$
- Portfolio weights $w$

Portfolio variance is: $$ \sigma^{2}_{p} = w^{2} \sigma^{2}_{1} $$

The notebook:
- Computes volatility over a dense weight grid
- Plots 3D risk surfaces
- Shows curvature changes as correlation varies
- Identifies minimum variance portfolios
---
## Feaures
- 3D volatility surface visualization
- Correlation sensitivity analysis
- Demonstrates convexity of variance
- Builds geometric intuition for diversification
- Connects surface curvature to efficient frontier theory
---
## Visualization
- 3D risk surface
- Contour plots
- Minimum variance locus
- Correlation shock scenarios
---
## Why It Matters
- Understanding the shape of the risk surface builds intuition for:
- Why diversification works
- When it fails (ρ → 1)
- How correlation drives convexity
- The geometry underlying Markowitz theory
- This is foundational for multi-asset portfolio construction.
--- 
## Requirements
- Python 3.x
- NumPy
- Matplotlib
---
Install dependencies:
``` bash
pip install numpy matplotlib
```
