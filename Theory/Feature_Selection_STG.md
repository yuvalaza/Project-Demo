### Feature Selection Using Stochastic Gates (STG)
Feature selection problems have been extensively
studied in the setting of linear estimation (e.g. LASSO), but less emphasis has been placed on feature selection for non-linear functions.
This study introduces a novel feature selection method for neural network estimation, employing a probabilistic relaxation of the `0 norm to identify key features. Our approach, utilizing a continuous approximation of the Bernoulli distribution, enables simultaneous learning of nonlinear regression or classification functions, while identifying and utilizing only a limited subset of relevant features, through gradient descent.








<p align="center">
  <img src="stg_figure1_left.png" alt="stg_image" width="500"/>
</p>

Top: Each stochastic gate z_d is drawn from the STG approximation of the Bernoulli distribution (shown as the blue histogram on the right). Specifically, z_d is obtained by applying the hard-sigmoid function to a mean-shifted Gaussian random variable. Bottom: The z_d stochastic gate is attached to the x_d input feature, where the trainable parameter µ_d controls the probability of the gate being active

