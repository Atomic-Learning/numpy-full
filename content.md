# Numpy: Full

You can create an array where every value is the same with `np.full()`.

```py-cell
import numpy as np

a = np.full([2, 3], 1)
print(a)
```

The first argument gives the shape of the array, in the same way as `np.zeros()`. The second argument gives the value that should be used for every entry.

This is a general way to create a filled array when you want something other than zeros.