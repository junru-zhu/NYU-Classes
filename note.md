## Lecture 7
Finding the Successor

```
Alg: TREE-SUCCESSOR(x)
if right[x] != null
    then return TREE-MINIMUM(right[x])
y = p[x]
while y != NULL and x = right[y]
    x = y
    y = p[y]
return y
```
