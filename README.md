# 📊 Stock Market Trend Analysis - Exploratory Data Analysis (EDA)

## 📝 Project Overview

This repository focuses on **Exploratory Data Analysis (EDA) and visualization techniques** to analyze stock market trends. The goal is to understand stock price movements, correlations, and data distributions using statistical methods and visualization tools. 

The project includes:
- **Distribution Analysis**: Histograms and bar charts for different stock features.
- **Correlation Analysis**: Heatmap to identify relationships between variables.
- **Scatter and Density Plots**: Understanding relationships and data spread.

---

## 🎯 Objectives

- **Analyze stock market trends** through visual and statistical methods.
- **Identify relationships between stock market variables** (e.g., price, volume).
- **Detect outliers and patterns** in stock price movements.
- **Visualize stock correlations and dependencies** for better insights.

---

## 🛠️ Environment & Dependencies

The project runs in **Google Colab** and requires the following dependencies:

```python
# Install missing dependencies
!pip install pandas numpy matplotlib seaborn
```

### **Required Libraries**
| Library | Purpose |
|---------|---------|
| `pandas` | Data manipulation and analysis |
| `numpy` | Numerical computations |
| `matplotlib` | Data visualization |
| `seaborn` | Advanced data visualization |

---

## 📂 Project Structure

```
📁 Stock-Market-Trend-Analysis
│── 📄 README.md          # Project documentation
│── 📄 Stock_Market_EDA.ipynb  # Jupyter Notebook (Google Colab)
│── 📄 data/              # Directory for dataset (if applicable)
│── 📄 results/           # Output results (graphs, reports)
│── 📄 Stock Market Trend Analysis.pdf  # Research Report
```

---

## 🚀 How to Run the Project

### **1️⃣ Open in Google Colab**
Click the badge below to open the notebook in **Google Colab**:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-repo-link/Stock-Market-Trend-Analysis.ipynb)

### **2️⃣ Clone the Repository**
To run the project locally, clone the repository:

```bash
git clone https://github.com/your-username/Stock-Market-Trend-Analysis.git
cd Stock-Market-Trend-Analysis
```

### **4️⃣ Run the Notebook**
Launch Jupyter Notebook and open `Stock_Market_EDA.ipynb`:

```bash
jupyter notebook
```

---

## 📌 Exploratory Data Analysis (EDA) Methods

### 1️⃣ **Distribution Graphs**
**Function: `plotPerColumnDistribution(df, nGraphShown, nGraphPerRow)`**

- Generates histograms/bar graphs for numerical and categorical stock features.
- Helps in understanding the **spread and distribution** of data.
- Filters **columns with 1-50 unique values** for meaningful visualizations.

📌 **Example:**
- Stock price distribution
- Trading volume trends

---

### 2️⃣ **Correlation Matrix**
**Function: `plotCorrelationMatrix(df, graphWidth)`**

- Computes the **correlation coefficients** between stock features.
- Visualizes relationships in a **heatmap format**.
- Filters out columns with **NaN values or constant values**.

📌 **Example:**
- Relationship between opening and closing prices.
- How volume affects stock price movement.

---

### 3️⃣ **Scatter & Density Plots**
**Function: `plotScatterMatrix(df, plotSize, textSize)`**

- Generates **pairwise scatter plots** to visualize **relationships** between features.
- Includes **density plots** along diagonals to see data spread.
- Reduces dimensionality by selecting **only the top 10 numerical columns**.

📌 **Example:**
- Stock price correlation with volume.
- Identifying **outliers** in stock performance.

---

## 📜 Results & Insights

This project provides:
- **Visual insights into stock market trends** through **EDA and statistical analysis**.
- **A clearer understanding of variable relationships** using correlation heatmaps.
- **Useful exploratory insights** before applying predictive modeling.

---

## 📄 References

- Pandas Documentation: [https://pandas.pydata.org](https://pandas.pydata.org)
- Matplotlib Documentation: [https://matplotlib.org](https://matplotlib.org)
- Seaborn Documentation: [https://seaborn.pydata.org](https://seaborn.pydata.org)

---

## 🤝 Contribution Guidelines

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a **Pull Request (PR)** with your updates.

---

## 📧 Contact

For any questions, feel free to reach out via **GitHub Issues** or email.
