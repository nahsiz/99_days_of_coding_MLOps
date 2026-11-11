# Day 002 - Iris Dataset EDA

## What I built
- Loaded the Iris dataset using Seaborn.
- Checked dataset shape, missing values, and unique species.
- Generated a statistical summary with describe().
- Plotted histograms to see feature distributions.
- Plotted a correlation heatmap to find feature relationships.

## What broke
- No major issues encountered.

## What I learned
- Basic EDA workflow using Pandas (head, shape, isnull, describe).
- How to visualize distributions and correlations with Matplotlib and Seaborn.
- Petal features separate species well and are highly correlated (~0.96).
- corr() needs numeric_only=True to skip text columns.
