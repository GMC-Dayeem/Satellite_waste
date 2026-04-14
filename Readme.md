# Satellite Data Processing & Visualization

This project explores and visualizes satellite data to analyze the distribution of **active satellites and space debris** in Earth's orbit.

The analysis is performed using Python in Jupyter notebooks, focusing on data cleaning, classification, and visualization.

---

## 📌 Overview

Using a real-world satellite dataset (`satcat.tsv`), this project:

- Cleans and preprocesses orbital data
- Identifies active satellites and debris
- Analyzes orbital distribution (LEO, MEO, etc.)
- Visualizes trends and spatial patterns

---

## 📂 Project Structure

- `Project.ipynb` – Main analysis notebook  
- `Final.ipynb` – Tested version
- `satcat.tsv` – Satellite dataset  
- `*.png` – Generated visualizations and icons  

---

## 🧠 Key Features

### 🔹 Data Cleaning
- Converted Perigee and Apogee values to numeric
- Removed invalid and missing values
- Handled negative orbital values

### 🔹 Satellite Classification
- Classified satellites into:
  - Active satellites
  - Space debris  
- Used dataset fields such as `Type` and `Status`

### 🔹 Data Reduction
- Reduced dataset size by sampling satellites with identical perigee values  
- Helped improve visualization clarity

### 🔹 Visualizations
- Polar plots showing orbital distribution
- Time-series plots of debris growth
- Comparative plots of active vs debris satellites
- Country-based comparisons using stacked and dot visualizations

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- ipywidgets

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn ipywidgets

2. Open Jupyter Notebook:
jupyter notebook

3. Run:
Project.ipynb
Final.ipynb