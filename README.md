# numpy-study
Practicing Numpy Notes


```
import numpy as np

np.zeros((2, 3)) // 2 rows 3 columns

np.random.random((2, 3)) // 2 rows 3 columns with random float values

np.arange(10) // 1D array with 10 elements starting 0
np.arange(1, 10) // 1D array with 9 elements starting 1
np.arange(1, 10, 2) // 1D array with 5 elements starting 1 with step 2

array = np.array([[1, 2, 3], [4, 5, 6]]) // 2D array with 2 rows 3 columns
array.shape // (2, 3)
array.dtype // dtype('int64')

array = np.array([[1, 2, 3], [4, 5, 6]], dtype=np.float64) // 2D array with 2 rows 3 columns and float values
array.dtype // dtype('float64')
```
