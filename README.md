# Quantitative Finance Analysis Suite

## Introduction

The Quantitative Finance Analysis Suite is a comprehensive collection of Python scripts and models designed for professionals, academics, and enthusiasts in the field of finance. This project aims to provide a robust toolkit for the simulation and analysis of various financial phenomena, portfolio management, option pricing, risk assessment, and fixed income security analysis. By leveraging this suite, users can gain insights into market behaviors, optimize investment strategies, and understand the pricing mechanisms of different financial instruments.

## Technology Stack

- **Programming Language**: Python 3.x
- **Libraries**: NumPy, pandas, Matplotlib (or other visualization libraries), SciPy
- **Development Environment**: Any IDE that supports Python (e.g., VS Code, PyCharm, Jupyter Notebook)

## Features

1. **Stochastic Processes and Financial Models**
    - Black-Scholes Model for option pricing (`BlackScholes.py`, `BlackScholesMonteCarlo.py`)
    - Geometric Brownian Motion for stock price simulation (`GBM.py`)
    - Ornstein-Uhlenbeck Process and Vasicek Model for interest rate dynamics (`OrnsteinUhlenbeckProcess.py`, `VasicekModel.py`)
    - Wiener Process and Random Walk fundamentals (`WienerProcess.py`, `RandomWalk.py`)

2. **Portfolio Management and Optimization**
    - Markowitz Portfolio Optimization framework (`MarkowitzModel.py`)
    - Capital Asset Pricing Model for asset expected returns (`CAPM.py`)

3. **Risk Management**
    - Value at Risk (VaR) calculation using historical and Monte Carlo methods (`VaR.py`, `VaRMonteCarlo.py`)

4. **Fixed Income Analysis**
    - Present Value calculation for cash flows (`PresentValue.py`)
    - Coupon and Zero-Coupon Bond pricing (`CouponBond.py`, `ZeroCouponBond.py`)

5. **Utility Scripts**
    - Conversion of stock prices to normal/log returns (`NormalReturns.py`)

## Installation and Usage

Ensure you have Python 3.x installed on your system. It is recommended to use a virtual environment for Python projects to manage dependencies effectively.

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/quantitative-finance-suite.git
    ```

2. Install required Python packages:
    ```sh
    pip install numpy pandas matplotlib scipy
    ```

3. Navigate to the script directory and run the desired Python scripts:
    ```sh
    cd quantitative-finance-suite
    python BlackScholes.py
    ```



