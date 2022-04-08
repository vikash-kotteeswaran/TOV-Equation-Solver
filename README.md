# TOV Equation Solver
This generally solves Ordinary Differential Equation (or Coupled Equations) Numerically using 4th Order Runge-Kutta Method and performs Numerical Integrations. But specifically, I have used it to solve the Tolmann Oppenheimer Volkoff equation (TOV). The TOV equation describes hydrostatic equillibrium in compact objects and hence it is a manifestation of General Relativity. The below diagram shows the TOV equation which is coupled with the mass equation. The TOV equation is represented in terms of ![](https://latex.codecogs.com/gif.latex?\rho) instead of **P**.

![TOV](https://user-images.githubusercontent.com/71982791/137198311-3ef55ff8-0ae4-4271-9432-fdc58c02b629.PNG)

### Recommendations:
* The preference would be to take independent variable ![](https://latex.codecogs.com/gif.latex?x) or ![](https://latex.codecogs.com/gif.latex?t) as ![](https://latex.codecogs.com/gif.latex?x1), dependent variable ![](https://latex.codecogs.com/gif.latex?y) as ![](https://latex.codecogs.com/gif.latex?x2) and so on.
* Solving differential equations of order greater than 1 requires decomposition of higher order differential equations into several first order differential equations.
* Provide Initial conditions to begin the calculation.

### Example:
![](https://latex.codecogs.com/gif.latex?\frac{d^2y}{dx^2}&plus;\frac{dy}{dx}=x)
<br />
<br /> This can be broken down into first order differential equations 
<br />
<br />![](https://latex.codecogs.com/gif.latex?\frac{dy}{dx}=z)
<br />![](https://latex.codecogs.com/gif.latex?\frac{dz}{dx}=x-z)
<br />

