## Pseudocode for Linear Algebra
```python
FUNCTION soilution(A,b):
  create the augmented matrix, K=[A|b]
    Reduce in Row Reducted Echlon form
    Rank=no of non zero rows of RREF
    IF Rank(K)!=Rank(A):
    print(system is inconsistent)
      ELSE IF:
        solve using back substitution
END FUNCTION

```

$$A=\begin{pmatrix}
1&2&3\\
3&4&5\\
5&6&7\\
\end{pmatrix}$$
