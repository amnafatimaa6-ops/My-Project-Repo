# IRIS-DATA_Analysis_and_Visualization

# Iris Dataset EDA and Visualization

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** and **visualization** on the classic **Iris dataset**, a widely used dataset in machine learning. The goal is to understand feature distributions, relationships, correlations, and potential outliers to gain insights for further analysis or predictive modeling.

---

## Dataset
- Total samples: 150  
- Features: 4 numerical (`sepal_length`, `sepal_width`, `petal_length`, `petal_width`) and 1 categorical (`species`)  
- Classes: 3 (`Setosa`, `Versicolor`, `Virginica`)  

---

## Libraries Used
- Python 
- [Pandas](https://pandas.pydata.org/) – Data manipulation  
- [Seaborn](https://seaborn.pydata.org/) – Data visualization  
- [Matplotlib](https://matplotlib.org/) – Plotting  

---

## Exploratory Data Analysis (EDA)

### 1. Dataset Overview
- No missing values in any column  
- Sepal and petal measurements vary across species  

**Basic statistics:**  
- Sepal length: min = 4.3, max = 7.9, mean ≈ 5.84  
- Sepal width: min = 2.0, max = 4.4, mean ≈ 3.05  
- Petal length: min = 1.0, max = 6.9, mean ≈ 3.76  
- Petal width: min = 0.1, max = 2.5, mean ≈ 1.20  

---

### 2. Visualizations

1. **Species Distribution**
   - Count plot shows a balanced dataset with 50 samples per species.

2. **Pairplot**
   - Scatter plots show **petal features separate species well**, while sepal features overlap more.  
   - Diagonal KDE plots show **Setosa is tightly grouped**, whereas Versicolor and Virginica are more spread out.

3. **Heatmap**
   - **Sepal length strongly correlates** with petal length and petal width, but weakly with sepal width.  
   - **Petal features are highly correlated** with each other, making them strong indicators for classification.  
   - Sepal width has weaker correlations overall.

4. **Boxplots**
   - Most features have **few outliers**, mainly in petal lenght and width.  
     



##  Key Insights
- **Petal length and width are the most informative features** for distinguishing species.  
- **Setosa** is easily distinguishable due to smaller and tightly grouped petal sizes.  
- **Versicolor and Virginica** overlap in sepal measurements but differ in petal sizes.  
- Outliers are rare, mostly in petal features for Setosa and Virginica.

---

## Conclusion
This EDA demonstrates the **importance of petal features** in classifying Iris species. The dataset is clean, balanced, and suitable for **machine learning tasks** such as classification or clustering. Visualizations provide clear insights into **feature relationships, distributions, and correlations**, making it an ideal starting point for predictive modeling.

---
