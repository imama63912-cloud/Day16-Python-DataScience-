# Pandas DataFrame Slicing with loc[] and iloc[] - Iris Dataset

This repository demonstrates data selection and filtering operations in Pandas using the classic 

**Iris Dataset**, focusing on label-based and position-based indexing.

---

## 🚀 Objectives
* Understand and implement Pandas' two core indexing methods: `loc[]` and `iloc[]`.
* Differentiate between label-based selection (`loc[]`) and integer position-based selection (`iloc[]`).
* Perform slicing, filtering, and conditional data extraction on the Iris dataset.

---

## 🛠️ Tools & Libraries
* **Python**
* **Pandas**
* **Jupyter Notebook**

---

## 📋 Code Implementation Highlights

### 1. Label-based Selection (`loc[]`)
```python
# Select rows 0 to 4 and specific columns by name
df.loc[0:4, ['SepalLengthCm', 'SepalWidthCm', 'Species']]

# Conditional filtering (Species = 'Iris-setosa')
df.loc[df['Species'] == 'Iris-setosa', ['Id', 'Species', 'PetalLengthCm']]
