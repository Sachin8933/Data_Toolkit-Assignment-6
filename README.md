# Data_Toolkit-Assignment-6
# 🐍 Python Data Analysis & Visualization Examples

This repository showcases various Python examples using libraries such as **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly**. These examples cover data manipulation, visualization, and numerical operations.

---

## 1. Create a 2D NumPy array and calculate the sum of each row
```python
import numpy as np

arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
row_sums = np.sum(arr, axis=1)

print("2D Array:\n", arr)
print("Sum of each row:", row_sums)
