You can create an array where every value is the same with `np.full()`.

```py-cell
import numpy as np

a = np.full([2, 3], 1)
print(a)
```

The first argument gives the shape of the array as a sequence (a list in the above example). The number of entries in the sequence gives the number of dimensions of the array. The values used in the sequence give the size of each dimension. In the example above, the array has 2 dimensions, with 2 rows and 3 columns.

The second argument gives the value that should be used for every entry.