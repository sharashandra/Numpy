# Numpy
This repository contains all the code and description about Numpy package
Importing NumPy:
import numpy as np

Creating Arrays:
  From a list:
arr = np.array([1, 2, 3, 4, 5])

From a tuple:
arr = np.array((1, 2, 3, 4, 5))

Array Operations:
Element-wise addition:
arr1 = np.array([1, 2, 3])
arr2 = np.array([4, 5, 6])
result = arr1 + arr2
Element-wise multiplication:
result = arr1 * arr2

Array Properties:
Shape of an array:
shape = arr.shape

Number of dimensions:
ndim = arr.ndim

Reshaping Arrays:
arr = np.array([1, 2, 3, 4, 5, 6])
reshaped_arr = arr.reshape(2, 3)

Indexing and Slicing:
Accessing elements:
element = arr[1]

Slicing:
subarray = arr[1:4]

Creating Special Arrays:
Zero array:
zeros = np.zeros((3, 4))

Ones array:
ones = np.ones((2, 3))

Identity matrix:
identity = np.eye(3)

Random Numbers:
Random array:
random_arr = np.random.rand(3, 4)
