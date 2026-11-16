# Multi-Armed Bandit Simulation

A simulation comparing exploration and exploitation strategies across 10 fishing ponds with unknown reward probabilities.

## Policies
- Random
- Epsilon-greedy
- Softmax
- Upper Confidence Bound (UCB)

Each policy is evaluated over 100 runs of 1,000 steps. Results include average cumulative reward, reward variability, and how often the best arm is selected.

## Getting started

```bash
pip install numpy matplotlib jupyter
jupyter notebook
```

Open `bandit_simulation.ipynb` and run the cells in order.

## Results

In one experiment, epsilon-greedy achieved the highest average reward. Results depend on the random seeds, policy settings, and reward probabilities.
