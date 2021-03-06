# Finite Difference Computing

![Python Version](https://img.shields.io/badge/python-3.7+-blue.svg)

Notes from Langtangen's "Finite Difference Computing with Exponential Decay Models", [published by Springer](http://link.springer.com/10.1007/978-3-319-29439-1).

### Chapters
1. **Algorithms and implementations**
    * The Forward Euler scheme
    * The Backward Euler scheme
    * The Crank-Nicolson scheme
    * The unifying / theta-rule
    * Numerical Error
    * Differentiate
    * Integrate
2. **Analysis**
    * Experimental investigations
    * Stability
    * Accuracy
    * Amplification error
    * Global error
    * Global integrated error
    * Truncation error
    * Consistency, stability, and convergence
    * Model errors
    * Data errors
    * Discretisation errors
    * Rounding errors
    * Exponential growth
3. **Generalisations**
    * Include variable coefficient and source term
    * Verification
    * Convergence
    * Systems of ODEs
    * Generic first-order ODEs
    * Implicit 2-step backward scheme
    * Leapfrog schemes
    * 2nd-order Runge-Kutta method
    * 2nd-order Taylor-series method
    * The 2nd- and 3rd-order Adams-Bashforth schemes
    * 4th-order Runge-Kutta method
3. **Models**
    * Scaling and dimensionless variables

### Dependencies
* [`Python`](https://www.python.org/) >= 3.7
* [`NumPy`](http://www.numpy.org/)
* [`SciPy`](https://www.scipy.org/)
* [`SymPy`](https://www.sympy.org/)
* [`Matplotlib`](https://matplotlib.org/)

### Usage
Overview of chapters is given above. To run all code for a particular chapter,
e.g. chapter 1, simply run
```
python chap1.py
```
To specify a particular method(s), then enter the name of the method after the
filename, e.g. to run the methods `forward_euler` and `backward_euler` inside
`chap1.py`, do
```
python chap1.py forward_euler backward_euler
```
