# Function Fitting with Continuous Variable Quantum Neural Network
Saptadip Saha  
**National Institute of Technology**  
Agartala, India  

**With**  
Felix Ringer  
**Jefferson Lab, Old Dominion University**, USA  

**As part of**  
**REYES 2024 (UC Berkeley)**  

---
### Abstract
This project implements a Continuous Variable Quantum Neural Network (CV-QNN) for supervised function approximation, using a single-mode photonic variational circuit composed of Gaussian (rotation, squeezing, displacement) and non-Gaussian (Kerr) operations. Inputs are encoded by displacing the vacuum state in phase space, after which multiple layers of parameterized Gaussian affine transformations followed by a nonlinear Kerr activation are applied, mirroring the linear-plus-nonlinear structure of classical MLPs. The model is trained in a hybrid quantum-classical loop on a Fock-basis simulator with cutoff dimension 10, optimizing circuit parameters via gradient-based Adam to minimize MSE between the measured x-quadrature expectation values and a noisy target sine function. The results demonstrate that CV quantum circuits can learn continuous nonlinear mappings and effectively approximate smooth functions, highlighting the expressive power of continuous-variable photonic architectures for quantum machine-learning tasks. [Read Paper](https://docs.google.com/document/d/1Ljt0nsRzKQw1dYahLFbjhvNZi7oC7whNajj9orlZqko/edit?usp=sharing)
