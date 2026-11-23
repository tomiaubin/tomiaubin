# Tomás Aubin

Physics undergraduate at the University of Buenos Aires (UBA), looking for roles in
**quantitative finance, data science and machine learning**. I like turning models into
code and checking them against exact results and real data.

**Tools:** Python (NumPy, pandas, SciPy, scikit-learn, Matplotlib) · SQL · Git · LaTeX

## Projects

| Project | What it does | Key result |
|---|---|---|
| [var-backtesting](https://github.com/tomiaubin/var-backtesting) | Value at Risk and Expected Shortfall (historical, parametric, Monte Carlo) with Kupiec and Basel backtesting on 10 years of stock data | The normal model fails at 99%: 61 exceptions vs 25 expected; red Basel zone in the 2020 crash |
| [option-pricing](https://github.com/tomiaubin/option-pricing) | Black-Scholes, binomial tree and Monte Carlo; Greeks, implied volatility, American options; independent price verification on 186 SPY market quotes | Flat-volatility marks fail for 91% of quotes because of the skew; IPV adjustment and bid-offer reserve for a sample book |
| [credit-default-ml](https://github.com/tomiaubin/credit-default-ml) | Credit card default prediction on 30,000 clients: SQL exploration, logistic regression, gradient boosting | AUC 0.786 on unseen clients |
| [ising-model-2d](https://github.com/tomiaubin/ising-model-2d) | Monte Carlo simulation of the 2D Ising model | Critical temperature 2.270 vs exact 2.2692 |
| [double-pendulum](https://github.com/tomiaubin/double-pendulum) | Euler vs RK4 vs `odeint` on a chaotic system | Measured convergence orders 1.18 and 3.93; Lyapunov exponent about 0.9 s⁻¹ |

Every project has tests, a README with the numbers above and instructions to reproduce them.
