# Chapter 1: Mathematical Fundamentals of Machine Learning

1. Differential calculus

2. Linear algebra

3. Probability Theory and Statistics

4. Stochastic process and sampling principle

## 1. Differential calculus
1. Three matrix

**Gradient** of a differentiable function f is the vector field whose value at a point p is the vector whose components are the partial derivatives of f at p.

**Jacobian Matrix**: R_n->R_m. Every role is a gradient vector.

**Hessian Matrix**: Hessian matrix is the Jacobian Matrix of gradient vector.

2. Optimization
- Maxima and minima: f''(x0)<0-> Maxima, f''(x0)>0->Minima
- Saddle point: not good
- Multivariable: Hessian Matrix, positive-definite matrix->Minima:

positive-definite matrix: determinant>0
3. Lagrange multiplier-equality constraint optimization problem

Add $/lamda$ to the optimization problem and take the derivatives of each variable and $/lamda$.
4. Tayler

## 2. Linear Algebra
1. Vector space
2. Vector
- dot product
```python
import numpy as np
a = np.array([a1, a2, a3])
b = np.array([b1, b2, b3])
c = np.dot(np.transpose(a), b)
c = np.dot(a.T, b)
```
- Linearly dependent and linearly independent. n Linearly independent vectors can form a vector space.
- Schmidt process (格拉姆-施密特正交化)： 由线性无关向量组构建正交向量组
Orthogonality (正交)
```python
from sympy.matrices import Matrix, GramSchmidt
l = [Matrix([1,2,-1]), Matrix([-1,3,1]), Matrix([4,1,0])]
o = GramSchmidt(l, True)
o
```
4. Norm范数 -Measure distance
f(x)>=0 f(ax)=|a|f(x) f(a+c)<=f(a)+f(c)
5. Matrix

Ax = b









