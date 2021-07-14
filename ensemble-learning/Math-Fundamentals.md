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
```python
x = np.arange(12).reshape(3,4)
np.linalg.norm(x,ord=1) #norm 1
np.linalg.norm(x,ord=2) #norm 2
np.linalg.norm(x,ord=np.inf) #norm inf
```

5. Matrix

Ax = b
```python
# 写矩阵
A = np.array([(1,2,3,4),(5,6,7,8),(9,10,11,12)]) #ndarray
B = np.mat(A) #转化成matrix datatype
m, n = 1,2
np.zeros((m, n)) #全零矩阵
np.ones((m, n)) #tuple #全1矩阵

# 矩阵加法
A = np.array([(1,2,3,4),(5,6,7,8),(9,10,11,12)])
B = np.array([(1,2,3,4),(5,6,7,8),(9,10,11,12)])
C = A + B

# 数乘
k = 10
k*A

# 矩阵乘法
np.matmul(A.T, B)

# 行列式
np.linalg.det(A)
```









