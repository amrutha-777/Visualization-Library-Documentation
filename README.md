# 📊 Visualization Guide: Matplotlib vs Seaborn

This project is a comprehensive documentation guide comparing two of Python’s most popular data visualization libraries: **Matplotlib** and **Seaborn**.

---

## 📌 Objective

To provide a clear, beginner-friendly guide demonstrating the range of graphs each library can generate, complete with practical code examples.

---

## 📚 Library Overview

### Matplotlib
Matplotlib is a low-level, highly customizable plotting library. Ideal for creating static, publication-quality plots.

- 📎 Great for: Full control over visuals, academic charts
- 🔧 Features: Static plots, extensive customization, integration with NumPy/Pandas

### Seaborn
Seaborn is a high-level statistical data visualization library built on Matplotlib. It simplifies complex plots and offers beautiful defaults.

- 📎 Great for: Quick and attractive statistical visualizations
- 🔧 Features: Integrated with Pandas, built-in themes, supports complex plots with minimal code

---

## 📈 Graph Types with Examples

Each graph is shown with a use case and code snippet. Some examples include:

### ✅ Line Plot
```python
import matplotlib.pyplot as plt
x = [1, 2, 3, 4, 5]
y = [10, 20, 25, 30, 40]
plt.plot(x, y)
plt.title("Line Plot")
plt.show()
