## pseudocode for linear algebra
the following `pseudocode` show how to solve a system of linear equations

    ```python
    FUNCTION solution: K = [A|b]
    Reduce to row reduced echelon form
    Rank = no:of non zero rows of RREF
    If Rank(k) != Rank(A):
        print (System is inconsistant)
    ELSEIF 
        solve using back substiution 
    END FUNCTION
    ```
   $$ A= \begin {bmatrix}
    1 & 2 & 3\\
    4 & 5 & 6\\
    7 & 8 & 9
  \end{bmatrix}
  $$
    
