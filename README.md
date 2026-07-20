# House Price Prediction using Multiple Linear Regression

A Machine Learning project that predicts house prices using the Ames Housing Dataset and Multiple Linear Regression.

---

# Project Overview

This project demonstrates the complete workflow of building a Multiple Linear Regression model to predict house prices.

The project includes:

- Data preprocessing
- Data validation
- Handling missing values
- Feature selection
- One-Hot Encoding
- Train/Test split
- Model training
- Prediction
- Model evaluation

---

# Dataset

**Dataset:** Ames Housing Dataset

The dataset contains detailed information about residential properties, including both numerical and categorical features.

**Target Variable**

- SalePrice

---

# Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Validation
4. Handle Missing Values
5. Feature Selection
6. One-Hot Encoding
7. Split Data into Training and Testing Sets
8. Train Multiple Linear Regression Model
9. Predict House Prices
10. Evaluate the Model

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# Model Performance

| Metric | Value |
|---------|------:|
| R² Score | 0.741 |
| MAE | 29,405.02 |
| MSE | 1,606,427,201.95 |
| RMSE | 40,080.26 |

---

# Project Structure

```text
Multiple_Linear_Regression_Project/
│
├── AmesHousing.csv
├── Multiple_Linear_Regression_Project.ipynb
├── README.md
├── requirements.txt
```

---

# How to Run

Clone the repository:

```bash
git clone https://github.com/khaled-amireh/House-Price-Prediction-MLR.git
```

Navigate to the project directory:

```bash
cd House-Price-Prediction-MLR
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook.

---

# Results

The Multiple Linear Regression model successfully learned the relationship between housing features and house prices.

After preprocessing the data and training the model, it achieved an **R² Score of approximately 0.74**, demonstrating good predictive performance on unseen test data.

---

# Future Improvements

- Apply Feature Engineering
- Perform Cross Validation
- Tune Hyperparameters
- Compare with other Regression Algorithms
- Deploy the model as a web application
---

# Author

**Khaled Amireh**

AI Student | Machine Learning
