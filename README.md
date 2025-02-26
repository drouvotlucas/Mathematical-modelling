Mathematical Optimization Techniques

This repository contains various implementations of mathematical optimization methods, focusing on solving different types of constrained and unconstrained optimization problems. Each method is implemented in Python using libraries such as NumPy, SciPy, SymPy, Matplotlib, and Seaborn.

Least Absolute Deviations using ADMM:
-Goal: Solve regression problems by minimizing the sum of absolute deviations between observed and predicted values, which is more robust to outliers than least squares regression.
-Method: Uses the Alternating Direction Method of Multipliers (ADMM) to efficiently handle the L1-norm minimization problem by splitting it into smaller subproblems.

LASSO Regression:
-Goal: Perform regression while enforcing sparsity in the model by adding an L1 penalty, helping with feature selection and preventing overfitting.
-Method: Uses coordinate descent or least-angle regression (LARS) to iteratively adjust coefficients while applying the L1 regularization term.

PASM (Proximal Alternating Sequential Method):
-Goal: Solve large-scale optimization problems where constraints or non-differentiable terms make traditional gradient-based approaches inefficient.
-Method: Alternates between solving subproblems using proximal operators, ensuring stability in non-smooth optimization settings.

Sequential Quadratic Programming (SQP):
-Goal: Solve constrained nonlinear optimization problems by approximating them with a series of quadratic subproblems.
-Method: Iteratively constructs and solves quadratic programming (QP) subproblems, using gradient and Hessian information to refine the solution step by step.

Each method is implemented in a Jupyter Notebook format using Google Colab, making it easy to run, experiment with different parameters, and visualize results.

Feel free to explore and contribute! 🚀
