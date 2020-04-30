# newton-fractals

## Idea
The purpose of this project is to generate beautiful fractals, made from the basins of convergence for the newton method. Each color represents a different root, while the shading represents the time the algorithm took to converge.

## Usage
- Make sure you have g++ installed and run `make` wherever the repository is cloned. This will compile the c++ script that calculates pixel values
- Run `python newton.py n path` to generate the fractal with `nxn` points and save it to `path`

## Examples
![](./examples/test.png)

![](./examples/z3-1[-1x1].png)

![](./examples/sin.png)
