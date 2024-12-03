# 2-2-MATRIX
import numpy as np
a=np.array([[10,20,30],[40,50,60]])
print(a)
d=a.dtype
print("the datatype of matrix a is=",d)

 #2 rank of matrix
rank=a.ndim
print("the rank of matrix a is=",rank)
#3 order of matrix

order=a.shape
print("the order of matrix a is=",order)

#4 CONVERTING 2D INTO 1D
shape=a.reshape(1,1,6)
print(shape)

 #5 CREATE NOTHER 2*2 MATRIX AND PERFORM ADD, SUBS,AND DIVISON OPERATIONS
b=np.array([[1,2,3],[4,5,6]])
add=a+b
print("the addition of matrix a and b is",add)
substract=a-b
print("the substraction of matrix a and b is",substract)
division=a/b
print("the division of matrix a and b is",division) 
