# Data Visualization

## Matplotlib
```
# Barplot Horizontal
import matplotlib.pyplot as plt
%matplotlib inline

plt.figure(figsize=(8, 8))
plt.barh('city','total',data=df) # Horizontal Plot
plt.title('Total Penduduk Tiap Kota')
plt.show()
```

Other
```
plt.scatter('Assault','Murder',data=df) #Scatterplot
plt.plot(city, total) #Line Chart
plt.pie(total, labels=city, autopct='%1.1f%%') #Pie Chart 

```


### Seaborn
```
import seaborn as sns
plt.figure(figsize=(8, 8))

sns.set(style="whitegrid")
ax = sns.barplot(x="total", y="city", data=df)
```


### Plotly





## Refference
1. https://plotly.com/python/bar-charts/
2. https://seaborn.pydata.org/generated/seaborn.barplot.html
3. https://pythonspot.com/matplotlib-pie-chart/