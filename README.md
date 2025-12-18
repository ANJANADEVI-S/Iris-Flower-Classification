# 🌸 Iris Flower Classification

## 📘 Overview
The **Iris Flower Classification** project is a classic machine learning problem that aims to classify iris flowers into one of three species — *Setosa*, *Versicolor*, and *Virginica* — based on the length and width of their sepals and petals.  
This project demonstrates the complete process of data analysis, visualization, preprocessing, model training, and evaluation using Python and Scikit-learn.

---

## 🧰 Tools & Libraries Used
- **Python**
- **Pandas** – for data manipulation and analysis  
- **Seaborn** & **Matplotlib** – for data visualization  
- **Scikit-learn (sklearn)** – for model building and evaluation  

---

## 🎯 Objective
To build a machine learning model that accurately classifies the species of iris flowers based on their four key features:
1. Sepal Length  
2. Sepal Width  
3. Petal Length  
4. Petal Width  

---

## 📊 Dataset
- The dataset used is the **Iris dataset**, one of the most well-known datasets in the field of machine learning.
- It consists of **150 samples** divided equally among the three species.
- Each sample contains **4 numerical features** and **1 target label**.

You can load it directly from `sklearn.datasets` using:
```python
from sklearn.datasets import load_iris
