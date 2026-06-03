# Sharpe Ratio

## Definition

The Sharpe ratio measures excess return per unit of total risk. It is often used to compare risk-adjusted performance across portfolios or strategies.

## Formula

```text
Sharpe Ratio = (R_p - R_f) / sigma_p
```

Where:

- `R_p` = portfolio return
- `R_f` = risk-free rate
- `sigma_p` = standard deviation of portfolio returns

## Intuition

A higher Sharpe ratio means the portfolio generated more excess return for each unit of volatility. It helps compare strategies with different return and risk levels.

## Common Trap

Sharpe ratio uses standard deviation, so it may not fully capture downside risk, skewness, fat tails, illiquidity, or rare large losses.

When comparing Sharpe ratios, use consistent return periods, risk-free rates, and data frequency. A daily Sharpe ratio is not directly comparable to an annual Sharpe ratio unless annualized consistently.

## Mini Example

A portfolio returns `10%`, the risk-free rate is `3%`, and portfolio standard deviation is `14%`.

```text
Sharpe Ratio = (10% - 3%) / 14% = 0.50
```

The portfolio earned `0.50` units of excess return per unit of total risk.

## Related Concepts

- Risk-adjusted return
- Standard deviation
- Sortino ratio
- Portfolio performance
- Excess return
