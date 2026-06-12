# data-visualization-with-python
# 📊 Matplotlib & Seaborn Practice Notes

These are my notes and practice exercises while learning data visualization in Python using Matplotlib and Seaborn.

The notebook includes basic plotting, figure customization, subplot handling, and some statistical visualizations that are commonly used in data analysis and machine learning.

---

## Libraries Used

* Python
* Matplotlib
* Seaborn
* Pandas
* NumPy

---

## Topics I Practiced

### Matplotlib

* Line plots
* Scatter plots
* Bar charts
* Pie charts
* Figure & Axes
* Subplots
* Figure size and DPI
* Plot styling

### Seaborn

* `lineplot()`
* `scatterplot()`
* `heatmap()`
* `histplot()`
* `kdeplot()`
* `hue` parameter

### Visualization Concepts

* Correlation
* KDE
* Distribution analysis
* Heatmaps
* Outliers
* Alpha transparency

---

## What I Learned

* How Matplotlib works with `fig` and `ax`
* Difference between Matplotlib and Seaborn syntax
* Creating and customizing different plot types
* Visualizing relationships between variables
* Basic statistical visualization
* Working with multiple plots in one figure

---

## Example

```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.lineplot(
    x=[1,2,3,4],
    y=[10,20,15,30]
)

plt.title("Simple Line Plot")
plt.show()
```

---

## File Structure

```bash
lesson4.ipynb
README.md
```

---

## Purpose

I created this notebook to keep my visualization notes organized and improve my understanding of Python data visualization before moving deeper into machine learning and data science projects.

---

## Future Plans

Later I want to add:

* boxplots
* regression plots
* pairplots
* real datasets
* more EDA examples

---

## Notes

This repository is mainly for learning and practice.
