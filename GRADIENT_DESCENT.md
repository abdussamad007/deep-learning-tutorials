### What is Gradient Descent/Mathematical Definition of Gradient Descent?
Gradient Descent is an optimization algorithm used to minimize (or maximize, with sign change) a differentiable function by iteratively moving in the direction 
of steepest descent (negative gradient).

#### 1️⃣ General Mathematical Definition
```
J(θ) = Cost / Loss function
θ = Parameter vector (θ1​,θ2​,…,θn​)
∇J(θ) = Gradient of the cost function
α = Learning rate (step size)
Update Rule
θ(t+1)= θ(t)−α∇J(θ(t))
This is the core mathematical definition of Gradient Descent.
```
In otherway, we can say Gradient Descent is an iterative optimization method that updates parameters in the negative direction of the gradient of the loss function with respect 
to the parameters,scaled by a learning rate, to minimize the function.
```
θt+1​=θt​−α∇J(θt​)​
```
### If partial derivate is the only method to determine gradient descent ?
Yes, mathematically, classical Gradient Descent relies on partial derivatives to compute the gradient.
But in practice, partial derivatives are not the only way gradients are obtained. There are alternative ways to estimate or approximate gradients when derivatives are hard or impossible to compute.
#### Why Partial Derivatives Are Used?
For a multivariable function:J(θ1​,θ2​,...,θn​)
The gradient is defined as the vector of partial derivatives:
<img width="196" height="158" alt="image" src="https://github.com/user-attachments/assets/926224f8-8adf-4a7f-9c4c-e2ab70f04dbf" />
 
 So mathematically: Gradient = Collection of partial derivatives. Therefore classical Gradient Descent requires them.

 #### If Partial Derivatives are the Only Way to determine Gradient?
Ans: No. They are the standard analytical method, but not the only practical method. There are 4 main ways gradients can be obtained:
