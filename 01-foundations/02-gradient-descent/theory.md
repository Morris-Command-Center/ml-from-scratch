# Gradient Descent

The optimization algorithm behind almost all of machine learning.

## The Idea

Instead of solving for the optimal parameters directly (like we did with linear regression), gradient descent finds them iteratively:

1. Start with random parameters
2. Calculate how wrong we are (the loss)
3. Figure out which direction to move to reduce the loss
4. Take a small step in that direction
5. Repeat until we stop improving

## Why It Matters

- **Works when closed-form solutions don't exist** (most neural networks)
- **Scales to huge datasets** (stochastic gradient descent)
- **The foundation of deep learning**

## The Math

For a loss function L(θ), we update parameters θ as:

```
θ_new = θ_old - learning_rate * ∂L/∂θ
```

The gradient (∂L/∂θ) tells us:
- **Direction**: Which way increases the loss
- **Magnitude**: How steep the slope is

We move in the *opposite* direction (hence the minus sign).

## Learning Rate

The step size we take. Too small = slow convergence. Too big = overshoot and diverge.

Finding a good learning rate is part of the art of ML.
