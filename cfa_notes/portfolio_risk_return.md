# Portfolio Risk and Return

## Definition

Portfolio expected return is the weighted average of the expected returns of the assets in the portfolio. Portfolio risk depends on each asset's risk and on how the assets move together.

## Formula

Two-asset expected return:

```text
E(R_p) = w_1 x E(R_1) + w_2 x E(R_2)
```

Two-asset variance:

```text
sigma_p^2 = w_1^2 sigma_1^2 + w_2^2 sigma_2^2 + 2w_1w_2rho_12sigma_1sigma_2
```

Where:

- `w` = portfolio weight
- `sigma` = standard deviation
- `rho_12` = correlation between asset 1 and asset 2

## Intuition

Return is straightforward because it is a weighted average. Risk is more interesting because correlation matters.

If assets are not perfectly positively correlated, diversification can reduce portfolio risk. The lower the correlation, the stronger the diversification benefit.

## Common Trap

Do not assume adding more assets automatically creates meaningful diversification. Diversification depends on correlations and exposures, not just the number of holdings.

Another trap is thinking portfolio standard deviation is the weighted average of asset standard deviations. That is only true in special cases.

## Mini Example

Asset A has expected return of `8%`, asset B has expected return of `4%`, and the portfolio weights are `60%` and `40%`.

```text
E(R_p) = 0.6 x 8% + 0.4 x 4% = 6.4%
```

The risk calculation also needs volatilities and correlation.

## Related Concepts

- Diversification
- Correlation
- Covariance
- Efficient frontier
- CAPM
