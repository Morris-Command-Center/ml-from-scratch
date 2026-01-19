# Linear Regression

The simplest ML model: fit a line through data points.

## The Goal

Given points (x, y), find the line `y = mx + b` that best fits them.

## What "Best" Means

Minimize the sum of squared errors:
- For each point, measure how far the line is from the actual y value
- Square those distances (so negatives don't cancel positives)
- Sum them up
- Find m and b that make this sum smallest

## The Math (optional, but cool)

The closed-form solution:
```
m = Σ(x - x̄)(y - ȳ) / Σ(x - x̄)²
b = ȳ - m * x̄
```

Or with matrices: `θ = (X'X)^(-1) X'y`

## Why This Matters

- Foundation for understanding all regression
- Shows that ML is just optimization
- The "loss function" concept carries to neural nets
- Gradient descent on this is your first optimization algorithm
