
# Battery State of Health Estimation using Physics-Informed Neural Networks

## Project Overview
This project implements Physics-Informed Neural Networks (PINNs) to estimate battery State of Health (SOH), combining machine learning with domain-specific battery physics.

## Accomplishments

### 1. Core PINN Implementation
- Integrated physics constraints into the loss function
- Trained models to satisfy differential equations governing battery behavior

### 2. Battery Modeling
- Explored PyBaMM (Python Battery Mathematical Modelling) framework
- Analyzed electrochemical battery models
- Generated synthetic battery degradation data

### 3. Technical Workflow
- Built Jupyter notebooks for experimentation and visualization
- Implemented custom neural network architectures
- Validated physics-informed predictions against domain knowledge

## Key Learnings

- **Physics-Informed ML**: How to embed differential equations as constraints in neural networks
- **Battery Science**: Fundamentals of electrochemistry and SOH degradation mechanisms
- **PyBaMM Framework**: Battery modeling libraries and simulation tools
- **Neural Network Design**: Architecture choices for constrained optimization problems
- **Deep Learning Validation**: Balancing data-driven and physics-based approaches

## Project Structure
```
├── PINNs/
│   ├── decay.ipynb
│   └── shm.ipynb
└── Battery Theory/
    └── pybamm.ipynb
```
