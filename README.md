# Ordinary-Differential-Equation-Numerical-Solver
Solving Ordinary Differential Equation Numerically using 4th Order Runge-Kutta Method and can also be used to perform Integrations Numerically
### Recommendations:
* The preference would be to take independent variable ![](https://latex.codecogs.com/gif.latex?x) or ![](https://latex.codecogs.com/gif.latex?t) as ![](https://latex.codecogs.com/gif.latex?x1), dependent variable ![](https://latex.codecogs.com/gif.latex?y) as ![](https://latex.codecogs.com/gif.latex?x2) and so on.
* Solving higher order differential equations (Order>1) requires decomposition of higher order differential equations into several first order differential equations.
* Provide Initial conditions to begin the calculation.
### Example:
![](https://latex.codecogs.com/gif.latex?\frac{d^2y}{dx^2}&plus;\frac{dy}{dx}=x)
<br />
<br /> This can be broken down into First order differential equations 
<br />
<br />![](https://latex.codecogs.com/gif.latex?\frac{dy}{dx}=z)
<br />![](https://latex.codecogs.com/gif.latex?\frac{dz}{dx}=x-z)
<br />
<br />The code also follows the same order of inputs
<br />
<br />Output of the following with ![](https://latex.codecogs.com/gif.latex?y=0) and ![](https://latex.codecogs.com/gif.latex?y'=0)
<br />at ![](https://latex.codecogs.com/gif.latex?x=x1=3.141), ![](https://latex.codecogs.com/gif.latex?x=x1=3.141&space;,\&space;y=x2&space;=&space;2.755799682673804&space,\&space;z=x3&space;=&space;2.1915219259916685)
