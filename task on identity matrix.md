Numpy.identity:

----> Return a identity matrix i.e. a square matrix with ones on the main diagonal.

syntax:

numpy.identity(n, dtype = None)

Parameters:

n:int
Number of rows (and columns) in n x n output.

dtype: data-type, optional
Data-type of the output. Defaults to float.

Returns:
out: ndarray
n x n array with its main diagonal set to one, and all other elements 0.


```python
import numpy as np
```


```python
np.identity(3)
```




    array([[1., 0., 0.],
           [0., 1., 0.],
           [0., 0., 1.]])



![NumPy-Identity-Matrix.jpg.webp](attachment:NumPy-Identity-Matrix.jpg.webp)

Numpy eye():
---->The numpy. eye() function in Python is used to return a two-dimensional array with ones (1) on         the diagonal and zeros (0) elsewhere.
---> The eye tool returns a 2-D array with  1’s as the diagonal and  0’s elsewhere.
---->The diagonal can be main, upper, or lower depending on the optional parameter k.
------>A positive k is for the upper diagonal, a negative k is for the lower, and a  0 k (default) is for the main diagonal.

Syntax:

numpy.eye(R, C = None, k = 0, dtype = type <‘float’>)

Parameters : 

R : Number of rows
C : Number of columns; By default M = N
k : int, optional, 0 by default
          Diagonal we require; k>0 means diagonal above main diagonal or vice versa.
dtype : optional, float(by Default) Data type of returned array.  

Returns : 

array of shape, R x C,an array where all elements 
are equal to zero, except for the k-th diagonal, 
whose values are equal to one.

![numpy-basic-image-exercise-27.png](attachment:numpy-basic-image-exercise-27.png)


```python
np.eye(3)
```




    array([[1., 0., 0.],
           [0., 1., 0.],
           [0., 0., 1.]])




```python
np.eye(2,k=1)
```




    array([[0., 1.],
           [0., 0.]])




```python
np.eye(3,k=0)
```




    array([[1., 0., 0.],
           [0., 1., 0.],
           [0., 0., 1.]])




```python
Numpy.ones():
    
-----> The numpy.ones() function returns a new array of given shape and type, with ones

Syntax: 
    
    numpy.ones(shape, dtype = None, order = 'C') 

Parameters : 

shape : integer or sequence of integers
order  : C_contiguous or F_contiguous
         C-contiguous order in memory(last index varies the fastest)
         C order means that operating row-rise on the array will be slightly quicker
         FORTRAN-contiguous order in memory (first index varies the fastest).
         F order means that column-wise operations will be faster. 
dtype : [optional, float(byDefault)] Data type of returned array.  

    
Returns : 

ndarray of ones having given shape, order and datatype.
```

![numpy-array-ones-function-image-1.png](attachment:numpy-array-ones-function-image-1.png)


```python
np.ones(5)
```




    array([1., 1., 1., 1., 1.])




```python
np.ones((5,1))
```




    array([[1.],
           [1.],
           [1.],
           [1.],
           [1.]])




```python
np.ones((2,1))
```




    array([[1.],
           [1.]])




```python
a = (3,3)
```


```python
np.ones(a)
```




    array([[1., 1., 1.],
           [1., 1., 1.],
           [1., 1., 1.]])



Numpy.zero():

----> The numpy.zeros() function returns a new array of given shape and type, with zeros

Syntax:

numpy.zeros(shape, dtype = None, order = 'C')

Parameters :

shape : integer or sequence of integers
order  : C_contiguous or F_contiguous
         C-contiguous order in memory(last index varies the fastest)
         C order means that operating row-rise on the array will be slightly quicker
         FORTRAN-contiguous order in memory (first index varies the fastest).
         F order means that column-wise operations will be faster. 
dtype : [optional, float(byDeafult)] Data type of returned array.  

Returns : 

ndarray of zeros having given shape, order and datatype.
![NumPy-Zeroes-Method-in-Python.png](attachment:NumPy-Zeroes-Method-in-Python.png)



```python
np.zeros(5)
```




    array([0., 0., 0., 0., 0.])




```python
np.zeros((2,5))
```




    array([[0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.]])



![download.png](attachment:download.png)



```python
s = np.zeros((5,5))
s
```




    array([[0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.]])




```python

```


```python

```


```python

```
