# NumPy Functions

## Introduction :

**NumPy (Numerical Python)** is a fundamental Python library for
numerical computing. It provides fast, memory-efficient **N-dimensional arrays** and a large collection
of functions for mathematical, statistical, linear-algebra, and
random-number operations.

------------------------------------------------------------------------

## 1. Import NumPy

-   `import numpy as np` --- Imports NumPy and gives it the commonly
    used alias `np`.

## 2. Create NumPy Arrays

-   `np.array()` --- Creates a NumPy array from a list, tuple, or other
    array-like object.

## 3. Array Dimensions

-   `ndim` --- Returns the number of dimensions of an array.
-   `shape` --- Returns the size of the array along each dimension.
-   `size` --- Returns the total number of elements in the array.
-   `dtype` --- Returns the data type of the array elements.

## 4. Create Arrays of Zeros

-   `np.zeros()` --- Creates an array filled with zeros.

## 5. Create Arrays of Ones

-   `np.ones()` --- Creates an array filled with ones.

## 6. Create Arrays with a Constant Value

-   `np.full()` --- Creates an array with a specified shape and constant
    value.

## 7. Create Identity Matrix

-   `np.identity()` --- Creates a square identity matrix with ones on
    the main diagonal.

## 8. Generate Number Sequences

-   `np.arange()` --- Generates evenly spaced values within a specified
    range using a step size.

## 9. Generate Evenly Spaced Values

-   `np.linspace()` --- Generates a specified number of evenly spaced
    values between two endpoints.

## 10. Array Indexing

-   `arr[index]` --- Accesses an individual element using its position.

## 11. Negative Indexing

-   `arr[-1]` --- Accesses elements from the end of an array.

## 12. Two-Dimensional Indexing

-   `arr[row, column]` --- Accesses an element at a specific row and
    column.

## 13. Array Slicing

-   `arr[start:stop:step]` --- Extracts a selected portion of an array.

## 14. Two-Dimensional Slicing

-   `arr[rows(start:stop:step), columns(start:stop:step)]` --- Selects specific rows and columns from a
    multidimensional array.

## 15. Element-wise Addition

-   `a + b` --- Adds corresponding elements of two compatible arrays.

## 16. Element-wise Subtraction

-   `a - b` --- Subtracts corresponding elements of two compatible
    arrays.

## 17. Element-wise Multiplication

-   `a * b` --- Multiplies corresponding elements of two compatible
    arrays.

## 18. Element-wise Division

-   `a / b` --- Divides corresponding elements of two compatible arrays.

## 19. Power Operation

-   `a ** n` --- Raises each array element to the specified power.

## 20. Scalar Operations

-   `arr * value` --- Applies the same arithmetic operation to every
    element of an array.

## 21. Universal Functions (ufunc)

-   `np.sqrt()` --- Calculates the square root of each element.
-   `np.exp()` --- Calculates the exponential of each element.
-   `np.log()` --- Calculates the natural logarithm of each element.
-   `np.sin()` --- Calculates the sine of each element.
-   `np.cos()` --- Calculates the cosine of each element.
-   `np.abs()` --- Returns the absolute value of each element.

## 22. Sum

-   `np.sum()` --- Calculates the sum of array elements.

## 23. Mean

-   `np.mean()` --- Calculates the arithmetic mean of array elements.

## 24. Median

-   `np.median()` --- Returns the middle value of sorted data.

## 25. Minimum and Maximum

-   `np.min()` --- Finds the smallest value in an array.
-   `np.max()` --- Finds the largest value in an array.

## 26. Standard Deviation

-   `np.std()` --- Measures the spread of values around the mean.

## 27. Variance

-   `np.var()` --- Calculates the average squared deviation from the
    mean.

## 28. Boolean Operations

-   `arr > value` --- Produces a Boolean array showing which elements
    satisfy the condition.

## 29. Boolean Indexing

-   `arr[condition(Boolean Operation)]` --- Selects elements that satisfy a Boolean
    condition.

## 30. Broadcasting

-   `broadcasting` --- Allows NumPy to perform operations between
    compatible arrays with different shapes.

## 31. Reshape Arrays

-   `np.reshape()` / `arr.reshape()` --- Changes the shape of an array
    without changing its data.

## 32. Flatten Arrays

-   `arr.flatten()` --- Converts a multidimensional array into a
    one-dimensional copy.

## 33. Ravel Arrays

-   `arr.ravel()` --- Converts an array into one dimension, usually
    without making a copy when possible.

## 34. Transpose Arrays

-   `arr.T` --- Swaps the rows and columns of a 2D array.

## 35. Concatenate Arrays

-   `np.concatenate()` --- Joins multiple arrays along an existing axis.

## 36. Vertical and Horizontal Stacking

-   `np.vstack()` --- Stacks arrays vertically.
-   `np.hstack()` --- Stacks arrays horizontally.

## 37. Split Arrays

-   `np.split()` --- Divides an array into multiple equal sections.

## 38. Sort Arrays

-   `np.sort()` --- Returns the sorted values of an array.

## 39. Find Unique Values

-   `np.unique()` --- Returns the unique values in an array and can
    optionally return their counts.

## 40. Random Number Generation

-   `np.random.default_rng()` --- Creates a modern NumPy random-number
    generator for reproducible random operations.
-   `rng.random()` --- Generates random floating-point values between 0
    and 1.
-   `rng.integers()` --- Generates random integer values.
-   `rng.normal()` --- Generates random values from a normal
    distribution.
-   `rng.shuffle()` --- Randomly rearranges elements of an array.

## 41. Linear Algebra

-   `np.linalg` --- Provides functions for matrix and vector
    calculations used extensively in Machine Learning.

## 42. Dot Product

-   `np.dot()` --- Calculates the dot product of vectors or performs
    matrix-related multiplication.

## 43. Matrix Multiplication

-   `A @ B` --- Performs matrix multiplication between compatible arrays.
-   `np.matmul()` --- Performs matrix multiplication explicitly.

## 44. Matrix Inverse 

-   `np.linalg.inv()` --- Calculates the inverse of a square matrix when
    an inverse exists.

## 45. Vector Norm

-   `np.linalg.norm()` --- Calculates the magnitude or norm of a vector
    or matrix.

## 46. Missing Values and Machine Learning Usage

-   `np.isnan()` --- Detects `NaN` values in an array.
-   `np.nanmean()` --- Calculates the mean while ignoring `NaN` values.
-   `np.nanmedian()` --- Calculates the median while ignoring `NaN`
    values.
-   `np.nanmin()` --- Finds the minimum while ignoring `NaN` values.
-   `np.nanmax()` --- Finds the maximum while ignoring `NaN` values.

### Common Machine Learning Usage

-   `X` --- Usually represents the input feature matrix containing
    samples and features.
-   `y` --- Usually represents the target or output values.
-   `axis=0` --- Performs an operation column-wise, commonly used to
    calculate feature statistics.
-   `axis=1` --- Performs an operation row-wise, commonly used to
    calculate sample statistics.

------------------------------------------------------------------------
