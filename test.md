---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.1'
      jupytext_version: 1.2.4
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

# Test notebook

```python
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt
```

```python
x = np.linspace(-1,1)
y = x**3 - x**2 + 1
plt.plot(x,y);
```
