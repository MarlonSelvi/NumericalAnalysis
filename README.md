# Numerical Lab

# README.md

# Numerical Approximation Techniques

This repository contains a Jupyter Notebook (`Lab2.ipynb`) that explores and implements various numerical approximation techniques for estimating the area under a curve without using traditional integration methods.

## Techniques Covered

- **Midpoint Interpolation**  
  Approximates the area by evaluating the midpoint of subintervals.

- **Trapezoidal Interpolation**  
  Approximates the area using trapezoids formed between consecutive points on the curve.

- **Simpson's Interpolation**  
  Approximates the area by fitting quadratic polynomials through subsets of points.

- **Gaussian Quadrature**  
  Provides highly accurate approximations using weighted sums of function values at specified points (abscissae).

## Features
- Clear implementation of each approximation technique
- Comparison of accuracy as the number of subintervals increases
- Visualization of convergence behavior for each method
- Organized and well-documented Python code with Markdown explanations

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `matplotlib`

You can install the required libraries using:
```bash
pip install numpy matplotlib
```

## How to Run
1. Clone the repository or download the notebook file.
2. Open `Lab2.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells to see the implementations and visualizations.

## Project Structure
```
.
├── Lab2.ipynb
└── README.md
```

## License
This project is licensed for educational purposes. Feel free to modify and use it for learning or academic assignments.

---

*Created as part of a study on numerical approximation techniques for numerical analysis.*


