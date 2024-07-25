## Pseudocode for linear algebra
```python
FUNCTION matrix_sum(A,B);
  Get the no. of rows and columns in matrix A
  Create an empty matrix C with same dimension
  FOR each row i;
    FOR each column j;
      set C[i][j] to the sum of A[i][j] and B[i][j]
  return the matrix C
END FUNCTION
```
## Pseudocode solution of sstemof equations 
FUNCTION Solution (A,b);
  create augmented matrix K=[A|b]
  Reduce in Row Reduced Echeler form
  Rank no. of non zero rows of RREF
  if Rank(K)!=Rank(A)
    else
