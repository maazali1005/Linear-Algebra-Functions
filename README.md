# Linear-Algebra-Functions# Linear-Algebra-Functions
import numpy as np

A = np.array([[1, 2], [3, 4]])

B = np.array([[2, 0], [1, 2]])

print("Transpose",A.T)

print("Determinant:", np.linalg.det(A))

print("Inverse:", np.linalg.inv(A))

print("Rank:", np.linalg.matrix_rank(A))

print("dot:", np.dot(A,B))

print("eigenvalues and eigenvectors:", np.linalg.eig(A))

print("singular value decomposition SVD:", np.linalg.svd(A))

O/P:

Transpose [[1 3]

[2 4]]

Determinant: -2.0000000000000004

Inverse: [[-2. 1. ]

[ 1.5 -0.5]]

Rank: 2

dot: [[ 4 4]

[10 8]]

eigenvalues and eigenvectors: (array([-0.37228132, 5.37228132]),

array([[-0.82456484, -0.41597356],

 [ 0.56576746, -0.90937671]]))

singular value decomposition SVD: (array([[-0.40455358,

-0.9145143 ],

 [-0.9145143 , 0.40455358]]), array([5.4649857 , 0.36596619]),

array([[-0.57604844, -0.81741556],

 [ 0.81741556, -0.57604844]]))
