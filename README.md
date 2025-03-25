# ML_Classification

This project demonstrates basic concepts of machine learning classification using logistic regression. It includes visualization of data and interactive tools for exploring classification boundaries.

## Project Structure

- **`main.py`**: The main script that visualizes classification data using Matplotlib. It plots single-variable and two-variable datasets.
- **`lab_utils_common.py`**: Contains utility functions for logistic regression, including cost computation, gradient descent, and data normalization.
- **`plt_one_addpt_onclick.py`**: Provides an interactive plotting tool to add data points and visualize logistic regression boundaries dynamically.
- **`plt_logistic_loss.py`**: Includes functions to visualize logistic loss and cost surfaces.
- **`plt_overfit.py`**: Contains tools to demonstrate overfitting and regularization in regression and classification tasks.
- **`deeplearning.mplstyle`**: A custom Matplotlib style file for consistent plot aesthetics.

## How to Run

1. Ensure you have Python installed with the required libraries:
   - `numpy`
   - `matplotlib`
   - `ipywidgets`
   - `scikit-learn`

2. Run the `main.py` script to visualize the classification data:
   ```bash
   python main.py