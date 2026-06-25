# Edutech_Data_Science_Task11
## Task 11: Principal Component Analysis (PCA) on Wine Dataset

### 📌 Project Overview
This project demonstrates the application of Principal Component Analysis (PCA) to handle and simplify high-dimensional data complexity. Using the classic Scikit-learn Wine Dataset, we compress 13 chemical features down to 2 principal components for effective 2D visualisation while maintaining maximum underlying variance.

### 🛠️ Tools & Libraries Used
- **Python 3**
- **Scikit-learn** (Data loading, Train-Test Split, StandardScaler, PCA)
- **Pandas & NumPy** (Data manipulation)
- **Matplotlib & Seaborn** (Data visualization)

### 📈 Key Insights & Results
- **Dimensionality Reduction:** Successfully reduced the feature space from 13 dimensions to 2 Principal Components (PCA1 & PCA2).
- **Variance Retained:** 
  - Principal Component 1 (PCA1) captures: **35.99%** variance.
  - Principal Component 2 (PCA2) captures: **18.60%** variance.
  - Total information retained in 2D space: **54.59%**.
- **Visual Separation:** The 2D scatter plot displays distinct, clear clustering among the three different wine classes.

### 📂 Repository Structure
- `Untitled232.ipynb` (Jupyter Notebook containing the code)
- `Wine Data Visualization.png` (Saved scatter plot image)
- `README.md` (Project explanation)
  
### 💬 Interview Questions Related To This Task

#### 1. What is dimensionality reduction?
Dimensionality reduction is a feature engineering technique used to reduce the number of input features (columns) in a dataset. It transforms high-dimensional data into a lower-dimensional space while retaining as much meaningful information (variance) as possible, making the data easier to visualise and faster for machine learning models to process.

#### 2. Why use PCA?
PCA (Principal Component Analysis) is an unsupervised linear technique used to find the directions of maximum variance (Principal Components) in high-dimensional data. We use it to:
- Compress data for **2D or 3D visualization**.
- Overcome multi-collinearity and reduce **overfitting**.
- Speed up model training time by eliminating redundant or noisy features.
