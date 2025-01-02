# Auto Encoder

# Overview

This assignment focuses on constructing and evaluating autoencoders using the given dataset, Pizza.csv. The main tasks involve designing an optimal autoencoder and analyzing its performance with varyinng code dimensions.

# Tasks

<ins> Autoencoder Design and MSE Evaluation</ins>

1. Data: Utilize features in columns 3 through 9 from the Pizza.csv dataset. Each row corresponds to a sample, forming the input matrix X.

2. Objective: Reconstruct X using an autoencoder with minimal MSE. The MSE is defined as:-

   MSE(X,X<sup>^</sup>) = 1/n ||X - X<sup>^</sup>||<sup>2</sup><sub>F</sub>

   where n is the number of samples and || . ||<sub>F</sub> denotes the Frobenius norm.

# Subtasks

<ins> 1. Linear Autoencoder Design </ins> :

Build an autoencoder with a linear encoder and decoder.

Exclude nonlinear activation functions.

Compute the MSE for varying code dimensions h ∈ {1,2,…,6}.

<ins> 2. Nonlinear Autoencoder Design </ins> :

Use ReLU activation function in the encoder and decoder layers.

Train the autoencoder for different code sizes.

Plot the MSE against code dimension h.

<ins> MSE and Singular Value Decomposition (SVD) </ins>

For the optimal encoder designed above, we need to explain how the MSE can be derived from the singular values of X for a fixed code dimension h.

# Dependencies

1. Python 3

2. NumPy

3. Pandas

4. TensorFlow/PyTorch

5. Matplotlib

# Results and Insights

Include visualizations and performance metrics.

Discuss trade-offs between linear and nonlinear activation functions in autoencoder design.
