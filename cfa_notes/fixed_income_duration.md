# Fixed Income Duration

## Definition

Duration measures a bond's sensitivity to changes in yield. It helps estimate how much a bond's price changes when interest rates move.

Macaulay duration is the weighted average time to receive the bond's cash flows. Modified duration adjusts Macaulay duration to estimate price sensitivity to yield changes.

## Formula

Approximate percentage price change:

```text
% Delta Price ~= -Modified Duration x Delta Yield
```

Modified duration:

```text
Modified Duration = Macaulay Duration / (1 + yield per period)
```

## Intuition

Duration is like the bond's effective waiting time for cash flows. The longer you wait to receive cash flows, the more exposed the bond is to discount-rate changes.

Higher duration means greater price sensitivity. Lower coupon bonds and longer maturity bonds usually have higher duration, all else equal.

## Common Trap

Duration is only a first-order approximation. It works best for small, parallel yield changes. It becomes less accurate for large yield changes because the bond price-yield relationship is curved, not perfectly linear.

Also, do not confuse maturity with duration. A coupon bond's duration is usually shorter than its maturity because some cash flows arrive before maturity.

## Mini Example

If a bond has modified duration of `6` and yield rises by `0.50%`, the approximate price change is:

```text
% Delta Price ~= -6 x 0.005 = -0.03 = -3%
```

The bond price is expected to fall by about `3%`.

## Related Concepts

- Bond price and yield
- Convexity
- Interest rate risk
- Macaulay duration
- Modified duration
