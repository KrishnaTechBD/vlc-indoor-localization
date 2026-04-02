# Methodology

## Problem Formulation
We formulate the central task for **Indoor Localization using Visible Light Communication and Geometric Inference** through the governing equation below.

$$\hat{\mathbf{p}} = \arg\min_{\mathbf{p}} \sum_{i=1}^{N}\left(P_{r,i}^{\mathrm{obs}} - P_{r,i}^{\mathrm{model}}(\mathbf{p})\right)^2$$

## Variable Definitions
| Symbol | Definition | Value |
|---|---|---|
| \hat{\mathbf{p}} | Estimated receiver position | Derived |
| P_{r,i}^{\mathrm{obs}} | Observed received optical power from LED i | Measured/Simulated |
| P_{r,i}^{\mathrm{model}}(\mathbf{p}) | Modelled received power at position p | Derived |
| N | Number of LED anchors | 4 |

## Evaluation Logic
The repository is framed around benchmark-aware comparison, reproducible parameterization, and professor-friendly reporting.
