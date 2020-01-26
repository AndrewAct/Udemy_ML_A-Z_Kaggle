# Linear Algebra 

## Vectors 
### Magnitude and Direction 
* Multiplication 
* ...
* ...

## Why use vectors? 

## Kernels in SVM 
### SGD -> NN 

## Work with algorithm 

## 2D Vector and 3D Vector 
1. Distances
2. Optimization 


###### Note 
* In machine learning, vector is default to be column vector

### dot(A, B) = ||a||* ||b|| *cos(theta)
###  The projection of a on b: d = a.b/||b||

```python 
import numpy as np 
a = np.array([3,4,5])
b = np.array([1,3,6])

print(np.dot(a, b))
```

## Vector Spacer 

#### Example 
```python 
x = np.matrix([1,2,3,4], [5,6,7,8])
```

## Transpose
#### Can be used in solveing linear matrixes 
### Linear dependence 

### Rank of a matrix 
```python 
from numpy import linalg as LA
x = np.matrix([[1,2,1], [2,2,1], [[3,5,3]]])
x.shape
LA.matrix_rank(x)
# The result is 3 
```

#### Multicollinearity 

### Inverse of Matrix 
* A* A[-1] = i

## Going from 2D to nD
* Hyperplane
* W[0] + W[T]x = 0