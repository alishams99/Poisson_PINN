# Physics-Informed Neural Network (PINN) for Solving the Poisson Equation


Physics-Informed Neural Networks (PINNs) are a class of neural networks used to solve partial differential equations (PDEs) while simultaneously learning the solution from data. In this project, we use a PINN to solve the Poisson equation:

```
∇^2 u = f(x, y)
```

where `u` is the solution, and `f(x, y)` is a given function. We also compare the PINN's solution to the exact solution of the Poisson equation.

## Requirements

- Python 3
- TensorFlow
- NumPy
- Matplotlib

## Usage

Clone the repository:

```bash
git clone https://github.com/alishams99/Poisson_PINN.git
```


## Results

After training, the PINN predicts the solution to the Poisson equation on a grid of points. You can visualize the predicted solution by running the provided visualization code or by using your preferred visualization tool.

