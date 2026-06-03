# CAPM

## Definition

The Capital Asset Pricing Model, or CAPM, estimates the expected return of an asset based on its systematic risk relative to the market.

CAPM says investors should be compensated for the time value of money and for bearing systematic market risk.

## Formula

```text
E(R_i) = R_f + beta_i x [E(R_m) - R_f]
```

Where:

- `E(R_i)` = expected return on asset `i`
- `R_f` = risk-free rate
- `beta_i` = sensitivity of the asset to market returns
- `E(R_m) - R_f` = expected market risk premium

## Intuition

Beta measures exposure to systematic risk. If beta is above `1`, the asset is expected to move more than the market. If beta is below `1`, the asset is expected to move less than the market.

Under CAPM, only systematic risk earns an expected return premium because unsystematic risk can be diversified away.

## Common Trap

CAPM output depends heavily on inputs. Beta, the risk-free rate, and the market risk premium are estimates. Do not treat the result as a precise forecast.

Another trap is assuming high total risk always means high expected return. CAPM rewards systematic risk, not diversifiable firm-specific risk.

## Mini Example

Assume:

- Risk-free rate = `3%`
- Beta = `1.2`
- Market risk premium = `5%`

```text
Expected return = 3% + 1.2 x 5% = 9%
```

## Related Concepts

- Beta
- Systematic risk
- Market risk premium
- Security market line
- Diversification
