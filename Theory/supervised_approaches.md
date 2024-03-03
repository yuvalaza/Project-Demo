---
layout: page
title: Key Approaches and Algorithms
permalink: /Theory/supervised_approaches/
menubar: theory_menu
---

# Supervised Key Approaches and Algorithms

- ## LASSO

    The LASSO (Least Absolute Shrinkage and Selection Operator) is renowned for its use of the L1 regularization term, which is mathematically denoted as:

    $$\lambda \|\beta\|_1 \$$

    Here, $\|\beta\|_1$ represents the L1 norm of the coefficients vector $\beta$. The L1 regularization term is the sum of the absolute values of the coefficients multiplied by a tuning parameter $\lambda$ .

    The parameter $\lambda$ is crucial. A larger λ value increases the amount of regularization, leading to more coefficients being shrinked to zero, effectively eliminating the influence of certain features in the model. This characteristic can provide interpretable models while effectively managing the risk of overfitting.

    It's important to note that LASSO's regularization is specifically designed for linear models. 