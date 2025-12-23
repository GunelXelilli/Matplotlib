# 📊 Data Visualization with Python

This project demonstrates data visualization using **Python libraries**:

- **Matplotlib** – for creating line plots, histograms, and customized charts.  
- **NumPy** – for generating and manipulating numerical data.  
- **Pandas** – for handling structured datasets (if used).  

## 🚀 Features

### 1. Line Plots
- Compare multiple data series.  
- Customized colors, markers, line styles, and legends.  
- Grid, titles, and axis labels for readability.  

```python
plt.plot(arr, label='Series 1', color='#42e9f5', linewidth=3, marker='o')
plt.plot(arr1, label='Series 2', color='purple', linestyle='--', marker='s')
plt.legend()
plt.grid(True)
plt.show()
```

### 2. Histograms
-Visualize distributions of numerical data.
-Adjustable number of bins, colors, transparency, and grid lines.
```python
random_data = np.random.normal(loc=50, scale=10, size=1000)
plt.hist(random_data, bins=60, color='#fcca03', edgecolor='black', alpha=0.7)
plt.title('Histogram of Random Data')
plt.xlabel('Value')
plt.ylabel('Frequency')
plt.grid(True)
plt.show()
```




