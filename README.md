# Ordinary-Differential-Equation-Numerical-Solver
Solving Ordinary Differential Equation (or Coupled Equations) Numerically using 4th Order Runge-Kutta Method and can also be used to perform Numerical Integrations. 
### Recommendations:
* The preference would be to take independent variable ![](https://latex.codecogs.com/gif.latex?x) or ![](https://latex.codecogs.com/gif.latex?t) as ![](https://latex.codecogs.com/gif.latex?x1), dependent variable ![](https://latex.codecogs.com/gif.latex?y) as ![](https://latex.codecogs.com/gif.latex?x2) and so on.
* Solving differential equations of order greater than 1 requires decomposition of higher order differential equations into several first order differential equations.
* Provide Initial conditions to begin the calculation.
### Example:
![](https://latex.codecogs.com/gif.latex?\frac{d^2y}{dx^2}&plus;\frac{dy}{dx}=x)
<br />
<br /> This can be broken down into First order differential equations 
<br />
<br />![](https://latex.codecogs.com/gif.latex?\frac{dy}{dx}=z)
<br />![](https://latex.codecogs.com/gif.latex?\frac{dz}{dx}=x-z)
<br />
<br />Numerical solution is accurate with analytical solution to three decimal places with ![](https://latex.codecogs.com/gif.latex?h=0.0001) 
