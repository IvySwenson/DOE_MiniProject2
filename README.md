## 🌲 DOE Wildfire Mini Project 2

### 🔍 Project Overview

This mini project explores wildfire data using Python and Jupyter Notebook.
The goal is to analyze patterns in wildfire size, causes, and environmental factors to support data-driven fire management decisions.

The project is part of the **DOE Wildfire Project** at the University of Alaska Fairbanks, focusing on developing predictive modeling and visualization techniques.

---

### 📘 Contents

* `fire_analysis.ipynb` — Main Jupyter Notebook containing code, analysis, and visualizations.
* `data/` — Folder containing cleaned or raw CSV datasets.
* `images/` — Exported visualizations (optional).
* `README.md` — This documentation file.

---

### ⚙️ Environment Setup

#### 1️⃣ Create and activate environment

```bash
conda create -n wildfire python=3.11
conda activate wildfire
```

#### 2️⃣ Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

### 📊 Example Analysis

The notebook includes:

* Exploratory Data Analysis (EDA)
* Correlation plots between fire size and environmental factors
* K-Means clustering by fire size
* Regression modeling and evaluation metrics (MAE, RMSE, R²)

---

### 🧠 Sample Visualization

```python
plt.figure(figsize=(10,6))
sns.boxplot(data=df, x='Fuel_Type', y='Fire_Size')
plt.title("Fire Size by Fuel Type")
plt.show()
```

Example output:
📈 *Boxplot showing fire size distribution per fuel type.*

---

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/IvySwenson/DOE_MiniProject2.git
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook fire_analysis.ipynb
   ```

---

### 👩‍💻 Author

**Ivy Swenson**
DOE Wildfire Project — UAF Data/AI Lab
💬 *Analyzing wildfire patterns through data and machine learning.*

---

### 🪶 License

This project is released under the MIT License.
