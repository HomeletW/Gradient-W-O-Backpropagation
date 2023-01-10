# Gradient With or Without Backpropagation

[Experiment code](https://colab.research.google.com/drive/1MK3vQ-CjrLPtr4G5Jn8yhHUEwr2iZ1YV?usp=sharing)

Gradient-based optimization plays a central role in the modern day of machine learning. 
Backpropagation, or reverse-mode automatic differentiation, is the most widely accepted methodology for computing the gradients during the optimization stage of learning algorithms. 
Recently, an formulation called __forward gradient__ overcame the drawback of forward-mode automatic differentiation, 
providing an efficient way to obtain an unbiased estimate of the true gradient through one forward pass of a given neural network model. 
In this project, we implemented the proposed formulation and showed the convergence of forward gradient under SGD. 
In addition to the original work and experiments under SGD, we utilize the Adam optimizer with forward gradient, and the training dynamics under various learning rates suggested that backpropagation performs significantly better than forward gradients with Adam.
