# Bond Price and Yield

## Definition

Bond price is the present value of the bond's promised cash flows. Yield is the discount rate that makes the present value of those cash flows equal to the bond's market price.

The key relationship is inverse: when required yield rises, bond price falls; when required yield falls, bond price rises.

## Formula

For a plain fixed-coupon bond:

```text
Price = C / (1 + y)^1 + C / (1 + y)^2 + ... + (C + FV) / (1 + y)^N
```

Where:

- `C` = coupon payment per period
- `y` = yield per period
- `FV` = face value
- `N` = number of periods

## Intuition

A bond usually pays fixed contractual cash flows. If the market now requires a higher return, those same fixed cash flows must be discounted at a higher rate. A higher discount rate produces a lower present value, so the bond price falls.

If market yields decline, the existing fixed coupon becomes more attractive, and the present value of the bond's cash flows rises.

## Common Trap

Do not say that the bond's coupon payment changes when market yield changes. For a fixed-rate bond, the coupon is fixed. The market price changes because the discount rate changes.

Another trap is confusing coupon rate with yield. Coupon rate is based on face value. Yield depends on the current price and expected cash flows.

## Mini Example

Assume a one-year bond pays `105` in one year. If the required yield is `5%`, its price is:

```text
105 / 1.05 = 100
```

If the required yield rises to `10%`, its price becomes:

```text
105 / 1.10 = 95.45
```

The cash flow is still `105`, but the price falls because the required yield is higher.

## Related Concepts

- Duration
- Convexity
- Yield spread
- Discount rate
- Present value
