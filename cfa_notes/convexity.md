# Convexity

## Definition

Convexity measures the curvature in the relationship between a bond's price and yield. It improves a duration-based estimate of bond price changes, especially when yield changes are large.

## Formula

Approximate percentage price change with duration and convexity:

```text
% Delta Price ~= -Modified Duration x Delta Yield + 0.5 x Convexity x (Delta Yield)^2
```

## Intuition

Duration treats the price-yield relationship as a straight line. Real bond prices follow a curve. Convexity adjusts for that curve.

For option-free bonds, positive convexity means price gains when yields fall are larger than price losses when yields rise by the same amount, all else equal.

## Common Trap

Positive convexity does not mean a bond price always rises. It means the price-yield curve bends favorably compared with a straight-line duration estimate.

Callable bonds can show negative convexity when yields fall because the issuer is more likely to call the bond, limiting price upside.

## Mini Example

Suppose modified duration is `5`, convexity is `40`, and yield rises by `1%`.

```text
Duration effect = -5 x 0.01 = -5.00%
Convexity effect = 0.5 x 40 x (0.01)^2 = 0.20%
Estimated change = -4.80%
```

Convexity makes the estimated loss slightly smaller than the duration-only estimate.

## Related Concepts

- Duration
- Callable bonds
- Interest rate risk
- Bond price-yield curve
