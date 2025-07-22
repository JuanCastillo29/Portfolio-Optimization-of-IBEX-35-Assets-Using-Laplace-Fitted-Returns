# Portfolio Optimization of IBEX 35 Assets Using Laplace-Fitted Returns



This repository contains the code and results for a portfolio optimization project comparing:
1. **Laplace-based (heavy-tailed) portfolio optimization**, and
2. **Classical Gaussian (Markowitz) mean-variance portfolio optimization**,  
benchmarked against the **IBEX 35 index**.

Classical mean-variance portfolios assume normally distributed returns, underestimating extreme risks.
By optimizing portfolios under a Laplace distribution, we capture heavy tails and achieve better risk-adjusted performance, as demonstrated on IBEX 35 data.

A more detailed description of the project can be found in [this article](https://medium.com/@juan.castillo.sanz/portfolio-optimization-of-ibex-35-assets-using-laplace-fitted-returns-ea35ab0c349b).

---

## **Key Features**
- **Laplace vs. Gaussian Optimization**: Robust portfolio weights computed under both distributional assumptions.
- **IBEX 35 Benchmark**: Real market index for baseline comparison.
- **Backtesting Framework**:
  - Start value normalized to **€1**.
  - **Long-only, fully invested portfolios.**
  - Monthly returns simulated **without rebalancing** (buy-and-hold after initial allocation).


---

## Project structure



* 'Data/': Raw and processed datasets.
* 'Notebooks/': Jupyter notebooks for data collection, modelling and backtesting.
* 'Scripts/': Reusable Python scripts
* 'Outputs/':  Backtesting results, plots, performance metrics
* 'requirements.txt':  Dependencies


## Goals



* Calculate and visualize log returns and volatility
* Analyze correlations between financial assets
* Optimize portfolios under the obtained metrics



## Getting Started



1. Clone the repository
2. Install dependencies listed in 'requirements.txt'
3. Run notebooks in sequence for data collection and anaysis



----



\*Project by Juan Castillo\*



References:



