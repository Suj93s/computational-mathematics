## Pseudocode_Solution of System of Equations
```python
FUNCTION solution(A,B):
Create Augmented matrix:K=[A/B]
Reduce in Reduced Reduced Echelon Form
Rank=no.of non zero rows of RREF
if Rank(k)!=RanK(A):
print("System is inconsistant")
ELSE IF:
Solve using back substitution
END FUNCTION
```
