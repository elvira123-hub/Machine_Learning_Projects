# Machine_Learning_Projects

**# Project1: AI4Chem**

In this project, I develop a simple proof of concept to investigate whether a machine learning model specifically, an **ensemble of neural networks** can accurately reproduce the CCSD(T) Cu–He binding energy curve while providing an estimate of the prediction uncertainty.

The Cu–He diatomic interaction serves as a **toy model**, allowing the complete machine learning workflow to be developed and understood on a simple system before extending it to more complex molecular systems. Reference binding energies are first computed using the **gold standard of quantum chemistry**, CCSD(T). These high-level electronic structure calculations are then used to train an ensemble of neural networks capable of learning the underlying potential energy curve.

*Goal:* The long-term objective is to replace computationally expensive *ab initio* calculations with accurate and efficient **machine learning surrogate models** that can predict potential energies within fractions of a second. 

This repository demonstrates a complete end-to-end machine learning workflow, including data preprocessing, neural network training, ensemble learning, uncertainty quantification, and visualization of the predicted potential energy surface. It is intended as a practical introduction to surrogate modeling for computational chemistry and scientific machine learning, while illustrating concepts that are broadly applicable to engineering, physics, and data-driven scientific computing.


**Take-home message:** Such an approach is not essential for a simple diatomic system (Cu–He interaction), as other well-established potentials, such as the Morse potential, already reproduce the binding energy curve extremely well. However, I use this approach because it provides the foundation for treating realistic molecular systems with many degrees of freedom, where high-level *ab initio* calculations become computationally prohibitive.


# Machine Learning Workflow for Potential Energy Prediction<img width="900" height="190" alt="grafik" src="https://github.com/user-attachments/assets/c7b32987-bd72-40ba-9c92-069e017c9861" />
