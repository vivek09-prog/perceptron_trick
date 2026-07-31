# Perceptron Notebook

## Work completed - 30 July 2026

- Created and set up the notebook as `perceptron.ipynb`.
- Added imports for NumPy, pandas, Matplotlib, logistic regression, and `r2_score`.

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

from sklearn.linear_model import LogisticRegression
from sklearn.metrics import r2_score
```

## Work completed - 31 July 2026

- Fixed the `perceptron` function error by adding `x` and `y` parameters.
- Replaced the hard-coded sample count (`100`) with `x.shape[0]`, so the function works with datasets of any size.
