# RBSDE via regularization

This repository contains Python notebooks for the paper [*Numerical approximation of RBSDEs via regularization*](https://hal.science/hal-05671000) by Ankush Agarwal, Emmanuel Gobet, and Yihan Zou.

## Notebooks

- Figure 1: [`notebooks/figure_1_max_rmse_y0.ipynb`](notebooks/figure_1_max_rmse_y0.ipynb)
- Figure 2: [`notebooks/figure_2_midpoint_profiles.ipynb`](notebooks/figure_2_midpoint_profiles.ipynb)
- Figure 3: [`notebooks/figure_3_discounted_obstacle_stopping_time.ipynb`](notebooks/figure_3_discounted_obstacle_stopping_time.ipynb)

## Environment

The recorded environment uses Python 3.10. Create a fresh virtual environment and install the pinned dependencies:

```bash
python3.10 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter lab
```
